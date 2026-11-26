# 🏙️ Awesome Generative 3D Architecture & World Building

<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Generative 3D Architecture & World Building Banner" width="100%" />
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badgel&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Generative-3D-Architecture-World-Building/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Generative-3D-Architecture-World-Building?style=social&color=white" alt="GitHub stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Generative-3D-Architecture-World-Building/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Generative-3D-Architecture-World-Building?style=social&color=white" alt="GitHub forks" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta200?label=Follow" /></a>
</p>

---

## 🌟 Executive Summary & Introduction

Welcome to **Awesome Generative 3D Architecture & World Building**, the ultimate curated index of state-of-the-art **commercial SaaS suites**, **open-source 3D foundation models**, **neural scene reconstruction pipelines**, and **procedural world generators**. 

Whether you are designing digital twins, building AAA game landscapes, synthesizing synthetic training environments for embodied robotics, or exploring text/image-to-3D neural meshes, this knowledge base catalogs industry leaders and bleeding-edge GitHub repositories updated continuously.

### 🎯 Key Focus Areas
- 🏛️ **Procedural Architecture & City Generation**: Synthesizing floorplans, structural topology, and complex urban environments.
- 🌍 **Procedural 3D World Building**: Infinite photorealistic biomes, terrain generation, and physics-ready spatial environments.
- 🔮 **Neural 3D Foundation Models**: Text-to-3D, Image-to-3D, and Multiview-to-3D PBR mesh generation (`TRELLIS`, `Hunyuan3D-2`, `TripoSR`).
- ⚡ **3D Gaussian Splatting & NeRFs**: Real-time volumetric radiance fields, view synthesis, and dense monocular depth estimation (`gsplat`, `nerfstudio`, `DUSt3R`).

---

