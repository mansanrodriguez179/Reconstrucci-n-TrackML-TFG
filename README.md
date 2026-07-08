# Reconstrucción de Trayectorias con Aprendizaje Automático en el Experimento CMS del LHC
Este repositorio contiene la muestra de datos y los códigos en formato Notebook de Python utilizados para la elaboración del Trabajo de Fin de Grado (TFG). 

## Descripción del Proyecto
El proyecto se centra en una etapa determinada del proceso de reconstrucción de trayectorias: la **clasificación de dobletes**. Se considerará que un doblete está formado por dos *hits* (impactos) en distintos puntos del detector de píxeles de silicio, 
que podrían haber sido producidos por una misma partícula cargada en su trayectoria. 
Para ello, se propone la implementación de técnicas de aprendizaje automático supervisado y no supervisado usando una muestra de datos simulada ofrecida por el concurso *TrackML Particle Tracking Challenge*.

## Contenido del Repositorio
* **Notebooks de Python** (Ejecutados en la plataforma en línea Kaggle):
  * `Trabajo de Fin de Grado con DNN y DBSCAN.ipynb`: Dedicado a la reconstrucción e identificación de los dobletes.
  * `Representaciones.ipynb`: Dedicado a representar las gráficas empleadas en los análisis.
## Recomendaciones
Ejecutarlo en el entrono de Kaggle para que sea mucho más simple de implementar, tanto el conjunto de los datos como la función `score_event`
