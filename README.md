#  Telecom X – Análisis de Cancelación de Clientes (Churn)

##  Descripción del Proyecto

Este proyecto tiene como objetivo analizar y predecir la cancelación de clientes (Churn) en una empresa ficticia de telecomunicaciones llamada **Telecom X**.

La empresa enfrenta una alta tasa de cancelaciones y necesita comprender **qué factores influyen en la pérdida de clientes** para poder implementar estrategias de retención más efectivas.

A través de técnicas de **análisis exploratorio de datos y modelos de Machine Learning**, se busca identificar patrones en el comportamiento de los clientes y construir modelos predictivos capaces de estimar la probabilidad de cancelación.

---

#  Objetivos

* Analizar el comportamiento de los clientes y detectar patrones asociados al abandono.
* Identificar las variables que más influyen en la cancelación de clientes.
* Construir modelos predictivos para anticipar el churn.
* Proponer estrategias de retención basadas en los resultados obtenidos.

---

#  Dataset

El dataset contiene información sobre clientes de la empresa Telecom X, incluyendo variables relacionadas con:

* Información demográfica del cliente
* Servicios contratados
* Tipo de contrato
* Método de pago
* Facturación mensual y total
* Tiempo de permanencia en la empresa
* Estado de cancelación del cliente

Variable objetivo:

**`abandono`**

* 0 = Cliente activo
* 1 = Cliente canceló el servicio

---

#  Tecnologías Utilizadas

Este proyecto fue desarrollado utilizando Python y las siguientes librerías:

* **Pandas** → Manipulación de datos
* **NumPy** → Operaciones numéricas
* **Matplotlib / Seaborn** → Visualización de datos
* **Scikit-learn** → Modelos de Machine Learning
* **Jupyter Notebook** → Desarrollo del análisis

---

#  Proceso de Análisis

El proyecto se desarrolló siguiendo las etapas principales de un flujo de trabajo de Ciencia de Datos:

### 1. Limpieza y preparación de datos

* Tratamiento de valores faltantes
* Conversión de variables categóricas
* Estandarización de variables numéricas

### 2. Análisis exploratorio de datos (EDA)

Se analizaron relaciones entre variables clave y la cancelación de clientes mediante:

* Boxplots
* Histogramas
* Análisis de distribución
* Comparaciones entre grupos

Ejemplo de análisis realizado:

* Tiempo como cliente vs Cancelación
* Gasto total vs Cancelación
* Cargo mensual vs Cancelación

---

### 3. Construcción de modelos predictivos

Se implementaron dos modelos de Machine Learning:

**Regresión Logística**

Modelo interpretable que permite analizar el impacto de cada variable sobre la probabilidad de cancelación.

**Random Forest**

Modelo basado en árboles de decisión que permite capturar relaciones complejas entre variables y calcular la importancia de cada una.

---

#  Evaluación de Modelos

Para evaluar el desempeño de los modelos se utilizaron las siguientes métricas:

* Accuracy
* Precision
* Recall
* F1-score
* ROC-AUC

Estas métricas permiten analizar tanto la precisión general del modelo como su capacidad para identificar clientes con alto riesgo de cancelación.

---

#  Principales Resultados

El análisis de importancia de variables mostró que los factores más influyentes en la cancelación de clientes son:

* **Cargo mensual**
* **Cargo total**
* **Tiempo como cliente**
* **Tipo de contrato**
* **Método de pago**

Los clientes con **menor antigüedad, mayor costo mensual y contratos más flexibles** presentan mayor probabilidad de abandonar el servicio.

---

#  Estrategias de Retención Propuestas

Basándose en los resultados del análisis, se sugieren las siguientes estrategias:

* Implementar **programas de fidelización para clientes nuevos**
* Incentivar **contratos de mayor duración**
* Revisar **planes con cargos mensuales elevados**
* Promover **métodos de pago automáticos más estables**

Estas acciones podrían ayudar a reducir la tasa de cancelación y mejorar la retención de clientes.

---

#  Posibles Mejoras Futuras

* Implementar modelos adicionales como:

  * Gradient Boosting
  * XGBoost
* Realizar optimización de hiperparámetros
* Aplicar técnicas para tratar el desbalance de clases (SMOTE)
* Implementar un dashboard interactivo con **Power BI o Tableau**

---

#  Autor

**Javiera Torres**

Estudiante de **Data Science**, interesada en análisis de datos, machine learning y visualización de datos.

---

 Si te interesa este proyecto o quieres colaborar, ¡no dudes en contactarme!
