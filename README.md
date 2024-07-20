# 3D-Mesh-Reconstruction-from-Point-Clouds
3D Mesh Reconstruction from Point Clouds

I completed this project as part of my internship at Bhabha Atomic Research Centre (BARC). I made an ML model that converts 2D point cloud images (with depth information) to reconstruct its 3D mesh surface. We used 3 algorithms - Poisson Surface Reconstruction, Ball Pivot Algorithm, and Delaunay Triangulation
The accuracy and consistency of the generated mesh are in the following order - Poisson Surface Reconstruction, followed by Delaunay Triangulation, and at last Ball Pivot Algorithm, which has holes in the mesh, the other two don't.


Dataset Used - NYU depth dataset 
It contains 1450 RGB images and their corresponding depth images 
