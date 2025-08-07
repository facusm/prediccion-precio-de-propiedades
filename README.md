# 🏠 Predicción del precio de propieades en CABA (Buenos Aires, Argentina)

## 🎯 Objetivo

Este proyecto tiene como objetivo desarrollar un modelo de aprendizaje automático para predecir los precios de propiedades en la Ciudad Autónoma de Buenos Aires (CABA), utilizando datos estructurados provenientes de publicaciones inmobiliarias. Para ello, se construyó un pipeline de modelado que permite extraer, procesar y analizar características relevantes de las propiedades.

Se diseñaron y entrenaron modelos específicos para cada tipo de propiedad (casas, departamentos y cocheras), dado que no todos los atributos están presentes o son relevantes en todos los casos. Esta diferenciación permite mejorar la precisión de las estimaciones y adaptarse mejor a las particularidades de cada segmento del mercado inmobiliario.

📄 [Jupyter Notebook para el análisis](https://github.com/login)

---

## 📊 Resultados

### 📈 Evaluación del Modelo y Resultados

- Se entrenaron múltiples modelos para predecir el precio de propiedades residenciales en CABA. Entre ellos, el **Random Forest Regressor** mostró el mejor desempeño.
- Este modelo fue capaz de capturar relaciones complejas y no lineales entre las características de las propiedades y sus precios.
- En la competencia de Kaggle, el modelo obtuvo un **RMSE (Root Mean Squared Error)** de aproximadamente **29.419**, lo que representa una buena capacidad predictiva considerando la alta variabilidad del mercado inmobiliario.
- Los mayores errores de predicción se observaron en propiedades con características **atípicas o poco frecuentes**.

### 🧹 Importancia del Preprocesamiento

- El proceso de **limpieza**, **transformación** e **imputación** de datos fue crucial para alcanzar un rendimiento satisfactorio.
- Mejoras en la **homogeneidad del dataset** —como una codificación más adecuada de variables categóricas o el tratamiento de valores extremos (outliers)— demostraron tener un impacto directo sobre el desempeño del modelo.

### 🏘️ Aplicación del Aprendizaje Automático al Mercado Inmobiliario

- El modelo desarrollado demuestra el potencial del aprendizaje automático para **respaldar decisiones basadas en datos** en el ámbito inmobiliario.
- Las predicciones generadas pueden aportar valor tanto a **compradores**, **vendedores** como a **agentes inmobiliarios**, ofreciendo estimaciones objetivas y reproducibles del valor de una propiedad.
- Esta herramienta puede ser utilizada para **identificar propiedades sobrevaloradas o subvaloradas**, contribuyendo a una mayor **transparencia y eficiencia del mercado**.

--- 

## 🗂️ Estructura del proyecto

<pre>
prediccion-precio-de-propiedades/
├── README.md                               # Documentación principal
├── Prediccion_Precio_de_Propiedades.ipynb  # Notebook principal
├── data/                                   # Carpeta con datos
│   ├── a_predecir.csv                      # Datos para predecir
│   └── entrenamiento.csv                   # Datos de entrenamiento
</pre>

---
## 🎓 Contexto académico
Este proyecto fue realizado en el marco de la materia Data Mining, perteneciente a la [Maestría en Explotación de Datos y Descubrimiento del Conocimiento](https://datamining.dc.uba.ar/datamining/) de la Universidad de Buenos Aires. 

La actividad consistió en una [competencia interna organizada mediante la plataforma kaggle](https://www.kaggle.com/competitions/fcen-dm-2025-prediccion-precio-de-propiedades/leaderboard), en la cual se aplicaron técnicas de aprendizaje supervisado sobre un conjunto de datos reales. El proceso abarcó desde el preprocesamiento y selección de modelos, hasta la optimización de hiperparámetros y evaluación de resultados.


## ✍️ Autor

Facundo San Martino

[LinkedIn](https://www.linkedin.com/in/facundo-san-martino/) | [Github](https://github.com/facusm)