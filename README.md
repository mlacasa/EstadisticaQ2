# Herramientas avanzadas de bioestadística · Q2

Prácticas para médicos, enfermeras y otros profesionales sanitarios que están aprendiendo a investigar. El objetivo es **plantear una pregunta clínica, ejecutar un análisis guiado e interpretar sus resultados**. Los itinerarios principales se realizan en Google Colab, desde el navegador, sin instalar programas en el ordenador.

**Docente:** Dr. Marcos Lacasa-Cazcarra. **Índice actualizado:** 3 de octubre de 2026.

## Empezar por el Tema 3: análisis discriminante en el hospital

**Nueva práctica:** datos reales de Wisconsin y una simulación hospitalaria de ingresos por disnea. Aprende a leer aciertos y errores, sensibilidad, especificidad e incertidumbre antes de estudiar las ampliaciones matemáticas.

[![Abrir el Tema 3 en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Tema_03_ADL/Tema_03_ADL_Hospital_Colab.ipynb)

[Instrucciones del Tema 3](Tema_03_ADL/README.md) · [Ver el notebook](Tema_03_ADL/Tema_03_ADL_Hospital_Colab.ipynb) · [Fuentes y datos](Tema_03_ADL/FUENTES_Y_DATOS.md)

Utiliza el **PDF alternativo del Tema 3, edición 03/10/2026, con cambios en azul**, facilitado por el docente. Sus apartados corresponden a los bloques B01–B16 del cuaderno. El manual se distribuye por separado y no está alojado en este repositorio.

## Elegir una práctica

- [Tema 1: comparación de grupos](#tema-1-comparación-de-grupos).
- [Tema 2: análisis de supervivencia](#tema-2-análisis-de-supervivencia).
- [Tema 3: análisis discriminante lineal](#tema-3-análisis-discriminante-lineal).
- [Otros métodos y modelos](#otros-métodos-y-modelos).
- [Actividades por convocatoria](#actividades-por-convocatoria).
- [Ejercicios complementarios](#ejercicios-complementarios).
- [Cuadernos de ediciones anteriores](#cuadernos-de-ediciones-anteriores).

## Cómo trabajar en Colab

1. Pulsa **Abrir en Colab** junto a la práctica elegida.
2. Guarda una copia mediante **Archivo → Guardar una copia en Drive**. Trabaja en esa copia para conservar tus respuestas.
3. Lee la introducción. Un cuaderno contiene celdas de texto, celdas de código y resultados. Pulsa ▶ para ejecutar la primera celda y continúa en orden, incluida la preparación automática.
4. Antes de cada cálculo, lee la pregunta. Después localiza las cifras indicadas y escribe tu interpretación en las celdas de respuesta.
5. Guarda tu copia al terminar y sigue las instrucciones de entrega de la asignatura.

En los itinerarios principales basta una sesión de CPU: no necesitas GPU ni saber programar. Las instalaciones que indique el propio cuaderno se realizan dentro de Colab. Las actividades de convocatorias anteriores pueden tener instrucciones diferentes; elige la indicada por tu docente.

Si aparece un error, reinicia la sesión y ejecuta desde el principio. Si continúa, comunica el nombre del cuaderno y el bloque que falla. Gemini es un apoyo opcional: redacta primero tu respuesta y contrástala con los resultados. No introduzcas información identificable de pacientes.

## Tema 1: comparación de grupos

Ten a mano el manual del Tema 1 facilitado por el docente. Sigue este orden para pasar de la representación visual al análisis y la interpretación de los ejemplos simulados del manual.

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| 1. Explorar cómo cambian las medias, la dispersión y F | [AnovaPlots.ipynb](AnovaPlots.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AnovaPlots.ipynb) |
| 2. Comparar medias: caso de colesterol | [Anova.ipynb](Anova.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Anova.ipynb) |
| 3. Comparar rangos en grupos independientes y medidas repetidas | [FactorialAnalysisNonParametrical.ipynb](FactorialAnalysisNonParametrical.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/FactorialAnalysisNonParametrical.ipynb) |
| 4. Preparar y defender un informe | [Actividad1_2026.ipynb](Actividad1_2026.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad1_2026.ipynb) |
| 5. Ampliación: ANCOVA y MANOVA | [AncovaManova.ipynb](AncovaManova.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AncovaManova.ipynb) |

## Tema 2: análisis de supervivencia

Sigue estos tres cuadernos junto al **manual del Tema 2 de supervivencia, edición docente 20/09/2026**. Trabajan la interpretación del tiempo hasta un evento y sus condiciones de análisis.

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| 1. Comprender antes de comparar | [SurvivalAnalysis01.ipynb](SurvivalAnalysis01.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/SurvivalAnalysis01.ipynb) |
| 2. Analizar datos reales: de colon al ajuste | [SurvivalAnalysis02.ipynb](SurvivalAnalysis02.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/SurvivalAnalysis02.ipynb) |
| 3. Reconocer cuándo debe cambiar el análisis | [SurvivalAnalysis03.ipynb](SurvivalAnalysis03.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/SurvivalAnalysis03.ipynb) |

El PDF se facilita por separado. Los enlaces locales al manual que contienen estos cuadernos corresponden a la entrega del docente; en Colab, abre el PDF por separado y busca el número de apartado.

## Tema 3: análisis discriminante lineal

La versión de referencia para el manual alternativo de octubre es el cuaderno hospitalario de la carpeta `Tema_03_ADL/`.

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| ADL en el hospital: comprender predicciones y errores | [Tema_03_ADL/Tema_03_ADL_Hospital_Colab.ipynb](Tema_03_ADL/Tema_03_ADL_Hospital_Colab.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Tema_03_ADL/Tema_03_ADL_Hospital_Colab.ipynb) |

El caso principal utiliza muestras reales de Wisconsin; el segundo crea 90 ingresos ficticios por disnea y está identificado como simulación. El recorrido básico combina preguntas, tablas, figuras y respuestas; las ampliaciones matemáticas están señaladas como opcionales. El bloque final exporta los recursos que utiliza el manual.

**Duración orientativa:** dos sesiones de 60–75 minutos para el recorrido básico; unos 30 minutos adicionales para las ampliaciones. Para generar todos los recursos, ejecuta también sus celdas, aunque omitas el estudio matemático.

Los cuadernos antiguos de ADL figuran al final. Algunas ediciones anteriores lo denominaban «Tema 2»; esa numeración no corresponde al manual alternativo del Tema 3.

## Otros métodos y modelos

Material complementario organizado por técnica. Consulta con el docente qué práctica corresponde a tu sesión; esta actualización del índice no constituye una revisión de estos cuadernos.

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| Regresión lineal | [RegresionLineal.ipynb](RegresionLineal.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/RegresionLineal.ipynb) |
| Regresión logística | [RegresionLogistica.ipynb](RegresionLogistica.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/RegresionLogistica.ipynb) |
| Árboles de decisión | [LosarbolesdeDecision.ipynb](LosarbolesdeDecision.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/LosarbolesdeDecision.ipynb) |
| Random forest | [RandomForest.ipynb](RandomForest.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/RandomForest.ipynb) |
| Comparación de modelos | [ComparaModelos.ipynb](ComparaModelos.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/ComparaModelos.ipynb) |
| Validación de modelos | [ValidacionDeModelos.ipynb](ValidacionDeModelos.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/ValidacionDeModelos.ipynb) |
| Análisis conjunto | [AnalisisConjunto.ipynb](AnalisisConjunto.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AnalisisConjunto.ipynb) |
| Series temporales | [TimeSeries.ipynb](TimeSeries.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/TimeSeries.ipynb) |

## Actividades por convocatoria

Abre únicamente la actividad de tu convocatoria. Los nombres parecidos no implican que los enunciados o las entregas sean intercambiables. La actividad `Actividad1_2026.ipynb` se encuentra en el itinerario del Tema 1.

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| Actividad de supervivencia: log-rank y Cox | [Actividad1_Supervivencia2026.ipynb](Actividad1_Supervivencia2026.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad1_Supervivencia2026.ipynb) |
| Actividad 1 · febrero de 2025 | [Actividad_1_Febrero_2025.ipynb](Actividad_1_Febrero_2025.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad_1_Febrero_2025.ipynb) |
| Actividad 1 · febrero de 2026 | [Actividad_1_Febrero_2026.ipynb](Actividad_1_Febrero_2026.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad_1_Febrero_2026.ipynb) |
| Actividad 2 | [Actividad2.ipynb](Actividad2.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad2.ipynb) |
| Actividad 2 · febrero de 2026 | [Actividad2_Febrero_2026.ipynb](Actividad2_Febrero_2026.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad2_Febrero_2026.ipynb) |
| Actividad 2 · regresión y clasificación · 2026 | [Actividad_2_Regresión_Clasificacion_2026.ipynb](Actividad_2_Regresi%C3%B3n_Clasificacion_2026.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad_2_Regresi%C3%B3n_Clasificacion_2026.ipynb) |

## Ejercicios complementarios

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| Ejercicio 1 | [Ejercicio1.ipynb](Ejercicio1.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Ejercicio1.ipynb) |
| Ejercicio 2 | [Ejercicio2.ipynb](Ejercicio2.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Ejercicio2.ipynb) |
| Ejercicio 3 | [Ejercicio3.ipynb](Ejercicio3.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Ejercicio3.ipynb) |

## Cuadernos de ediciones anteriores

Se conservan para consultar trabajos previos y mantener sus enlaces. Para empezar los temas actuales utiliza los itinerarios de supervivencia y ADL de arriba. **Iris no es un conjunto de datos clínicos** y no forma parte de la nueva práctica hospitalaria.

| Práctica | Ver cuaderno | Ejecutar |
| --- | --- | --- |
| ADL con Iris · edición anterior | [AnalisisDiscriminanteLineal.ipynb](AnalisisDiscriminanteLineal.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AnalisisDiscriminanteLineal.ipynb) |
| ADL con Wisconsin · edición anterior | [LDABreastCancer.ipynb](LDABreastCancer.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/LDABreastCancer.ipynb) |
| Supervivencia · cuaderno anterior | [AnálisisSupervivencia.ipynb](An%C3%A1lisisSupervivencia.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/An%C3%A1lisisSupervivencia.ipynb) |
| Supervivencia en colon · cuaderno anterior | [SurvivalAnalysisColon.ipynb](SurvivalAnalysisColon.ipynb) | [Abrir en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/SurvivalAnalysisColon.ipynb) |

## Versiones y comprobaciones

El notebook hospitalario del Tema 3, versión **2026-10-03-v1**, se ejecutó completo en un kernel local nuevo: 17 celdas de código, sin errores, con comprobaciones de recuentos, etiquetas, resultados y exportaciones. Se verificó su correspondencia con el PDF alternativo. **No se ha probado su ejecución en una sesión remota de Google Colab.**

La publicación conserva el código y las salidas de esa versión verificada. La organización de este README no certifica la ejecución ni la revisión de todos los materiales históricos. Para detalles del nuevo caso, consulta las [instrucciones](Tema_03_ADL/README.md) y las [fuentes](Tema_03_ADL/FUENTES_Y_DATOS.md).

## Autoría, fuentes y colaboración

Si reutilizas el material, cita el repositorio según [Citation.cff](Citation.cff). Los conjuntos de datos mantienen sus propias condiciones de uso; la atribución de Wisconsin y las características de la simulación se describen en [Fuentes y datos del Tema 3](Tema_03_ADL/FUENTES_Y_DATOS.md).

Para comunicar una corrección, [abre una incidencia](https://github.com/mlacasa/EstadisticaQ2/issues) indicando cuaderno, bloque y problema observado, sin adjuntar información identificable de pacientes.
