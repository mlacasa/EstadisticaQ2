# Fuentes y datos

Consultas comprobadas el 03/10/2026.

## Wisconsin (real)

Wolberg y colaboradores. Breast Cancer Wisconsin (Diagnostic). UCI Machine Learning Repository. DOI https://doi.org/10.24432/C5DW2B. Fuente: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic. UCI declara **CC BY 4.0**: atribuir el conjunto, enlazar la licencia https://creativecommons.org/licenses/by/4.0/ e indicar transformaciones. La copia numérica se obtiene de `load_breast_cancer()` de scikit-learn, cuya documentación se enlaza en el cuaderno.

Se mantienen 569 muestras, 30 predictores y 0=maligno/1=benigno. Se agrega solo un índice docente para seguir filas (no entra en el modelo). No hay exclusiones, datos ausentes ni imputaciones. Se calculan transformaciones exclusivamente con entrenamiento. La copia no incluye una auditoría de todas las verificaciones diagnósticas originales ni identificadores de seguimiento. No atribuir unidades físicas no documentadas a las variables de imagen.

## Disnea (simulada)

Simulación nueva, semilla 20261003: 90 ingresos, 30 por grupo. Normal multivariante con medias y covarianza fijadas de antemano, sin recortes ni búsqueda de semillas. Un ingreso ficticio por persona; no hay casos mixtos. Las seis variables y unidades, matrices y reglas se incluyen en el manifiesto. El aire ambiente es una condición ficticia del generador, no una instrucción asistencial. Los datos no proceden de pacientes reales, no renombran Iris y no validan un clasificador clínico.

## Publicación y uso docente

Wolberg WH, Street WN, Mangasarian OL (1994). Machine learning techniques to diagnose breast cancer from image-processed nuclear features of fine needle aspirates. Cancer Letters 77:163-171. DOI https://doi.org/10.1016/0304-3835(94)90099-X. Resumen: https://pubmed.ncbi.nlm.nih.gov/8168063/.

Se ha consultado el resumen. Diseño descrito: desarrollo de un sistema diagnóstico con 569 pacientes y evaluación en 54 pacientes nuevos; muestras de aspirados mamarios y clasificación diagnóstica. Función: preguntar qué añade evaluar nuevas observaciones. Orientación: distinguir desarrollo de generalización y reconocer que un resumen no permite auditar sesgos y verificación de referencia. No se atribuyen al artículo las cifras del ADL docente; no se reanalizan sus 54 pacientes. Texto completo no revisado; datos individuales de esa evaluación no obtenidos; figuras no reproducidas. La licencia de UCI no constituye permiso de reproducción de figuras del artículo.

## Método

https://scikit-learn.org/stable/modules/lda_qda.html
https://scikit-learn.org/stable/common_pitfalls.html
https://scikit-learn.org/stable/datasets/toy_dataset.html#breast-cancer-dataset

No se concede mediante este archivo una licencia nueva sobre el manual, las marcas institucionales o el contenido docente preexistente.
