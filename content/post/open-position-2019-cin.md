+++
date = "2019-09-03T12:00:00"
draft = false
tags = ["open-positions", "español"]
title = "Convocatoria para Estudiantes Avanzados de Ingeniería - EVC-CIN 2019"
math = true
summary = """Estamos entrevistando candidatos para aplicar a las becas de estímulo a las vocaciones científicas EVC 2019 del CIN (Consejo Universitario Nacional)."""
+++

![Flyer](/img/headers/open-position-2019-cin-header.png)




## Resumen

Estamos entrevistando estudiantes avanzados de Ingeniería de Sistemas para aplicar a las [Becas de Estímulo a las Vocaciones Científicas (EVC) del Consejo Universitario Nacional (CIN)](http://evc.cin.edu.ar/). Estas becas te permiten trabajar 12 horas semanales durante 12 meses en un proyecto de investigación específico, con la ayuda de un/a director/a. Los resultados de tu trabajo podés usarlos después como tesis de grado, o como un punto de apoyo para más adelante hacer un postgrado.

Dado que estas becas son muy competitivas (se dan unas 1500 para todo el país), estamos haciendo una preselección de candidatos, para asegurarnos que el/la postulante que se presente tenga muchas más chances de quedar.

El proyecto en el que trabajarías si saliera la beca se enfoca en desarrollar métodos basados en deep learning (aprendizaje profundo) para la caracterización de los vasos sanguíneos de la retina, usando como entrada fotografías de fondo de ojo. Queremos poder tener un algoritmo preciso que pueda segmentar el árbol vascular y clasificar cada uno de sus segmentos en arteria o vena.

**Si el proyecto te interesa y te entusiasma hacer investigación en un área como esta, mandame __antes del 1ero de octubre de 2019__ un mail con el asunto "EVC-CIN 2019" y tu CV como adjunto a [jiorlando@conicet.gov.ar](mailto:jiorlando@conicet.gov.ar).**

Más abajo vas a encontrar más detalles sobre la convocatoria, el proyecto y el grupo de investigación.

Mucha suerte!



## Requisitos mínimos, preselección y fechas

Los requisitos mínimos de la convocatoria podés encontrarlos en este link. En resumen, necesitás:

* No ser mayor de 30 años al 31 de diciembre de 2019.
* Tener un promedio con aplazos mayor a 6 puntos.
* Tener aprobados con finales más del 50% de las materias de la carrera (tené en cuenta que esto también incluye a las optativas).

Si además tenés algo de experiencia programando en Python o algunas ideas básicas de machine learning o deep learning, es un plus más para nosotros, aunque no es excluyente. Sí nos parece importante que el/la candidato/a sea alguien proactivo/a y que lo/a entusiasme mucho la investigación.

Aunque la convocatoria en sí no exige una preselección, analizaremos los perfiles de todos/as los/as candidatos/as que se postulen para asegurarnos que la persona seleccionada tenga muchas chances de quedar.

**La fecha límite para participar de la preselección es el __1ero de octubre de 2019__. Cumplido ese plazo, tenemos tiempo hasta el __4 de octubre de 2019__ para presentar toda la documentación y presentarnos a la beca.**




## El proyecto

Muchas enfermedades tanto visuales como sistémicas se manifiestan a través de alteraciones en la distribución o morfología del árbol vascular de la retina. Las [fotografías de fondo de ojo](https://en.wikipedia.org/wiki/Fundus_photography) son una modalidad de imagen médica que permite estudiar de manera no-invasiva la retina y sus diferentes regiones anatómicas, incluyendo los vasos sanguíneos.

La idea central del proyecto es utilizar [redes neuronales convolucionales (convolutional neural networks)](https://en.wikipedia.org/wiki/Convolutional_neural_network) para procesar fotografías de fondo de ojo y extraer información de interés sobre la morfología vascular. En particular, queremos poder desarrollar un método lo suficientemente robusto como para simultaneamente [segmentar](https://ieeexplore.ieee.org/document/7420682) y [clasificar](https://limo.libis.be/primo-explore/fulldisplay?docid=LIRIAS2811989&context=L&vid=Lirias&search_scope=Lirias&tab=default_tab&lang=en_US) cada uno de los vasos sanguíneos en arteria o vena. Contar con esta herramienta nos permitirá más adelante estudiar de forma mucho más eficiente grandes volúmenes de imágenes, y poder realizar [simulaciones hemodinámicas](https://arxiv.org/pdf/1805.10273.pdf) para comprender si ciertos parámetros obtenidos de dichas simulaciones se relacionan o no con la presencia de algunas enfermedades.

El proyecto estará supervisado por mí. Durante el transcurso de la beca vamos a utilizar el lenguaje de programación Python y la librería para deep learning Pytorch para desarrollar los métodos propuestos, además de placas gráficas de NVIDIA para correr los experimentos. Además, la iniciativa involucra aprender conceptos muy interesantes de análisis de imagen, visión computacional y machine learning, y embarrarnos un toque con una matemática no muy áspera :)

Si querés saber más, mandame un mail a jiorlando@conicet.gov.ar y nos juntamos a conversar un poco más del tema. También podés encontrar más información sobre temas relacionados en algunas de nuestras publicaciones más recientes:

* Orlando, J. I., Breda, J. B., Van Keer, K., Blaschko, M. B., Blanco, P. J., & Bulant, C. A. (2018, September). [Towards a glaucoma risk index based on simulated hemodynamics from fundus images](https://arxiv.org/abs/1805.10273). In International Conference on Medical Image Computing and Computer-Assisted Intervention (pp. 65-73). Springer, Cham.

* Orlando, J. I., Prokofyeva, E., del Fresno, M., & Blaschko, M. B. (2018). [An ensemble deep learning based approach for red lesion detection in fundus images](https://arxiv.org/abs/1706.03008). Computer methods and programs in biomedicine, 153, 115-127.

* Orlando, J. I., Van Keer, K., Barbosa Breda, J., Manterola, H. L., Blaschko, M. B., & Clausse, A. (2017). [Proliferative diabetic retinopathy characterization based on fractal features: Evaluation on a publicly available dataset](https://www.ncbi.nlm.nih.gov/pubmed/29044550). Medical physics, 44(12), 6425-6434.

* Orlando, J. I., Prokofyeva, E., & Blaschko, M. B. (2016). [A discriminatively trained fully connected conditional random field model for blood vessel segmentation in fundus images](https://ieeexplore.ieee.org/document/7420682). IEEE transactions on Biomedical Engineering, 64(1), 16-27.




## PLADEMA

[PLADEMA](http://www.pladema.net/) es un instituto de investigación de referencia a nivel nacional en materia de análisis de imagen médica. Ubicados en el Campus Universitario de la UNICEN, contamos con numerosos investigadores responsables distribuidos en varios grupos de investigación que se enfocan en diversas áreas, yendo desde la computación gráfica y la simulación hasta el análisis de redes de energía y sistemas de transporte. 

Como parte de este proyecto te incorporarías a Yatiris, el grupo de análisis de imágenes médicas. Además de un excelente clima de laburo y unos muy buenos cebadores de mates, contamos con acceso a recursos de cómputo suficientes para que puedas trabajar sin inconvenientes y hacer los experimentos necesarios. Contamos además con acceso a bases de datos públicas de imágenes de la retina, y contacto con instituciones de salud en Argentina, Bélgica y Austria como para acceder a datos extra de ser necesario. Como tu potencial director, te puedo ofrecer toda la mano que necesites (incluso codeando! amo codear, jeje) y algunos años de experiencia ya laburando con este tipo de imágenes.