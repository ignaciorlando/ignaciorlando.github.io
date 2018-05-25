+++
abstract = "*Purpose:* Diabetic retinopathy (DR) is one of the most widespread causes of preventable blindness in the world. The most dangerous stage of this condition is proliferative DR (PDR), in which the risk of vision loss is high and treatments are less effective. Fractal features of the retinal vasculature have been previously explored as potential biomarkers of DR, yet the current literature is inconclusive with respect to their correlation with PDR. In this study we experimentally assess their discrimination ability to recognize PDR cases. *Methods:* A statistical analysis of the viability of using three reference fractal characterization schemes--namely box, information and correlation dimensions--to identify patients with PDR is presented. These descriptors are also evaluated as input features for training L1 and L2 regularized logistic regression classifiers, to estimate their performance. *Results:* Our results on MESSIDOR, a public data set of 1200 fundus photographs, indicate that patients with PDR are more likely to exhibit a higher fractal dimension than healthy subjects or patients with mild levels of DR (p < 1.3 x 10^-2). Moreover, a supervised classifier trained with both fractal measurements and red lesion based features reports an area under the ROC curve of 0.93 for PDR screening and 0.96 for detecting patients with optic disc neovascularizations. *Conclusions:* The fractal dimension of the vasculature increases with the level of DR. Furthermore, PDR screening using multiscale fractal measurements is more feasible than using their derived fractal dimensions."
authors = ["JI Orlando", "K van Keer", "J Barbosa Breda", "HL Manterola", "MB Blaschko", "A Clausse"]
date = "2017-02-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *Medical Physics*."
publication_short = ""
selected = false
title = "Proliferative Diabetic Retinopathy Characterization based on Fractal Features: Evaluation on a Publicly Available Data Set"
url_code = "https://github.com/ignaciorlando/fundus-fractal-analysis"
url_dataset = "https://app.box.com/s/66y5hyvj705lir82ckt89wan693fdb4r"
url_pdf = ""
url_project = "https://github.com/ignaciorlando/fundus-fractal-analysis"
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/medphys-fractals.png"
caption = "From left to right: green band of a fundus picture of a patient with proliferative DR, raw vessel segmentation, segmentation after removing spurious segments, skeletonization."


+++
