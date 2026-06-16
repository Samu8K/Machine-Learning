# Machine Learning - Análisis y Modelado Estadístico

## Descripción del proyecto

Este repositorio contiene un conjunto de análisis de Machine Learning orientados a la regresión y a la segmentación de datos. El trabajo está documentado en dos notebooks principales y cubre desde el preprocesamiento hasta la evaluación de modelos y la interpretación estadística.

## Contenido del repositorio

- `202502_Rosario_Regresion_Lasso_Rige_Updated (2).ipynb`
  - Análisis de regresión lineal
  - Evaluación de supuestos clásicos (normalidad, heterocedasticidad, autocorrelación)
  - Estandarización de variables
  - División de conjuntos de entrenamiento y prueba
  - Regresión Lasso, Ridge y Elastic Net
  - Diagnóstico de multicolinealidad con VIF
- `Actividad_2.ipynb`
  - Análisis descriptivo y exploratorio
  - Análisis de Componentes Principales (PCA)
  - Clustering: K-Means, K-Medoides y Clustering Jerárquico
  - Visualización y evaluación de agrupamientos

## Objetivo

El objetivo es demostrar un flujo completo de análisis de datos con técnicas de regresión y clustering en Python, apoyado en buenas prácticas de validación y análisis estadístico.

## Tecnologías y librerías utilizadas

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- statsmodels
- scipy
- mlxtend
- sklearn-extra

## Instrucciones de uso

1. Clonar el repositorio:
   ```bash
   git clone https://github.com/Samu8K/Machine-Learning.git
   cd Machine-Learning
   ```
2. Crear un entorno virtual e instalar dependencias:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install --upgrade pip
   pip install pandas numpy matplotlib seaborn scikit-learn statsmodels scipy mlxtend scikit-learn-extra
   ```
3. Abrir los notebooks en Jupyter o en VS Code:
   ```bash
   jupyter notebook
   ```
4. Ejecutar las celdas secuencialmente y explorar los resultados.

## Recomendaciones

- Revisar primero el notebook de regresión para entender la preparación de datos y los supuestos del modelo.
- Luego, analizar el notebook de clustering para explorar técnicas de segmentación y reducción de dimensionalidad.
- Adaptar rutas y nombres de archivos de datos según el origen de los conjuntos utilizados.

## Estructura del proyecto

- `202502_Rosario_Regresion_Lasso_Rige_Updated (2).ipynb` - Notebook de regresión y regularización
- `Actividad_2.ipynb` - Notebook de análisis descriptivo, PCA y clustering
- `README.md` - Documentación del proyecto

## Resultado esperado

- Modelos de regresión ajustados con interpretación de métricas de desempeño
- Evaluaciones de supuestos estadísticos
- Segmentaciones de datos con agrupamientos más representativos
- Visualizaciones que apoyan la toma de decisiones

## Contacto

Para más información o mejoras, puedes contactarme a través del repositorio de GitHub.
