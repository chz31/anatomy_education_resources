# 3D Slicer Trunk Anatomy Study Resource

This repository accompanies a short tutorial on using a publicly available CT volume and instructor-prepared anatomical segmentations in [3D Slicer](https://www.slicer.org/) to explore selected relationships in the trunk.

The resource is intended to supplement the anatomical relationships presented in the course dissector, lectures, and gross anatomy laboratory.

A study guide can be found at [3D_ANATOMY_STUDY_GUIDE.md](https://github.com/chz31/anatomy_education_resources/blob/main/3D_ANATOMY_STUDY_GUIDE.md). 3D Slicer installation instruction can be found at [SLICER_INSTALLATION.md](https://github.com/chz31/anatomy_education_resources/blob/main/SLICER_INSTALLATION.md)

## Important educational notice (PLEASE READ)

- This resource is optional and is provided for supplemental visualization and self-study only.
- **Students should base their examination preparation on the lectures, dissector, laboratory work, syllabus, and other officially designated course materials.**
- **If this resource differs from official course materials or instructions, the official course materials and instructions take precedence.**
- Automated segmentations can contain errors and are limited by the CT image quality, image resolution, and the segmentation model. Confirm relationships using the original CT slices and authoritative course resources.
- This resource is not intended for diagnosis, clinical decision-making, or patient care.

The [tutorial](https://github.com/chz31/anatomy_education_resources/blob/main/3D_ANATOMY_STUDY_GUIDE.md) and accompanying explanations reflect the creator's own work and views. They do not represent or speak on behalf of any institution. The original data providers, the Imaging Data Commons, The Cancer Imaging Archive, 3D Slicer, and TotalSegmentator do not endorse this teaching resource.

## Repository contents

- [3D Anatomy Study Guide](3D_ANATOMY_STUDY_GUIDE.md): suggested structures and relationships to examine in 3D and 2D.
- [Slicer installation](https://github.com/chz31/anatomy_education_resources/blob/main/SLICER_INSTALLATION.md): how to install the software and download the data set.
- **Tutorial video for loading data into Slicer and interactively viewing 3D anatomy:** [video link](https://youtu.be/gJbVeTes4bc)
- **3D Slicer scene with the 3D CT volume with segmentation (`.mrb`) (please log in Google Drive using your tamu.edu account):** [downloadable link](https://drive.google.com/file/d/1ybLQZzBahESlPH69cQmSKMhzkjs4jBkf/view?usp=sharing)

## Source CT data

The source CT series was obtained from the National Cancer Institute's [Imaging Data Commons (IDC)](https://portal.imaging.datacommons.cancer.gov/explore/). It belongs to the [CPTAC-CCRCC collection](https://www.cancerimagingarchive.net/collection/cptac-ccrcc/) hosted by [The Cancer Imaging Archive (TCIA)](https://www.cancerimagingarchive.net/).

| Field | Value |
|---|---|
| IDC case ID | `C3D-01524` |
| Modality | CT |
| Series description | `NEPHROGENIC` |
| Series Instance UID | `1.3.6.1.4.1.14519.5.2.1.2932.1975.255072988367557196694880426160` |
| Source DOI | [`10.7937/K9/TCIA.2018.OBLAMN27`](https://doi.org/10.7937/K9/TCIA.2018.OBLAMN27) |
| Source-data license | [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/) |

### Data citation

National Cancer Institute Clinical Proteomic Tumor Analysis Consortium (CPTAC). (2018). *The Clinical Proteomic Tumor Analysis Consortium Clear Cell Renal Cell Carcinoma Collection (CPTAC-CCRCC)* (Version 14) [Data set]. The Cancer Imaging Archive. <https://doi.org/10.7937/K9/TCIA.2018.OBLAMN27>

### IDC citation

Fedorov, A., Longabaugh, W. J. R., Pot, D., et al. (2023). National Cancer Institute Imaging Data Commons: Toward transparency, reproducibility, and scalability in imaging artificial intelligence. *RadioGraphics, 43*(12). <https://doi.org/10.1148/rg.230180>

## License and attribution notes

The source CT data are licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/), which permits sharing and adaptation for any purpose when appropriate credit is provided, the license is linked, and changes are indicated.

For this teaching resource:

- One CT series was isolated from the source collection and packaged as a 3D Slicer scene.
- Anatomical segmentations were generated separately using TotalSegmentator; IDC-provided segmentation and annotation series are not included.
- Display settings, scene organization, segment visibility, and other presentation elements may have been modified for teaching.

The CC BY 4.0 statement above applies to the source CT data. It does not automatically place the creator's original tutorial text, images, video, or other repository materials under CC BY 4.0, and it does not change the licenses of 3D Slicer or TotalSegmentator.

## Software and methods acknowledgments

The anatomical segmentations were generated using [TotalSegmentator](https://github.com/wasserth/TotalSegmentator), and the teaching scene was prepared in [3D Slicer](https://www.slicer.org/).

Wasserthal, J., Breit, H.-C., Meyer, M. T., et al. (2023). TotalSegmentator: Robust segmentation of 104 anatomic structures in CT images. *Radiology: Artificial Intelligence, 5*(5), e230024. <https://doi.org/10.1148/ryai.230024>

Kikinis, R., Pieper, S. D., & Vosburgh, K. G. (2013). 3D Slicer: A platform for subject-specific image analysis, visualization, and clinical support. In *Intraoperative Imaging and Image-Guided Therapy* (pp. 277-289). Springer.

## Questions and feedback

For questions about using the dataset or tutorial, please contact Dr. Chi Zhang. Comments and feedback are welcome.
