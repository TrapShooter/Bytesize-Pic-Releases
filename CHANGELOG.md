# Changelog

All notable changes to Bytesize Pic are documented here.

## [1.2.0] - 2026-06-11

### New features

- Testing
- Color & Tone panel overhauled: effects are now multi-instance and can be reordered via drag-and-drop
- New effects: Noise/Grain, Gradient Map, and Brightness/Contrast
- Modulate effect renamed to Hue/Saturation
- Colorize mode added to Hue/Saturation
- Brightness/Contrast is now a dedicated effect (Brightness moved out of Hue/Saturation)
- Brightness now offers Multiply and Lift modes
- Blend mode selector for Tint effect
- Gradient mode for Tint effect
- Transparency grid background setting for previews
- Hover previews now preserve transparency: images with an alpha channel are shown as PNG instead of JPEG so transparency is visible in the preview
- Undo/redo for settings and file list changes
- Sidebar cards can now collapse individual sections independently

### Improvements

- Color fields now use a consistent swatch + hex text input across all effects

### Fixes

- Fixed previews not regenerating when switching between basic and advanced mode
- Fixed context menu not closing on scroll or when another menu opens
- Fixed Tint effect stripping transparency on images with an alpha channel

## [1.1.0] - 2026-06-08

### New features

- Lightbox filmstrip for quick file navigation
- Before/After comparison toggle in toolbar and lightbox
- Collapsible settings sidebar in lightbox
- Sharpen, Blur, and Threshold controls in Color & Tone
- Fill crop position control
- Multiple folders can be selected at once via Add Folders
- Scrolling filename on hover for truncated names
- One-click in-app updates: the update banner now downloads and installs the new version directly. No browser or manual download required.
- What's New window: view the full release history from the update banner or Settings.

### Improvements

- Relative path prefix shown in lighter color on filenames and lightbox
- Hover tooltips on settings fields
- Improved section spacing in settings
- Per-format reset buttons in advanced format options
- Renamed "Exact output size" to "Exact size with padding"

## [1.0.1] - 2026-05-27

### New features

- Added auto-update checks based on the current app version compared to the last GitHub release.
- Added usage analytics. The app now collects anonymous usage data to help guide future improvements. This includes app launches, batch counts, output format, and which options were active — nothing more. Your images never leave your device and no personal information is collected.

## [1.0.0] - 2026-05-20

### Initial release

- Batch image compression and conversion (JPEG, PNG, WebP, AVIF, GIF, TIFF, HEIC)
- Drag-and-drop file and folder input
- Per-format quality control with presets
- Resize with multiple modes: scale, contain, extend, crop
- Configurable resampling (Lanczos, Mitchell, Nearest)
- Transforms: flip horizontal/vertical, rotate, grayscale, blur, sharpen
- Color/tone adjustments: brightness, contrast, saturation, hue
- Advanced per-format encoding options (progressive JPEG, lossless WebP, AVIF effort, PNG palette, TIFF compression, HEIC codec)
- Preset system with import/export support
- Output modes: alongside originals or to a separate output folder
- Live optimized preview with Ctrl+hover comparison
- Concurrent batch processing with configurable worker count (1–8)
- Desktop notifications on batch completion
- Processing log export
- Settings window with performance and notification configuration
