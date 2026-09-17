# ConnectaTel — Análisis y Segmentación de Clientes

## Descripción del proyecto

Este proyecto presenta un análisis exploratorio de datos de clientes de ConnectaTel, con el objetivo de identificar patrones de uso, evaluar la calidad de los datos y segmentar a los usuarios de acuerdo con su comportamiento y edad.

El análisis fue desarrollado utilizando Python y las librerías Pandas, NumPy, Matplotlib y Seaborn.

## Objetivos

- Explorar y evaluar la calidad de los datos.
- Identificar valores nulos, valores inválidos y posibles inconsistencias.
- Analizar la distribución de las principales variables de uso.
- Detectar posibles valores atípicos mediante boxplots y el método IQR.
- Crear segmentos de clientes según su nivel de uso.
- Crear segmentos de clientes según su edad.
- Analizar la relación entre los segmentos de clientes y el tipo de plan.
- Generar insights y recomendaciones para apoyar la toma de decisiones del negocio.

## Datasets utilizados

El análisis utiliza tres datasets:

- `plans.csv`: información sobre los planes disponibles.
- `users_latam.csv`: información demográfica y contractual de los clientes.
- `usage.csv`: registros de llamadas y mensajes realizados por los usuarios.

## Etapas del análisis

1. Carga y exploración inicial de los datos.
2. Identificación de problemas de calidad.
3. Tratamiento de valores inválidos y fechas inconsistentes.
4. Creación de métricas de uso por usuario.
5. Análisis estadístico descriptivo.
6. Visualización de distribuciones.
7. Identificación de valores atípicos mediante IQR.
8. Segmentación de clientes por edad y nivel de uso.
9. Análisis de la relación entre segmentos y planes.
10. Elaboración de insights y recomendaciones para stakeholders.

## Principales resultados

El análisis identificó que:

- El 73.58 % de los clientes pertenece al segmento de uso medio.
- El 19.45 % pertenece al segmento de bajo uso.
- El 6.98 % pertenece al segmento de alto uso.
- El 50.45 % de los clientes pertenece al grupo Adulto.
- El 30.55 % pertenece al grupo Adulto Mayor.
- El 19.00 % pertenece al grupo Joven.
- El plan Básico representa el 64.88 % de los clientes y el Premium el 35.12 %.
- La distribución de los planes es similar entre los diferentes niveles de uso, por lo que no se observa una asociación fuerte entre el tipo de plan y el nivel de uso.

## Herramientas utilizadas

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

## Cómo ejecutar el proyecto

1. Descargar o clonar este repositorio.
2. Abrir el archivo `.ipynb` en un entorno compatible con Jupyter Notebook.
3. Asegurarse de contar con los datasets necesarios.
4. Instalar las librerías utilizadas si no se encuentran disponibles.
5. Ejecutar las celdas del notebook en orden.

> Nota: las rutas de los datasets pueden necesitar ajustes dependiendo del entorno donde se ejecute el notebook.

## ▶️ Cómo abrir el notebook en Google Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tatianabarthelemy/connectatel-analysis/blob/main/S7%20Version-Estudiante-Project-ConnectaTel.ipynb)

Haz clic en el botón anterior para abrir directamente el notebook en Google Colab.

## Opción alternativa

1. Abre Google Colab.
2. Selecciona **Archivo → Abrir cuaderno**.
3. Selecciona **GitHub**.
4. Busca el repositorio `tatianabarthelemy/connectatel-analysis`.
5. Abre `S7 Version-Estudiante-Project-ConnectaTel.ipynb`.

## Archivo principal

`S7 Version-Estudiante-Project-ConnectaTel.ipynb`

Contiene el proceso completo de limpieza, análisis exploratorio, visualización, segmentación e interpretación de resultados.

## Contexto académico

Proyecto desarrollado como parte del programa **Data Analyst de TripleTen**, con fines educativos y de desarrollo de portafolio.

## Autora

Tatiana Ivanova Román
