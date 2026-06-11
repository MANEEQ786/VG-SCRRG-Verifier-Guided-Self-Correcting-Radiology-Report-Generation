# Dataset Access

This repository does not include clinical datasets.

The experiments described in the paper use datasets and resources such as MIMIC-CXR, MIMIC-CXR-JPG, IU X-Ray, Chest ImaGenome, MS-CXR, ReXVal, and RadGraph-related resources.

Users must obtain all datasets from their official sources and follow the applicable licenses, credentialing requirements, and data-use agreements.

## Official Dataset Links

| Resource | Version | Official link | Local use |
| --- | --- | --- | --- |
| MIMIC-CXR-JPG - chest radiographs with structured labels | 2.1.0 | [PhysioNet](https://physionet.org/content/mimic-cxr-jpg/2.1.0/) / [DOI](https://doi.org/10.13026/jsn5-t979) | Chest X-ray JPG images, split files, metadata, and structured labels. |
| Chest ImaGenome Dataset | 1.0.0 | [PhysioNet](https://physionet.org/content/chest-imagenome/1.0.0/) / [DOI](https://doi.org/10.13026/wv01-y230) | Scene graphs, anatomy objects, bounding boxes, and region-consistency support. |
| MS-CXR | 1.1.0 | [PhysioNet](https://physionet.org/content/ms-cxr/1.1.0/) / [DOI](https://doi.org/10.13026/9g2z-jg61) | Radiologist-reviewed phrase grounding annotations for local image-text validation. |
| Radiology Report Expert Evaluation (ReXVal) Dataset | 1.0.0 | [PhysioNet](https://physionet.org/content/rexval-dataset/1.0.0/) / [DOI](https://doi.org/10.13026/2fp8-qr71) | Radiologist report-error annotations for expert evaluation support. |

These PhysioNet resources are restricted-access datasets. Access generally requires a credentialed PhysioNet account, completion of required training, and signing the relevant data-use agreement. MIMIC-CXR-JPG is derived from MIMIC-CXR, so users must also follow parent-project requirements when using the underlying reports or parent data.

Do not commit or upload:

* MIMIC-CXR images.
* MIMIC-CXR-JPG images.
* Free-text radiology reports.
* Patient-level metadata.
* Restricted labels.
* Derived files containing restricted clinical data.
* Full generated outputs from restricted datasets.
* Model checkpoints unless release is explicitly permitted.
