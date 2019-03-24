+++
abstract = "Optical coherence tomography (OCT) has become the most important imaging modality in ophthalmology. A substantial amount of research has recently been devoted to the development of machine learning (ML) models for the identification and quantification of pathological features in OCT images. Among the several sources of variability the ML models have to deal with, a major factor is the acquisition device, which can limit the ML model's generalizability. In this paper, we propose to reduce the image variability across different OCT devices (Spectralis and Cirrus) by using CycleGAN, an unsupervised unpaired image transformation algorithm. The usefulness of this approach is evaluated in the setting of retinal fluid segmentation, namely intraretinal cystoid fluid (IRC) and subretinal fluid (SRF). First, we train a segmentation model on images acquired with a source OCT device. Then we evaluate the model on (1) source,(2) target and (3) transformed versions of the target OCT images. The presented transformation strategy shows an F1 score of 0.4 (0.51) for IRC (SRF) segmentations. Compared with traditional transformation approaches, this means an F1 score gain of 0.2 (0.12)."
authors = ["P Seeböck", "D Romo-Bucheli", "S Waldstein", "H Bogunović", "JI Orlando", "BS Gerendas", "G Langs", "U Schmidt-Erfurth"]
date = "2018-12-18"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *IEEE International Symposium on Biomedical Imaging*, ISBI."
publication_short = "In *ISBI 2019*"
selected = true
title = "Using CycleGANs for effectively reducing image variability across OCT devices and improving retinal fluid segmentation"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1901.08379.pdf"
url_project = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/ISBI_2019_banner_web-960.jpg"
caption = ""


+++
