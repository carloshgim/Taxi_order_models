# Análisis del riesgo de incumplimiento de los prestatarios por *Carlos Horta* (carlosgim@gmail.com)

## Descripción del proyecto

La compañía Sweet Lift Taxi ha recopilado datos históricos sobre pedidos de taxis en los aeropuertos. Para atraer a más conductores durante las horas pico, se necesita predecir la cantidad de pedidos de taxis para la próxima hora. El objetivo de este proyecto es construir un modelo de predicción para cumplir con esta tarea.

La métrica utilizada para evaluar el rendimiento del modelo será el Root Mean Squared Error (RMSE) en el conjunto de prueba, y se establece un umbral máximo de 48 para dicha métrica.

## Instrucciones del proyecto

El proyecto se divide en las siguientes etapas:

1. Descarga de datos: Se debe descargar el archivo `taxi.csv` que contiene los datos históricos de los pedidos de taxis.
2. Remuestreo por hora: Los datos se encuentran en intervalos de tiempo más pequeños, por lo que es necesario realizar un remuestreo para tener la cantidad de pedidos de taxis por hora.
3. Análisis de datos: Se debe realizar un análisis exploratorio de los datos para comprender su distribución, identificar patrones y visualizar tendencias.
4. Entrenamiento de modelos: Se deben entrenar diferentes modelos utilizando diferentes conjuntos de hiperparámetros. Se recomienda utilizar una muestra de prueba que represente el 10% del conjunto de datos inicial.
5. Evaluación del modelo: Se debe evaluar el rendimiento de los modelos utilizando la muestra de prueba y la métrica de RMSE. Se debe comparar el RMSE obtenido con el umbral máximo establecido (48) para determinar si el modelo cumple con los requisitos del proyecto.
6. Conclusiones: Se deben proporcionar conclusiones sobre el rendimiento de los modelos y su capacidad para predecir la cantidad de pedidos de taxis para la próxima hora.

## Descripción de los datos

Los datos están almacenados en el archivo `taxi.csv`. La columna relevante para este proyecto es `num_orders`, que representa la cantidad de pedidos de taxis para cada intervalo de tiempo.

-----

# Default Risk Analysis of Borrowers by Carlos Horta (carlosgim@gmail.com)

## Project Description

Sweet Lift Taxi has collected historical data on taxi orders at airports. To attract more drivers during peak hours, it is necessary to predict the number of taxi orders for the next hour. The objective of this project is to build a prediction model to fulfill this task.

The evaluation metric used to assess the model's performance will be Root Mean Squared Error (RMSE) on the test set, with a maximum threshold of 48 for this metric.

## Project Instructions

The project is divided into the following stages:

1. Data Download: Download the `taxi.csv` file containing the historical data of taxi orders.
2. Hourly Resampling: The data is in smaller time intervals, so resampling is needed to have the number of taxi orders per hour.
3. Data Analysis: Perform exploratory data analysis to understand its distribution, identify patterns, and visualize trends.
4. Model Training: Train different models using different sets of hyperparameters. It is recommended to use a test sample representing 10% of the initial dataset.
5. Model Evaluation: Evaluate the performance of the models using the test sample and the RMSE metric. Compare the obtained RMSE with the established maximum threshold (48) to determine if the model meets the project requirements.
6. Conclusions: Provide conclusions on the performance of the models and their ability to predict the number of taxi orders for the next hour.

## Data Description

The data is stored in the `taxi.csv` file. The relevant column for this project is `num_orders`, which represents the number of taxi orders for each time interval.

-----