## 📑 Table of Contents

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [☁️ SaaS/Hosted & Commercial Platforms](#️-saashosted--commercial-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [📈 Star History](#-star-history)
- [🛠️ How to Contribute](#️-how-to-contribute)
- [💖 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics

The global **Generative 3D, Procedural World Building & Spatial Content Creation** market is valued at approximately **$4.5B–$6.2B in 2026** and is projected to expand at a compound annual growth rate (CAGR) of **~28%–35%** through 2030, accelerated by real-time game asset synthesis, architectural digital twins, and synthetic 3D spatial simulations for robotics and embodied AI. 

The sector is currently **moderately fragmented** across specialized proprietary foundation model providers (e.g., Luma AI, Meshy, Tripo3D, Rodin/Hyper3D, Spline) rather than a winner-take-all monopoly, while facing strong competitive pressure from high-performing open-source weights (`Microsoft TRELLIS`, `Tencent Hunyuan3D-2`, `Infinigen`, `nerfstudio`).

---

## ☁️ SaaS/Hosted & Commercial Platforms

*Sorted descending by company scale (valuation / annual revenue).*

| Platform | Description | Company Scale (Valuation / Revenue) | Starting Paid Tier | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[Luma AI (Luma Genie)](https://lumalabs.ai)** | Multimodal 3D capture and generative 3D asset/world creation suite turning text prompts, images, and smartphone videos into PBR 3D meshes and NeRFs. | **~$300M–$500M+ Valuation** ($70M+ VC funding led by a16z) | **$30.00 / month** ($25.00/mo billed annually for Plus plan, 10,000 generation credits/mo) | **Forever Free Account** (Free mobile 3D NeRF/Gaussian Splatting captures; text-to-3D Genie generations require paid credit packs or subscription) |
| **[Meshy.ai](https://meshy.ai)** | Leading AI 3D model and PBR texture generator turning text and concept art into game-ready, auto-rigged, and retopologized 3D assets in seconds. | **~$100M–$200M Est. Valuation** (~$15M–$25M+ est. ARR; >2M 3D creators) | **$16.00 / month** billed annually ($20.00/mo monthly for Pro plan with 1,000 credits/mo) | **Forever Free Plan** (**200 free generation credits/month**, max 10 tasks/day, personal CC-BY-4.0 non-commercial downloads) |
| **[Tripo3D (VAST AI)](https://tripo3d.ai)** | High-speed 3D foundation model SaaS and developer API generating clean quad-retopologized, rigged, and textured 3D meshes from text or single images. | **~$100M+ Est. Valuation** ($30M+ VC funding; creators of open-source TripoSR) | **$15.90 / month** billed annually ($19.90/mo monthly for Professional plan, 3,000 credits/mo) | **Forever Free Plan** (**300 free credits/month** (~10–30 models/mo), standard generation queue, personal non-commercial license) |
| **[Spline](https://spline.design)** | Collaborative browser-based 3D design, interactive web animation, and AI 3D generation tool exporting directly to React, Three.js, and iOS/visionOS. | **~$50M–$100M Est. Valuation** ($15M+ VC funding led by Gradient & First Round) | **$12.00 / month** billed annually ($15.00/mo monthly for Starter plan; $24.00/mo for Super with AI 3D features) | **Forever Free Plan** (Unlimited personal files, interactive web embeds with Spline watermark, and **20 MCP calls/day**; AI 3D generation requires paid tier) |
| **[Rodin Gen-1 / Gen-2 (Deemos / Hyper3D)](https://hyper3d.ai)** | High-precision 3D generative platform producing detailed, part-aware 3D assets and photorealistic PBR materials from multi-view images and text. | **~$50M–$100M Est. Valuation** (Venture-backed spatial AI foundation lab) | **$24.00 / month** billed annually ($30.00/mo monthly for Creator plan, ~60 high-fidelity exports/mo) | **Forever Free Plan** (**10 free signup credits**, unlimited free low/medium preview generations, and up to 10 private asset slots; charged upon final export) |
| **[Kaedim](https://kaedim3d.com)** | Hybrid AI + artist-in-the-loop 3D production pipeline converting 2D concept art into studio-grade, clean-topology, UV-unwrapped game and architectural assets. | **~$50M–$80M Est. Valuation** ($15M+ Series A led by a16z) | **$29.00 / month** for Starter tier ($150.00/mo for Studio plan with 10 production assets) | **7-day Trial / Demo Pilot** (Access to pre-generated downloadable 3D sample packs and scheduled custom pilot test; no perpetual free generation tier) |
| **[CSM 3D (Common Sense Machines)](https://csm.ai)** | Multimodal 3D world and asset generation platform converting images, sketches, and videos into controllable 3D meshes, environments, and world models. | **~$40M–$70M Est. Valuation** (Acquired by Alphabet; previously $15M+ VC funding) | **$20.00 / month** for Maker plan (100 credits/mo; enterprise pipelines via Alphabet) | **Forever Free Tinkerer Plan** (**10 starter credits** on signup for slow public queue previews; CC BY 4.0 license and no API access) |
| **[Masterpiece X](https://masterpiecex.com)** | Text-to-3D generative platform built for game developers and XR creators, outputting textured, auto-rigged, and animated FBX/GLB models in browsers. | **~$15M–$30M Est. Valuation** (~$10M+ VC funding; Canadian spatial AI company) | **$10.99 / month** for Starter plan (750 credits/mo with commercial export rights) | **Forever Free Tier** (**250 free signup credits** upon registration to generate, auto-rig, and download introductory 3D models) |
| **[Sloyd.ai](https://sloyd.ai)** | Parametric + AI 3D asset generator and SDK creating customizable, clean-topology architectural props, buildings, and game assets in real time. | **~$10M–$25M Est. Valuation** (Venture-backed Norwegian 3D tech startup) | **$15.00 / month** billed annually ($20.00/mo monthly for Plus plan) | **Forever Free Guest Plan** (**1 free AI 3D generation per day**, unlimited real-time parametric editor tweaks, personal non-commercial license) |
| **[3DFY.ai](https://3dfy.ai)** | Automated prompt-to-3D and scalable catalog generation platform synthesizing clean, segmented, UV-mapped 3D models for virtual worlds and e-commerce. | **~$10M–$20M Est. Valuation** (Venture-backed Israeli generative 3D company) | **$20.00 / month** for Starter plan (10 generation credits/mo + standard downloads) | **Free Trial Plan** (**10 free generation credits** upon account registration to test prompt-to-3D texturing and GLB/FBX exports) |

---

## 💻 Open-Source GitHub Projects

*Sorted descending by GitHub star counts. Each star badge links to the repository's stargazers page.*

| Project | Stars | License | Description |
| :--- | :--- | :--- | :--- |
| **[Blender (`blender/blender`)](https://github.com/blender/blender)** | [![Stars](https://img.shields.io/github/stars/blender/blender?style=social&color=white)](https://github.com/blender/blender/stargazers) | **GPL-2.0+** | The premier open-source 3D creation suite powering procedural geometry nodes, computational architecture, rendering, and synthetic world generation pipelines. |
| **[Hunyuan3D-2 (`Tencent/Hunyuan3D-2`)](https://github.com/Tencent/Hunyuan3D-2)** | [![Stars](https://img.shields.io/github/stars/Tencent/Hunyuan3D-2?style=social&color=white)](https://github.com/Tencent/Hunyuan3D-2/stargazers) | **Tencent License** | State-of-the-art open-weight foundation model suite for high-resolution 3D asset generation with large-scale diffusion models. |
| **[TRELLIS (`microsoft/TRELLIS`)](https://github.com/microsoft/TRELLIS)** | [![Stars](https://img.shields.io/github/stars/microsoft/TRELLIS?style=social&color=white)](https://github.com/microsoft/TRELLIS/stargazers) | **MIT** | Microsoft's structured 3D latent foundation model producing production-grade 3D assets, radiance fields, and PBR textured meshes from single images. |
| **[Open3D (`isl-org/Open3D`)](https://github.com/isl-org/Open3D)** | [![Stars](https://img.shields.io/github/stars/isl-org/Open3D?style=social&color=white)](https://github.com/isl-org/Open3D/stargazers) | **MIT** | Modern open-source library for 3D spatial data processing, point clouds, meshes, scene reconstruction, and spatial machine learning. |
| **[Nerfstudio (`nerfstudio-project/nerfstudio`)](https://github.com/nerfstudio-project/nerfstudio)** | [![Stars](https://img.shields.io/github/stars/nerfstudio-project/nerfstudio?style=social&color=white)](https://github.com/nerfstudio-project/nerfstudio/stargazers) | **Apache-2.0** | Modular framework for end-to-end Neural Radiance Field (NeRF) development, real-time export, and 3D Gaussian Splatting scene creation. |
| **[Stable-Dreamfusion (`ashawkey/stable-dreamfusion`)](https://github.com/ashawkey/stable-dreamfusion)** | [![Stars](https://img.shields.io/github/stars/ashawkey/stable-dreamfusion?style=social&color=white)](https://github.com/ashawkey/stable-dreamfusion/stargazers) | **Apache-2.0** | PyTorch implementation of text-to-3D and image-to-3D synthesis with NeRFs, score distillation sampling (SDS), and mesh exportation. |
| **[Infinigen (`princeton-vl/infinigen`)](https://github.com/princeton-vl/infinigen)** | [![Stars](https://img.shields.io/github/stars/princeton-vl/infinigen?style=social&color=white)](https://github.com/princeton-vl/infinigen/stargazers) | **BSD-3-Clause** | Princeton's procedural generator for infinite photorealistic natural 3D worlds, biomes, terrains, and physics assets built on Blender. |
| **[TripoSR (`VAST-AI-Research/TripoSR`)](https://github.com/VAST-AI-Research/TripoSR)** | [![Stars](https://img.shields.io/github/stars/VAST-AI-Research/TripoSR?style=social&color=white)](https://github.com/VAST-AI-Research/TripoSR/stargazers) | **MIT** | Fast feed-forward 3D reconstruction model generating textured 3D meshes from a single image in under 0.5 seconds on consumer GPUs. |
| **[DUSt3R (`naver/dust3r`)](https://github.com/naver/dust3r)** | [![Stars](https://img.shields.io/github/stars/naver/dust3r?style=social&color=white)](https://github.com/naver/dust3r/stargazers) | **CC-BY-NC-SA-4.0** | Groundbreaking geometric 3D computer vision paradigm for dense multi-view reconstruction and camera calibration without prior poses. |
| **[gsplat (`nerfstudio-project/gsplat`)](https://github.com/nerfstudio-project/gsplat)** | [![Stars](https://img.shields.io/github/stars/nerfstudio-project/gsplat?style=social&color=white)](https://github.com/nerfstudio-project/gsplat/stargazers) | **Apache-2.0** | High-performance, CUDA-accelerated library for rasterizing 3D Gaussian Splatting models with sub-millisecond rendering speeds. |
| **[Depth Pro (`apple/ml-depth-pro`)](https://github.com/apple/ml-depth-pro)** | [![Stars](https://img.shields.io/github/stars/apple/ml-depth-pro?style=social&color=white)](https://github.com/apple/ml-depth-pro/stargazers) | **Apple Sample Code** | Apple's zero-shot metric depth estimation foundation model generating sharp, high-resolution spatial depth maps in under a second. |
| **[InstantMesh (`TencentARC/InstantMesh`)](https://github.com/TencentARC/InstantMesh)** | [![Stars](https://img.shields.io/github/stars/TencentARC/InstantMesh?style=social&color=white)](https://github.com/TencentARC/InstantMesh/stargazers) | **Apache-2.0** | Efficient feed-forward framework synthesizing 3D meshes from a single image via sparse-view diffusion and multi-view reconstruction. |
| **[Zero-1-to-3 (`cvlab-columbia/zero123`)](https://github.com/cvlab-columbia/zero123)** | [![Stars](https://img.shields.io/github/stars/cvlab-columbia/zero123?style=social&color=white)](https://github.com/cvlab-columbia/zero123/stargazers) | **MIT** | Zero-shot novel view synthesis and 3D reconstruction from a single RGB image through camera viewpoint control conditioning. |
| **[Occupancy Networks (`autonomousvision/occupancy_networks`)](https://github.com/autonomousvision/occupancy_networks)** | [![Stars](https://img.shields.io/github/stars/autonomousvision/occupancy_networks?style=social&color=white)](https://github.com/autonomousvision/occupancy_networks/stargazers) | **MIT** | Fundamental continuous 3D implicit representation framework learning continuous surface boundaries from point clouds, voxels, and images. |
| **[Shape As Points (`autonomousvision/shape_as_points`)](https://github.com/autonomousvision/shape_as_points)** | [![Stars](https://img.shields.io/github/stars/autonomousvision/shape_as_points?style=social&color=white)](https://github.com/autonomousvision/shape_as_points/stargazers) | **MIT** | Differentiable Poisson surface reconstruction for synthesizing watertight 3D architectural shapes and geometric manifolds from point clouds. |

---

## 📈 Star History

[![Star History Chart](https://www.star-history.com/svg?repos=ishandutta2007/Awesome-Generative-3D-Architecture-World-Building&type=date&legend=top-left)](https://www.star-history.com/#ishandutta2007/Awesome-Generative-3D-Architecture-World-Building&type=date&legend=top-left)

---

## 🛠️ How to Contribute

Contributions are warmly welcomed! 🤝 To suggest a new commercial platform, open-source 3D foundation model, or procedural world generation tool:

1. 🍴 Fork this repository.
2. 🌿 Create a new feature branch (`git checkout -b feat/add-awesome-tool`).
3. 📝 Add your entry under either the **SaaS/Hosted Platforms** or **Open-Source GitHub Projects** table maintaining strict alphabetical or sorted conventions with exact pricing, free tier limits, and verifiable star links.
4. 🚀 Push your branch and open a clean Pull Request with a clear description.

---

## 💖 Support & Sponsorship

If you find this repository valuable for your research, architectural workflows, or game development pipelines, please consider showing your support:

- ⭐ **Star this repository** to help others discover it across GitHub.
- 🍴 **Fork and share** it with fellow 3D artists, spatial AI researchers, and engineers.
- ☕ **Buy me a coffee & support ongoing maintenance** via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

Your sponsorship directly funds ongoing benchmarking, research into emerging 3D neural foundation models, and community curation! ✨

---

## ⚠️ Disclaimer

*All product names, logos, brands, and registered trademarks cited in this repository are property of their respective owners. Mention of commercial platforms and open-source models does not imply endorsement or official affiliation.*
