# Técnicas-de-Aprendizaje-Automáico-MIA---PER-11399

# Laboratorio: Regresión Lineal y Árboles de Decisión para Tareas de Regresión

## Autor
**Axel Rodriguez**

## Descripción
Este notebook forma parte del laboratorio del Máster Universitario en Inteligencia Artificial. La actividad está centrada en aplicar técnicas de aprendizaje automático supervisado, específicamente regresión lineal múltiple y árboles de decisión, para resolver un problema de predicción utilizando un conjunto de datos reales relacionados con la calidad del aire.

## Objetivos

- Realizar un análisis exploratorio de datos (EDA) aplicado a un problema de Machine Learning.
- Aplicar técnicas de regresión lineal múltiple.
- Aplicar árboles de decisión en un contexto de regresión.
- Comparar el rendimiento de ambos modelos.
- Evaluar los modelos mediante métricas de desempeño.
- Investigar aplicaciones reales de la regresión en publicaciones científicas recientes.

## Dataset

- **Nombre:** Air Quality Dataset
- **Fuente:** UCI Machine Learning Repository  
  [https://archive.ics.uci.edu/dataset/360/air+quality](https://archive.ics.uci.edu/dataset/360/air+quality)
- **Descripción:** Datos horarios de sensores de calidad del aire ubicados en una ciudad italiana, recogidos durante un año (marzo 2004 - febrero 2005).
- **Instancias:** 9357 (tras limpieza)
- **Variables:** Concentraciones de gases contaminantes, temperatura, humedad, entre otras.

## Estructura del Notebook

1. **Carga y limpieza del conjunto de datos**
   - Eliminación de columnas y filas nulas.
   - Conversión de tipos de datos.

2. **Análisis Exploratorio de Datos**
   - Descripción estadística de los atributos.
   - Visualizaciones de correlación.

3. **Aplicación de Modelos**
   - Regresión lineal múltiple.
   - Árboles de decisión para regresión.

4. **Evaluación de Modelos**
   - Métricas utilizadas: MSE, RMSE, R².
   - Comparación de resultados.

5. **Investigación**
   - Revisión de un artículo científico reciente (post 2015) que emplee regresión lineal o árboles de decisión sin usar deep learning.
   - Análisis del objetivo, metodología y resultados del estudio.

## Requisitos

Este notebook requiere los siguientes paquetes de Python:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

Puedes instalar los paquetes necesarios con:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

