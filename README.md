# SliceVision256: A Multi-Paradigm Synthetic Dataset for Network Slice Visualization

## Overview
SliceVision256 is a comprehensive synthetic dataset containing **12,000 high-resolution (256×256) images** of network slice visualizations generated through four distinct algorithmic approaches. Designed for machine learning research in 5G/6G network slicing, computer vision, and pattern recognition, this dataset provides unique representations of three key network slice types:

- **eMBB** (Enhanced Mobile Broadband)
- **URLLC** (Ultra-Reliable Low-Latency Communications)  
- **mMTC** (Massive Machine-Type Communications)

Each generation method captures different aspects of network behavior through specialized visualization paradigms.

## Dataset Samples
| Generation Method | Sample Visualization |
|-------------------|----------------------|
| **Wave-Based Procedural** | ![Procedural Sample](https://raw.githubusercontent.com/AbidHasanRafi/SliceVision256/main/Wave-Based%20Procedural%20Synthetic%20Network%20Slice%20Images/sample.png) |
| **Fractal-Based** | ![Fractal Sample](https://raw.githubusercontent.com/AbidHasanRafi/SliceVision256/main/Fractal-Based%20Synthetic%20Network%20Slice%20Images/sample.png) |
| **Agent-Based** | ![Agent Sample](https://raw.githubusercontent.com/AbidHasanRafi/SliceVision256/main/Agent-Based%20Synthetic%20Network%20Slice%20Images/sample.png) |
| **Graph-Based** | ![Graph Sample](https://raw.githubusercontent.com/AbidHasanRafi/SliceVision256/main/Graph-Based%20Synthetic%20Network%20Slice%20Images/sample.png) |

## Dataset Structure
```
AbidHasanRafi/SliceVision256/
├── Agent-Based Synthetic Network Slice Images/
│   ├── metadata.csv
│   └── images/          # 3,000 agent-based slice images
├── Fractal-Based Synthetic Network Slice Images/
│   ├── metadata.csv
│   └── Images/          # 3,000 fractal-based slice images  
├── Graph-Based Synthetic Network Slice Images/
│   ├── metadata.csv
│   └── images/          # 3,000 graph-based slice images
└── Wave-Based Procedural Synthetic Network Slice Images/
    ├── metadata.csv
    └── images/          # 3,000 procedural slice images
```

## Generation Methodologies
### 1. Wave-Based Procedural Generation
- **Technique**: Mathematical waveform synthesis (sinusoidal + Poisson patterns)
- **Characteristics**:
  - Red channel: Bandwidth as multi-frequency waveforms
  - Green channel: Latency as directional wavefronts  
  - Blue channel: Reliability as Gaussian zones
- **Class Specialization**: Burst traffic (eMBB), priority paths (URLLC), periodic reporting (mMTC)

### 2. Fractal-Based Generation  
- **Technique**: Perlin noise with multi-octave persistence
- **Characteristics**:
  - Organic, self-similar patterns
  - Channel-specific noise scaling
  - Class-specific modifications (bursts, directional emphasis, sparse points)

### 3. Agent-Based Simulation
- **Technique**: Autonomous agent modeling
- **Characteristics**:
  - eMBB: Random walk with traffic bursts
  - URLLC: Linear low-jitter paths  
  - mMTC: Sparse device activation patterns
- **Visual Output**: Smoothed trajectory heatmaps

### 4. Graph-Based Generation
- **Technique**: Network topology rendering
- **Graph Types**:
  - eMBB: Scale-free (Barabási–Albert) networks
  - URLLC: Grid networks  
  - mMTC: Random geometric graphs
- **Rendering**: Edge-based traffic simulation with node effects

## Metadata Schema
All subdirectories contain a `metadata.csv` with:
```csv
image_path, slice_type, bandwidth, latency, reliability
```

## Usage Terms
**This dataset is part of ongoing research.** All rights reserved by the authors. Any use of this dataset must comply with:
1. **Academic Use**: Reference required
2. **Commercial Use**: Prohibited without any consent
3. **Redistribution**: Not permitted without authorization

## Contributors
- **Algorithm Design**: [Md. Abid Hasan Rafi](mailto:ahr16.abidhasanrafi@gmail.com), [Mst. Fatematuj Johora](mailto:mstfatematujjohora246@gmail.com)  
- **Validation**: [Mohima Binte Rasel](mailto:mohimabinte002@gmail.com)
- **Institutional Affiliation**: Department of Electronics and Communication Engineering, HSTU, Dinajpur, Bangladesh