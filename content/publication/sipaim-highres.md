+++
abstract = "Several ophthalmological and systemic diseases are manifested through pathological changes in the properties and the distribution of the retinal blood vessels. The characterization of such alterations requires the segmentation of the vasculature, which is a tedious and time-consuming task that is infeasible to be performed manually. Numerous attempts have been made to propose automated methods for segmenting the retinal vasculature from fundus photographs, although their application in real clinical scenarios is usually limited by their ability to deal with images taken at different resolutions. This is likely due to the large number of parameters that have to be properly calibrated according to each image scale. In this paper we propose to apply a novel strategy for automated feature parameter estimation, combined with a vessel segmentation method based on fully connected conditional random fields. The estimation model is learned by linear regression from structural properties of the images and known optimal configurations, that were previously obtained for low resolution data sets. Our experiments in high resolution images show that this approach is able to estimate appropriate configurations that are suitable for performing the segmentation task without requiring to re-engineer parameters. Furthermore, our combined approach reported state of the art performance on the benchmark data set HRF, as measured in terms of the F1-score and the Matthews correlation coefficient."
authors = ["JI Orlando", "M Fracchia", "V del Rio", "M del Fresno"]
abstract_short = ""
date = "2017-10-05"
image_preview = ""
math = true
publication_types = ["1"]
publication = "In *13th International Symposium on Medical Image Processing and Analysis*, SIPAIM."
publication_short = "In *SIPAIM 2017*"
selected = false
title = "Retinal blood vessel segmentation in high resolution fundus photographs using automated feature parameter estimation"
url_code = ""
url_dataset = "https://github.com/ignaciorlando/high-resolution-vessel-segmentation"
url_pdf = "https://goo.gl/EJ97C9"
url_project = ""
url_slides = ""
url_video = ""


# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/sipaim-highres.png"
caption = "Improvements in the segmentation results obtained by integrating our approach for adjusting feature parameters."

+++
