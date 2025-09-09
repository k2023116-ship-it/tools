# Toolify Color Picker & Generator — Comprehensive Guide

## Overview
The Toolify Color Picker & Generator helps you extract precise colors from any image, copy HEX/RGB values, assemble custom palettes, and preview CSS gradients. The tool runs fully offline in your browser for privacy and speed.

## Quick Start
1. Open the Color Picker tool.
2. Click "Upload Image" or drag-and-drop an image onto the drop zone.
3. Click anywhere on the image to pick a pixel color.
4. View the color swatch, HEX, and RGB values.
5. Click "+ Add" to store the current color in your palette.
6. With two or more colors in your palette, click "Generate" under Gradient.

## Features
- Pixel-accurate sampling from a canvas-rendered image
- Instant HEX and RGB readouts
- Palette management (add and remove colors)
- Gradient preview using your palette order
- Drag-and-drop image support
- Privacy-friendly: works offline, no uploads

## Supported Inputs
- Images: PNG, JPG/JPEG, and other browser-renderable formats
- Output formats: HEX (e.g., #1A2B3C) and RGB (e.g., rgb(26, 43, 60))

## Palette Management
- Use "+ Add" to append the current color.
- Remove colors with the × icon next to a palette entry.
- The gradient respects the order of colors in your palette; add them in the sequence you want to visualize.

## Gradient Generation
- Requires at least two colors in the palette.
- Uses a horizontal CSS linear gradient at 90 degrees.
- Example:
  ```css
  background: linear-gradient(90deg, #1E3A8A, #22D3EE, #F59E0B);
  ```

## Tips for Accurate Picking
- Zoom your browser (Ctrl/Cmd + +) for finer pixel selection.
- Prefer higher-resolution images for precise sampling.
- Add important colors to your palette as you go to avoid losing a selection.

## Copying Values
- HEX and RGB are displayed beneath the swatch.
- Select the text and copy with Ctrl/Cmd + C.
- Paste directly into your design tools or code editors.

## Privacy & Offline Use
- All processing is local to your device.
- No network requests are made during picking or palette creation.
- Once loaded, the tool works without an internet connection.

## Troubleshooting
- Image not loading: Ensure the file is a valid PNG or JPG and not corrupted.
- No color on click: Wait until the image fully loads onto the canvas.
- Gradient not showing: Add at least two colors to your palette.
- Performance with huge images: Resize the image before uploading for smoother interaction.

## FAQ
- Can I reorder colors? Remove and re-add them in the preferred order.
- Does the tool support alpha? Displayed formats are HEX (no alpha) and RGB.
- Can I pick from outside the image? No, picking is limited to the canvas area.

## Best Practices
- Ensure adequate contrast in palettes for accessibility.
- Test gradients on both light and dark backgrounds.
- Save common brand colors for quicker reuse.

## Changelog
- 1.0.0 — Initial guide documentation for the Color Picker & Generator.

— Made with ❤️ by Toolify
