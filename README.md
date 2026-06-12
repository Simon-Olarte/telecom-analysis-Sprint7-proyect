# Proyecto 6 - Análisis de Uso de Servicios de Telecomunicaciones en ConnectaTel

## Descripción del Proyecto

Este proyecto tiene como objetivo analizar el comportamiento de los clientes de **ConnectaTel**, una empresa de telecomunicaciones con operaciones en México y Colombia.

A partir de información sobre usuarios, planes contratados y uso real de servicios móviles, se busca identificar patrones de consumo, detectar comportamientos atípicos y comprender cómo varían las necesidades de los distintos segmentos de clientes.

Los hallazgos obtenidos permiten generar recomendaciones orientadas a la optimización de la oferta comercial, la mejora de la experiencia del usuario y la identificación de oportunidades de negocio.

---

## Objetivos

* Analizar el uso de llamadas y mensajes por parte de los clientes.
* Identificar segmentos de usuarios con patrones de consumo diferenciados.
* Detectar valores atípicos que puedan representar errores, fraude o comportamientos inusuales.
* Evaluar la relación entre edad, plan contratado y nivel de consumo.
* Generar insights accionables para la toma de decisiones comerciales.

---

## Datasets Utilizados

### 1. `plans.csv`

Contiene información sobre los planes disponibles:

* Nombre del plan
* Precio mensual
* Minutos incluidos
* Datos móviles incluidos (GB)
* Costos por excedentes

### 2. `users_latam.csv`

Información de los clientes:

* ID de usuario
* Edad
* Ciudad y país
* Fecha de registro
* Plan contratado
* Estado de churn (cancelación)

### 3. `usage.csv`

Registro de actividad de los usuarios:

* ID de usuario
* Duración de llamadas
* Cantidad de mensajes
* Longitud de mensajes
* Fecha de actividad

---

## Preguntas de Negocio

El análisis busca responder las siguientes preguntas:

* ¿Qué segmentos de clientes muestran mayor o menor uso de llamadas y mensajes?
* ¿Qué usuarios presentan comportamientos atípicos?
* ¿Cómo varía el consumo según la edad y el plan contratado?
* ¿Qué patrones pueden utilizarse para mejorar los planes y aumentar la satisfacción del cliente?

---

## 🛠 Herramientas Utilizadas

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Etapas del Análisis

### 1. Carga y Exploración de Datos

* Importación de los datasets.
* Revisión de estructura, dimensiones y tipos de datos.
* Identificación inicial de posibles problemas de calidad.

### 2. Limpieza y Preparación

* Detección y tratamiento de valores nulos.
* Conversión de formatos de fecha.
* Corrección de tipos de datos inconsistentes.
* Identificación de valores centinela y registros anómalos.

### 3. Análisis Estadístico Descriptivo

* Cálculo de medidas de tendencia central.
* Análisis de dispersión y percentiles.
* Comparación entre variables numéricas y categóricas.

### 4. Visualización de Datos

* Histogramas para analizar distribuciones.
* Boxplots para detectar valores atípicos.
* Gráficos comparativos entre segmentos de usuarios.

### 5. Detección de Outliers

* Identificación de consumos extremos.
* Evaluación de posibles errores de registro o comportamientos inusuales.

### 6. Segmentación de Clientes

* Segmentación por edad.
* Segmentación por nivel de consumo.
* Comparación entre planes contratados.

### 7. Generación de Insights

* Interpretación de patrones observados.
* Respuesta a las preguntas de negocio.
* Recomendaciones comerciales basadas en evidencia.

---

## Cómo Ejecutar el Proyecto

## Google Colab

1. Descargar el notebook (`.ipynb`) y los archivos CSV.
2. Abrir Google Colab.
3. Seleccionar **Archivo → Subir Notebook**.
4. Cargar el notebook del proyecto.
5. Subir los datasets al entorno de trabajo de Colab.
6. Ejecutar las celdas en orden.

## Guía de Reproducción

Para reproducir completamente el análisis:

1. Descargar o clonar este repositorio.

2. Verificar que los archivos:

   * `plans.csv`
   * `users_latam.csv`
   * `usage.csv`

   se encuentren en la carpeta de trabajo.

3. Instalar las librerías requeridas.

4. Ejecutar el notebook de principio a fin.

5. Revisar las visualizaciones, estadísticas y conclusiones generadas.

---

## Resultados Esperados

Al finalizar la ejecución del notebook se obtiene:

* Un perfil detallado del comportamiento de los clientes.
* Identificación de segmentos de alto, medio y bajo consumo.
* Detección de usuarios con patrones atípicos.
* Insights para optimizar planes y estrategias comerciales.
* Recomendaciones orientadas a mejorar la experiencia del cliente y la rentabilidad del negocio.

---

## Autor

Proyecto desarrollado por Simón Olarte como parte de un ejercicio de análisis de datos enfocado en exploración, limpieza, segmentación y generación de insights para una empresa de telecomunicaciones como parte de mi bootcamp de Tripleten
