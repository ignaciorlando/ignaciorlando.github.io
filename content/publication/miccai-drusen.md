+++
abstract = "Automated drusen segmentation in retinal optical coherence tomography (OCT) scans is relevant for understanding age-related macular degeneration (AMD) risk and progression. This task is usually performed by segmenting the top/bottom anatomical interfaces that define drusen, the outer boundary of the retinal pigment epithelium (OBRPE) and the Bruch's membrane (BM), respectively. In this paper we propose a novel multi-decoder architecture that tackles drusen segmentation as a multitask problem. Instead of training a multiclass model for OBRPE/BM segmentation, we use one decoder per target class and an extra one aiming for the area between the layers. We also introduce connections between each class-specific branch and the additional decoder to increase the regularization effect of this surrogate task. We validated our approach on private/public data sets with 166 early/intermediate AMD Spectralis, and 200 AMD and control Bioptigen OCT volumes, respectively. Our method consistently outperformed several baselines in both layer and drusen segmentation evaluations.."
authors = ["R Asgari", "JI Orlando", "S Waldstein", "F Schlanitz", "M Baratsits", "U Schmidt-Erfurth", "H Bogunović"]
abstract_short = ""
date = "2019-06-18"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *International Conference on Medical Image Computing and Computer Assisted Intervention*, MICCAI."
publication_short = "In *MICCAI 2019*"
selected = false
title = "Multiclass segmentation as multitask learning for drusen segmentation in retinal optical coherence tomography"
url_code = ""
url_dataset = ""
url_pdf = "https://arxiv.org/pdf/1906.07679.pdf"
url_project = ""
url_slides = ""
url_video = ""


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/miccai2019header.png"
caption = "Different approaches for multiclass segmentation. Our approach uses decoders with connections to better exploit the interaction between features of sandwiched layers."

+++
