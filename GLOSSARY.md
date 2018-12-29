# Glossary of Terms and Acronyms

<dl>
  <dt>Acceleration Structure</dt>
  <dd>A data structure to optimize ray-primitive intersections in a scene. Often a BVH.</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bidirectional_reflectance_distribution_function">BRDF</a></dt>
  <dd>Bidirectional Reflectance Distribution Function</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bidirectional_scattering_distribution_function">BSDF</a></dt>
  <dd>Bidirectional Scattering Distribution Function</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bidirectional_scattering_distribution_function#Overview_of_the_BxDF_functions">BSSRDF</a></dt>
  <dd>Bidirectional Scattering-Surface Reflectance Function</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bidirectional_scattering_distribution_function#Overview_of_the_BxDF_functions">BTDF</a></dt>
  <dd>Bidirectional Transmittance Distribution Function</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bidirectional_texture_function">BTF</a></dt>
  <dd>Bidirectional Texture Function</dd>
  <dt>BVH</dt>
  <dd>Bounding Volume Hierarchy</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bounding_volume_hierarchy">Bounding Volume Hierarchy</a></dt>
  <dd>An acceleration structure that envelopes scene geometry into a tree of volumes.</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Bidirectional_scattering_distribution_function#Overview_of_the_BxDF_functions">BxDF</a></dt>
  <dd>Bidirectional X (anything) Distribution Function. A catch all term for Bidirectional Distribution Functions.</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Caustic_(optics)">Caustics</a></dt>
  <dd>When light transmits through a curved surface such as water ripples or a drinking glass and creates patches of light.</dd>
  <dt>Convergence</dt>
  <dd>When a frame has rendered to within an error threshold or bias. Usually to an acceptable level of noise.</dd>
  <dt>GI</dt>
  <dd>Global Illumination</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Global_illumination">Global Illumination</a></dt>
  <dd>A method of realistic lighting. Light bounces off of objects and is not only direct lighting.</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Lambertian_reflectance">Lambertian</a></dt>
  <dd>A diffuse matte material</dd>
  <dt>Offline</dt>
  <dd>A rendering method that is not intended for interaction. Render times are less important and can take seconds, minutes, hours, or more. Usually very high quality rendering is the goal.</dd>
  <dt>Realtime</dt>
  <dd>A rendering method that is intended for interaction. Usually requires render times in the milliseconds.</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Path_tracing">Path Tracing</a></dt>
  <dd>A method of rendering that is faithful to global illumination.
  <dt>PBR</dt>
  <dd>
    1. Physically Based Rendering
    <br>2. Physically Based Rendering Book
  </dd>
  <dt><a href="https://pbrt.org/">PBRT</a></dt>
  <dd>Physically Based Rendering Book</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Phong_reflection_model">Phong</a></dt>
  <dd>Ambient, diffuse, and specular material</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Ray_casting">Ray Casting</a></dt>
  <dd>
  1. A method of rendering that casts primary rays and returns a color.
  <br>2. Sending a ray into a scene and intersecting with geometry.
  </dd>
  <dt><a href="https://en.wikipedia.org/wiki/Ray_tracing_(graphics)">Ray Tracing</a></dt>
  <dd>
  1. A method of rendering that casts rays into a scene.
  <br>2. Whitted style ray tracing. Cast rays and detect shadow and light rays.
  <br>3. Path tracing.
  </dd>
  <dt>SSS</dt>
  <dd>Subsurface Scattering</dd>
  <dt><a href="https://en.wikipedia.org/wiki/Subsurface_scattering">Subsurface Scattering</a></dt>
  <dd>When light enters a material, scatters, and exits from another point. Example materials requring this method to look realistic are human skin, leaves, wax, and milk.</dd>
</dl>
