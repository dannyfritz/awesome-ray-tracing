# Awesome Ray Tracing [![CC0 License](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of ray tracing resources.
PR's welcome!

![Ray Trace Spheres](https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Recursive_raytrace_of_a_sphere.png/240px-Recursive_raytrace_of_a_sphere.png)

## Table of Contents

- [Glossary of Terms](GLOSSARY.md)
- [Ray Tracing](#ray-tracing)
- [Path Tracing](#path-tracing)
- [Photon Mapping](#photon-mapping)
- [Math](#math)
- [Ray Casting](#ray-casting)
- [BxDF](#bxdf)
- [Sampling Methods](#sampling-methods)
- [Realtime](#realtime)
- [Reference Scenes](#reference-scenes)
- [News](#news)
- [API's](#apis)
  - [Nvidia RTX](#nvidia-rtx)
  - [Microsoft DirectX Raytracing (RTX)](#microsoft-directx-raytracing-dxr)
  - [Nvidia OptiX](#nvidia-optix)
  
## Legend

| Icon | Meaning |
| ---- | ------- |
| 📖 | Reading |
| 📺 | Video |
| 💾 | Code / Asset |

---

## [Glossary of Terms](GLOSSARY.md)

## Ray Tracing

![Whitted Ray Tracing Diagram](https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Ray_trace_diagram.svg/320px-Ray_trace_diagram.svg.png)

- 📖 [What’s the Difference Between Ray Tracing and Rasterization? - (2018) *Brian Caulfield*](https://blogs.nvidia.com/blog/2018/03/19/whats-difference-between-ray-tracing-rasterization/)
- 📺 [Rendering / Ray Tracing Course - (2017) *TU Wien*](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi)
- 📖 [Ray Tracing in One Weekend - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)
  - 📖 [Ray Tracing: The Next Week - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-second-weekend.html)
  - 📖 [Ray Tracing: The Rest of Your Life - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/03/ray-tracing-rest-of-your-life.html)
- 📖 [Physically Based Rendering Book (PBRT) - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/)
- 📖 [Real-Time Rendering Ray Tracing Resources - (2018) *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/raytracing.html)
- 📖 [The Rendering Equation - (1986) *James T. Kajiya*](http://www.dca.fee.unicamp.br/~leopini/DISCIPLINAS/IA725/ia725-12010/kajiya-SIG86-p143.pdf)
- 📖 [Global Illumination Compendium - (2003) *Philip Dutré*](https://people.cs.kuleuven.be/~philip.dutre/GI/TotalCompendium.pdf)
- 📖 [Robust Monte Carlo Methods for Light Transport Simulation (1998) - *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)

## Path Tracing

- 📺 [Disney's Practical Guide to Path Tracing - (2016) *Disney*](https://youtu.be/frLwRLS_ZR0)
- 📖 [Path Tracing - (2017) *Fabio Pellacini and Steve Marschner*](http://pellacini.di.uniroma1.it/teaching/graphics17b/lectures/12_pathtracing.pdf)
- 📖 [Ray Tracing in One Weekend - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)
- 📖 [Path Tracing in Production - (2018) *Luca Fascione, Johannes Hanika, Rob Pieké, Ryusuke Villemin, Christophe Hery, Manuel Gamito, Luke Emrose, and André Mazzone*](https://jo.dreggn.org/path-tracing-in-production/2018/index.html)
- 📖 [Path Tracing Coherency - *Anders Lindqvist*](https://www.breakin.se/learn/pathtracing-coherency.html)
- 📖 [Path Traced Depth of Field and Bokeh - (2018) *Alan Wolfe*](https://blog.demofox.org/2018/07/04/pathtraced-depth-of-field-bokeh/)
- 📖 [Daily Path Tracer - (2018) *Aras Pranckevičius*](http://aras-p.info/blog/2018/03/28/Daily-Pathtracer-Part-0-Intro/)
- 📖 [Microfacet-based Normal Mapping for Robust Monte Carlo Path Tracing - (2017) *Vincent Schüssler, Eric Heitz, Johannes Hanika, Carsten Dachsbacher*](https://jo.dreggn.org/home/2017_normalmap.pdf)

## Photon Mapping

- 📖 [Photon Mapping - *Zack Waters*](https://web.cs.wpi.edu/~emmanuel/courses/cs563/write_ups/zackw/photon_mapping/PhotonMapping.html)

## Math

![Dot Product](https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Inner-product-angle.svg/320px-Inner-product-angle.svg.png)

- 📖 [PBRT Chapter 2 Geometry and Transformations - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Geometry_and_Transformations.html)
- 📖 [PBRT Chapter 3 Shapes - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Shapes.html)
- 📺 [Linear Algebra - *Khan Academy*](https://www.khanacademy.org/math/linear-algebra)

## Ray Casting

![Ray Triangle Intersection](https://upload.wikimedia.org/wikipedia/commons/6/6c/Ray_triangle.png)![BVH](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Example_of_bounding_volume_hierarchy.svg/320px-Example_of_bounding_volume_hierarchy.svg.png)

- 📖 [Ray-Triangle Intersection: Geometric Solution - *Scratchapixel*](https://www.scratchapixel.com/lessons/3d-basic-rendering/ray-tracing-rendering-a-triangle/ray-triangle-intersection-geometric-solution)
- 📖 [Introduction to Acceleration Structures - *Scratchapixel*](https://www.scratchapixel.com/lessons/advanced-rendering/introduction-acceleration-structure/bounding-volume)
- 📖 [PBRT Chater 4 Primitives and Intersection Acceleration - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Primitives_and_Intersection_Acceleration.html)
* 📺 [How to Make 3D Fractals](https://www.youtube.com/watch?v=svLzmFuSBhk)

## BxDF

![BRDF](https://upload.wikimedia.org/wikipedia/en/thumb/d/d8/BSDF05_800.png/179px-BSDF05_800.png)

- 📖 [PBRT Chapter 5.6 Surface Reflection - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Color_and_Radiometry/Surface_Reflection.html)
- 📖 [PBRT Chapter 8 Reflection Models - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Reflection_Models.html)
- 📖 [PBRT Chapter 9 Materials - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Materials.html)
- 📖 [PBRT Chapter 11 Volume Scattering - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Volume_Scattering.html)
- 📺 [Geometric Optics Playlist - (2013) *Doc Schuster*](https://www.youtube.com/playlist?list=PLLUpvzaZLf3IB4GEhaCg7L3ioiLkHLk7Q)
- 📖 [Physically Based Sky, Atmosphere, and Cloud Rendering in Frostbite - (2016) *Sebastien Hillaire*](https://media.contentapi.ea.com/content/dam/eacom/frostbite/files/s2016-pbs-frostbite-sky-clouds-new.pdf)
- 📖 [Revisiting Physically Based Shading in ImageWorks - (2017) *Christopher Kulla & Alejandro Conty*](https://blog.selfshadow.com/publications/s2017-shading-course/imageworks/s2017_pbs_imageworks_slides.pdf)
- 📖 [A Multifaceted Explanation Part 1 - (2018) *Stephen Hill*](https://blog.selfshadow.com/2018/05/13/multi-faceted-part-1/)
  - 📖 [A Multifaceted Explanation Part 2 - (2018) *Stephen Hill*](https://blog.selfshadow.com/2018/06/04/multi-faceted-part-2/)
  - 📖 [A Multifaceted Explanation Part 3 - (2018) *Stephen Hill*](https://blog.selfshadow.com/2018/08/05/multi-faceted-part-3/)
  
## Sampling Methods

![Hammersley Set](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Hammersley_set_2D.svg/289px-Hammersley_set_2D.svg.png)

- 📖 [PBRT Chapter 7 - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Sampling_and_Reconstruction.html)
- 📖 [Generating Random Points in a Sphere - (2018) *Karthik Karanth*](https://karthikkaranth.me/blog/generating-random-points-in-a-sphere/)
- 📖 [Robust Monte Carlo Methods Chapters 2, 9, & 11 - (1998) *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)
- 📖 [Flavors of Sampling in Ray Tracing  - (2018) *Peter Shirley*](http://psgraphics.blogspot.com/2018/10/flavors-of-sampling-in-ray-tracing.html)
- 📖 [Position-Free Monte Carlo Simulation for Arbitrary Layered BSDFs - (2018) *Yu Guo, Miloš Hašan, Shuang Zhao*](https://shuangz.com/projects/layered-sa18/)
- 📖 [Monte Carlo Integration - *Anders Lindqvist*](https://www.breakin.se/mc-intro/)
- 📖 [Monte Carlo Integration Explanation in 1D - (2018) *Alan Wolfe*](https://blog.demofox.org/2018/06/12/monte-carlo-integration-explanation-in-1d/)
- 📖 [Importance Sampling techniques for GGX with Smith Masking-Shadowing Part 1 - (2018) *Joe Schutte*](https://schuttejoe.github.io/post/ggximportancesamplingpart2/)
  - 📖 [Importance Sampling techniques for GGX with Smith Masking-Shadowing Part 2 - (2018) *Joe Schutte*](https://schuttejoe.github.io/post/ggximportancesamplingpart2/)
- 📖 [Double Hierarchies for Directional Importance Sampling in Monte Carlo Rendering - (2018) *Norbert Bus and Tamy Boubekeur*](http://www.jcgt.org/published/0006/03/02/)
- 📖 [Importance Sampling of Many Lights with Adaptive Tree Splitting - (2018) *Alejandro Conty and Christopher Kulla*](https://docs.google.com/viewer?a=v&pid=sites&srcid=ZGVmYXVsdGRvbWFpbnxja3VsbGF8Z3g6NWM0NmU2YWVlNjE3ODk1Yw)
- 📖 [Monte Carlo Methods for Volumetric Light Transport Simulation - (2018) *Jan Novák, Iliyan Georgiev, Johannes Hanika, and Wojciech Jarosz*](http://iliyan.com/publications/VolumeSTAR)

## Realtime

- 📖 [Real-Time Rendering Chapter - (2018) *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/Real-Time_Rendering_4th-Real-Time_Ray_Tracing.pdf)
- 📖 [Real-Time Ray Tracing of Correct* Soft Shadows - (2018) *Stephen Hill and Morgan McGuire*](http://advances.realtimerendering.com/s2018/s2018_real_time_correct_soft_shadows.pdf)
- 📺 [Stochastic All the Things: Raytracing in Hybrid Real-Time Rendering - (2018) *Tomasz Stachowiak*](https://www.ea.com/seed/news/seed-dd18-presentation-slides-raytracing)
- 📖 [Adopting Lessons From Offline Ray-Tracing to Real-Time Ray-Tracing for Practical Pipelines - (2018) *Matt Pharr*](http://advances.realtimerendering.com/s2018/Pharr%20-%20Advances%20in%20RTR%20-%20Real-time%20Ray%20Tracing.pdf)
- 📖 [Game Ray Tracing: State-of-the-Art and Open Problems - (2018) *Colin Barré Brisebois*](https://www.ea.com/seed/news/hpg-2018-keynote)

## Reference Scenes

![Cornell Box](https://upload.wikimedia.org/wikipedia/commons/2/24/Cornell_box.png)![Stanford Bunny](https://upload.wikimedia.org/wikipedia/en/a/a7/Stanford_Bunny.png)

- 💾 [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html)
- 💾 [Benedikt Bitterli](https://benedikt-bitterli.me/resources/)
- 💾 [PBRT Scenes v3](https://www.pbrt.org/scenes-v3.html)
- 💾 [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca)
- 💾 [Disney Data Sets](https://www.technology.disneyanimation.com/collaboration-through-sharing)

## News

- 📖 [Graphics Programming Weekly - *Jendrik Illner*](https://www.jendrikillner.com/post/)

## API's

- [Nvidia RTX](https://developer.nvidia.com/rtx)
- [Microsoft DirectX Raytracing (DXR)](https://blogs.msdn.microsoft.com/directx/2018/03/19/announcing-microsoft-directx-raytracing/)
- [Nvidia OptiX](https://developer.nvidia.com/optix)
- [AMD Radeon-Rays](www.realtimerendering.com/raytracing.html)
- [Intel Embree](http://embree.github.io/)

### Nvidia RTX

- 📖 [Introduction to Real-Time Ray Tracing with Vulkan - (2018) *Nuno Subtil*](https://devblogs.nvidia.com/vulkan-raytracing/)
- 📖 [Vulkan Raytracing Tutorials - (2018) *iOrange*](https://iorange.github.io/p02/TeapotAndBunny.html)
- 📺 [Video Series: Practical Real-Time Ray Tracing With RTX - (2018) *Nvidia*](https://devblogs.nvidia.com/practical-real-time-ray-tracing-rtx/)
- 📖 [Effectively Integrating RTX Ray Tracing into a Real-Time Rendering Engine - (2018) *Juha Sjoholm*](https://devblogs.nvidia.com/effectively-integrating-rtx-ray-tracing-real-time-rendering-engine/)

### Microsoft DirectX Raytracing (DXR)

- 📺📖 [Introducion to DirectX Raytracing - (2018) *Chris Wyman, Shawn Hargreaves, Peter Shirley, Colin Barré-Brisebois*](http://intro-to-dxr.cwyman.org/)
- 📖 [DX12 Ray Tracing Tutorials - (2018) *Martin-Karl Lefrançois and Pascal Gautron*](https://news.developer.nvidia.com/dx12-raytracing-tutorials/)
- 💾 [DXRPathTracer](https://github.com/TheRealMJP/DXRPathTracer)
- 📺 [Real-Time Ray Tracing for Interactive Global Illumination Workflows in Frostbite - (2018) *Sebastien Hillaire, Charles de Rousiers, Diede Apers and Petter Edblom*](https://devblogs.nvidia.com/video-real-time-ray-tracing-workflows-frostbite/)

### Nvidia OptiX

- 📖 [OptiX QuickStart - *Nvidia*](https://docs.nvidia.com/gameworks/content/gameworkslibrary/optix/optix_quickstart.htm)
- 📺 [GPU Ray Tracing for Film and Design: High Performance Ray Tracing with OptiX - (2018) *Oliver Klehm*](http://on-demand.gputechconf.com/siggraph/2018/video/sig1812-2-oliver-klehm-high-performance-optix.html)
