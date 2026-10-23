<div align="center">

<img width="860" alt="DRH Color Ramp Studio" src="docs/media/Logo.png" />

# DRH - Color Ramp Studio

**A color ramp that takes twelve clicks today takes one. And you keep the stops editable.**

![Status](https://img.shields.io/badge/Status-Released-22C55E?style=for-the-badge) ![Version](https://img.shields.io/badge/Version-1.1.0-00B7FF?style=for-the-badge) ![Blender](https://img.shields.io/badge/Blender-4.2%2B-0B1F4D?style=for-the-badge) ![Platforms](https://img.shields.io/badge/Platforms-Windows%20%7C%20macOS%20%7C%20Linux-334155?style=for-the-badge)

[![Download](https://img.shields.io/badge/Download-Free%20on%20BlendKit-0B1F4D?style=for-the-badge)](https://www.blendkit.com/asset-gallery-detail/62ac725e-c55e-4e26-9e39-f6b81432d962/) [![Issues](https://img.shields.io/badge/Support-Issues-1E5BFF?style=for-the-badge)](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues) [![Hub](https://img.shields.io/badge/DRH-Hub-334155?style=for-the-badge)](https://github.com/pacosalasv/DRH_Addons_Hub)

</div>

## The wall

You have a reference image, a brand palette, or a mood in your head. Blender gives you two stops and a slider. Getting from that to a ramp you actually like means adding stops one at a time, guessing at hex values, and rebuilding the whole thing when the client says "warmer."

Color Ramp Studio 1.1.0 shortens that loop. Build a ramp from a preset, an image, or a screen sample, edit it in sRGB where your eyes work, and convert it into a node group when you need to reuse it. Convert back to a native ramp whenever you want, which matters if you've ever been handed a .blend full of nested groups you didn't make.

<img src="docs/media/ScreenShot_01.png" alt="Preset library with color family filtering" width="100%" />

## What's in it

**Presets you can filter, not scroll.** Category, text search, and dominant color family stack together. There's a dedicated Grayscale category, and the library got curated in 1.1.0 to drop families that looked the same as each other.

**Sampling that doesn't invent colors.** Point at an image or a screen region and get a usable ramp. Image handling runs on a temporary datablock the add-on owns, with bounded pixel sampling, and the sRGB to linear conversion happens on an explicit pipeline instead of by accident.

**Editing that understands color.** Hue, saturation, harmony, and temperature style moves happen in sRGB-aware space before values return to Blender's linear RGB. Stops can be copied, pasted, reversed, normalized, redistributed, randomized, simplified, sorted, mirrored, rotated, nudged, or refined one at a time.

**Conversion with a way back.** Ramps convert into editable group-based setups and restore to native ramps. Cleanup after a failed conversion is transactional, so a bad pass doesn't leave orphaned nodes in your tree.

**Alpha handled like color.** Set a uniform alpha, build an alpha gradient, and keep alpha edits through conversion.

Works across Shader Editor, Geometry Nodes, and Compositor wherever the node types exist. New ramps land at the center of your visible canvas instead of wherever the node cursor happened to be pointing.

## Who it's for

Material artists who build ramps all day. Technical artists who need ramps generated to a rule instead of by feel. Anyone handed a shader file by someone else and told to "just tweak the colors."

## Get it

Free on BlendKit. Blender 4.2 or newer.

[![Download on BlendKit](https://img.shields.io/badge/Get%20Color%20Ramp%20Studio-BlendKit-1597E5?style=for-the-badge&logo=blender)](https://www.blendkit.com/asset-gallery-detail/62ac725e-c55e-4e26-9e39-f6b81432d962/)

Changelog: [CHANGELOG.md](CHANGELOG.md) · Manual: [docs](docs) · Bugs and requests: [open an issue](https://github.com/pacosalasv/DRH_Color_Ramp_Studio-Support/issues)

A rating on BlendKit puts this in front of the next artist searching for it.

<div align="center">
  <a href="https://ko-fi.com/pacosalasv">
    <img width="560" alt="Support on Ko-fi" src="docs/media/SupportMe.png" />
  </a>
</div>
