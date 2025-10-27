# Digital Twin Models for Cities

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14259022.svg)](https://doi.org/10.5281/zenodo.14259022)

## Overview
This repository contains digital twin models of cities developed as part of research supported by the NSF CIVIC Program (Grant No. 2431326). The models represent detailed 3D reconstructions of Fargo, ND and Terre Haute, IN.

## Models Included

### 1. Fargo Map Large.blend
- **Location**: Fargo, North Dakota
- **Description**: Large-scale digital twin model of Fargo city
- **File Size**: Large file (requires Git LFS)

### 2. Terre Haute.blend
- **Location**: Terre Haute, Indiana
- **Description**: Digital twin model of Terre Haute city
- **File Size**: Large file (requires Git LFS)

## File Structure
```
├── README.md
├── LICENSE
├── .gitattributes (for Git LFS)
├── models/
│   ├── Fargo Map Large.blend
│   └── Terre Haute.blend
└── documentation/
    └── usage_guide.md
```

## Requirements
- Blender 3.0 or higher
- Minimum 8GB RAM recommended (16GB+ for large models)
- Graphics card with OpenGL support
- Git LFS for downloading large files

## Usage
1. Install Blender from [blender.org](https://www.blender.org/)
2. Clone this repository with Git LFS:
   ```bash
   git lfs install
   git clone https://github.com/youngbrain85/civic-digital-twin-models.git
   ```
3. Open the .blend files in Blender
4. Navigate using standard Blender controls (see documentation for details)

## Downloading the Models
The Blender model files are available on Zenodo due to their large size:

**Download from Zenodo**: https://doi.org/10.5281/zenodo.14259022

For Git LFS users:
```bash
# Clone with LFS
git clone https://github.com/youngbrain85/civic-digital-twin-models.git
cd civic-digital-twin-models

# If you already cloned without LFS, pull the large files
git lfs pull
```

## License
This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0). You are free to use, share, and adapt these models for any purpose, including commercial use, as long as you provide appropriate attribution.

## Related Publications
[Publications related to these digital twin models will be listed here]

## Acknowledgments
This material is based upon work supported by the National Science Foundation under Grant No. 2431326, CIVIC-PG Track A: Disaster Response Metaverse (DRM) for Enhancing Community Engagement through Immersive, Interactive Experiences.