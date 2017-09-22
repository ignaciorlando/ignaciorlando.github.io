+++
abstract = "*Objective:* In this work, we present an extensive description and evaluation of our method for blood vessel segmentation in fundus images based on a discriminatively trained, fully connected conditional random field model. *Methods:* Standard segmentation priors such as a Potts model or total variation usually fail when dealing with thin and elongated structures. We overcome this difficulty by using a conditional random field model with more expressive potentials, taking advantage of recent results enabling inference of fully connected models almost in real-time. Parameters of the method are learned automatically using a structured output support vector machine, a supervised technique widely used for structured prediction in a number of machine learning applications. *Results:* Our method, trained with state of the art features, is evaluated both quantitatively and qualitatively on four publicly available data sets: DRIVE, STARE, CHASEDB1 and HRF. Additionally, a quantitative comparison with respect to other strategies is included. *Conclusion:* The experimental results show that this approach outperforms other techniques when evaluated in terms of sensitivity, F1-score, G-mean and Matthews correlation coefficient. Additionally, it was observed that the fully connected model is able to better distinguish the desired structures than the local neighborhood based approach. *Significance:* Results suggest that this method is suitable for the task of segmenting elongated structures, a feature that can be exploited to contribute with other medical and biological applications."
authors = ["JI Orlando", "E Prokofyeva", "MB Blaschko"]
date = "2017-02-01"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *IEEE Transactions on Biomedical Engineering*."
publication_short = ""
selected = false
title = "A Discriminatively Trained Fully Connected Conditional Random Field Model for Blood Vessel Segmentation in Fundus Images"
url_code = "https://github.com/ignaciorlando/fundus-vessel-segmentation-tbme/tree/refactoring"
url_dataset = "http://homes.esat.kuleuven.be/~mblaschk/projects/retina/"
url_pdf = "https://lirias.kuleuven.be/bitstream/123456789/531621/3/OrlandoTBME2016.pdf"
url_project = "http://homes.esat.kuleuven.be/~mblaschk/projects/retina/"
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/tbme-vessels.jpg"
caption = "From left to right: original RGB image from HRF, preprocessing, ground truth segmentation, local neighborhood based approach, our results"


+++
