✈️ Análisis de Fidelización y Comportamiento de Clientes: Aerolínea. Como ejercicio de aprendizaje para el 3 módulo de Adalab.
📝 Descripción del Proyecto
Este proyecto consiste en un análisis exploratorio de datos (EDA) y estadístico de una base de datos de una aerolínea. El objetivo principal es identificar los factores que influyen en el valor del cliente (CLV) y su frecuencia de vuelo, analizando variables demográficas, económicas y de fidelidad.

📊 Principales Hallazgos (Insights)
Desconexión Salarial: Se demostró mediante matrices de correlación que el salario no es un predictor del número de vuelos. Clientes con diversos niveles de ingresos muestran comportamientos de viaje similares.

Poder de la Fidelización: Existe una relación directa y positiva entre el tipo de tarjeta de lealtad (Loyalty Card) y la actividad del cliente. Los miembros Aurora son los más activos.

Geografía del Vuelo: Provincias como New Brunswick y British Columbia presentan los promedios de vuelo más altos, independientemente del nivel adquisitivo de sus habitantes.

Educación y Economía: Se confirmó que un mayor nivel educativo correlaciona positivamente con el salario, pero no necesariamente con la lealtad a la marca.

🛠️ Herramientas Utilizadas
Python 3.11

Pandas: Limpieza, manipulación y unificación de datasets (Merge).

Seaborn & Matplotlib: Visualización de datos (Heatmaps, Boxplots, Scatterplots).

📂 Estructura del Repositorio
data/: Contiene los archivos CSV originales (Vuelos y Clientes).

notebooks/: Jupyter Notebook con el paso a paso del análisis.

README.md: Descripción general del proyecto.

🚀 Pasos Realizados
Limpieza de Datos: Manejo de valores nulos, eliminación de registros con salarios negativos y corrección de tipos de datos.

Unificación (Merge): Creación de una tabla maestra agrupando los datos mensuales de vuelos por cliente.

Análisis Descriptivo: Evaluación de métricas clave por nivel educativo, provincia y estado civil.

Visualización: Creación de gráficos interactivos y estáticos para validar hipótesis de negocio.

🔮 Próximas Líneas de Investigación
Para llevar este análisis al siguiente nivel y aportar más valor a la toma de decisiones, se proponen las siguientes acciones:

Predicción de Churn (Abandono): Desarrollar un modelo de Machine Learning para identificar patrones en los clientes que cancelan su suscripción, permitiendo acciones de retención proactivas.

Modelado de Propensión de Compra: Analizar qué factores demográficos (más allá del salario) impulsan a un cliente a subir de categoría de tarjeta (Star → Nova → Aurora).

Optimización de Rutas: Cruzar los datos de Distance con la rentabilidad por vuelo para optimizar la oferta en las provincias con mayor demanda.

Análisis de Sentimiento: Integrar datos de encuestas de satisfacción para entender por qué los clientes de ciertas provincias vuelan más que otros.
