+++
date = "2018-12-18T12:00:00"
draft = false
tags = ["news", "english"]
title = "Two papers accepted for ISBI 2019!"
math = true
summary = """Our two papers on automated retinal OCT image analysis using deep learning have been accepted for presentation at ISBI 2019."""
+++

![Brief description of our pipeline](/img/ISBI_2019_banner_web-960.jpg)

Excellent news to finish an amazing year of work as OPTIMA! We got two papers accepted for presentation at ISBI 2019 :)

**"U2-Net: A Bayesian U-Net model with epistemic uncertainty feedback for photoreceptor layer segmentation in pathological OCT scans"** describes a novel U-shaped architecture for photoreceptor layer segmentation in OCT scans. We modified the basic U-Net with LeakyReLUs, batch normalization and dropout to improve the original segmentation performance. Additionally, we used epistemic uncertainty estimation based on Monte Carlo sampling with dropout on test time to provide qualitative feedback about potential errors of the network. We compared our performance with other baseline approaches and we got state of the art performance for this segmentation task! This study was possible thanks to the support of my co-authors: Phillip Seeböck and Hrvoje Bogunović (who helped me with the technical details), Sophie Klimscha and Christoph Grechenig (who coordinated the manual annotation procedure for us, thank you guys!), and Sebastian Waldstein, Bianca S. Gerendas and Ursula Schmidt-Erfurth (who supervised the clinical aspects of our article). Thanks a lot!

The second papers is **"Using CycleGANs for effectively reducing image variability across OCT devices and improving retinal fluid segmentation"**, and it is a joint research lead both by Phillip Seeböck and David Romo-Bucheli. They introduced the idea of using a CycleGAN to reduce the covariate shift between different OCT devices and allows the transfer of existing segmentation models. I've colaborated with them developing part of the segmentation model. The co-authors are Sebastian Waldstein, Hrvoje Bogunović, Bianca S. Gerendas, Georg Langs and Ursula Schmidt-Erfurth.

We kindly acknowledge the funding agencies supporting this research, including the Christian Doppler Research Association, the Austrian Federal Ministry for Digital and Economic Affairs and the National Foundation for Research, Technology and Development and the Austrian Science Fund, towards the projects FWF I2714-B31 and WWTF AugUniWien / FA746A0249. We also thank the NVIDIA Corporation for donating Titan X and Titan XP GPUs for our experiments.