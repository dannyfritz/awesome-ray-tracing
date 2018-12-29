# Awesome Ray Tracing [![CC0 License](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of ray tracing resources.
PR's welcome!

![Ray Trace Spheres](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Recursive_raytrace_of_a_sphere.png/240px-Recursive_raytrace_of_a_sphere.png)

## Table of Contents

- [Ray Tracing](#ray-tracing)
- [Math](#math)
- [Ray Casting](#ray-casting)
- [BXDF](#bxdf)
- [Path Tracing](#path-tracing)
- [Photon Mapping](#photon-mapping)
- [Sampling Methods](#sampling-methods)
- [Reference Scenes](#reference-scenes)
- [News](#news)
- [API's](#apis)
  - [Nvidia RTX](#nvidia-rtx)
  - [Microsoft DirectX Raytracing (RTX)](#microsoft-directx-raytracing-dxr)
  - [Nvidia OptiX](#nvidia-optix)
- [Glossary of Terms](GLOSSARY.md)
  
---

## Ray Tracing

![Whitted Ray Tracing Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Ray_trace_diagram.svg/320px-Ray_trace_diagram.svg.png)

- [Rendering / Ray Tracing Course - (2017) *TU Wien*](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi)
- [Ray Tracing in One Weekend - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)
  - [Ray Tracing: The Next Week - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-second-weekend.html)
  - [Ray Tracing: The Rest of Your Life - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/03/ray-tracing-rest-of-your-life.html)
- [Physically Based Rendering Book (PBRT) - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/)
- [Real-Time Rendering Chapter - (2018) *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/raytracing.html)
- [The Rendering Equation - (1986) *James T. Kajiya*](http://www.dca.fee.unicamp.br/~leopini/DISCIPLINAS/IA725/ia725-12010/kajiya-SIG86-p143.pdf)
- [Global Illumination Compendium - (2003) *Philip Dutré*](https://people.cs.kuleuven.be/~philip.dutre/GI/TotalCompendium.pdf)
- [Robust Monte Carlo Methods for Light Transport Simulation (1998) - *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)

## Math

![Dot Product](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Inner-product-angle.svg/320px-Inner-product-angle.svg.png)

- [PBRT Chapter 2 Geometry and Transformations - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Geometry_and_Transformations.html)
- [PBRT Chapter 3 Shapes - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Shapes.html)
- [Linear Algebra - *Khan Academy*](https://www.khanacademy.org/math/linear-algebra)

## Ray Casting

![Ray Triangle Intersection](https://upload.wikimedia.org/wikipedia/commons/6/6c/Ray_triangle.png)![BVH](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Example_of_bounding_volume_hierarchy.svg/320px-Example_of_bounding_volume_hierarchy.svg.png)

- [Ray-Triangle Intersection: Geometric Solution - *Scratchapixel*](https://www.scratchapixel.com/lessons/3d-basic-rendering/ray-tracing-rendering-a-triangle/ray-triangle-intersection-geometric-solution)
- [Introduction to Acceleration Structures - *Scratchapixel*](https://www.scratchapixel.com/lessons/advanced-rendering/introduction-acceleration-structure/bounding-volume)
- [PBRT Chater 4 Primitives and Intersection Acceleration - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Primitives_and_Intersection_Acceleration.html)

## BXDF

![BRDF](https://upload.wikimedia.org/wikipedia/en/thumb/d/d8/BSDF05_800.png/179px-BSDF05_800.png)

- [PBRT Chapter 5.6 Surface Reflection - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Color_and_Radiometry/Surface_Reflection.html)
- [PBRT Chapter 8 Reflection Models - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Reflection_Models.html)
- [PBRT Chapter 9 Materials - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Materials.html)
- [PBRT Chapter 11 Volume Scattering - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Volume_Scattering.html)

## Path Tracing

- [Path Tracing - (2017) *Fabio Pellacini and Steve Marschner*](http://pellacini.di.uniroma1.it/teaching/graphics17b/lectures/12_pathtracing.pdf)
- [Ray Tracing in One Weekend - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)

## Photon Mapping

- [Photon Mapping - *Zack Waters*](https://web.cs.wpi.edu/~emmanuel/courses/cs563/write_ups/zackw/photon_mapping/PhotonMapping.html)

## Sampling Methods

![Hammersley Set](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Hammersley_set_2D.svg/289px-Hammersley_set_2D.svg.png)

- [PBRT Chapter 7 - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Sampling_and_Reconstruction.html)
- [Robust Monte Carlo Methods Chapters 2, 9, & 11 - (1998) *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)
- [Flavors of Sampling in Ray Tracing  - (2018) *Peter Shirley*](http://psgraphics.blogspot.com/2018/10/flavors-of-sampling-in-ray-tracing.html)

## Reference Scenes

![Cornell Box](https://upload.wikimedia.org/wikipedia/commons/2/24/Cornell_box.png)![Stanford Bunny](https://upload.wikimedia.org/wikipedia/en/a/a7/Stanford_Bunny.png)

- [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html)
- [Benedikt Bitterli](https://benedikt-bitterli.me/resources/)
- [PBRT Scenes v3](https://www.pbrt.org/scenes-v3.html)
- [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca)
- [Disney Data Sets](https://www.technology.disneyanimation.com/collaboration-through-sharing)

## News

- [Graphics Programming Weekly - *Jendrik Illner*](https://www.jendrikillner.com/post/)

## API's

- [Nvidia RTX](https://developer.nvidia.com/rtx)
- [Microsoft DirectX Raytracing (DXR)](https://blogs.msdn.microsoft.com/directx/2018/03/19/announcing-microsoft-directx-raytracing/)
- [Nvidia Optix](https://developer.nvidia.com/optix)
- [AMD Radeon-Rays](www.realtimerendering.com/raytracing.html)
- [Intel Embree](http://embree.github.io/)

### Nvidia RTX

- [Introduction to Real-Time Ray Tracing with Vulkan - (2018) *Nuno Subtil*](https://devblogs.nvidia.com/vulkan-raytracing/)
- [Vulkan Raytracing Tutorials - (2018) *iOrange*](https://iorange.github.io/p02/TeapotAndBunny.html)
- [Video Series: Practical Real-Time Ray Tracing With RTX - (2018) *Nvidia*](https://devblogs.nvidia.com/practical-real-time-ray-tracing-rtx/)

### Microsoft DirectX Raytracing (DXR)

- [DXRPathTracer](https://github.com/TheRealMJP/DXRPathTracer)

### Nvidia OptiX

- [OptiX QuickStart - *Nvidia*](https://docs.nvidia.com/gameworks/content/gameworkslibrary/optix/optix_quickstart.htm)

## [Glossary of Terms](GLOSSARY.md)
