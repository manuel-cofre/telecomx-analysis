# Telecom X - Análisis de Evasión de Clientes

Este proyecto aborda el análisis de la evasión de clientes (churn) en la empresa ficticia Telecom X. El objetivo es identificar patrones y factores asociados a la deserción de clientes para diseñar estrategias de retención más efectivas.

## Contenido del proyecto

1. **Extracción de datos**  
   - Lectura del archivo JSON proporcionado.  
   - Conversión a DataFrame de Pandas para facilitar el análisis.  

2. **Transformación de datos**  
   - Normalización de nombres de columnas.  
   - Conversión de tipos de datos numéricos.  
   - Limpieza de valores nulos y categorías inconsistentes.  

3. **Exploración del dataset**  
   - Revisión de tipos de datos y estadísticas descriptivas.  
   - Distribución de variables categóricas y numéricas.  
   - Identificación de variables más relevantes para el churn.  

4. **Validación de calidad de datos**  
   - Detección de valores faltantes y duplicados.  
   - Revisión de coherencia en variables numéricas.  
   - Corrección de inconsistencias detectadas.  

5. **Análisis Exploratorio (EDA)**  
   - Visualización de la relación entre churn y variables como contrato, método de pago, antigüedad y cargos.  
   - Análisis de correlación entre variables numéricas.  

6. **Informe final**  
   - Principales hallazgos sobre factores de churn.  
   - Recomendaciones estratégicas para la empresa.  

## Tecnologías utilizadas

- Python 3  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

## Hallazgos principales

- Los clientes con contratos mensuales presentan mayor tasa de churn que aquellos con contratos de uno o dos años.  
- El método de pago con Electronic check está asociado a mayor deserción.  
- Los clientes con menor antigüedad (tenure) tienen mayor probabilidad de abandonar.  
- Los cargos mensuales elevados, especialmente en servicios de fibra óptica, están correlacionados con mayor churn.  

## Recomendaciones

- Incentivar contratos de largo plazo mediante descuentos o beneficios.  
- Implementar planes de fidelización dirigidos a clientes nuevos en sus primeros meses.  
- Evaluar políticas de precios, especialmente en planes de fibra óptica.  
- Mejorar la experiencia del cliente en el uso de pagos electrónicos.  

