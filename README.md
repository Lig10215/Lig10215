# Lig10215

Independent developer working on **3D Gaussian Splatting (3DGS)** tooling — local reconstruction workstations, model fusion, and repair pipelines.

## What I build

| Project | What it does |
| :--- | :--- |
| [LigSplat](https://github.com/Lig10215/LigSplat) | Local Vulkan-based 3DGS workstation for Windows x64. Train, view and export splat scenes without a cloud dependency. GPL-3.0. |
| [gaussian-splat-fusion](https://github.com/Lig10215/gaussian-splat-fusion) | Align, fuse, repair and verify existing 3DGS PLY models. Covers aerial + ground capture fusion, floating artifacts, and occlusion repair. CPU-only. |

## Focus areas

- Large-scale scene reconstruction from combined aerial and ground captures
- Repairing splat models: floaters, duplicated surfaces, transparent structures
- Vulkan / native GPU rendering for real-time splat viewing on desktop
- Keeping the whole pipeline local — no uploads, no cloud round-trips

## Toolbox

`Python` `C++` `Vulkan` `PyTorch` `Open3D` `COLMAP` `Linux` `Windows`

## Elsewhere

- Latest build: [LigSplat releases](https://github.com/Lig10215/LigSplat/releases/latest)
- Open to issues, bug reports and feature discussions on any repo
