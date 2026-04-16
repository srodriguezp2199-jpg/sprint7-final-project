# sprint7-final-project
# 📊 Análisis de Segmentación de Clientes - ConnectaTel

🎯 Objetivo del Proyecto
Analizar el comportamiento de uso de servicios móviles (llamadas y mensajes) de los clientes de ConnectaTel para:

Identificar patrones de uso y comportamientos atípicos
Segmentar clientes según sus necesidades diferenciadas
Detectar outliers que puedan indicar fraude o errores de registro
Generar insights comerciales para optimizar la oferta y mejorar la experiencia del usuario
📁 Datasets Utilizados
El proyecto trabaja con tres fuentes principales de datos:

plans.csv: Catálogo de planes disponibles
Precio, minutos incluidos, GB incluidos, costo por extras
users.csv: Información demográfica de clientes
Edad, ciudad, fecha de registro, plan contratado, churn
usage.csv: Datos de uso real de servicios
Duración de llamadas, longitud de mensajes, actividad por usuario
🔄 Etapas del Análisis Realizadas
### 1. Exploración y Limpieza de Datos
- Carga e integración de las tres fuentes de datos
- Validación y estandarización de tipos de datos
- Detección y tratamiento de valores inconsistentes

### 2. Análisis Estadístico Descriptivo
- Perfil estadístico del uso por cliente
- Análisis por segmentos demográficos (edad, país, plan)

### 3. Detección de Outliers
- Identificación de comportamientos atípicos
- Métodos estadísticos y visuales para detección de anomalías

### 4. Segmentación de Clientes
- Creación de grupos basados en edad, país y comportamiento de uso
- Análisis de patrones diferenciados por segmento

### 5. Visualización e Insights
- Gráficos comparativos entre segmentos
- Extracción de insights comerciales accionables

🚀 Cómo Ejecutar el Notebook
### Opción 1: Google Colab (Recomendado)
1. Abre Google Colab
2. Sube el archivo analisis_connectatel.ipynb
3. Descarga los datasets desde los enlaces proporcionados en el notebook
4. Sube los archivos CSV a la sesión de Colab
5. Ejecuta las celdas secuencialmente

### Opción 2: Entorno Local
1. Clona este repositorio
2. Instala las dependencias: pip install pandas numpy matplotlib seaborn jupyter
3. Descarga los datasets en la carpeta del proyecto
4. Ejecuta: jupyter notebook analisis_connectatel.ipynb

###📋 Guía de Reproducción
### Requisitos Previos
- Python 3.7+
- Bibliotecas: pandas, numpy, matplotlib, seaborn

Pasos para Reproducir el Análisis
Preparación de datos
Descarga los tres archivos CSV
Colócalos en la misma carpeta que el notebook
Ejecución secuencial
Ejecuta las celdas en orden
Cada sección está claramente documentada
Los resultados se generan automáticamente
Interpretación de resultados
Revisa las visualizaciones generadas
