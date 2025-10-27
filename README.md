# Digital Twin Models for Cities

## Overview
This repository contains digital twin models of cities developed as part of research supported by the NSF CIVIC Program (Grant No. 2431326).

## Models
This repository includes two Blender (.blend) files containing detailed 3D digital twin models of urban environments.

## Funding Acknowledgment
This work was supported by the National Science Foundation (NSF) CIVIC Program under Grant No. 2431326.

## File Structure
```
├── README.md
├── LICENSE
├── .gitattributes (for Git LFS)
├── models/
│   ├── [Model1.blend] - To be uploaded via Git LFS
│   └── [Model2.blend] - To be uploaded via Git LFS
└── documentation/
    └── usage_guide.md
```

## Requirements
- Blender 3.0 or higher
- Minimum 8GB RAM recommended
- Graphics card with OpenGL support

## Usage
1. Install Blender from [blender.org](https://www.blender.org/)
2. Open the .blend files in Blender
3. Navigate using standard Blender controls

## How to Upload Large Files
Due to the large size of .blend files, you'll need to use Git LFS:

```bash
# Clone the repository
git clone https://github.com/youngbrain85/civic-digital-twin-models.git
cd civic-digital-twin-models

# Install Git LFS
git lfs install

# Track .blend files
git lfs track "*.blend"

# Create models directory
mkdir models

# Copy your .blend files to models/
# Then add and commit
git add models/*.blend
git commit -m "Add digital twin models"
git push
```

## Citation
If you use these models in your research, please cite:
```
[Your Name]. (2025). Digital Twin Models for Cities [Data set]. 
Supported by NSF CIVIC Program (Grant No. 2431326). 
https://doi.org/[DOI]
```

## License
This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Contact
[Your contact information]

## Contributors
- [Your name and affiliation]
- Indiana State University

## Related Publications
[Add any related papers or reports here]