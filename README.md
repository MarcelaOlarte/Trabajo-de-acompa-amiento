#  Análisis de prevalencia de enfermedades en Colombia
Este repositorio contiene un análisis exploratorio de datos (EDA) de un dataset público sobre la prevalencia de enfermedades crónicas y su distribución en la población, segmentado por sexo, edad y ciclo de vida.

El objetivo de este proyecto es explorar y visualizar los patrones de enfermedades crónicas en una población específica, utilizando un dataset público de Colombia. A través de este análisis, se busca responder a preguntas clave como:

* ¿Cuál es la distribución de enfermedades como la diabetes, hipertensión o asma según el sexo?
* ¿Cómo varía la cantidad promedio de enfermedades a lo largo de los diferentes ciclos de vida?
* ¿Existe una diferencia en el riesgo cardiovascular (definido por la presencia de hipertensión y/o diabetes) entre hombres y mujeres?

## Descripción de los datos

* **Nombre de la Base de Datos:** `Estadísticas de enfermedades crónicas`.
* **Fuente:** [Datos.gov.co](https://www.datos.gov.co/resource/4iz7-suhz.json), una base de datos pública del gobierno colombiano.
* **Contenido:** El dataset incluye información anónima sobre individuos, como:
    * `sexo`, `grupo_etareo`, `ciclo_de_vida`.
    * Columnas binarias (1=Sí, 2=No) para las siguientes enfermedades:
        `artritis`, `diabetes`, `hipertensi_n`, `epoc`, `asma`, `insuficiencia_cardiaca`, `c_ncer`, `huerfanas_hemofilias_y_otras`, `cirugia_cardiaca`, `trasplantados`.

## Hallazgos clave

 **1. Distribución de enfermedades por sexo:**
Las enfermedades más frecuentes son hipertensión, diabetes y artritis.

Diferencias por género:

**♂️ Hombres:** Mayor prevalencia de hipertensión y diabetes.

**♀️ Mujeres:** Mayor prevalencia de artritis e insuficiencia cardíaca.

**2. Riesgo cardiovascular**
- El 37% de la población presenta un riesgo alto.
- Este riesgo es más alto en hombres que en mujeres.
- La mayoría de los casos de alto riesgo se concentran en personas mayores de 60 años.

**3. Carga de enfermedades por ciclo de vida**
La carga de enfermedades aumenta con la edad.

- **Niños y jóvenes:** Carga casi nula.
- **Adultos:** Incremento gradual, especialmente en hipertensión y diabetes.
- **Personas mayores (60+):** Carga más alta, con múltiples enfermedades coexistiendo.

**4.Prevalencia total y multimorbilidad** 
- Las enfermedades crónicas cardiovasculares y metabólicas son las más frecuentes.
- Una proporción significativa de la población presenta más de una enfermedad, lo que indica un riesgo acumulado.
- Enfermedades raras, cirugías cardíacas y trasplantes tienen una baja incidencia, pero son importantes para identificar subpoblaciones vulnerables.


  <img width="1006" height="689" alt="image" src="https://github.com/user-attachments/assets/ef8d2723-a7cd-4cf4-a42c-caadeaa9bd33" />

## Conclusión 

El análisis de la base de datos evidencia que las enfermedades crónicas cardiovasculares y metabólicas como hipertensión y diabetes son las más prevalentes, especialmente en hombres y en personas mayores de 60 años. Se observa un incremento progresivo de la carga de enfermedades con la edad, y una proporción significativa de la población presenta multimorbilidad, lo que implica riesgos acumulativos para la salud.

Estos hallazgos resaltan la importancia de implementar estrategias preventivas y de manejo integral, orientadas tanto a la detección temprana como al control de múltiples enfermedades, especialmente en los grupos más vulnerables.

## Tecnologías y herramientas

* **Lenguajes:** `Python`
* **Librerías:**
    * `Pandas` para la manipulación y análisis de datos.
    * `NumPy` para operaciones numéricas.
    * `Matplotlib` para la creación de gráficos.
    * `Seaborn` para visualizaciones estadísticas más atractivas.
* **Entorno:** `Google Colab`

  ## Visualizaciones

<img width="696" height="470" alt="image" src="https://github.com/user-attachments/assets/8113f5af-dcf9-4f27-824d-bd60c1c34424" /> 

<img width="846" height="635" alt="image" src="https://github.com/user-attachments/assets/8ce1395c-80c4-4b84-9e36-404e92be0683" />

## Cómo reproducir el análisis

Este análisis fue desarrollado en **Google Colab**. Para reproducirlo, haz clic en el siguiente enlace y ejecuta las celdas del notebook en tu navegador:

[![https://colab.research.google.com/drive/1rOGkogxqQXzAl6OkodRjC1StNHAY7XL6?usp=sharing]

El notebook incluye la carga de datos, la manipulación, los cálculos y la generación de todas las visualizaciones mencionadas. Solo necesitas ejecutar las celdas en orden.

**Realizado por:**
- Ivanna Stefany Lerma Hernandez
- Juan Esteban Galeano Marin
- Diana Marcela Olarte Vargas

