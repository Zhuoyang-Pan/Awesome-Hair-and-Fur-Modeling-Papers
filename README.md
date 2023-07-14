# Awesome-Hair-and-Fur-Modeling-Papers
A Collection of Papers and Codes about Hair and Fur Modeling

## Catalogue

- [SIGGRAPH 2023](#SIGGRAPH2023)
- [ECCV 2022](#ECCV2022)

<a name="SIGGRAPH2023"></a>
# SIGGRAPH2023 [[back](#catalogue)]

**Sag-free Initialization for Strand-based Hybrid Hair Simulation**
- Paper: https://graphics.cs.utah.edu/research/projects/sag-free-hair/sig23_sagfree-hair.pdf
- Project Website: https://graphics.cs.utah.edu/research/projects/sag-free-hair/
- Tags: Hair Simulation, Strand-based
- Abstract:
  > *This paper proposes a novel four-stage, sag-free initialization framework to solve stable quasistatic configurations for hybrid, strand-based hair dynamic systems. Our results show that our method successfully prevents sagging on various hairstyles and has minimal impact on the hair motion during simulation.*

**CT2Hair: High-Fidelity 3D Hair Modeling using Computed Tomography**
- Code: https://github.com/facebookresearch/CT2Hair
- Project Website: http://yuefanshen.net/CTHair
- Abstract:
  > *We introduce CT2Hair, a fully automatic framework for creating high-fidelity 3D hair models using computed tomography. Our approach utilizes real-world hair wigs as input and is able to reconstruct hair strands for a wide range of hair styles. The 3D hair models are suitable for use in downstream graphics applications.*

**Interactive Hair Simulation on the GPU Using ADMM**
- Paper: https://d1qx31qr3h6wln.cloudfront.net/publications/Interactive%20Hair%20Simulation%20on%20the%20GPU%20Using%20ADMM.pdf
- Project Website: https://research.nvidia.com/publication/2023-08_interactive-hair-simulation-gpu-using-admm
- Abstract:
  > *We design and validate a local-global solver dedicated to the simulation of Kirchhoff rods with Coulomb friction that can fully leverage the massively parallel compute capabilities of moderns GPUs, enabling interactive physics-based simulation and authoring of virtual grooms.*

**A Practical Wave Optics Reflection Model for Hair and Fur**
- Paper: https://mandyxmq.github.io/research/assets/WaveFiber3d_paper_compress.pdf
- Project Website: https://mandyxmq.github.io/research/wavefiber_3d.html
- Abstract:
  > *We propose a practical model for simulating wave effects from rough fibers with arbitrary 3D microgeometry. This model can be easily combined with existing scattering models to render hair and fur of various colors, adding colorful glints that were missing from previous models.*

**NeRF-Texture: Texture Synthesis with Neural Radiance Fields**
- Paper: [Coming Soon]
- Code: https://github.com/yihua7/NeRF-Texture
- Project Website: https://yihua7.github.io/NeRF-Texture-web/
- Abstract:
  > *We propose NeRF-Texture, a novel texture synthesis method based on NeRF. It effectively models real-world textures containing both meso-scale geometry and view-dependent appearance by utilizing a coarse-fine disentanglement representation and synthesizes NeRF textures of arbitrary sizes via patch matching, which can be applied to new surfaces to add rich details.*

<a name="ECCV2022"></a>
# ECCV2022 [[back](#catalogue)]

**Neural Strands: Learning Hair Geometry and Appearance from Multi-View Images**
- Paper: https://arxiv.org/pdf/2207.14067.pdf
- Project Website: https://radualexandru.github.io/neural_strands/
- Abstract:
  > *We present Neural Strands, a novel learning framework for modeling accurate hair geometry and appearance from multi-view image inputs. The learned hair model can be rendered in real-time from any viewpoint with high-fidelity view-dependent effects. Our model achieves intuitive shape and style control unlike volumetric counterparts. To enable these properties, we propose a novel hair representation based on a neural scalp texture that encodes the geometry and appearance of individual strands at each texel location. Furthermore, we introduce a novel neural rendering framework based on rasterization of the learned hair strands. Our neural rendering is strand-accurate and anti-aliased, making the rendering view-consistent and photorealistic. Combining appearance with a multi-view geometric prior, we enable, for the first time, the joint learning of appearance and explicit hair geometry from a multi-view setup. We demonstrate the efficacy of our approach in terms of fidelity and efficiency for various hairstyles.*
