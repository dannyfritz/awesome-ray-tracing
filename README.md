# Awesome Ray Tracing [![CC0 License](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

A curated list of ray tracing resources.
PR's welcome!

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/32/Recursive_raytrace_of_a_sphere.png/240px-Recursive_raytrace_of_a_sphere.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/ec/Glasses_800_edit.png/320px-Glasses_800_edit.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/3/36/Ray-traced_steel_balls.jpg/320px-Ray-traced_steel_balls.jpg" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Global_illumination.JPG" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/c/cb/Alexexterior2.jpg" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Path_tracing_001.png/240px-Path_tracing_001.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/4/40/Glass_ochem.png/640px-Glass_ochem.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/6/63/Glas-1000-enery.jpg/320px-Glas-1000-enery.jpg" height="200">

## Table of Contents

- [Glossary of Terms](GLOSSARY.md)
- [What is Ray Tracing?](#what-is-ray-tracing)
- [Iconic Publications](#iconic-publications)
- [Path Tracing](#path-tracing)
- [Photon Mapping](#photon-mapping)
- [Math](#math)
- [Ray Casting](#ray-casting)
- [BxDF](#bxdf)
- [Sampling Methods](#sampling-methods)
- [Denoising, Filtering, and Reconstruction](#denoising-filtering-and-reconstruction)
- [Realtime](#realtime)
- [Reference Scenes](#reference-scenes)
- [News](#news)
- [API's](#apis)
  - [Vulkan Ray Tracing](#vulkan-ray-tracing)
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

## What is Ray Tracing?

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/8/83/Ray_trace_diagram.svg/320px-Ray_trace_diagram.svg.png" height="200">

- 📺 [Ray Tracing Essentials - (2020) *Eric Haines*](https://www.youtube.com/playlist?list=PL5B692fm6--sgm8Uiava0IIvUojjFOCSR)
- 📺 [Disney's Practical Guide to Path Tracing - (2016) *Disney*](https://youtu.be/frLwRLS_ZR0)
- 📖 [What’s the Difference Between Ray Tracing and Rasterization? - (2018) *Brian Caulfield*](https://blogs.nvidia.com/blog/2018/03/19/whats-difference-between-ray-tracing-rasterization/)
- 📖 [Ray Tracing Resources Page - (2018) *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/raytracing.html)
- 📖 [An Introduction to Ray Tracing - (1991) *Andrew Glassner*](http://www.realtimerendering.com/raytracing/An-Introduction-to-Ray-Tracing-The-Morgan-Kaufmann-Series-in-Computer-Graphics-.pdf)
- 📖 [Physically Based Rendering Book (PBR) - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/)
- 📖 [Ray Tracing in One Weekend - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-in-one-weekend.html)
  - 📖 [Ray Tracing: The Next Week - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/01/ray-tracing-second-weekend.html)
  - 📖 [Ray Tracing: The Rest of Your Life - (2016) *Peter Shirley*](http://in1weekend.blogspot.com/2016/03/ray-tracing-rest-of-your-life.html)
- 📺 [An Explanation of the Rendering Equation - (2019) *Eric Arnebäck*](https://www.youtube.com/watch?v=eo_MTI-d28s)
- 📺 [Ray Marching for Dummies! - (2018) *Martijn Steinrucken*](https://www.youtube.com/watch?v=PGtv-dBi2wE)
- 📺 [Rendering / Ray Tracing Course - (2017) *TU Wien*](https://www.youtube.com/playlist?list=PLujxSBD-JXgnGmsn7gEyN28P1DnRZG7qi)

## Iconic Publications

- 📖 [Some Techniques for Shading Machine Renderings of Solids - (1968) *Arthur Appel*](http://graphics.stanford.edu/courses/Appel.pdf)
- 📖 [An Improved Illumination Model for Shaded Display - (1979) * J.D. Foley and Turner Whitted*](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.156.1534)
- 📖 [The Rendering Equation - (1986) *James T. Kajiya*](http://www.dca.fee.unicamp.br/~leopini/DISCIPLINAS/IA725/ia725-12010/kajiya-SIG86-p143.pdf)
- 📖 [Robust Monte Carlo Methods for Light Transport Simulation (1998) - *Eric Veach*](https://graphics.stanford.edu/papers/veach_thesis/)
- 📖 [Global Illumination Compendium - (2003) *Philip Dutré*](https://people.cs.kuleuven.be/~philip.dutre/GI/TotalCompendium.pdf)


## Path Tracing

- 📖 [Path Tracing - (2017) *Fabio Pellacini and Steve Marschner*](http://pellacini.di.uniroma1.it/teaching/graphics17b/lectures/12_pathtracing.pdf)
- 📖 [Path Tracing in Production - (2018) *Luca Fascione, Johannes Hanika, Rob Pieké, Ryusuke Villemin, Christophe Hery, Manuel Gamito, Luke Emrose, and André Mazzone*](https://jo.dreggn.org/path-tracing-in-production/2018/index.html)
- 📖 [Path Tracing Coherency - *Anders Lindqvist*](https://www.breakin.se/learn/pathtracing-coherency.html)
- 📖 [Path Traced Depth of Field and Bokeh - (2018) *Alan Wolfe*](https://blog.demofox.org/2018/07/04/pathtraced-depth-of-field-bokeh/)
- 📖 [Daily Path Tracer - (2018) *Aras Pranckevičius*](http://aras-p.info/blog/2018/03/28/Daily-Pathtracer-Part-0-Intro/)
- 📖 [Microfacet-based Normal Mapping for Robust Monte Carlo Path Tracing - (2017) *Vincent Schüssler, Eric Heitz, Johannes Hanika, Carsten Dachsbacher*](https://jo.dreggn.org/home/2017_normalmap.pdf)

## Photon Mapping

- 📖 [Photon Mapping - *Zack Waters*](https://web.cs.wpi.edu/~emmanuel/courses/cs563/write_ups/zackw/photon_mapping/PhotonMapping.html)

## Math

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/7/76/Inner-product-angle.svg/320px-Inner-product-angle.svg.png" height="200">

- 📖 [PBRT Chapter 2 Geometry and Transformations - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Geometry_and_Transformations.html)
- 📖 [PBRT Chapter 3 Shapes - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Shapes.html)
- 📖 [Immersive Math - Linear Algebra - (2015) *J. Ström, K. Åström, and T. Akenine-Möller*](http://immersivemath.com/ila/index.html)
- 📺 [Linear Algebra - *Khan Academy*](https://www.khanacademy.org/math/linear-algebra)

## Ray Casting

<img src="https://upload.wikimedia.org/wikipedia/commons/6/6c/Ray_triangle.png" height="150"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Example_of_bounding_volume_hierarchy.svg/320px-Example_of_bounding_volume_hierarchy.svg.png" height="150">

- 📖 [Ray-Triangle Intersection: Geometric Solution - *Scratchapixel*](https://www.scratchapixel.com/lessons/3d-basic-rendering/ray-tracing-rendering-a-triangle/ray-triangle-intersection-geometric-solution)
- 📖 [Realtime Rendering Object/Object Intersection Page - (2019) *Eric Haines*](http://www.realtimerendering.com/intersections.html)
- 📖 [ERIT: A Collection of Efficient and Reliable Intersection Tests - (1998) *Martin Held*](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.49.9172&rep=rep1&type=pdf)
- 📖 [Introduction to Acceleration Structures - *Scratchapixel*](https://www.scratchapixel.com/lessons/advanced-rendering/introduction-acceleration-structure/bounding-volume)
- 📖 [PBRT Chater 4 Primitives and Intersection Acceleration - (2018) *Matt Pharr, Wenzel Jakob, Greg Humphreys, and Morgan Kaufmann*](http://www.pbr-book.org/3ed-2018/Primitives_and_Intersection_Acceleration.html)
- 📖 [Dynamic BVH - (2019) *Erin Catto*](http://box2d.org/files/GDC2019/ErinCatto_DynamicBVH_Full.pdf)
- 📺 [How to Make 3D Fractals](https://www.youtube.com/watch?v=svLzmFuSBhk)

## BxDF

<img src="https://upload.wikimedia.org/wikipedia/en/thumb/d/d8/BSDF05_800.png/179px-BSDF05_800.png" height="200">

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

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a4/Hammersley_set_2D.svg/289px-Hammersley_set_2D.svg.png" height="200">

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

## Denoising, Filtering, and Reconstruction

<img src="https://upload.wikimedia.org/wikipedia/commons/f/f4/Noise_salt_and_pepper.png" height="200">

- 📺 [RTX Coffee Break: Ray Tracing and Denoising - (2018) *Edward Lu*](https://news.developer.nvidia.com/rtx-coffee-break-ray-tracing-and-denoising/)
- 📺 [RTX Coffee Break: Ray Traced Reflections and Denoising - (2018) *Edward Lu*](https://news.developer.nvidia.com/rtx-coffee-break-ray-traced-reflections-and-denoising-952-minutes/)
- 📖 [Spatiotemporal Variance-Guided Filtering: Real-Time Reconstruction for Path-Traced Global Illumination - (2017) *Christoph Schied, Anton Kaplanyan, Chris Wyman, Anjul Patney, Chakravarty R. Alla Chaitanya, John Burgess, Shiqiu Liu, Carsten Dachsbacher, Aaron Lefohn, Marco Salvi*](http://cg.ivd.kit.edu/svgf.php)
- 📖 [Multidimensional Adaptive Sampling and Reconstruction for Ray Tracing - (2008) *Toshiya Hachisuka, Wojciech Jarosz, Richard Peter Weistroffer, Kevin Dale, Greg Humphreys, Matthias Zwicker, and Henrik Wann Jensen*](http://graphics.ucsd.edu/~henrik/papers/multidimensional_adaptive_sampling/)

## Realtime

- 📖 [Real-Time Rendering Chapter - (2018) *Tomas Akenine-Möller, Eric Haines, Naty Hoffman, Angelo Pesce, Michał Iwanicki, and Sébastien Hillaire*](http://www.realtimerendering.com/Real-Time_Rendering_4th-Real-Time_Ray_Tracing.pdf)
- 📺 [Real-Time Raytracing for Interactive Global Illumination Workflows in Frostbite / Shiny Pixels and Beyond: Real-Time Raytracing at SEED - (2018) *Sébastien Hillaire, Johan Andersson, and Colin Barré-Brisebois*](https://youtu.be/rhlGBCSv02M)
- 📖 [Real-Time Ray Tracing of Correct* Soft Shadows - (2018) *Stephen Hill and Morgan McGuire*](http://advances.realtimerendering.com/s2018/s2018_real_time_correct_soft_shadows.pdf)
- 📺 [Stochastic All the Things: Raytracing in Hybrid Real-Time Rendering - (2018) *Tomasz Stachowiak*](https://www.ea.com/seed/news/seed-dd18-presentation-slides-raytracing)
- 📖 [Adopting Lessons From Offline Ray-Tracing to Real-Time Ray-Tracing for Practical Pipelines - (2018) *Matt Pharr*](http://advances.realtimerendering.com/s2018/Pharr%20-%20Advances%20in%20RTR%20-%20Real-time%20Ray%20Tracing.pdf)
- 📖 [Game Ray Tracing: State-of-the-Art and Open Problems - (2018) *Colin Barré Brisebois*](https://www.ea.com/seed/news/hpg-2018-keynote)

## Reference Scenes

<img src="https://upload.wikimedia.org/wikipedia/commons/2/24/Cornell_box.png" height="200"><img src="https://upload.wikimedia.org/wikipedia/en/a/a7/Stanford_Bunny.png" height="200">

- 💾 [McGuire Computer Graphics Archive](http://casual-effects.com/data/index.html)
- 💾 [Benedikt Bitterli](https://benedikt-bitterli.me/resources/)
- 💾 [PBRT Scenes v3](https://www.pbrt.org/scenes-v3.html)
- 💾 [ORCA: Open Research Content Archive](https://developer.nvidia.com/orca)
- 💾 [Disney Data Sets](https://www.technology.disneyanimation.com/collaboration-through-sharing)

## News

- 📖 [Graphics Programming Weekly - *Jendrik Illner*](https://www.jendrikillner.com/post/)

## API's

- [Vulkan Ray Tracing](https://www.khronos.org/registry/vulkan/specs/1.2-extensions/man/html/VK_KHR_ray_tracing.html)
- [Nvidia RTX](https://developer.nvidia.com/rtx)
- [Microsoft DirectX Raytracing (DXR)](https://blogs.msdn.microsoft.com/directx/2018/03/19/announcing-microsoft-directx-raytracing/)
- [Nvidia OptiX](https://developer.nvidia.com/optix)
- [AMD Radeon-Rays](www.realtimerendering.com/raytracing.html)
- [Intel Embree](http://embree.github.io/)

### Vulkan Ray Tracing

- 📖 [Ray Tracing In Vulkan - (2020) *Khronos*](https://www.khronos.org/blog/ray-tracing-in-vulkan)

### Nvidia RTX

- 📖 [NVIDIA Vulkan Ray Tracing Tutorial - (2018) *NVidia*](https://developer.nvidia.com/rtx/raytracing/vkray)
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

- 📖 [Introduction to OptiX - (2017) *Nvidia*](http://on-demand.gputechconf.com/gtc/2017/presentation/s7455-martin-stich-optix.pdf)
- 📖 [OptiX QuickStart - *Nvidia*](https://docs.nvidia.com/gameworks/content/gameworkslibrary/optix/optix_quickstart.htm)
- 📖 [Ray Tracing The Next Week in OptiX - (2018) *João Vítor Silva*](https://joaovbs96.github.io/optix/2018/12/24/next-week.html)
- 💾 [optix_advanced_samples - (2018) *Nvidia*](https://github.com/nvpro-samples/optix_advanced_samples)
- 📺 [GPU Ray Tracing for Film and Design: High Performance Ray Tracing with OptiX - (2018) *Oliver Klehm*](http://on-demand.gputechconf.com/siggraph/2018/video/sig1812-2-oliver-klehm-high-performance-optix.html)
