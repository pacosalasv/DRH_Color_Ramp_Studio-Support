<div align="center">
  <img width="680" alt="Color Ramp Studio banner" src="https://github.com/user-attachments/assets/f30d565c-d040-471d-86d9-0b774c0351e1" />
</div>

<br>

<div align="center">

# Color Ramp Studio

### Public Support Hub · Documentation · Feedback · Pre-release Validation

**A Blender utility for creating, converting, sampling, refining, and managing Color Ramp workflows.**

![Status](https://img.shields.io/badge/status-production%20ready%2C%20pending%20approval-F59E0B?style=for-the-badge)
![Version](https://img.shields.io/badge/version-1.0.0-00B7FF?style=for-the-badge)
![Blender](https://img.shields.io/badge/blender-4.2%2B-0B1F4D?style=for-the-badge)
![Platforms](https://img.shields.io/badge/platforms-Windows%20%7C%20macOS%20%7C%20Linux-EAF2FF?style=for-the-badge&labelColor=0B1F4D&color=EAF2FF)

<br>

**Part of the DRH Add-ons ecosystem — Blender tools, updates, and releases.**

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

<!--
<div align="center">

[![Superhive](https://img.shields.io/badge/Superhive-Coming%20Soon-1E5BFF?style=for-the-badge)](#)
[![Gumroad](https://img.shields.io/badge/Gumroad-Coming%20Soon-00B7FF?style=for-the-badge)](#)
[![BlenderKit](https://img.shields.io/badge/BlenderKit-Coming%20Soon-0B1F4D?style=for-the-badge)](#)

</div>
-->

---

<div align="center">

**Color Ramp Studio** helps Blender users build, sample, convert, organize, and refine Color Ramp setups more efficiently.

This repository is the central public hub for support, documentation, issue tracking, compatibility feedback, and community validation before marketplace release.

</div>

---

<details>
  <summary><strong>📚 Table of Contents</strong></summary>

## Menu

- [Overview](#overview)
- [Media preview](#media-preview)
- [What Color Ramp Studio does](#what-color-ramp-studio-does)
- [Key features](#key-features)
- [Full feature list](#full-feature-list)
- [Who is it for?](#who-is-it-for)
- [Current status](#current-status)
- [Feedback wanted before release](#feedback-wanted-before-release)
- [Quick links](#quick-links)
- [Before you post](#before-you-post)
- [Where to post](#where-to-post)
- [Support policy](#support-policy)
- [Technical notes](#technical-notes)
- [Availability](#availability)
- [Documentation](#documentation)
- [License](#license)

</details>

---

## Overview

**Color Ramp Studio** is a Blender workflow utility designed to make Color Ramp creation, editing, conversion, sampling, and reuse easier across visual workflows.

It is intended for users who work with materials, shaders, procedural textures, Geometry Nodes, compositing, look development, gradients, palettes, and color-driven effects.

Instead of rebuilding ramps manually or losing useful color setups inside isolated node trees, Color Ramp Studio helps turn Color Ramp workflows into a more reusable, editable, and organized process.

<!--

---

## Media preview

### Demo video

Replace `YOUTUBE_VIDEO_ID` with your real YouTube video ID.

Example:
https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID

<div align="center">
  <a href="https://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID" target="_blank">
    <img width="720" alt="Color Ramp Studio demo video" src="https://img.youtube.com/vi/YOUTUBE_VIDEO_ID/maxresdefault.jpg" />
  </a>
  <br>
  <sub>Click the image to watch the demo on YouTube.</sub>
</div>
-->

<!--
### Quick demo GIF

Recommended size: 1280x720 or 960x540.

<div align="center">
  <img width="720" alt="Color Ramp Studio quick demo" src="docs/media/color-ramp-studio-demo.gif" />
</div>
-->

<!--
### Screenshots

<div align="center">

| Ramp Creation | Ramp Refinement |
|---|---|
| <img width="420" alt="Color Ramp Studio creation view" src="docs/media/screenshot-create.png" /> | <img width="420" alt="Color Ramp Studio refinement view" src="docs/media/screenshot-refine.png" /> |

| Image Sampling | Node Workflow |
|---|---|
| <img width="420" alt="Color Ramp Studio image sampling" src="docs/media/screenshot-sampling.png" /> | <img width="420" alt="Color Ramp Studio node workflow" src="docs/media/screenshot-nodes.png" /> |

</div>
-->

<!--
### Visual preview

Use this section if you want one large image instead of a gallery.

<div align="center">
  <img width="760" alt="Color Ramp Studio preview" src="docs/media/color-ramp-studio-preview.png" />
</div>
-->

<!--
Temporary placeholder while media is not available.

<div align="center">

Media preview coming soon.

</div>
-->

---

## What Color Ramp Studio does

Color Ramp Studio helps you create, sample, convert, refine, restore, and transfer Color Ramp setups inside Blender.

It is not only a simple gradient preset tool. It is designed as a workflow helper for artists and technical users who rely on Color Ramps for materials, procedural effects, masks, stylized looks, terrain, particles, shader variation, and node-based color control.

Use it to:

- Create Color Ramp setups faster
- Generate useful ramp variations
- Sample colors from image-based sources
- Convert color information into usable ramps
- Refine ramp stops and color distribution
- Restore or reuse previous ramp setups
- Transfer Color Ramp data across supported workflows
- Improve shader, material, and procedural color workflows

---

## Key features

- Create Color Ramp workflows for Blender materials and nodes
- Generate ramp structures for faster look development
- Sample palettes from selected image files
- Convert sampled color data into Color Ramp setups
- Refine color positions, stops, and ramp distribution
- Restore or reuse useful ramp configurations
- Transfer ramp data across supported node workflows
- Support cleaner and more repeatable color-driven Blender setups

---

<details>
  <summary><strong>🧩 Full feature list</strong></summary>

## Full feature list

### Color Ramp creation

- Create Color Ramp setups more quickly
- Generate ramp structures for shader and material workflows
- Build reusable color gradients
- Support faster experimentation with procedural color designs
- Reduce repetitive manual ramp setup inside Blender

### Palette and image sampling

- Select image files for palette-based workflows
- Sample colors from image references
- Convert visual references into usable ramp color data
- Support material, shader, and look-development workflows based on existing images
- Help artists move from reference image to Blender ramp faster

### Ramp conversion

- Convert sampled color information into ramp-ready setups
- Transform palette data into organized ramp structures
- Support workflows where color information needs to be reused across nodes
- Help reduce manual color picking and repeated setup work

### Ramp refinement

- Adjust Color Ramp stops and positions
- Refine color distribution
- Improve gradient readability and visual balance
- Support iterative look development
- Help users tune ramps for materials, masks, procedural effects, and stylized shading

### Ramp restoration and reuse

- Restore useful ramp configurations when applicable
- Reuse color setups across different materials or node workflows
- Help preserve useful ramp states during experimentation
- Reduce the need to recreate previous ramp ideas manually

### Node workflow support

- Assist Color Ramp workflows inside Blender node-based contexts
- Support material and shader use cases
- Support procedural workflows where ramps control masks, colors, or transitions
- Help make ramp-heavy node setups easier to manage

### Workflow organization

- Keep Color Ramp work more structured
- Improve repeatability when building materials or shader looks
- Help compare and reuse ramp ideas
- Support faster iteration for artists working with color-driven effects

### Transparency

- Source-based add-on
- No obfuscation
- No binary-only content
- No external services required
- No account requirements
- File access is only used to select image files for palette-based workflows

</details>

---

## Who is it for?

Color Ramp Studio is designed for:

- Blender material artists
- Shader artists
- Procedural texture artists
- Geometry Nodes users
- Compositing users
- Look development artists
- Environment artists
- Stylized rendering artists
- Technical artists
- Asset creators
- Users who work frequently with gradients, palettes, masks, and color-driven node setups

---

## Current status

| Item | Details |
|---|---|
| **Status** | 🟠 Production Ready, Pending Approval |
| **Current version** | 1.0.0 |
| **Minimum Blender version** | 4.2.0 |
| **Platforms** | Windows, macOS, Linux |
| **Release type** | Preparing for public marketplace release |
| **Support repository** | [DRH Color Ramp Studio Support](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support) |

This add-on is production ready and currently pending marketplace approval. Compatibility feedback, usability comments, and workflow suggestions are welcome before public release.

---

## Feedback wanted before release

This repository is open for public feedback before marketplace release.

Feedback is especially welcome on:

- Feature usefulness
- Missing ramp workflow options
- Image sampling expectations
- Material and shader workflow needs
- Geometry Nodes or compositing use cases
- Compatibility concerns
- Installation experience
- Documentation clarity
- Expected pricing
- Marketplace expectations

Useful feedback examples:

> “I would use this to create ramps from reference images.”

> “This should support saving favorite ramp presets.”

> “I need a way to transfer ramps between materials.”

> “This would be useful if it works well with Geometry Nodes.”

> “The sampling workflow should include control over number of colors.”

---

## Quick links

- [Support repository](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support)
- [Ask a question in Discussions](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/discussions)
- [Open a new issue](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues/new/choose)
- [Report a bug](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues/new?template=bug_report.yml)
- [Request a feature](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues/new?template=feature_request.yml)
- [Report a compatibility issue](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues/new?template=compatibility_issue.yml)

---

## Before you post

Please include as much of the following information as possible:

- Add-on version
- Blender version
- Operating system
- Installation method
- Clear steps to reproduce
- Expected result
- Actual result
- Error message, screenshot, or console output when available

For compatibility issues, please also include:

- Blender build type, if known
- Portable or installed Blender version
- Node editor context where the issue happened
- Whether the issue happens with a clean Blender configuration
- Whether the issue involves a specific image file, material, node tree, or scene setup

---

## Use Discussions for

- Questions
- How-to topics
- Installation help
- Compatibility checks
- FAQ
- Suggestions
- Pre-release feedback
- Pricing feedback
- Workflow ideas

---

## Use Issues for

- Confirmed bugs
- Reproducible compatibility problems
- Feature requests
- Regressions
- Marketplace or listing-related problems
- Documentation errors

---

## Where to post

Open a **Discussion** for:

- General questions
- Setup help
- Workflow advice
- Suggestions
- Early feedback

Open an **Issue** for:

- Confirmed bugs
- Reproducible compatibility problems
- Regressions
- Feature requests
- Documentation problems

---

## Support policy

This repository is a public support hub.

Do not post:

- Private account details
- License keys
- Payment information
- Confidential production files
- Private client files
- Sensitive system information

If a private file is required to reproduce an issue, please describe the problem first and wait for further instructions.

---

## Technical notes

This add-on is source based, with:

- No obfuscation
- No binary-only content
- No external services
- No account requirements

File access is only used to:

- Select image files for palette-based workflows

The add-on is intended to work locally inside Blender.

---

## Availability

This add-on may be available through multiple marketplaces and storefronts after release.

This GitHub repository remains the central public location for:

- Support
- Documentation
- Issue tracking
- Compatibility reports
- Public feedback
- Release notes

---

## Documentation

- [User Manual](docs/manual/user-manual.pdf)
- [Changelog](CHANGELOG.md)

---

## License

This repository is distributed under **GPL-3.0-or-later**.

---

<div align="center">

### DRH Add-ons

**Blender tools, updates, and releases.**

Built for clean workflows, practical utilities, and production-friendly Blender setups.

[![DRH Add-ons Hub](https://img.shields.io/badge/DRH%20Add--ons%20Hub-Visit%20Hub-1E5BFF?style=for-the-badge&labelColor=0B1F4D)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>
