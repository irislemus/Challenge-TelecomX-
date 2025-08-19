# Proyecto: Predicción de Evasión (Churn)

Este proyecto tiene como objetivo desarrollar un modelo de Machine Learning para predecir la evasión de clientes en una empresa de telecomunicaciones. El modelo final identifica a los clientes con mayor riesgo de cancelar sus servicios, permitiendo al equipo de negocio implementar estrategias de retención proactivas y dirigidas.

Estructura del Proyecto
El proyecto se desarrolla en un flujo de trabajo típico de ciencia de datos, con las siguientes etapas clave:

1. Análisis Exploratorio de Datos (EDA): Exploración y comprensión del conjunto de datos, identificación de patrones iniciales y visualización de la relación entre las variables y la evasión.

2. Preprocesamiento de Datos: Limpieza, manejo de datos nulos y categóricos, y escalado de variables.

3. Selección de Variables: Uso de métodos como SelectKBest y RFE para identificar las características más relevantes y reducir la dimensionalidad.

4. Modelado y Evaluación: Entrenamiento y comparación de varios modelos de clasificación (Regresión Logística, Random Forest, XGBoost) en escenarios balanceados y desbalanceados.

5. Optimización de Hiperparámetros: Ajuste fino del mejor modelo (XGBoost) para maximizar su rendimiento.

6. Interpretabilidad del Modelo: Análisis de la importancia de las características y el impacto de las variables en las predicciones usando SHAP.

Tecnologías y Librerías Utilizadas

Lenguaje: Python 3.x

Análisis de Datos: pandas, numpy

Visualización: matplotlib, seaborn

Machine Learning: scikit-learn, xgboost, shap

Resultados Clave

Se obtuvo un modelo robusto y confiable, con un rendimiento superior a los modelos de referencia.

<img width="619" height="141" alt="image" src="https://github.com/user-attachments/assets/489ac199-3521-4191-ab3f-9316a791981f" />

Conclusiones y Recomendaciones

El XGBoost Balanceado es el modelo recomendado para su implementación, ya que ofrece el mejor equilibrio entre recall y precisión, con una superior capacidad discriminativa (AUC).

Los principales factores de riesgo identificados son los contratos mensuales, el método de pago de cheque electrónico y el servicio de fibra óptica. Por el contrario, la antigüedad del cliente y los contratos a largo plazo son los mayores factores protectores.

Se sugiere activar campañas de retención dirigidas a los clientes con mayor riesgo, con ofertas personalizadas que aborden los factores de riesgo identificados, como descuentos en facturas o cambios a planes con contratos más largos.

El modelo debe ser monitoreado continuamente y reentrenado periódicamente para garantizar su relevancia con el tiempo.
