# Awesome Ray Tracing [![CC0 License](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of ray tracing materials.
PR's welcome!

![Ray Trace Spheres](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Recursive_raytrace_of_a_sphere.png/240px-Recursive_raytrace_of_a_sphere.png)

## Table of Contents

- [Ray Tracing](#ray-tracing)
- [Math](#math)
- [Ray Casting](#ray-casting)
- [BRDF, BSSDF, BTDF, and BRDF](#brdf-bssdf-btdf-and-brdf)
- [Path Tracing](#path-tracing)
- [Photon Mapping](#photon-mapping)
- [Sampling Methods](#sampling-methods)
- [Reference Scenes](#reference-scenes)
- [API's](#apis)
  - [Nvidia OptiX](#nvidia-optix)
  - [Nvidia RTX](#nvidia-rtx)
  - [Microsoft DirectX Raytracing (RTX)](#microsoft-directx-raytracing-dxr)
- [News](#news)
  
---

## Ray Tracing

![Ray Tracing Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Ray_trace_diagram.svg/320px-Ray_trace_diagram.svg.png)

- [A course on photorealistic rendering, ray tracing and global illumination - *TU Wien*](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi)
- [Ray Tracing in One Weekend - *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)
- [Physically Based Rendering Book (PBRT) - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/)
- [Real-Time Rendering Chapter - *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/raytracing.html)
- [The Rendering Equation (1986) - *James T. Kajiya*](http://www.dca.fee.unicamp.br/~leopini/DISCIPLINAS/IA725/ia725-12010/kajiya-SIG86-p143.pdf)

## Math

![Dot Product](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Inner-product-angle.svg/320px-Inner-product-angle.svg.png)

- [PBRT Chapter 2 Geometry and Transformations - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Geometry_and_Transformations.html)
- [PBRT Chapter 3 Shapes - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Shapes.html)
- [Linear Algebra - *Khan Academy*](https://www.khanacademy.org/math/linear-algebra)

## Ray Casting

![Ray Triangle Intersection](https://upload.wikimedia.org/wikipedia/commons/6/6c/Ray_triangle.png)![BVH](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Example_of_bounding_volume_hierarchy.svg/320px-Example_of_bounding_volume_hierarchy.svg.png)

- [Ray-Triangle Intersection: Geometric Solution - *Scratchapixel*](https://www.scratchapixel.com/lessons/3d-basic-rendering/ray-tracing-rendering-a-triangle/ray-triangle-intersection-geometric-solution)
- [Introduction to Acceleration Structures - *Scratchapixel*](https://www.scratchapixel.com/lessons/advanced-rendering/introduction-acceleration-structure/bounding-volume)
- [PBRT Chater 4 Primitives and Intersection Acceleration - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Primitives_and_Intersection_Acceleration.html)

## BRDF, BSSDF, BTDF, and BRDF

![BRDF](https://upload.wikimedia.org/wikipedia/en/thumb/d/d8/BSDF05_800.png/179px-BSDF05_800.png)

- [PBRT Chapter 5.6 Surface Reflection - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Color_and_Radiometry/Surface_Reflection.html)
- [PBRT Chapter 8 Reflection Models - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Reflection_Models.html)
- [PBRT Chapter 9 Materials - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Materials.html)
- [PBRT Chapter 11 Volume Scattering - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Volume_Scattering.html)

## Path Tracing

- [Ray Tracing in One Weekend - *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)

## Photon Mapping

- [Photon Mapping - *Zack Waters*](https://web.cs.wpi.edu/~emmanuel/courses/cs563/write_ups/zackw/photon_mapping/PhotonMapping.html)

## Sampling Methods

![Hammersley Set](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Hammersley_set_2D.svg/289px-Hammersley_set_2D.svg.png)

- [PBRT Chapter 7 - *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Sampling_and_Reconstruction.html)
- [Robust Monte Carlo Methods for Light Transport Simulation - *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)
- [Flavors of Sampling in Ray Tracing  - *Peter Shirley*](http://psgraphics.blogspot.com/2018/10/flavors-of-sampling-in-ray-tracing.html)

## Reference Scenes

![Cornell Box](https://upload.wikimedia.org/wikipedia/commons/2/24/Cornell_box.png)![Stanford Bunny](https://upload.wikimedia.org/wikipedia/en/a/a7/Stanford_Bunny.png)

- [Benedikt Bitterli](https://benedikt-bitterli.me/resources/)
- [PBRT Scenes v3](https://www.pbrt.org/scenes-v3.html)
- [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html)

## API's

### Nvidia OptiX

- [OptiX QuickStart - *Nvidia*](https://docs.nvidia.com/gameworks/content/gameworkslibrary/optix/optix_quickstart.htm)

### Nvidia RTX

- [Introduction to Real-Time Ray Tracing with Vulkan - *Nuno Subtil*](https://devblogs.nvidia.com/vulkan-raytracing/)
- [Vulkan Raytracing Tutorials - *iOrange*](https://iorange.github.io/p02/TeapotAndBunny.html)
- [Video Series: Practical Real-Time Ray Tracing With RTX - *Nvidia*](https://devblogs.nvidia.com/practical-real-time-ray-tracing-rtx/)

### Nvidia CUDA

- [Accelerated Ray Tracing in One Weekend in CUDA - *Roger Allen*](https://devblogs.nvidia.com/accelerated-ray-tracing-cuda/)

### Microsoft DirectX Raytracing (DXR)

- [DXRPathTracer](https://github.com/TheRealMJP/DXRPathTracer)

## News

- [Graphics Programming weekly - *Jendrik Illner*](https://www.jendrikillner.com/post/)
