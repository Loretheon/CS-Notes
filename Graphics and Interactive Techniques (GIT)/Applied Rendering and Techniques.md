# Applied Rendering and Techniques
KA Core: (See also: SPD-Game)
1. Object and scene modeling
a. Object representations: polygonal, parametric, etc.
b. Modeling transformations: affine and coordinate-system transformations
c. Scene representations: scene graphs
2. Camera and projection modeling
a. Pinhole cameras, similar triangles, and projection model
b. Camera models
c. Projective geometry
3. Radiometry and light models
a. Radiometry
b. Rendering equation
c. Rendering in nature – emission and scattering, etc.
4. Rendering
a. Simple triangle rasterization
b. Rendering with a shader-based API
c. Visibility and occlusion, including solutions to this problem (e.g., depth buffering, Painter’s
algorithm, and ray tracing)
d. Texture mapping, including minification and magnification (e.g., trilinear MIP mapping)
e. Application of spatial data structures to rendering.
f. Ray tracing
g. Sampling and anti-aliasing
Illustrative Learning Outcomes:
KA Core:
1. Describe and illustrate the light transport problem (i.e., light is emitted, scatters around the scene,
and is measured by the eye).
2. Describe the basic rendering pipeline.
3. Compare and contrast how forward and backwards rendering factor into the graphics pipeline.
4. Create a program to display 2D shapes in a window.
5. Create a program to display 3D models.
6. Produce linear perspective from similar triangles by converting points (x, y, z) to points (x/z, y/z, 1).
7. Compute two-dimensional and 3-dimensional points by applying affine transformations.
8. Indicate the changes required to extend 2D transformation operations to handle transformations in
3D.
9. Define texture mapping, sampling, and anti-aliasing, and describe examples of each.
10. Compare ray tracing and rasterization for the visibility problem.
11. Construct a program that performs transformation and clipping operations on simple two-
dimensional shapes.
12. Implement a simple real-time renderer using a rasterization API (e.g., OpenGL, webGL) using
vertex buffers and shaders.
13. Compare and contrast the different rendering techniques.
14. Compare and contrast the difference in transforming the camera vs the models.