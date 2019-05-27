+++
abstract = "Diagnosis and treatment guidance are aided by detecting relevant biomarkers in medical images. Although supervised deep learning can perform accurate segmentation of pathological areas, it is limited by requiring a-priori definitions of these regions, large-scale annotations, and a representative patient cohort in the training set. In contrast, anomaly detection is not limited to specific definitions of pathologies and allows for training on healthy samples without annotation. Anomalous regions can then serve as candidates for biomarker discovery. Knowledge about normal anatomical structure brings implicit information for detecting anomalies. We propose to take advantage of this property using bayesian deep learning, based on the assumption that epistemic uncertainties will correlate with anatomical deviations from a normal training set. A Bayesian UNet is trained on a well-defined healthy environment using weak labels of healthy anatomy produced by existing methods. At test time, we capture epistemic uncertainty estimates of our model using Monte Carlo dropout. A novel post-processing technique is then applied to exploit these estimates and transfer their layered appearance to smooth blob-shaped segmentations of the anomalies. We experimentally validated this approach in retinal optical coherence tomography (OCT) images, using weak labels of retinal layers. Our method achieved a Dice index of 0.789 in an independent anomaly test set of age-related macular degeneration (AMD) cases. The resulting segmentations allowed very high accuracy for separating healthy and diseased cases with late wet AMD, dry geographic atrophy (GA), diabetic macular edema (DME) and retinal vein occlusion (RVO). Finally, we qualitatively observed that our approach can also detect other deviations in normal scans such as cut edge artifacts."
authors = ["P Seeböck", "JI Orlando", "T Schlegl", "S Waldstein", "H Bogunović", "S Klimscha", "G Langs", "U Schmidt-Erfurth"]
date = "2019-05-27"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *IEEE Transactions on Medical Imaging*."
publication_short = ""
selected = false
title = "Exploiting Epistemic Uncertainty of Anatomy Segmentation for Anomaly Detection in Retinal OCT"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/tmi-2019.png"
caption = "Qualitative results of the proposed method, on the late wet AMD test set. Central B-scans of volumes in which the proposed method performed best/worst in terms of the Dice index are shown. The corresponding Dice values are 0.82, 0.81, 0.72 and 0.72, from top to bottom. The last column indicates the overlap between the manual annotations of anomaly in green and the prediction of anomaly by our model in red."


+++
