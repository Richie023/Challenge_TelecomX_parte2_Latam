📊 Challenge Telecom X – Análisis de Evasión de Clientes (Churn)
🎯 Misión
Desarrollar modelos predictivos capaces de prever qué clientes tienen mayor probabilidad de cancelar sus servicios, con el fin de que la empresa pueda anticiparse y tomar acciones de retención.

🧠 Objetivos del Desafío
Preparar los datos para el modelado (tratamiento, codificación, normalización).

Realizar análisis de correlación y selección de variables.

Entrenar dos o más modelos de clasificación.

Evaluar el rendimiento de los modelos usando métricas estándar.

Interpretar los resultados, incluyendo la importancia de las variables.

Elaborar una conclusión estratégica destacando los principales factores de cancelación.

📁 Contenido del Proyecto
TelecomX_Data.json: Datos originales de clientes.

datos_tratados.csv: Datos preprocesados (ya con columnas relevantes y variables limpias).

churn_analysis.ipynb: Notebook de análisis con todo el pipeline.

Visualizaciones: Gráficos generados con matplotlib, seaborn y plotly.

Informe final: Resumen y recomendaciones de negocio.

🧹 Limpieza y Tratamiento de Datos
Pasos realizados:

Importación del dataset.

Limpieza de valores nulos o inconsistentes.

Estandarización de variables categóricas.

Ingeniería de características:

cuentas_diarias: Costo diario promedio.

cantidad_servicios: Total de servicios activos contratados.

Codificación binaria (0 y 1) y one-hot encoding para variables categóricas.

📊 Análisis Exploratorio de Datos (EDA)
Se exploraron las siguientes relaciones:

Distribución global de clientes que cancelan (churn).

Comparación por género, tipo de contrato y forma de pago.

Relación entre cantidad_servicios y churn.

Distribución de cuentas_diarias por clase.

Matriz de correlación entre variables numéricas.

📈 Visualizaciones utilizadas
Gráficos de barras y torta (pie).

Violin plots y boxplots (Plotly).

Heatmap de correlación.

💡 Conclusiones del Análisis
Los clientes con menos servicios contratados tienen mayor propensión a abandonar.

Los contratos mensuales y cargos diarios altos están asociados con más churn.

Clientes nuevos (pocos meses de contrato) tienden a cancelar más.

Los clientes con internet, soporte técnico y seguridad tienden a permanecer más tiempo.

🧭 Recomendaciones Estratégicas
Promover contratos anuales o de mayor duración.

Crear paquetes combinados de servicios para aumentar el valor percibido.

Identificar y monitorear a clientes en riesgo de churn.

Evaluar y optimizar la estructura de precios y cargos diarios.

Aplicar campañas de fidelización especialmente en los primeros meses del contrato.

🛠️ Tecnologías Usadas
Python 3

Pandas

Seaborn

Matplotlib

Plotly

Scikit-learn

Imbalanced-learn (SMOTE)

Google Colab 

📌 Cómo usar el proyecto

git clone https://github.com/Richie023/TelecomX_LATAM_challenge.git
👤 Autor: Ricardo Andrés Ulloa Araya

