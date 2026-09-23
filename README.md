<div align="center">

<img width="860" alt="DRH - Color Ramp Studio featured image" src="docs/media/Featured_Image.png" />

# DRH - Color Ramp Studio

**Color Ramp generation, conversion, sampling, and editing tools**

![Status](https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge) ![Version](https://img.shields.io/badge/Version-1.0.0-00B7FF?style=for-the-badge) ![Blender](https://img.shields.io/badge/Blender-4.2%2B-0B1F4D?style=for-the-badge) ![Platforms](https://img.shields.io/badge/Platforms-Windows%2C%20macOS%2C%20Linux-334155?style=for-the-badge)

[![Download](https://img.shields.io/badge/Download-Open-0B1F4D?style=for-the-badge)](https://www.blendkit.com/asset-gallery-detail/62ac725e-c55e-4e26-9e39-f6b81432d962/) [![Support](https://img.shields.io/badge/Support-Issues%20%26%20Discussions-1E5BFF?style=for-the-badge)](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues) [![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add-ons%20Hub-Visit-334155?style=for-the-badge)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

---

## Overview

DRH - Color Ramp Studio is a Blender workflow utility designed to make Color Ramp creation, editing, conversion, sampling, and reuse easier across visual workflows.

It is intended for users who work with materials, shaders, procedural textures, Geometry Nodes, compositing, look development, gradients, palettes, and color-driven effects.

## Product status

| Item | Details |
|---|---|
| Status | **Released** |
| Version | 1.0.0 |
| Blender | 4.2+ |
| Platforms | Windows, macOS, Linux |
| Availability | Free public release. |
| Distribution | Official installable releases are distributed through the linked download page. |
| Repository role | Documentation, support, issue tracking, compatibility feedback, and product feedback |

GitHub is used for documentation, support, issues, and release information; installable packages are not mirrored here.

## Capabilities

| Details |
|---|
| Image-to-ramp palette extraction for faster look development |
| Non-destructive conversion of native ramps into editable advanced workflows |
| Copy, paste, and transfer tools for reusing ramps across node setups |
| Screen color sampling for palette capture directly from visual references |
| Ramp cleanup and refinement tools for positions, colors, alpha, and distribution |
| Restore tools for safe round-tripping after conversion |
| Preset browser with previews, search, and color-family filtering |
| Works across Shader Editor, Geometry Nodes, and Compositor |

## Media

Primary product screenshots are shown below. Additional screenshots, when present, remain in `docs/media/`.

<div align="center">
  <img width="420" alt="DRH - Color Ramp Studio ScreenShot 01" src="docs/media/ScreenShot_01.png" />
  <img width="420" alt="DRH - Color Ramp Studio ScreenShot 02" src="docs/media/ScreenShot_02.png" />
  <img width="420" alt="DRH - Color Ramp Studio ScreenShot 03" src="docs/media/ScreenShot_03.png" />
  <img width="420" alt="DRH - Color Ramp Studio ScreenShot 04" src="docs/media/ScreenShot_04.png" />
</div>

Additional repository screenshots: `ScreenShot_05.png`, `ScreenShot_06.png`, `ScreenShot_07.png`, `ScreenShot_08.png`.

## Product reference

<details>
<summary>Open detailed feature reference</summary>

### Feature reference

#### Ramp generation
| Details |
|---|
| Generate ramps from presets |
| Generate ramps from images |
| Generate ramps from complementary palettes |
| Generate ramps from analogous palettes |
| Generate ramps from greyscale palettes |
| Generate ramps from random palettes |
| Generate ramps from stripe palettes |
| Adjustable stop count |
| Interpolation controls |
| Distribution controls |
| Randomized stop positions |
| Decimal limiting for stop positions |

#### Conversion and restore
| Details |
|---|
| Convert native Color Ramp nodes |
| Build editable group-based ramp workflows |
| Restore converted ramps |
| Safe conversion flow |
| Warning handling for lossy conversion cases |
| Add Group Input links |
| Expose ramp controls to group inputs |

#### Sampling and image workflows
| Details |
|---|
| Extract palettes from image files |
| Screen color sampler workflow |
| Capture backend diagnostics |
| Merge similar neighboring stops |
| Load a reference image |
| Clear the reference image |
| Open an Image Editor workspace helper |
| Close the temporary Image Editor helper |

#### Editing and cleanup
| Details |
|---|
| Copy ramp |
| Paste ramp |
| Redistribute stops |
| Reverse stops |
| Normalize stops |
| Randomize stops |
| Duplicate midpoints |
| De-duplicate midpoints |
| Simplify sampled stops |
| Limit stop decimals |
| Nudge stop positions |
| Set uniform alpha |
| Create alpha gradients |

#### Color design tools
| Details |
|---|
| Invert colors |
| Sort by luminance |
| Sort by hue |
| Mirror ramp colors |
| Shuffle ramp colors |
| Rotate ramp colors |
| Shift color temperature |
| Apply harmony modes |
| Shape values for contrast |
| Shape values for cinematic looks |
| Shape values for pastel looks |
| Shape values for deep-shadow looks |
| Mutate palettes to softer variants |
| Mutate palettes to darker variants |
| Mutate palettes to vivid variants |
| Mutate palettes to desaturated variants |
| Mutate palettes with warm shifts |
| Mutate palettes with cool shifts |

#### Smart builders
| Details |
|---|
| Highlights / Midtones / Shadows builder |
| Terrain Mask builder |
| Stylized Sky builder |
| Heat Map builder |
| Skin Tones builder |

#### Presets and workflow
| Details |
|---|
| Preset browser with thumbnail previews |
| Search presets by name |
| Filter presets by dominant color family |
| Context-menu helpers |
| Sidebar settings workflow |
| Support for Shader Editor |
| Support for Geometry Nodes |
| Support for Compositor |

</details>

## Documentation and support

| Resource | Link |
|---|---|
| Support guide | [SUPPORT.md](SUPPORT.md) |
| User manual | [PDF manual](docs/manual/user-manual.pdf) |
| Repository changelog | [CHANGELOG.md](CHANGELOG.md) |
| Issues | [Open or review issues](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues) |
| Discussions | [Ask questions and share feedback](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/discussions) |

## Support development

Ko-fi support is optional. Contributions help fund maintenance, Blender compatibility work, documentation, testing, and continued development of free DRH tools.

<div align="center">
  <a href="https://ko-fi.com/pacosalasv">
    <img width="620" alt="Support Paco Salas | DRH on Ko-fi" src="docs/media/SupportMe.png" />
  </a>
</div>

## Ecosystem

| Destination | Link |
|---|---|
| Download | [Official product page](https://www.blendkit.com/asset-gallery-detail/62ac725e-c55e-4e26-9e39-f6b81432d962/) |
| DRH Add-ons Hub | [Catalog and roadmap](https://github.com/pacosalasv/DRH_Addons_Hub) |
| Paco Salas | DRH | [GitHub profile](https://github.com/pacosalasv) |
| Ko-fi | [Support development](https://ko-fi.com/pacosalasv) |

## License

See [LICENSE](LICENSE) for repository licensing terms.
