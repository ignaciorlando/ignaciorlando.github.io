+++
abstract = "Most current systems for automated glaucoma detection in fundus images rely on segmentation-based features, which are known to be influenced by the underlying segmentation methods. Convolutional Neural Networks (CNNs) are powerful tools for solving image classification tasks as they are able to learn highly discriminative features from raw pixel intensities. However, their applicability to medical image analysis is limited by the non-availability of large sets of annotated data required for training. In this article we present results of analysis of the viability of using CNNs that are pre-trained from non-medical data for automated glaucoma detection. Two different CNNs, namely OverFeat and VGG-S, were applied to fundus images to generate feature vectors. Preprocessing techniques such as vessel inpainting, contrast-limited adaptive histogram equalization (CLAHE) or cropping around the optic nerve head (ONH) area were explored within this framework to evaluate the improvement in feature discrimination, combined with both L1 and L2 regularized logistic regression models. Results on the Drishti-GS1 dataset, evaluated in terms of area under the average ROC curve, suggests the viability of this approach and oer significant evidence of the importance of well-chosen image pre-processing for transfer learning when the amount of data is not sufficient for fine-tuning the network."
authors = ["JI Orlando", "E Prokofyeva", "M del Fresno", "MB Blaschko"]
abstract_short = ""
date = "2016-12-05"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *12th International Symposium on Medical Image Processing and Analysis*, SIPAIM."
publication_short = "In *SIPAIM 2016*"
selected = false
title = "Convolutional neural network transfer for automated glaucoma identification"
url_code = "https://github.com/ignaciorlando/overfeat-glaucoma"
url_dataset = ""
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/554709/1/4126_postprint.pdf"
url_project = ""
url_slides = ""
url_video = ""


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/sipaim-glaucoma.jpg"
caption = "Preprocessing strategies evaluated for feeding OverFeat and VGG-16 pre-trained networks."

+++
