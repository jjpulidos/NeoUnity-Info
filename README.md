# NeoUnity-Info

The code is confidential, but you can see a first vis of the product here

**In Progress**

3D Graph Editor Using Unity

Editing Position of a Node (and edges too).
![](https://i.imgur.com/vw00dU7.gif)

Navigating through the graph

![](https://media.giphy.com/media/7SUdNKC53U5nQj0qZ7/giphy.gif)


- The Editor shows a 3D Complete Graph (in which every pair of distinct vertices is connected by a unique edge)
- The Editor allows you take a node or a set of nodes and move like you want.
- The Editor allows you navigate inside of the graph and see all the nodes from inside


Benchmark:

### Testing with 50.000 vertices 

**Edges (gl lines), Vertices as primitive game objects**

	- Without Spheres (reducing a lot of variables unused to optimize memory in every node), Without Edges, just void GameObjects: 70-80 FPS

	- Without Spheres , Without Edges, just void GameObjects: 70-80 FPS

	- With Spheres (using Sphere Collider) (reducing a lot of variables unused to optimize memory in every node), Without Edges: 40-60 FPS

	- With Spheres (not using Sphere Collider (Destroy))(reducing a lot of variables unused to optimize memory in every node) , Without Edges: 45-70 FPS

	- With Spheres (not using Sphere Collider (DestroyImmediate)) (reducing a lot of variables unused to optimize memory in every node), Without Edges: 45-70 FPS

	- Without Spheres , With Edges, just void GameObject: +-7fps

	- With Spheres (not using Sphere Collider (DestroyImmediate)) (reducing a lot of variables unused to optimize memory in every node), With Edges: +-6 FPS	



**Special Tests:**

	- With Spheres (100.000 nodes)(not using Sphere Collider (DestroyImmediate)) (reducing a lot of variables unused to optimize memory in every node), Without Edges: +-20 FPS

	- With Spheres (1.000 nodes)(not using Sphere Collider (DestroyImmediate)) (reducing a lot of variables unused to optimize memory in every node), With Edges: 70-90 FPS

	- With Spheres (10.000 nodes)(not using Sphere Collider (DestroyImmediate)) (reducing a lot of variables unused to optimize memory in every node), With Edges: +-20 FPS

	- With Spheres (100.000 nodes)(not using Sphere Collider (DestroyImmediate)) (reducing a lot of variables unused to optimize memory in every node), With Edges: +- 3 FPS	


If you are interested in the code of the project or want be a collaborator, send me a ![email](jjpulidos98@gmail.com), there a lot of stuffs TODO :)


