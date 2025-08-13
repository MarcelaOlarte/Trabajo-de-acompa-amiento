# Análisis de prevalencia de enfermedades en Colombia
Este repositorio contiene un análisis exploratorio de datos (EDA) de un dataset público sobre la prevalencia de enfermedades crónicas y su distribución en la población, segmentado por sexo, edad y ciclo de vida.

El objetivo de este proyecto es explorar y visualizar los patrones de enfermedades crónicas en una población específica, utilizando un dataset público de Colombia. A través de este análisis, se busca responder a preguntas clave como:

* ¿Cuál es la distribución de enfermedades como la diabetes, hipertensión o asma según el sexo?
* ¿Cómo varía la cantidad promedio de enfermedades a lo largo de los diferentes ciclos de vida?
* ¿Existe una diferencia en el riesgo cardiovascular (definido por la presencia de hipertensión y/o diabetes) entre hombres y mujeres?

## 📂 Descripción de los Datos

* **Nombre de la Base de Datos:** `Estadísticas de enfermedades crónicas`.
* **Fuente:** [Datos.gov.co](https://www.datos.gov.co/resource/4iz7-suhz.json), una base de datos pública del gobierno colombiano.
* **Contenido:** El dataset incluye información anónima sobre individuos, como:
    * `sexo`, `grupo_etareo`, `ciclo_de_vida`.
    * Columnas binarias (1=Sí, 2=No) para las siguientes enfermedades:
        `artritis`, `diabetes`, `hipertensi_n`, `epoc`, `asma`, `insuficiencia_cardiaca`, `c_ncer`, `huerfanas_hemofilias_y_otras`, `cirugia_cardiaca`, `trasplantados`.

  
#  Limpieza y transformación de datos

Se convirtieron los valores de enfermedades a 1 = Sí y 0 = No.

Se creó la columna riesgo_cardiovascular:
