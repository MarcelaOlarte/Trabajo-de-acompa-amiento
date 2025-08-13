#  📊 Análisis de prevalencia de enfermedades en Colombia
Este repositorio contiene un análisis exploratorio de datos (EDA) de un dataset público sobre la prevalencia de enfermedades crónicas y su distribución en la población, segmentado por sexo, edad y ciclo de vida.

🚀 El objetivo de este proyecto es explorar y visualizar los patrones de enfermedades crónicas en una población específica, utilizando un dataset público de Colombia. A través de este análisis, se busca responder a preguntas clave como:

* ¿Cuál es la distribución de enfermedades como la diabetes, hipertensión o asma según el sexo?
* ¿Cómo varía la cantidad promedio de enfermedades a lo largo de los diferentes ciclos de vida?
* ¿Existe una diferencia en el riesgo cardiovascular (definido por la presencia de hipertensión y/o diabetes) entre hombres y mujeres?

## 📂 Descripción de los datos

* **Nombre de la Base de Datos:** `Estadísticas de enfermedades crónicas`.
* **Fuente:** [Datos.gov.co](https://www.datos.gov.co/resource/4iz7-suhz.json), una base de datos pública del gobierno colombiano.
* **Contenido:** El dataset incluye información anónima sobre individuos, como:
    * `sexo`, `grupo_etareo`, `ciclo_de_vida`.
    * Columnas binarias (1=Sí, 2=No) para las siguientes enfermedades:
        `artritis`, `diabetes`, `hipertensi_n`, `epoc`, `asma`, `insuficiencia_cardiaca`, `c_ncer`, `huerfanas_hemofilias_y_otras`, `cirugia_cardiaca`, `trasplantados`.

## 📈 Hallazgos clave

 **📊 Distribución de enfermedades por sexo:**
Las enfermedades más frecuentes son hipertensión, diabetes y artritis.

Diferencias por género:

**♂️ Hombres:** Mayor prevalencia de hipertensión y diabetes.

**♀️ Mujeres:** Mayor prevalencia de artritis e insuficiencia cardíaca.

**🚨 Riesgo cardiovascular**
- El 37% de la población presenta un riesgo alto.
- Este riesgo es más alto en hombres que en mujeres.
- La mayoría de los casos de alto riesgo se concentran en personas mayores de 60 años.

**📈 Carga de enfermedades por ciclo de vida**
La carga de enfermedades aumenta con la edad.

- **Niños y jóvenes:** Carga casi nula.
- **Adultos:** Incremento gradual, especialmente en hipertensión y diabetes.
- **Personas mayores (60+):** Carga más alta, con múltiples enfermedades coexistiendo.

**🏥 Prevalencia total y multimorbilidad** 
- Las enfermedades crónicas cardiovasculares y metabólicas son las más frecuentes.
- Una proporción significativa de la población presenta más de una enfermedad, lo que indica un riesgo acumulado.
- Enfermedades raras, cirugías cardíacas y trasplantes tienen una baja incidencia, pero son importantes para identificar subpoblaciones vulnerables.
  
