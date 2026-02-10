# Rebar-GR-Dataset

## Overview

**Rebar-GR-Dataset** is a publicly available dataset for on-site reinforced concrete (RC) inspection, designed to support research on automated rebar spacing measurement, geometric reasoning, and semantic understanding of structural components.

The dataset contains annotated rebar data extracted from real construction site scans, with semantic labels corresponding to different structural elements such as beams, columns, slabs, and other components.

This dataset is developed to facilitate reproducible research in construction automation, computer vision, and intelligent inspection.

---

## Dataset Structure
The repository is organized as follows:
```
Rebar-GR-Dataset/
├── rebar_25/
│   ├── Annotations/
│   │   ├── beam_1.txt
│   │   ├── column_1.txt
│   │   ├── slab_1.txt
│   │   └── other_1.txt
│   └── rebar_25.txt
├── rebar_26/
├── …
├── rebar_414/
├── .gitattributes
├── .gitignore
└── README.md
``` 

Each `rebar_xx` folder corresponds to one inspection instance.

- `rebar_xx.txt`  
  Rebar data for the corresponding instance.

- `Annotations/`  
  Semantic annotations of rebars grouped by structural component:
  - `beam_*.txt`
  - `column_*.txt`
  - `slab_*.txt`
  - `other_*.txt`

---

## Data Format

All files are provided in plain text (`.txt`) format.

The data encode geometric and semantic information of rebars extracted from real construction site scans.  
Detailed definitions of the data fields and annotation principles are described in the accompanying publication.

---

## Applications

The dataset can be used for:

- Automated rebar spacing measurement
- Semantic parsing of reinforced concrete components
- Geometry-based reasoning for construction inspection
- Validation of end-to-end inspection frameworks
- Benchmarking learning-based and hybrid inspection methods

---

## Availability

The dataset is publicly available at:
``` 
https://github.com/Iris-chestnut/Rebar-GR-Dataset
``` 

Large files are managed using **Git LFS**.

---

## Citation

If you use this dataset in your research, please cite the corresponding paper:
(To be updated upon publication)

---

## License

This dataset is released for **academic and research use only**.

For commercial use or redistribution, please contact the authors.

---

## Contact

For questions or issues related to the dataset, please open an issue on GitHub.
