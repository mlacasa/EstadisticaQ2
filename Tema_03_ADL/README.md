# Tema 3 · ADL en el hospital

**Versión 2026-10-03-v1 · Médicos y enfermeras · Sin programar.**

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mlacasa/EstadisticaQ2/blob/main/Tema_03_ADL/Tema_03_ADL_Hospital_Colab.ipynb)

[Ver el notebook](Tema_03_ADL_Hospital_Colab.ipynb) · [Volver al índice](../README.md)

## Qué aprenderás

Partimos de una pregunta: ¿qué errores comete una regla al clasificar muestras de Wisconsin como benignas o malignas? Aprenderás a distinguir entrenamiento de evaluación, leer una tabla de errores, interpretar sensibilidad y especificidad con incertidumbre y redactar una conclusión con límites claros.

Después explorarás una simulación nueva de 90 ingresos por disnea, con tres grupos y seis mediciones. Los datos simulados explican el método; no validan una herramienta de diagnóstico.

## Abrir y completar la práctica

1. Pulsa **Abrir en Colab** y guarda una copia en Drive.
2. Usa una sesión de CPU y ejecuta las celdas en orden, empezando por la bienvenida y la preparación automática.
3. Lee las preguntas antes de ejecutar; escribe en «Tu respuesta» antes de desplegar las orientaciones.
4. Dedica dos sesiones de 60–75 minutos a B01–B10 y B14–B16. B11–B13 son ampliaciones de unos 30 minutos.
5. Para exportar figuras y tablas en B16, ejecuta todas las celdas anteriores, incluidas las de las ampliaciones. Descarga `recursos_adl_v1.zip` desde el panel Archivos de Colab y guarda el notebook con tus respuestas.

No necesitas instalar programas en tu ordenador, editar Python, obtener claves API ni utilizar GPU. La preparación instala automáticamente los paquetes ausentes en la sesión. Gemini es opcional.

## Relación con el manual

Utiliza exclusivamente el **PDF alternativo del Tema 3, edición 03/10/2026, con cambios en azul**, que facilita el docente por separado. Cada bloque remite a sus apartados; la práctica no depende de que el PDF esté en GitHub. No mezcles estas referencias con el antiguo manual de ADL rotulado Tema 2.

| Bloques | Contenido | Apartados del manual |
| --- | --- | --- |
| B01–B07 | Datos, errores, métricas y evaluación en Wisconsin | Capítulos 1, 2, 4 y 5 |
| B08–B10 | Simulación hospitalaria, ejes, elipses y evaluación | Capítulos 3 y 6 |
| B11–B13 | Pesos, matrices, autovalores y Wilks; ampliaciones | Capítulos 7 y 8 |
| B14–B16 | Publicación, informe, autoevaluación y recursos | Capítulo 9 |

Las figuras, tablas y cifras del manual se generan desde el notebook. No es necesario descargar previamente los recursos para ejecutar: Wisconsin se obtiene con scikit-learn y la simulación tiene semilla fija.

## Archivos de esta carpeta

- [Tema_03_ADL_Hospital_Colab.ipynb](Tema_03_ADL_Hospital_Colab.ipynb): cuaderno completo, con salidas guardadas.
- [FUENTES_Y_DATOS.md](FUENTES_Y_DATOS.md): procedencia, condiciones de uso y límites de los casos y la publicación comentada.
- [requirements_docente.txt](requirements_docente.txt): versiones del entorno numérico local probado, para mantenimiento docente. El alumno de Colab no necesita gestionar este archivo.

## Comprobaciones y ayuda

La versión publicada conserva exactamente el notebook ejecutado localmente en un kernel nuevo: 61 celdas, 17 de código, 9 figuras y 19 tablas HTML; sin errores en esa ejecución. Se verificaron recuentos, etiquetas, intervalos, resultados y exportaciones, además de su correspondencia con el PDF. **No se ha probado una sesión remota de Colab.**

Si falla una celda, reinicia la sesión y ejecuta desde el principio. Si persiste, comunica el identificador B01–B16 y el mensaje al docente. No necesitas reparar dependencias ni introducir información identificable de pacientes.
