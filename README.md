# Object Tracking and Track Analysis using TrackMate and CellTracksColab

I2K 2024 workshop materials for "Object Tracking and Track Analysis using TrackMate and CellTracksColab"

**Instructor:**

Joanna Pylvänäinen, Åbo Akademi University  
joanna.pylvanainen@abo.fi  

## Workshop Overview (1 hour)

In life sciences, tracking objects within movies is crucial for quantifying the behaviour of particles, organelles, bacteria, cells, and entire organisms. However, tracking multiple objects across numerous movies and analysing the objects’ movements can be challenging. This workshop aims to demonstrate the effective utilization of **TrackMate** for object tracking across multiple movies through hands-on exercises. Additionally, participants will learn how to compile, analyse, and explore the acquired tracking data using the **CellTracksColab** platform. Both tools offer user-friendly interfaces tailored to life scientists without coding experience.

## Software:
[**TrackMate**](https://imagej.net/plugins/trackmate/): <br>
-  An open-source FIJI/ImageJ plugin for tracking cells/particles in 2D microscopy images. 

[**CellTracksColab**](https://github.com/CellMigrationLab/CellTracksColab): <br> 
- A cloud-based platform for analyzing tracking data with no need for local software installations. 

## Hands-on with TrackMate and CellTracksColab

### Hands-On Task:
In this demo we will create tracking settings to track objects in multiple movies and analyse the tracking results using CellTracksColab. 

Downloads

> [Image for tracking settings](https://abofi-my.sharepoint.com/:i:/g/personal/joanna_pylvanainen_abo_fi/ERvu_iiIWvBMo2Bnrk9bf7kB69vlmMwmCKNbxbDaP-1APQ?e=yqmxpc) <br>
> [T-cell dataset](https://abofi-my.sharepoint.com/:f:/g/personal/joanna_pylvanainen_abo_fi/Eqq_uT6T5pNAsGPt6wKYlAQBTnQx4cxu6uAGb2SmiyFSlQ?e=kDtrcc) <br>
> [Whole dataset](https://abofi-my.sharepoint.com/:f:/g/personal/joanna_pylvanainen_abo_fi/EmFrrkXC_R5Fq5rMFkBmmoABJQXFpE7kwXQ9z1lOYh_-OA?e=CIe7rj) (2,2 GB, backup)

### Steps:
1. Cell Tracking with TrackMate
- Define parameters in the **TrackMate interface**
- Use [Image for tracking settings](https://abofi-my.sharepoint.com/:i:/g/personal/joanna_pylvanainen_abo_fi/ERvu_iiIWvBMo2Bnrk9bf7kB69vlmMwmCKNbxbDaP-1APQ?e=yqmxpc) to set tracking parameters.
- **Save traking settings** as XML for batch processing.
- **Batch process** all images from the [T-cell dataset](https://abofi-my.sharepoint.com/:f:/g/personal/joanna_pylvanainen_abo_fi/Eqq_uT6T5pNAsGPt6wKYlAQBTnQx4cxu6uAGb2SmiyFSlQ?e=kDtrcc) using the TrackMate batcher.
- **Export tracking data** (spot tables, track tables, movies).

2. Analyze **TrackMate output** in CellTracksColab.

- Upload your tracking results to your Google Drive ([or use the pre-made dataset](https://abofi-my.sharepoint.com/:f:/g/personal/joanna_pylvanainen_abo_fi/EsvL0faXSb1BgtheKIK3phkBnvuCTzr05fXij3fDO7i_Hw?e=vVPtho))
- Open CellTracksColab TrackMate notebook 
- **CellTracksColab**.
- Generate **plots** and visualize large datasets.
- Interpret and analyze the biological insights from the tracking data.

> **[Link to CellTracksColab](https://github.com/CellMigrationLab/CellTracksColab)**  
> **[Download Tracking Output](https://drive.google.com/drive/folders/1UcIp-HBMeizYnuVLvrC5zqIQbLAZYpxG?usp=sharing)**  
> **[Link to Slides](https://drive.google.com/file/d/1P0s1Uy419S7hgleyeX3YkTN33DviiwVO/view?usp=sharing)**  

---

By the end of this workshop, participants will be familiar with TrackMate's tracking capabilities, will have analyzed tracking data using CellTracksColab, and will know how to export and visualize their results for further research.

## References
TrackMate
Ershov, D., Phan, M. S., Pylvänäinen, J. W., Rigaud, S. U., Le Blanc, L., Charles-Orszag, A., Conway, J. R. W., Laine, R. F., Roy, N. H., Bonazzi, D., Duménil, G., Jacquemet, G., & Tinevez, J. Y. (2022). **TrackMate 7: integrating state-of-the-art segmentation algorithms into tracking pipelines.** Nature methods, 19(7), 829–832. [https://doi.org/10.1038/s41592-022-01507-1](https://doi.org/10.1038/s41592-022-01507-1)

CellTracksColab
Gómez-de-Mariscal, E., Grobe, H., Pylvänäinen, J. W., Xénard, L., Henriques, R., Tinevez, J. Y., & Jacquemet, G. (2024). **CellTracksColab is a platform that enables compilation, analysis, and exploration of cell tracking data.** PLoS biology, 22(8), e3002740. [https://doi.org/10.1371/journal.pbio.3002740](https://doi.org/10.1371/journal.pbio.3002740)

T-Cell Dataset
Guillaume Jacquemet. (2023). **T cell dataset for CellTracksColab - 2** [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.8420011](https://doi.org/10.5281/zenodo.8420011)
