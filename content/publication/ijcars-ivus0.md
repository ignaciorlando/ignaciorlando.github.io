+++
abstract = "*Background:* Intravascular ultrasound (IVUS) provides axial gray-scale images, allowing the assessment of the vessel wall and the surrounding tissues. Several studies have described automatic segmentation of the luminal boundary and the media-adventitia interface by means of different image features. *Purpose:* The aim of the present study is to evaluate the capability of some of the most relevant state-of-the-art image features for segmenting IVUS images. The study is focused on Volcano 20 MHz frames not containing plaque or containing fibrotic plaques, and, in principle, it could not be applied to frames containing shadows, calcified plaques, bifurcations and side vessels. *Methods:* Several image filters, textural descriptors, edge detectors, noise and spatial measures were taken into account. The assessment is based on classification techniques previously used for IVUS segmentation, assigning to each pixel a continuous likelihood value obtained using Support Vector Machines (SVMs). To retrieve relevant features, sequential feature selection was performed guided by the area under the Precision-Recall curve (AUC-PR). *Results:* Subsets of relevant image features for lumen, plaque and surrounding tissues characterization were obtained, and SVMs trained with these features were able to accurately identify those regions. The experimental results were evaluated with respect to ground truth segmentations from a publicly available dataset, reaching values of AUC-PR up to 0.97 and Jaccard index close to 0.85. *Conclusion:* Noise-reduction filters and Haralick's textural features denoted their relevance to identify lumen and background. Laws’ textural features, Local Binary Patterns, Gabor filters and edge detectors had less relevance in the selection process."
authors = ["LD lo Vercio", "JI Orlando", "M del Fresno", "I Larrabide"]
abstract_short = ""
date = "2016-08-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *International Journal of Computer Assisted Radiology and Surgery*, IJCARS."
publication_short = "In *IJCARS*"
selected = false
title = "Assessment of image features for vessel wall segmentation in intravascular ultrasound images"
url_code = ""
url_dataset = ""
url_pdf = "https://www.researchgate.net/profile/Jose_Orlando2/publication/289380551_Assessment_of_image_features_for_vessel_wall_segmentation_in_Intravascular_Ultrasound_images/links/568c637d08ae71d5cd04d72b.pdf"
url_project = ""
url_slides = ""
url_video = ""


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/ijcars-ivus.jpg"
caption = "Left: IVUS scan in polar coordinates. Right: lumen/no lumen characterization using our method."

+++
