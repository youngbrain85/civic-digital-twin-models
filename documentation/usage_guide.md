# Usage Guide for Digital Twin Models

## Overview
This repository contains two digital twin models:
1. **Fargo Map Large.blend** - Digital twin of Fargo, North Dakota
2. **Terre Haute.blend** - Digital twin of Terre Haute, Indiana

## Getting Started

### Prerequisites
1. **Blender Installation**
   - Download Blender from [blender.org](https://www.blender.org/)
   - Recommended version: 3.0 or higher
   - Ensure you have at least 8GB RAM (16GB+ recommended for smooth performance)
   - Graphics card with OpenGL support

### Downloading the Models
These are large files stored with Git LFS:
```bash
# Clone with Git LFS
git lfs install
git clone https://github.com/youngbrain85/civic-digital-twin-models.git
cd civic-digital-twin-models

# If already cloned, pull the large files
git lfs pull
```

### Opening the Models
1. Launch Blender
2. Go to File → Open
3. Navigate to the `models/` folder
4. Select either:
   - `Fargo Map Large.blend` for Fargo city model
   - `Terre Haute.blend` for Terre Haute city model
5. Click "Open Blender File"

### Navigation Controls
- **Rotate View**: Middle mouse button drag
- **Pan View**: Shift + Middle mouse button drag
- **Zoom**: Mouse wheel or Ctrl + Middle mouse button drag
- **Focus on Object**: Numpad period (.)
- **Toggle Perspective**: Numpad 5
- **Frame All Objects**: Home key

## Model-Specific Information

### Fargo Map Large.blend
- **Coverage**: Large-scale city model of Fargo, ND
- **Features**: Buildings, streets, terrain, infrastructure
- **Recommended RAM**: 16GB+
- **Performance tip**: Use solid shading mode for better viewport performance

### Terre Haute.blend
- **Coverage**: City model of Terre Haute, IN
- **Features**: Urban structures, road network, terrain
- **Local context**: Includes Indiana State University area
- **Performance tip**: Hide layers not in use to improve performance

## Performance Optimization
1. **Enable GPU rendering**:
   - Edit → Preferences → System
   - Select your GPU for Cycles Render Devices

2. **Viewport Performance**:
   - Use Solid shading instead of Material Preview
   - Reduce viewport subdivision levels
   - Hide collections/layers not actively being worked on

3. **For slower systems**:
   - Use Wireframe or Solid shading
   - Disable overlays when not needed
   - Work with one city model at a time

## Exporting for Other Applications
To export for use in game engines or other 3D software:
1. Select the objects you want to export
2. File → Export → Choose format:
   - FBX (recommended for Unity/Unreal)
   - OBJ (universal compatibility)
   - GLTF 2.0 (web applications)
3. Configure export settings as needed

## Data Structure
Each model contains organized collections:
- **Buildings**: Individual building geometries
- **Terrain**: Ground/elevation data
- **Infrastructure**: Roads, bridges, utilities
- **Vegetation**: Trees and green spaces (if included)

## Common Issues and Solutions

### Model appears black
- Switch viewport shading to Solid mode
- Check that lights are enabled in the scene

### Performance is slow
- Reduce viewport quality settings
- Enable GPU acceleration
- Close other applications to free RAM

### File won't open
- Ensure Git LFS files are fully downloaded
- Check Blender version compatibility
- Verify sufficient disk space

## Research Applications
These models can be used for:
- Urban planning visualization
- Infrastructure analysis
- Disaster response planning
- Community engagement
- Educational purposes

## Support
For questions or issues:
1. Check this documentation first
2. Open an issue on the [GitHub repository](https://github.com/youngbrain85/civic-digital-twin-models/issues)
3. Contact the research team at Indiana State University

## Acknowledgments
These digital twin models were developed with support from NSF CIVIC Program (Grant No. 2431326).