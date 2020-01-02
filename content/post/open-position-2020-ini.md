+++
date = "2020-01-01T12:00:00"
draft = true
tags = ["open-positions", "español"]
title = "Convocatoria para Estudiantes Avanzados de Ingeniería - Becas INI 2020"
math = true
summary = """Estamos entrevistando candidatos para aplicar a las becas de ingreso a la investigación de la Secretaría de Ciencia, Arte y Tecnología de la UNICEN."""
+++

![Flyer](/img/headers/open-position-2020-ini-header.png)


---

## Resumen

Estamos entrevistando estudiantes avanzados de Ingeniería de Sistemas para aplicar a las [Becas de Ingreso a la Investigación (INI) 2020/2021 de la Secretaría de Ciencia, Arte y Tecnología (SECAT) de la UNICEN](http://secat.unicen.edu.ar/wp-content/uploads/2019/12/Convocatoria_INI_2019v2.pdf). Estas becas te aseguran una remuneración de $4500 mensuales que por trabajar 10 horas semanales durante 1 año en un proyecto de investigación específico, con la ayuda de un/a director/a. Los resultados de tu trabajo podés usarlos después como tesis de grado e incluso como prácticas profesionales supervisadas (PPS). Si te interesa, además podemos continuarlo en el marco de un postgrado.

Las becas son muy competitivas: se dan unas 30 para toda la universidad. La SECAT arma un orden de mérito único con todos los candidatos de toda la universidad, y otorga las becas a los primeros 30. Por este motivo estamos haciendo una preselección de postulantes, para asegurarnos que la persona que se presente tenga muchas más chances de quedar.

El proyecto en el que trabajarías si saliera la beca se enfoca en desarrollar métodos basados en inteligencia artificial (en particular, redes neuronales convolucionales) para estudiar automáticamente imágenes de la retina (fotografías de fondo de ojo). Queremos poder tener un algoritmo preciso que pueda determinar la existencia de lesiones asociadas a la retinopatía diabética, y que posteriormente pueda utilizarse en una plataforma inteligente de telemedicina oftalmológica que estamos desarrollando con el Hospital El Cruce de Florencio Varela.

**Si el proyecto te interesa y te entusiasma hacer investigación en un área como esta, mandame __antes del 1ero de marzo de 2020__ un mail con el asunto "INI 2020" y tu CV como adjunto a [jiorlando@pladema.exa.unicen.edu.ar](mailto:jiorlando@pladema.exa.unicen.edu.ar).**

Una vez que recibamos tu correo, te mandaremos un mail para coordinar una entrevista en PLADEMA, para conocerte un poco más. Más abajo vas a encontrar más detalles sobre la convocatoria, el proyecto y el grupo de investigación.

Mucha suerte!


---


## Requisitos mínimos, preselección y fechas

Los requisitos mínimos de la convocatoria podés encontrarlos [en este link](http://secat.unicen.edu.ar/wp-content/uploads/2019/12/Convocatoria_INI_2019v2.pdf). En resumen, necesitás:

* Ser alumno/a avanzado/a de Ingeniería de Sistemas, con más del 50% de las materias aprobadas (con final, incluyendo optativas!)
* Tener un promedio (con aplazos) mayor a al histórico de la carrera (que a junio de 2019 era de 7.15)

Si además tenés algo de experiencia programando en Python o algunas ideas básicas de machine learning o deep learning, es un plus más para nosotros, aunque no es excluyente. Sí nos parece importante que el/la candidato/a sea alguien proactivo/a y que lo/a entusiasme mucho la investigación, y que maneje un poco de inglés (al menos escribiendo).

Aunque la convocatoria en sí no exige una preselección, analizaremos los perfiles de todos/as los/as candidatos/as que se postulen para asegurarnos que la persona seleccionada tenga muchas chances de quedar.
Si de todas formas no quedás en la preselección, te vamos a tener en cuenta para otras becas que aparezcan, y por supuesto [https://www.exa.unicen.edu.ar/es/piexa/banco-tesis](podés hacer la tesis con nosotros en cualquiera de los temas que tenemos disponibles en el banco de tesis de la facu) (en el combo box "A cargo de:" seleccioná "Dr. José Ignacio Orlando")

**La fecha límite para participar de la preselección es el __1ero de marzo de 2020. Cumplido ese plazo, tenemos tiempo hasta el __25 de marzo de 2020__ para completar toda la documentación y presentarnos a la beca.**

Si te presentamos, los resultados de la beca van a estar publicados el 30 de abril de 2020. Para más info, [consultá el detalle de la convocatoria](hhttp://secat.unicen.edu.ar/wp-content/uploads/2019/12/Convocatoria_INI_2019v2.pdf).


---


## El proyecto

La retinopatía diabética es una de las consecuencias típicas de la diabetes. Se trata de una enfermedad asintomática que es hoy día una de las principales causas de ceguera evitable a nivel mundial. Las [fotografías de fondo de ojo](https://en.wikipedia.org/wiki/Fundus_photography) son la modalidad de imagen médica más barata para estudiar de manera no-invasiva la retina y detectar los signos más tempranos de la enfermedad para arrancar a tiempo el tratamiento. El Hospital El Cruce de Florencio Varela tiene una red de telemedicina oftalmológica mediante la cual técnicos (no médicos) le toman imágenes en distintos puntos de la provincia de Buenos Aires a pacientes de riesgo. Las imágenes se mandan al hospital, donde los olftalmólogos las analizan y responden con un informe y una recomendación sobre ir o no a consultar un oftalmólogo.

Este tipo de redes tiene dos problemas: por un lado, necesitás tener muchos médicos cuando el número de imágenes que hay que estudiar empieza a crecer; y por el otro, detectar los signos más tempranos de la retinopatía diabética es un bardo, porque son unos puntitos rojos (microaneurismas) que se confunden mucho con el fondo de la imagen. Es decir, necesitás mucho tiempo por imagen, y por ende muchos médicos cuando el número de imágenes crece.

La idea central del proyecto es utilizar [redes neuronales convolucionales (convolutional neural networks)](https://en.wikipedia.org/wiki/Convolutional_neural_network) para procesar fotografías de fondo de ojo y [determinar automáticamente el riesgo de que el paciente tenga retinopatía diabética](https://arxiv.org/pdf/1706.03008.pdf). En particular, queremos poder desarrollar un método lo suficientemente robusto como para asignar un valor de probabilidad a la imagen que indique si el paciente tiene o no retinopatía diabética, y que además brinde información respecto a dónde están las lesiones tenidas en cuneta por la red. 

Google hizo algo parecido en la India, como se ve [en este video tremendo narrado por Iron Man](https://youtu.be/V5aZjsWM2wo?t=955). Nosotros queremos hacer algo parecido acá, con nuestros propios métodos, 100% argento, para que no haya que comprarle a Google una solución: a fin de cuentas, tenemos todo lo necesario para hacerlo nosotros! Contar con esta herramienta facilitaría mucho el trabajo de los médicos del Hospital El Cruce, y estaríamos resolviendo un problema enorme a nivel local, regional y mundial!

El proyecto estará supervisado por mí. Durante el transcurso de la beca vamos a utilizar el lenguaje de programación Python y la librería para deep learning Pytorch para desarrollar los métodos propuestos, además de placas gráficas de NVIDIA para correr los experimentos. Además, la iniciativa involucra aprender conceptos muy interesantes de análisis de imagen, visión computacional y machine learning, y embarrarnos un toque con una matemática no muy áspera pero que siempre viene bien aprender :)

Si querés saber más, mandame un mail a jiorlando@pladema.exa.unicen.edu.ar y nos juntamos a conversar un poco más del tema. También podés encontrar más información sobre temas relacionados en algunas de nuestras publicaciones más recientes:

* Orlando, J. I., Breda, J. B., Van Keer, K., Blaschko, M. B., Blanco, P. J., & Bulant, C. A. (2018, September). [Towards a glaucoma risk index based on simulated hemodynamics from fundus images](https://arxiv.org/abs/1805.10273). In International Conference on Medical Image Computing and Computer-Assisted Intervention (pp. 65-73). Springer, Cham.

* Orlando, J. I., Prokofyeva, E., del Fresno, M., & Blaschko, M. B. (2018). [An ensemble deep learning based approach for red lesion detection in fundus images](https://arxiv.org/abs/1706.03008). Computer methods and programs in biomedicine, 153, 115-127.

* Orlando, J. I., Van Keer, K., Barbosa Breda, J., Manterola, H. L., Blaschko, M. B., & Clausse, A. (2017). [Proliferative diabetic retinopathy characterization based on fractal features: Evaluation on a publicly available dataset](https://www.ncbi.nlm.nih.gov/pubmed/29044550). Medical physics, 44(12), 6425-6434.

* Orlando, J. I., Prokofyeva, E., & Blaschko, M. B. (2016). [A discriminatively trained fully connected conditional random field model for blood vessel segmentation in fundus images](https://ieeexplore.ieee.org/document/7420682). IEEE transactions on Biomedical Engineering, 64(1), 16-27.


---


## PLADEMA

[PLADEMA](http://www.pladema.net/) es un instituto de investigación de referencia a nivel nacional en materia de análisis de imagen médica. Ubicados en el Campus Universitario de la UNICEN, contamos con numerosos investigadores responsables distribuidos en varios grupos de investigación que se enfocan en diversas áreas, yendo desde la computación gráfica y la simulación hasta el análisis de redes de energía y sistemas de transporte. 

Como parte de este proyecto te incorporarías a [Yatiris](https://yatiris.github.io), el grupo de análisis de imágenes médicas. Además de un excelente clima de laburo y unos muy buenos cebadores de mates, contamos con acceso a recursos de cómputo suficientes para que puedas trabajar sin inconvenientes y hacer los experimentos necesarios. Contamos además con acceso a bases de datos de imágenes de la retina tanto nuestras como del Hospital El Cruce, y contacto con instituciones de salud en Argentina, Bélgica y Austria como para acceder a datos extra de ser necesario. Como tu potencial director, te puedo ofrecer toda la mano que necesites (incluso codeando! amo codear, jeje) y algunos años de experiencia ya laburando con este tipo de imágenes.