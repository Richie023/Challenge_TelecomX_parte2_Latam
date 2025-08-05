# 📊 Challenge Telecom X – Análisis de Evasión de Clientes (Churn)

Este proyecto forma parte del Challenge Telecom X – Parte 2, donde se desarrolla un pipeline de análisis predictivo para anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios (churn). El análisis se enfoca en entender los factores que motivan la evasión y ofrecer soluciones basadas en datos.

---

## 🎯 Misión

Desarrollar modelos de machine learning capaces de prever la cancelación de clientes, permitiendo a la empresa implementar estrategias de retención antes de que ocurra la pérdida del usuario.

---

## 🧠 Objetivos del Desafío

- Preparar y transformar los datos para modelado (tratamiento, codificación, normalización).
- Realizar análisis de correlación y exploración dirigida de variables.
- Entrenar al menos dos modelos de clasificación.
- Evaluar los modelos utilizando métricas clave.
- Interpretar los resultados y la importancia de las variables.
- Generar una conclusión estratégica basada en datos para reducir la tasa de churn.

---

## 📁 Contenido del Proyecto

| Archivo / Carpeta             | Descripción                                               |
|------------------------------|-----------------------------------------------------------|
| `TelecomX_Data.json`         | Archivo original con la información de clientes.          |
| `datos_tratados.csv`         | Datos limpios y transformados para el modelado.           |



## 📊 Actividades Realizadas (Challenge Parte 2)

1. **Extracción del archivo tratado**: Se cargaron datos previamente limpiados.
2. **Eliminación de columnas irrelevantes**: Se descartaron identificadores y datos no útiles para la predicción.
3. **Codificación de variables**: Se aplicó One-Hot Encoding a variables categóricas.
4. **Verificación de la proporción de cancelación (churn)**: Se revisó el balance de clases.
5. **Balanceo de clases**: Se aplicó SMOTE para mitigar desbalance en los datos.
6. **Normalización**: Se utilizó `StandardScaler` para modelos basados en distancia.
7. **Análisis de correlación**: Se visualizó la matriz de correlaciones.
8. **Análisis dirigido**: Se exploró la relación entre tiempo de contrato, cargos y churn.
9. **Separación de datos**: Se dividió el conjunto en entrenamiento y prueba (70/30).
10. **Creación de modelos**:
    - Modelo 1: Regresión Logística (requiere normalización).
    - Modelo 2: Random Forest (no requiere normalización).
11. **Evaluación de modelos**:
    - Accuracy
    - Precision
    - Recall
    - F1-Score
    - Matriz de confusión
12. **Importancia de variables**:
    - Se interpretaron los coeficientes (Regresión Logística).
    - Se usó `feature_importances_` en Random Forest.
13. **Conclusión estratégica**: Se documentaron hallazgos clave y recomendaciones.

---

## 📈 Resultados y Conclusiones

- Los clientes con **menos servicios contratados** tienen mayor probabilidad de cancelar.
- Los **contratos mensuales** y **cargos diarios elevados** están relacionados con más churn.
- Los **clientes nuevos** (con menos meses en la empresa) son más propensos a abandonar.
- La presencia de servicios como **soporte técnico**, **seguridad online** e **internet** se asocia a mayor retención.

---

## 🧭 Recomendaciones

- Promover **contratos de mayor duración** para reducir cancelaciones mensuales.
- Ofrecer **paquetes combinados de servicios** para incrementar el valor percibido.
- Identificar clientes con **alto riesgo de churn** y aplicar campañas de fidelización.
- Evaluar la estructura de **tarifas y cargos diarios**.
- Monitorear activamente a **clientes nuevos en sus primeros meses**.

---

## 🛠️ Tecnologías Usadas

- Python 3
- Pandas
- Seaborn
- Matplotlib
- Plotly
- Scikit-learn
- Imbalanced-learn (SMOTE)
- Google Colab

  📌 Cómo usar este repositorio
Clona este repositorio:
git clone https://github.com/Richie023/Challenge_TelecomX_parte2_Latam.git


👤 Autor [Ricardo Andres Ulloa Araya]




