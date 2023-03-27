# <h1 align=center> **PROYECTO ML ALQUILERES** </h1>

<p align="center">
<img src="https://www.elfinancierocr.com/resizer/A5KgZLcsRVT3f-WgEPquNkv0C-4=/1440x0/filters:format(jpg):quality(70)/cloudfront-us-east-1.images.arcpublishing.com/gruponacion/KPYSWMMBFFARXOIAJERIT7ZLVY.jpg"   
>
</p>


## Introducción:

¡Hola!  Mi nombre es Leonel Balleis, y este es un proyecto de machine Learnig Didactico.

## Objetivos: 

Aquí enumero los Pasos que voy a dar en este Proyecto:

1. Encuadrar el problema y observar el panorama general.

2. Obtener los datos.

3. Explorar y visualizar los datos.

4. Preparar los datos para los algoritmos.

5. Seleccionar el modelo y entrenarlo.

6. Ajustar el modelo.

7. Presentar Soluciones.

8. Lanzar el modelo.

## Contexto

Contexto: Nuestra tarea es utilizar los datos del censo de California de 1990 para crear un modelo para predecir los precios de las viviendas en el estado.
Estos datos incluyen métricas como población, ingreso promedio, precio promedio por manzana (una manzana es la medida geográfica mínima para censos con una población de entre 600 y 300 habitantes).
Los vamos a llamar distritos.
Usaremos el conjunto de datos de precios de viviendas de California del repositorio StatLib.

## Explicación del modelo:

Este problema es una tarea típica de aprendizaje supervisado, ya que el modelo se puede entrenar con ejemplos etiquetados. Más específicamente, un problema de REGRECIÓN MÚLTIPLE ya que el sistema utilizará múltiples características para hacer predicciones.
También es un problema de REGRECIÓN UNIVARIABLE, ya que solo estamos tratando de predecir un valor único para cada distrito.
No hay un flujo continuo de datos que ingresan al sistema, no hay necesidad de cambiar los datos rápidamente y los datos son pequeños, por lo que el APRENDIZAJE POR LOTES debería funcionar bien.

## Explicación de los contenidos del Repositorio:

+ En la carpeta `datasets` se encuentran el dataset analizado.

+ En el notebook `modelo.ipynb` se encuentra el código comentado paso por paso, explicando las decisiones tomadas a la hora de encarar este proyecto.

+ En el archivo `my_california_housing_model.pkl` se encuentra el modelo  creado, importado con la librería de Joblib.


## Herramientas/librerías utilizadas:

+ Python. 🐍

+ Pandas. 🐼

+ Numpy. 📟

+ Mathplotlib. 📊

+ ScikitLearn. 🤖

+ Joblib. 📁


