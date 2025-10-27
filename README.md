# Digital Twin Models for Cities

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

## Funding Acknowledgment
This work was supported by the National Science Foundation (NSF) CIVIC Program under Grant No. 2431326.

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
Since these are large files, they are stored using Git LFS:

```bash
# Clone with LFS
git clone https://github.com/youngbrain85/civic-digital-twin-models.git
cd civic-digital-twin-models

# If you already cloned without LFS, pull the large files
git lfs pull
```

## Citation
If you use these models in your research, please cite:
```
Park, J. (2025). Digital Twin Models for Cities: Fargo and Terre Haute [Data set]. 
Indiana State University. Supported by NSF CIVIC Program (Grant No. 2431326). 
https://doi.org/[ZENODO_DOI]
```

## License
This work is licensed under a Creative Commons Attribution 4.0 International License (CC BY 4.0).

## Contact
- Principal Investigator: Jisoo Park
- Affiliation: Indiana State University
- Email: [Your email]

## Contributors
- Jisoo Park, Indiana State University
- NSF CIVIC Program Team

## Related Publications
[Publications related to these digital twin models will be listed here]

## Acknowledgments
We thank the NSF CIVIC Program for supporting this research under Grant No. 2431326. We also acknowledge the communities of Fargo, ND and Terre Haute, IN for their collaboration in developing these digital twin models.