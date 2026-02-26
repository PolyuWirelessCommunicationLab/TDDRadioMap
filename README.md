# TDDRadioMap Dataset

## Overview

This repository contains comprehensive radio map datasets designed for wireless communication research, including radio propagation modeling, coverage prediction, and network planning applications.

## Dataset Description

The dataset comprises two complementary sub-datasets:

### 1. 3D Radio Map with Multi-Resolution Spatial Data

The 3D radio map dataset provides three-dimensional radio signal strength measurements across various spatial resolutions, enabling multi-scale analysis of radio propagation patterns.

**Key Features:**
- Multi-resolution spatial grids for different analysis granularities
- 3D coordinate system (X, Y, Z) with corresponding signal measurements

**Spatial Resolutions:**
- High resolution: [e.g., "1m × 1m × 1m grid"]
- Low resolution: [e.g., "4m × 4m × 4m grid"]

### 2. Dynamic 2D Radio Map

The dynamic 2D radio map captures temporal variations in radio signal distribution, reflecting changes due to environmental factors, user mobility, or network dynamics.

**Key Features:**
- Time-series radio signal measurements
- 2D spatial grid with temporal dimension

## Dataset Structure

```
radio-map-dataset/
├── 3DRadioMap/
│   ├── 3D_Building_Structure/
│   │   ├── env_1.npy
│   │   ├── ...
│   │   └── env_1000.npy
│   ├── 3D_RadioMap_1m_Res/
│   │   ├── env_1.npy
│   │   ├── ...
│   │   └── env_250.npy
│   └── 3D_RadioMap_4m_Res/
│       ├── env_1.npy
│       ├── ...
│       └── env_1000.npy
├── 2D_Dynamic_RadioMap/
│   ├── 2D_Building_Layout
│   │   ├── building_ground_mask_v2v_000_00.png
│   │   ├── ...
│   │   └── building_ground_mask_v2v_999_20.png
│   ├── Transmitter
│   │   ├── tx_000_00.png
│   │   ├── ...
│   │   └── tx_000_19.png
│   ├── 2D_Radio_Map
│   │   ├── RSS_000_00_00.png
│   │   ├── ...
│   │   └── RSS_999_19_20.png
│   └── 2D_Radio_Rendered
│       ├── render_000_00_00.png
│       ├── ...
│       └── render_000_00_00.png
├── README.md
└── LICENSE

```

## Dataset Download

- Public download links (provide one or more)
  - Google Drive: <https://drive.google.com/file/d/1C9oSUC0XBwRWs5Ab0B9JAtqPkT8PA44T/view?usp=sharing>
  - Baidu Netdisk: <https://pan.baidu.com/s/11WlXOs6HQP2zift4MGO2_A?pwd=htfs>

- Access notes
  - Citation: If you use this dataset, please cite this repository and the corresponding DOI.

## Contact

For questions or collaboration opportunities, please contact:

- **Name**: Lin ZHU    |    Zishen LIU
- **Email**: lin-eee.zhu@connect.polyu.hk | zishen.liu@connect.polyu.hk
- **Institution**: The Hong Kong Polytechnic University


## Changelog

### Version 1.0 (2025-10-18)
- Initial release
- 3D radio maps at three spatial resolutions
- Dynamic 2D radio map with temporal data
