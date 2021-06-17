## Octree: A spatial data-structure to store point-cloud representations

An [Octree](https://en.wikipedia.org/wiki/Octree) is a three-dimensional analogue of the Quadtree, the latter can be explained more easily. A quadtree is a spatial data structure that stores region information in quadrants formed by recursively subdividing square regions. A point can thus be approximated by a quadrant small enough to adequately enclose the point within reasonable bounds on accuracy. Our team created a presentation on the importance of such classes of data-structures and the octree which can be found [here](https://www.youtube.com/watch?v=ZysTeC49ldw)

![Quadtree](https://upload.wikimedia.org/wikipedia/commons/b/b5/StructureQuadTree.png)
*Fig. 1 Quadtree*

Here, we create an Octree using similar principles and use it store the point cloud information of a highly detailed model [here](https://www.youtube.com/watch?v=9rGK7Gmiuoo).

This data structure reduces the time and space complexity of rendering objects in 3D and allows faster spatial operations such as Nearest-Neighbor (NN) search and Frustum Culling.

####  Running the code
The application may be run by running the python code using an ".obj" file. This will extract the points from the model and remove surfaces, surface normals and color and textural data. The set of points extracted can then be used in the blenderpy script at the end of the code.

