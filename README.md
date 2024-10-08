# Object Tracking and Track Analysis using TrackMate and CellTracksColab

I2K 2024 workshop materials for "Object Tracking and Track Analysis using TrackMate and CellTracksColab"

**Instructor:**

Joanna Pylvänäinen, Åbo Akademi University  
joanna.pylvanainen@abo.fi  

## Workshop Overview (1 hour)

In life sciences, tracking objects within movies is crucial for quantifying the behaviour of particles, organelles, bacteria, cells, and entire organisms. However, tracking multiple objects across numerous movies and analysing the objects’ movements can be challenging. This workshop aims to demonstrate the effective utilization of **TrackMate** for object tracking across multiple movies through hands-on exercises. Additionally, participants will learn how to compile, analyse, and explore the acquired tracking data using the **CellTracksColab** platform. Both tools offer user-friendly interfaces tailored to life scientists without coding experience.

### Key Concepts:
- **TrackMate**: An open-source FIJI/ImageJ plugin for tracking cells/particles in 2D microscopy images. We'll briefly cover object detection, tracking algorithms (LAP, Kalman filter), and export options.
- **CellTracksColab**: A cloud-based platform for analyzing tracking data with no need for local software installations. Learn how to process large datasets using Google Colab and extract key metrics.

Hands-on with TrackMate (25 minutes)

### Hands-On Task:
Downloads

> [Dataset for tracking settings](https://abofi-my.sharepoint.com/:i:/g/personal/joanna_pylvanainen_abo_fi/ERvu_iiIWvBMo2Bnrk9bf7kB69vlmMwmCKNbxbDaP-1APQ?e=yqmxpc) <br>
> [T-cell dataset](https://abofi-my.sharepoint.com/:f:/g/personal/joanna_pylvanainen_abo_fi/Eqq_uT6T5pNAsGPt6wKYlAQBTnQx4cxu6uAGb2SmiyFSlQ?e=kDtrcc) <br>
> [Whole dataset]([T-cell dataset](https://abofi-my.sharepoint.com/:f:/g/personal/joanna_pylvanainen_abo_fi/Eqq_uT6T5pNAsGPt6wKYlAQBTnQx4cxu6uAGb2SmiyFSlQ?e=kDtrcc))

### Steps:
1. Define parameters in the **TrackMate interface**
- Use sample T-cell data to set tracking parameters.
- **Save settings** as XML for batch processing.
- Export tracking data (spot tables, track tables, movies).

2. 
---

## Session 3: Hands-on with CellTracksColab (20 minutes)

### Hands-On Task:
- Analyze **TrackMate output** in CellTracksColab.

### Steps:
- Upload tracking data into **CellTracksColab**.
- Generate **plots** and visualize large datasets.
- Interpret and analyze the biological insights from the tracking data.

> **[Link to CellTracksColab](https://github.com/CellMigrationLab/CellTracksColab)**  
> **[Download Tracking Output](https://drive.google.com/drive/folders/1UcIp-HBMeizYnuVLvrC5zqIQbLAZYpxG?usp=sharing)**  
> **[Link to Slides](https://drive.google.com/file/d/1P0s1Uy419S7hgleyeX3YkTN33DviiwVO/view?usp=sharing)**  

---

By the end of this workshop, participants will be familiar with TrackMate's tracking capabilities, will have analyzed tracking data using CellTracksColab, and will know how to export and visualize their results for further research.
