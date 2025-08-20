# Análisis de Churn - Telecom X

## Descripción del Proyecto
Este proyecto analiza los datos de clientes de Telecom X para identificar patrones de cancelación de servicios (churn). Se aplicaron técnicas de limpieza, transformación y análisis exploratorio de datos, así como modelos de machine learning, para obtener insights clave sobre la retención de clientes.

## Estructura del Proyecto
- **Extracción:** Obtención de datos desde un archivo JSON.  
- **Transformación:** Limpieza y preprocesamiento de datos, incluyendo manejo de valores nulos y codificación de variables categóricas.  
- **Análisis Exploratorio:** Visualización de patrones de cancelación según características de los clientes.  
- **Modelos:** Árbol de Decisión y Random Forest optimizados con GridSearchCV.  
- **Resultados:** Evaluación de métricas, matriz de confusión e importancia de variables.

## Requisitos
- Python 3
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

Instalación de dependencias:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn


## Uso

1. Clonar el repositorio:
2. Abrir el notebook en Google Colab o Jupyter Notebook.  
3. Ejecutar todas las celdas para obtener los análisis y visualizaciones.

## Datos

Los datos provienen del archivo `TelecomX_Data.json`, que contiene información sobre clientes, contratos, servicios y métodos de pago.

## Resultados

- Los clientes con contratos mes a mes presentan mayor riesgo de cancelación.  
- El método de pago y el tipo de servicio impactan directamente en la retención.  
- Random Forest mostró mejor precisión global y estabilidad que un Árbol de Decisión individual.  

Este proyecto proporciona insights para implementar estrategias de retención más efectivas y dirigidas a segmentos específicos de clientes.
