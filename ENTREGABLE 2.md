# Estado del arte comercial
1. WEMU:

![imahttps://github.com/JosephOviedo/Proyecto_de_Funbio/assets/143360320/6b918c02-4b87-4b7b-b24a-4e37a7ecc3cb)

Rivero E. WEMU: La camiseta que detecta convulsiones [Internet]. unocero. 2014 [citado el 20 de septiembre de 2023]. Disponible en: https://www.unocero.com/noticias/wemu-la-camiseta-que-detecta-convulsiones/


1.1 Concepto  
[4] Se propuso una camiseta equipada con sensores biométricos conectados a una aplicación de un teléfono que permitirá el almencenamiento de datos.

1.2 Beneficios
- Elimina la necesidad de que el paciente esté conectado a una máquina mucho más sofisticada y con bastantes más cables.
- Da uso a las conexiones inalámbricas en lugar que tener que usar equipos de escritorio, lo que permite un continuo análisis de datos     
  desde cualquier lugar en cualquier momento.

1.3 Patente
![image](https://github.com/JosephOviedo/Proyecto_de_Funbio/assets/143360320/cb023055-c7d9-4d34-a3c6-ce15b354792c)

WIPO - search international and national patent collections [Internet]. Wipo.int. [citado el 20 de septiembre de 2023]. Disponible en: https://patentscope.wipo.int/search/en/detail.jsf?docId=FR319917205&_cid=P12-LMH550-21427-1


1.4 Paper:
Hanif U, Gimenez U, Cairns A, Lewin D, Ashraf N, Mignot E. Automatic detection of chronic insomnia from polysomnographic and clinical variables      using machine learning [Internet]. Com.au. [citado el 13 de septiembre de 2023]. Disponible en: https://arinex.com.au/EMBC/pdf/full-paper_562.pdf

2. EmbracePlus

   
![image](https://github.com/JosephOviedo/Proyecto_de_Funbio/assets/143360320/249878e6-76df-47d8-994e-b5f4389513bd)

Empatica.com. [citado el 20 de septiembre de 2023]. Disponible en: https://www.empatica.com/assets/images/e4/2/e4-perspective-back-trasp-xhdpi.jpg

2.1 Concepto

[5] Se basa en un brazalete con sensores diseñados para poder identificar datos de alto nivel. Este dispositivo detecta simultáneamente las medidas dela actividad del sistema nervioso simpático y frecuencia cardíaca. 

2.2 Beneficio
- Es el único dispositivo "wearable" que combina los sensores de tipo EDA y PPG.
- Proporciona evidencia actualizada de la efectividad respecto a las señales captadas.
- Reduce los riesgos de muerte por los ataques epilépticos.

2.3 Patente
![image](https://github.com/JosephOviedo/Proyecto_de_Funbio/assets/143360320/2a8220a1-0bf1-4198-85da-0c9944147270)

OMPI – Búsqueda en las colecciones de patentes nacionales e internacionales [Internet]. Wipo.int. [citado el 20 de septiembre de 2023]. Disponible en: https://patentscope.wipo.int/search/es/detail.jsf?docId=CN370168613&_cid=P12-LMH5VE-26802-4


2.4 Artículo relacionado: 
Regalia G, Onorati F, Lai M, Caborni C, Picard RW. Multimodal wrist-worn devices for seizure detection and advancing research: Focus on the Empatica wristbands. Epilepsy Res [Internet]. 2019;153:79–82. Disponible en: https://www.sciencedirect.com/science/article/pii/S0920121118305849

3. mjn-SERAS

![image](https://github.com/JosephOviedo/Proyecto_de_Funbio/assets/143360320/d4f42d58-6b3f-41f8-92db-a7f87c4be7cf)

Els-cdn.com. [citado el 20 de septiembre de 2023]. Disponible en: https://ars.els-cdn.com/content/image/1-s2.0-S2589986423000187-gr2.jpg


3.1 Concepto

[6] El prototipo consta de un auricular impreso en 3D que cuantifica la actividad cerebral para alertarr al usuario en caso sea posible un riesgo de crisis de epilepsia.

3.2 Beneficios
- La impresión 3D permite que el prototipo sea fabricado a medida personalizada del usuario, beneficiando su comodidad.
- Los datos recopilados por el auricular son enviados a una aplicación en celular que permite un monitoreo constante.

3.3 Patente

![image](https://github.com/JosephOviedo/Proyecto_de_Funbio/assets/143360320/2e369b10-bb34-4f4c-8d1f-bddc29ca720d)

WIPO - search international and national patent collections [Internet]. Wipo.int. [citado el 20 de septiembre de 2023]. Disponible en: https://patentscope.wipo.int/search/en/detail.jsf?docId=US344952179&_cid=P12-LMH83F-49155-1


3.4 Página de la empresa: mjn-SERAS [Internet]. mjn-neuro - Un auricular que evalúa el riesgo de crisis de epilepsia. mjn-neuro; 2017 [citado el 13 de septiembre de 2023]. Disponible en: https://mjn.cat/

3.5 Artículo relacionado: Torres-Gaona G, Aledo-Serrano Á, García-Morales I, Toledano R, Valls J, Cosculluela B, et al. Artificial intelligence system, based on mjn-SERAS algorithm, for the early detection of seizures in patients with refractory focal epilepsy: A cross-sectional pilot study. Epilepsy Behav Rep [Internet]. 2023;22(100600):100600. Disponible en: https://www.sciencedirect.com/science/article/pii/S2589986423000187


# Funcionales: ¿Qué es lo que el diseño debe hacer?
- Identificación de los centros convulsivos por medio de imágenes de los lóbulos cerebrales.
- Informe de lo detectado apto para el entendendimiento del doctor y el tutor del paciente.
- Recepción de señales en cada instante para la toma de datos con almacenamiento de estos.
- Ayudar a generar más campo visual para que el doctor para que encuentre soluciones un mejor tratamiento.
  
# No funcionales: ¿Cuáles son las propiedades de mi diseño?
- No invasivo para el paciente.
- Cómodo y versátil.
- Fácil de transportar.
- Ergonómico.

# Propuesta de solución
 Wearable centrado en la epilepsia tipo "tónico-clónica", capaz de leer las señales del cuerpo y el cerebro (lecturas dadas antes y durante las etapas de las convulsiones), además de almacenar datos en la nube e informar los resultados al doctor encargado y paciente por medio de un aplicación móvil. 
