+++
abstract = "Purpose: In this paper we propose to apply generative adversarial neural networks trained with a cycle-consistency loss, or CycleGANs, to improve realism in ultrasound (US) simulation from Computed Tomography (CT) scans. Methods: A ray-casting US simulation approach is used to generate intermediate synthetic images from abdominal CT scans. Then, an unpaired set of these synthetic and real US images is used to train CycleGANs with two alternative architectures for the generator, a U-Net and a ResNet. These networks are finally used to translate ray-casting based simulations into more realistic synthetic US images. Results: Our approach was evaluated both qualitatively and quantitatively. A user study performed by two experts in US imaging shows that both networks significantly improve realism with respect to the original ray-casting algorithm (p << 0.001), with the ResNet model performing better than the U-Net. Conclusion: Applying CycleGANs allows to obtain better synthetic US images of the abdomen. These preliminary results pave the way towards efficient patient-specific US simulation for low-cost training of medical doctors and radiologists."
authors = ["S Vitale", "JI Orlando", "E Iarussi", "I Larrabide"]
date = "2018-12-18"
image_preview = ""
math = true
publication_types = ["2"]
publication = "In *Computer Assisted Radiology and Surgery*, CARS."
publication_short = "In *CARS 2019*"
selected = true
title = "Improving realism in patient-specific abdominal Ultrasound simulation using CycleGANs"
url_code = ""
url_dataset = ""
url_pdf = ""
url_project = ""
url_slides = ""
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/cars-pipeline.png"
caption = ""


+++
