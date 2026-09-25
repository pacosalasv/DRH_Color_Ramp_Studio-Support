# Changelog

## 1.1.0 - Color accuracy, presets, safety, and workflow refinement

### Color accuracy and safety
- Standardized preset, hex, screen-sampled, and image-sampled colors around an explicit sRGB-to-linear pipeline before storing colors in Blender ramps.
- Runs HSV-style editing operations in sRGB space and converts the results back to linear RGB for Blender.
- Improved image palette extraction so temporary image data is add-on-owned and existing user image datablocks are not removed.
- Uses bounded pixel sampling instead of copying a complete image pixel buffer into Python.
- Made generated-group conversion cleanup transactional and delays persistent/fake-user assignment until a conversion is ready to commit.

### Presets and discovery
- Refined the preset library to reduce near-duplicate palettes while keeping compatibility aliases for older files.
- Expanded category-based discovery with Trending, Pastel, Dark, Vibrant, Earthy, Warm, Cool, Neutral, and Grayscale categories.
- Preset search, category filtering, and color-family filtering can be combined.
- Refreshed preset-preview caching for the 1.1 release.

### Generator, preferences, and UI
- Reworked the Generator entry point to prepare either Color Sampler or Preset workflows.
- Preset mode now creates a default native Color Ramp and waits for **Generate Ramp** before applying preset colors.
- New ramps are placed at the center of the visible Node Editor canvas.
- Preference changes update defaults without overwriting settings in every open scene.
- Existing scene-level values are preserved during registration.
- Improved reset coverage, migration behavior, diagnostics, and internal namespacing.

### Architecture and compatibility
- Modularized color-space, palette, ramp-algorithm, preset, and image-sampling logic.
- Removed obsolete pre-Blender-4 node-interface branches while retaining Blender 4.2 as the minimum supported version.
- Release packages exclude bytecode caches, ZIPs, and hidden build artifacts.

## 1.0.0 - Initial release
- Initial public release.
