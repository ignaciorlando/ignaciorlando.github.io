+++
abstract = "In this work, we present a novel method for blood vessel segmentation in fundus images based on a discriminatively trained, fully connected conditional random field model. Retinal image analysis is greatly aided by blood vessel segmentation as the vessel structure may be considered both a key source of signal, e.g. in the diagnosis of diabetic retinopathy, or a nuisance, e.g. in the analysis of pigment epithelium or choroid related abnormalities. Blood vessel segmentation in fundus images has been considered extensively in the literature, but remains a challenge largely due to the desired structures being thin and elongated, a setting that performs particularly poorly using standard segmentation priors such as a Potts model or total variation. In this work, we overcome this difficulty using a discriminatively trained conditional random field model with more expressive potentials. In particular, we employ recent results enabling extremely fast inference in a fully connected model. We find that this rich but computationally efficient model family, combined with principled discriminative training based on a structured output support vector machine yields a fully automated system that achieves results statistically indistinguishable from an expert human annotator."
authors = ["JI Orlando", "MB Blaschko"]
abstract_short = ""
date = "2014-09-14"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *International Conference on Medical Image Computing and Computer Assisted Intervention*, MICCAI."
publication_short = "In *MICCAI 2014*"
selected = false
title = "Learning fully-connected CRFs for blood vessel segmentation in retinal images"
url_code = "https://www.dropbox.com/s/ofj9cfa1xa9s5i3/MICCAI_code.rar?dl=0"
url_dataset = "http://pages.saclay.inria.fr/matthew.blaschko/projects/retina/OrlandoMICCAI2014segmentations.zip"
url_pdf = "https://hal-ecp.archives-ouvertes.fr/file/index/docid/1024226/filename/OrlandoMICCAI2014.pdf"
url_project = "http://pages.saclay.inria.fr/matthew.blaschko/projects/retina/"
url_slides = ""
url_video = ""
[[url_custom]]
    name = "Poster"
    url = "pdf/miccai_2014_poster.pdf"


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/miccai-vessels.jpg"
caption = "From left to right: original RGB images from DRIVE, ground truth segmentations by a first and a second human observer, our results"

+++
