# 🚗 Análisis de Autos Usados - Predicción de Precios con Machine Learning

## 📊 Descripción del Proyecto

Este proyecto implementa un **análisis completo de machine learning** para la predicción de precios de autos usados utilizando el dataset de Craigslist Cars & Trucks. El análisis incluye exploración de datos, limpieza inteligente, modelado predictivo y optimización de hiperparámetros.

### 🎯 Objetivo Principal
Desarrollar un modelo predictivo robusto capaz de estimar precios de vehículos usados con alta precisión, implementando mejores prácticas de ciencia de datos y machine learning.

## 🏆 Resultados Destacados

| Métrica | Linear Regression | Random Forest | Random Forest Optimizado |
|---------|-------------------|---------------|---------------------------|
| **R² Score** | 0.678 | 0.908 | **0.909** |
| **RMSE** | $7,511 | $4,016 | **$3,994** |
| **MAE** | $5,536 | $2,062 | **$2,045** |

### 🎉 **Modelo Final: Random Forest Optimizado**
- **Precisión:** 90.9% de varianza explicada
- **Error promedio:** $2,045
- **Datos procesados:** 363,223 registros (85.1% retención)

## 🛠️ Tecnologías y Librerías Utilizadas

### **Core Technologies**
- **Python 3.8+** - Lenguaje principal
- **Jupyter Notebook** - Entorno de desarrollo interactivo

### **Data Science Stack**
- **Pandas** - Manipulación y análisis de datos
- **NumPy** - Computación numérica
- **Scikit-learn** - Machine learning y modelado
- **Matplotlib & Seaborn** - Visualización de datos

### **Técnicas Implementadas**
- **Imputación inteligente** por grupos
- **RobustScaler** (resistente a outliers)
- **OneHotEncoder** para variables categóricas
- **GridSearchCV** para optimización
- **Pipeline completo** de preprocesamiento

## 📁 Estructura del Proyecto

