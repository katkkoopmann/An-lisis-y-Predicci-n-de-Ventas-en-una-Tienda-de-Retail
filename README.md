Proyecto 1: Análisis y Predicción de Ventas en una Tienda de Retail
Descripción
Este proyecto tiene como objetivo principal realizar un análisis exploratorio de datos (EDA), preprocesar los datos y comparar diferentes técnicas de machine learning para predecir ventas en una tienda de retail. Además, se ha generado una presentación de una página para resumir los hallazgos y conclusiones clave. El proyecto busca proporcionar insights accionables para optimizar las operaciones y estrategias comerciales.

Estructura del Repositorio
/Proyecto1
├── /data
│   ├── retail_sales_dataset.csv                  #Conjunto de datos utilizado para el análisis
├── /notebooks
│  Proyecto_1_Final.ipynb 			#Trabajo completo con exploración y análisis de datos, preprocesamiento y comparación de modelos.
├── onepage_presentation.pptx    # Presentación de una página con resultados clave
├── README.md                        # Descripción del proyecto y cómo ejecutarlo
Principales Hallazgos
Mejor Modelo: RandomForestRegressor con un R² de 95.6%.
Conclusión: Las variables más influyentes en la predicción de ventas es precio por unidad ('Price per unit').
Recomendación: Implementar el modelo seleccionado en sistemas de predicción en tiempo real para optimizar el inventario y estrategias de ventas.

Autor
Katia Koopmann: Análisis de datos.

Licencia
Este proyecto se publica bajo la licencia MIT. Consulta el archivo LICENSE para más información.
