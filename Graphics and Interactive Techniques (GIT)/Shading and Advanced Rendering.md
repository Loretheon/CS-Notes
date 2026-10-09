# Shading and Advanced
KA Core:
1. Solutions and approximations to the rendering equation, for example
a. Distribution ray tracing and path tracing
b. Photon mapping
c. Bidirectional path tracing
d. Metropolis light transport
2. Time (motion blur), lens position (focus), and continuous frequency (color) and their impact on rendering
3. Shadow mapping
4. Occlusion culling
5. Bidirectional Scattering Distribution function (BSDF) theory and microfacets
6. Subsurface scattering
7. Area light sources
8. Hierarchical depth buffering
9. Image-based rendering
10. Non-photorealistic rendering
11. Realtime rendering
12. GPU architecture (See also: AR-Heterogeneity)
13. Human visual systems including adaptation to light, sensitivity to noise, and flicker fusion (See also:
HCI-Accessibility, SEP-DEIA)
Illustrative Learning Outcomes:
KA Core:
1. Describe how an algorithm estimates a solution to the rendering equation.
2. Discuss the properties of a rendering algorithm (e.g., complete, consistent, and unbiased).
3. Analyze the bandwidth and computation demands of a simple shading algorithm.
4. Implement a non-trivial shading algorithm (e.g., toon shading, cascaded shadow maps) under a
rasterization API.
5. State how a particular artistic technique might be implemented in a renderer.
6. Describe how one might recognize the shading techniques used to create a particular image.
7. Write a program that implements any of the specified graphics techniques using a primitive graphics
system at the individual pixel level.
8. Write a ray tracer for scenes using a simple (e.g., Phong’s) Bidirectional Reflection Distribution
Function (BRDF) plus reflection and refraction.