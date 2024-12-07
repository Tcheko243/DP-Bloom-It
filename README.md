# Bloom It - Blender Compositing Addon

## Overview
Bloom It is a powerful and user-friendly Blender addon that simplifies the process of creating and managing bloom effects in your renders. Designed for Blender 4.2+, it provides an intuitive interface for controlling bloom effects using the compositing nodes system.

## Features

### Core Features
- Quick bloom effect setup with one click
- Real-time parameter adjustments
- Multiple bloom types (Fog Glow, Ghosts, Streaks, Simple Star)
- Advanced color tinting options
- Custom masking system
- Preset management system

### Bloom Controls
- Size: Control the spread of the bloom effect
- Intensity: Adjust the strength of the bloom
- Threshold: Set the brightness threshold for bloom
- Quality: Choose between Low, Medium, and High quality settings

### Advanced Options
- Color tinting with RGB control
- Gamma correction
- Custom mask support
- Layer-based effect control
- Blend mode options
- Streak customization (for Streak type)

### Quality of Life
- Save and load presets
- Node cleanup options
- Real-time updates
- Intuitive UI organization

## Installation

1. Download the latest release (zip file)
2. Open Blender 4.2 or later
3. Go to Edit > Preferences > Add-ons
4. Click "Install" and select the downloaded zip file
5. Enable the addon by checking the checkbox

## Usage

### Basic Setup
1. Open the 3D Viewport
2. Access the Bloom It panel in the sidebar (Press N if sidebar is hidden)
3. Click "Create Bloom" to set up the initial effect
4. Adjust parameters as needed
5. Use "Update Bloom" to apply changes

### Working with Presets
1. Adjust bloom settings to your liking
2. Enter a name for your preset
3. Click the save icon to store the preset
4. Load presets using the load icon

### Advanced Features
- **Masking**: Enable "Use Mask" to control bloom areas
- **Color Tinting**: Enable "Use Color Tint" for colored bloom effects
- **Quality Control**: Adjust quality settings based on your needs
- **Layer Control**: Choose which layers receive the bloom effect

## Settings Reference

### Basic Settings
- **Bloom Type**: Choose between different bloom effects
  - Fog Glow: Soft, atmospheric bloom
  - Ghosts: Lens flare-like effect
  - Streaks: Directional light streaks
  - Simple Star: Star-shaped bloom
- **Size**: Controls the spread of the bloom (1-100)
- **Intensity**: Controls the strength of the effect (0-1)
- **Threshold**: Sets the brightness cutoff for blooming (0-10)

### Advanced Settings
- **Blend Amount**: Controls the mix between original and bloomed image
- **Gamma Correction**: Adjusts the gamma of the bloom effect
- **Mask Threshold**: Controls the mask cutoff point
- **Blur Quality**: Sets the quality of the blur preprocessing

### Streak Settings (Streak type only)
- **Streaks**: Number of light streaks (2-16)
- **Angle Offset**: Rotation of the streak pattern
- **Fade**: Fade-out factor for the streaks

## Compatibility

- Blender 4.2+
- Works with Cycles and Eevee
- Compatible with CPU and GPU rendering
- Supports all standard render resolutions

## Known Issues

- High resolution renders might require more memory
- Real-time viewport updates may be slower with high quality settings
- Some settings may need adjustment based on scene lighting

## Troubleshooting

1. **Bloom not visible:**
   - Check if compositing is enabled
   - Verify threshold settings
   - Ensure render layers are properly connected

2. **Performance issues:**
   - Lower the quality settings
   - Reduce bloom size
   - Disable unnecessary features

3. **Preset loading fails:**
   - Check preset file permissions
   - Verify preset file location
   - Ensure compatible preset format

## Support

For bug reports and feature requests, please use the GitHub issues page.

## Credits

Created by Dimona Patrick
Version: 1.1
License: GPL

## License

This addon is licensed under the GNU General Public License v3.0.

## Changelog

### Version 1.1
- Added preset system
- Improved UI organization
- Added color tinting features
- Enhanced masking system
- Performance optimizations

### Version 1.0
- Initial release
- Basic bloom functionality
- Simple parameter controls
