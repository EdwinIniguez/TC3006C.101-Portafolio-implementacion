# Portafolio de Implementación

Este repositorio integra las evidencias de los proyectos desarrollados en los diferentes módulos de la asignatura. Cada sección contiene enlaces específicos a las carpetas del workspace que contienen las evidencias requeridas, con descripciones claras de lo que se encuentra en cada ubicación para facilitar la evaluación de los profesores.

---

## Evidencias por Subcompetencia

### 1. Aprendizaje e IA (SMA0401A)

#### **Indicador 1:** Implementa una técnica o algoritmo de aprendizaje máquina **sin uso de framework**
- **Ubicación:** `Aprendizaje/codes/models/`
- **Archivos específicos:**
  - `elasticNet_manual.py` - Implementación manual de ElasticNet desde cero
  - `elasticNet_manual_upgrade.py` - Versión mejorada con validación cruzada
  - `knn_manual.py` - Implementación manual de K-Nearest Neighbors
- **Descripción:** Implementaciones completamente manuales de algoritmos de regresión sin utilizar frameworks externos, solo bibliotecas básicas como `math` y `csv`.

#### **Indicador 2:** Implementa una técnica o algoritmo de aprendizaje máquina **usando un framework**
- **Ubicación:** `Aprendizaje/codes/models/`
- **Archivos específicos:**
  - `decisionTree_Regressor_framework.py` - Árbol de decisión con scikit-learn
  - `decisionTree_Regressor_framework_adjusted.py` - Árbol con hiperparámetros ajustados
  - `elasticNet_framework.py` - ElasticNet usando scikit-learn
  - `randomForestRegressor_framework.py` - Random Forest con framework
  - `knnRegressor_framework.py` - KNN usando scikit-learn
- **Análisis comparativo:** `Aprendizaje/codes/performanceAnalysis.py` - Script que compara el rendimiento entre implementaciones manuales y con framework
- **Descripción:** Implementaciones usando scikit-learn con análisis completo de métricas, curvas de aprendizaje, y comparación de desempeño.

---

### 2. Construcción de Modelos (SMA0101A)

#### **Indicador 1:** Construye un modelo manualmente a partir de un set de datos, seleccionando las variables a utilizar
- **Ubicación:** `MODELADO/1/`
- **Archivos específicos:**
  - `Exploracion_Datos.ipynb` - Análisis exploratorio y selección de variables
  - `UniendoDatos.ipynb` - Proceso de integración de fuentes de datos
  - `Modelo_Binario.ipynb` - Construcción manual del modelo de clasificación
- **Dataset:** `MODELADO/2/data_clean.csv` - Datos procesados y variables seleccionadas
- **Descripción:** Proceso completo de construcción manual de modelos con selección justificada de variables basada en análisis exploratorio.

#### **Indicador 2:** Explica correctamente cada una de las variables seleccionadas en el modelo y su utilidad
- **Ubicación:** `MODELADO/1/`
- **Archivos específicos:**
  - `Diccionario_Simple_VisualizacionAonline.xlsx` - Diccionario de variables con explicaciones
  - `Exploracion_Datos.ipynb` - Análisis detallado de cada variable y su utilidad
- **Descripción:** Documentación completa de cada variable utilizada, incluyendo su importancia, distribución y contribución al modelo.

#### **Indicador 3:** Explica cómo funciona el modelo que utiliza y valida los supuestos del modelo
- **Ubicación:** `MODELADO/3/`
- **Archivos específicos:**
  - `actividad_curvas_aprendizaje_validacion.ipynb` - Validación de modelos y curvas de aprendizaje
  - `ejemplos_tema2_regresion_lineal.ipynb` - Explicación de funcionamiento de regresión lineal
- **Ubicación adicional:** `MODELADO/Problema de regresion/`
- **Archivos específicos:**
  - `problema_de_regresion.ipynb` - Validación de supuestos en problema de regresión
- **Descripción:** Explicación teórica y práctica del funcionamiento de los modelos, con validación estadística de supuestos y diagnóstico de desempeño.

---

### 3. Análisis Estadístico Complementario (Data Science)

#### **Evidencias adicionales de soporte:**
- **Ubicación:** `Data Science/notebooks/`
- **Archivos específicos:**
  - `8_Minimos_cuadrados_(Lin_reg).ipynb` - Fundamentos teóricos de regresión
  - `11_PCA.ipynb` - Análisis de componentes principales
  - `6_Prueba_de_hipotesis_[Public].ipynb` - Validación estadística
- **Proyecto final:** `Data Science/proyecto/`
  - `Proyecto__Minimos_cuadrados.ipynb` - Aplicación de mínimos cuadrados
  - `Proyecto__Regresion_logistica.ipynb` - Implementación de regresión logística

