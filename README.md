# Object Tracking and Track Analysis using TrackMate and CellTracksColab

I2K 2024 workshop materials for "Object Tracking and Track Analysis using TrackMate and CellTracksColab"

**Instructor:**

Joanna Pylvänäinen, Åbo Akademi University  
joanna.pylvanainen@abo.fi  

## I2K 2024

Check out the video:

[![Watch the video](https://img.youtube.com/vi/fIE4i3G7L9Y/0.jpg)](https://www.youtube.com/watch?v=fIE4i3G7L9Y)

## Workshop Overview

In life sciences, tracking objects within movies is crucial for quantifying the behaviour of particles, organelles, bacteria, cells, and entire organisms. However, tracking multiple objects across numerous movies and analysing the objects’ movements can be challenging. This workshop aims to demonstrate the effective utilization of **TrackMate** for object tracking across multiple movies through hands-on exercises. Additionally, participants will learn how to compile, analyse, and explore the acquired tracking data using the **CellTracksColab** platform. Both tools offer user-friendly interfaces tailored to life scientists without coding experience.

By the end of this workshop, participants will be familiar with TrackMate's tracking capabilities, will have analyzed tracking data using CellTracksColab, and will know how to export and visualize their results for further research.

[Worshops slides available here](https://github.com/CellMigrationLab/I2K_2024/blob/main/workshop-presentation/I2K_TrackMate-CellTracksColab.pdf)

---

## Software:
[**TrackMate**](https://imagej.net/plugins/trackmate/): <br>
-  An open-source FIJI/ImageJ plugin for tracking cells/particles in 2D microscopy images. 

[**CellTracksColab**](https://github.com/CellMigrationLab/CellTracksColab): <br> 
- A cloud-based platform for analyzing tracking data.

---

## Hands-on with TrackMate and CellTracksColab

### If you want to test the tools during the workshop please do these before the workshop:

**1. Download these datasets:**

[Link to Zenodo](https://zenodo.org/records/14645477)

<img width="843" alt="image" src="https://github.com/user-attachments/assets/99b48321-af84-4f64-b199-07ea84585e19">

- 0_Tracking_settings.zip
- 1_TrackMate_batcher_input.zip
- 2_CellTracksColab_input.zip

**2. Download and prepare Fiji**

- [Download Fiji](https://fiji.sc/)
- Open Fiji and activate TrackMate Helper update site. Restart Fiji.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/bf27c70c-6ba2-4c3a-9ec3-a878563eae7e" /></td>
  </tr>
</table>

**3. You need to have access to google drive** (personal or create one for the purpose of this course)
- Unzip the 2_CellTracksColab_input.zip and upload it to your google drive
- Create a new folder on you google drive called Results

## Workshop step-by-step:

**1. Cell Tracking with TrackMate**
- Define tracking parameters in the **TrackMate interface** useing the *image_for_tracking_settings* -image from the *0_Tracking_settings* folder.
- **Save traking settings** as XML for batch processing.
- **Batch process** all images from the *1_TrackMate_batcher_input* -folder using the TrackMate batcher.
- **Export tracking data** (spot tables, track tables, movies).

**2. Analyze TrackMate output in CellTracksColab.**

- Upload your tracking results to your Google Drive. Make sure that the folders are correctly organized.

<table>
  <tr>
    <td><img src="https://github.com/user-attachments/assets/30d5f2dc-125b-462e-a063-66c18a1763ee" /></td>
  </tr>
</table>

- You can also use the pre-made CellTracksColab input from the *2_CellTracksColab_input* -folder
- Create a folder for results
- Open The [CellTracksColab TrackMate notebook](https://colab.research.google.com/github/guijacquemet/CellTracksColab/blob/main/Notebook/CellTracksColab_TrackMate.ipynb) and make a copy to your drive 
- Run all cells visualize and to generate plots.
- Bonus: Utilize advanced dimensionality reduction techniques to understand your data using [Dimensionality Reduction notebook](https://colab.research.google.com/github/guijacquemet/CellTracksColab/blob/main/Notebook/CellTracksColab_Dimensionality_Reduction.ipynb) 

---

## References
**TrackMate**<br>
Ershov, D., Phan, M. S., Pylvänäinen, J. W., Rigaud, S. U., Le Blanc, L., Charles-Orszag, A., Conway, J. R. W., Laine, R. F., Roy, N. H., Bonazzi, D., Duménil, G., Jacquemet, G., & Tinevez, J. Y. (2022). **TrackMate 7: integrating state-of-the-art segmentation algorithms into tracking pipelines.** Nature methods, 19(7), 829–832. [https://doi.org/10.1038/s41592-022-01507-1](https://doi.org/10.1038/s41592-022-01507-1)

**CellTracksColab**<br>
Gómez-de-Mariscal, E., Grobe, H., Pylvänäinen, J. W., Xénard, L., Henriques, R., Tinevez, J. Y., & Jacquemet, G. (2024). **CellTracksColab is a platform that enables compilation, analysis, and exploration of cell tracking data.** PLoS biology, 22(8), e3002740. [https://doi.org/10.1371/journal.pbio.3002740](https://doi.org/10.1371/journal.pbio.3002740)

**T-Cell Dataset**<br>
Guillaume Jacquemet. (2023). **T cell dataset for CellTracksColab - 2** [Data set]. Zenodo. [https://doi.org/10.5281/zenodo.8420011](https://doi.org/10.5281/zenodo.8420011)
