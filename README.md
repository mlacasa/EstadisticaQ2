# Herramientas Avanzadas de Bioestadística - Fichas Interactivas en Google Colab

Este repositorio recopila una serie de **fichas prácticas interactivas** diseñadas para la asignatura *Herramientas Avanzadas de Bioestadística*, impartida en el marco de programas de posgrado en ciencias de la salud. Cada ficha está elaborada en formato `.ipynb` y ejecutable directamente desde Google Colab, permitiendo el análisis reproducible y la exploración guiada de técnicas estadísticas avanzadas.

## 📖 Tema 1: del manual al análisis

Ten a mano el **manual teórico del Tema 1 facilitado por el docente** y sigue el
itinerario de la tabla. Estos cinco cuadernos incluyen preguntas antes del cálculo,
explicaciones para interpretar las salidas y referencias a los apartados y páginas
del manual. El manual se distribuye por separado. Los datos son simulados y
reproducen los ejemplos del texto.

| Orden | Práctica | Abrir y trabajar |
| --- | --- | --- |
| 1 | Ver cómo cambia F: medias, dispersión y tamaño muestral | [AnovaPlots en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AnovaPlots.ipynb) |
| 2 | Calcular ANOVA y explicar el caso de colesterol | [Anova en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Anova.ipynb) |
| 3 | Comparar rangos con grupos independientes y medidas repetidas | [No paramétricos en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/FactorialAnalysisNonParametrical.ipynb) |
| 4 | Preparar y defender tu propio informe | [Actividad 1 en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Actividad1_2026.ipynb) |
| 5 | Ampliar: ajuste basal con ANCOVA y dos respuestas con MANOVA | [ANCOVA y MANOVA en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AncovaManova.ipynb) |

Guarda una copia en Drive y ejecuta las celdas en orden. La preparación instala las
bibliotecas necesarias en la sesión y genera los datos: no necesitas GPU, subir CSV
ni descargar un proyecto completo. Escribe tus conclusiones en celdas de texto.

## Tema 2: entender y evaluar el análisis discriminante

Abre el **manual teórico del Tema 2 facilitado por el docente** y empieza por Iris.
Cada bloque incluye una pregunta antes del cálculo y referencias a los apartados
y páginas de la edición revisada del manual, que se distribuye por separado.

| Orden | Práctica | Abrir y trabajar |
| --- | --- | --- |
| 1 | Iris: de ANOVA a las direcciones discriminantes, elipses, Wilks y evaluación | [ADL con Iris en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/AnalisisDiscriminanteLineal.ipynb) |
| 2 | Cáncer de mama: etiquetas, preprocesamiento dentro de validación y métricas | [ADL con Wisconsin en Colab](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/LDABreastCancer.ipynb) |

Guarda una copia en Drive y ejecuta desde la primera celda. Los datos vienen con
scikit-learn y las funciones están incluidas; basta una sesión de Python con CPU.
Las semillas están fijadas para contrastar tus resultados con el manual. En Iris
distinguimos el ajuste descriptivo de la evaluación en test; en Wisconsin definimos
malignidad como evento y comprobamos si la búsqueda mejora realmente el modelo.
Escribe tus interpretaciones junto a las salidas: una cifra correcta también necesita
una explicación de lo que permite concluir.

## 🧪 Contenido del repositorio

Las fichas se agrupan en distintas áreas temáticas clave:

### 📊 Modelización Estadística y Pruebas Clásicas
- `RegresionLineal.ipynb`
- `RegresionLogistica.ipynb`
- `Anova.ipynb`
- `AnovaPlots.ipynb`
- `AncovaManova.ipynb`

### 🧬 Análisis Multivariante
- `AnalisisConjunto.ipynb`
- `AnalisisDiscriminanteLineal.ipynb`
- `LDABreastCancer.ipynb`
- `FactorialAnalysisNonParametrical.ipynb`

### 🌳 Machine Learning aplicado a Bioestadística
- `LosarbolesdeDecision.ipynb`
- `RandomForest.ipynb`
- `ComparaModelos.ipynb`
- `ValidacionDeModelos.ipynb`

### ⏳ Análisis de Supervivencia y Series Temporales
- `AnálisisSupervivencia.ipynb`
- `SurvivalAnalysisColon.ipynb`
- `TimeSeries.ipynb`

### 📁 Actividades por convocatoria
- `Actividad_1_Febrero_2025.ipynb`
- `Actividad_1_Febrero_2026.ipynb`
- `Actividad2.ipynb`
- `Actividad2_Febrero_2026.ipynb`

### 📝 Otros ejercicios introductorios
- `Ejercicio1.ipynb`
- `Ejercicio2.ipynb`
- `Ejercicio3.ipynb`

## 📌 Cómo usar estas fichas

Cada cuaderno está pensado para ser ejecutado en [Google Colab](https://colab.research.google.com/), sin necesidad de instalación local. Para empezar:

1. Haz clic en el fichero `.ipynb` deseado.
2. Pulsa el botón **"Open in Colab"** o selecciona "Abrir con Colab" desde la interfaz.
3. Ejecuta las celdas secuencialmente, siguiendo las instrucciones comentadas.

> ⚠️ Algunas fichas requieren la instalación de paquetes como `lifelines`, `scikit-learn`, `statsmodels` o `pingouin`. Estas instrucciones están incluidas en cada notebook.

## 📚 Citación

Si reutilizas parte de este material con fines docentes o científicos, por favor, cita el repositorio según el archivo [`Citation.cff`](./Citation.cff).

---

## 👨‍🏫 Autoría y colaboración

Estas fichas han sido desarrolladas en el contexto de la docencia universitaria en bioestadística avanzada, y se actualizan periódicamente para incluir nuevas técnicas y casos de estudio.

¿Tienes sugerencias o correcciones? ¡Puedes proponer cambios a través de *pull requests* o abrir un *issue*!

---
