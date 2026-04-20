
________________________________________
Análisis Comparativo de Modelos para la Proyección de Demanda de Gas Natural en el Sector Eléctrico Peruano
Este repositorio contiene la implementación técnica y el análisis comparativo de modelos clásicos (Econométricos y ARIMA) frente a modelos modernos (Machine Learning - Prophet) para el pronóstico de la demanda de gas natural en la generación eléctrica del Sistema Eléctrico Interconectado Nacional (SEIN) del Perú.
________________________________________
📋 Tabla de Contenidos
1.	Resumen del Proyecto
2.	Objetivo de la Investigación
3.	Metodología
4.	Resultados Principales
5.	Estructura del Repositorio
6.	Tecnologías Utilizadas
________________________________________
📝 Resumen del Proyecto
La investigación aborda la complejidad de modelar el consumo de gas natural en el sector eléctrico peruano (2005-2022). Se integraron datos del COES y entidades oficiales para realizar proyecciones a cinco años, evaluando la capacidad predictiva de tres enfoques distintos frente a la interacción de variables macroeconómicas y energéticas.
🎯 Objetivo de la Investigación
Establecer el modelo con mayor precisión predictiva para la demanda de gas natural mediante el contraste riguroso de metodologías determinísticas y estocásticas, facilitando la toma de decisiones en el planeamiento energético nacional.
⚙️ Metodología
Se evaluaron tres enfoques experimentales:
•	Modelo Causal Econométrico: Basado en cointegración biecuacional.
•	Modelo Estocástico: ARIMA con tratamiento exhaustivo de valores atípicos (outliers).
•	Machine Learning: Implementación mediante la librería Prophet (desarrollada por Meta/Facebook).
📊 Resultados Principales
El Modelo Econométrico Cointegrado demostró superioridad en la precisión de las proyecciones, superando a las alternativas en las métricas de error estadístico:
Modelo	MAPE (Error Absoluto Medio)
Econométrico Cointegrado	3.04%
ARIMA	4.39%
Prophet	5.87%
________________________________________
📂 Estructura del Repositorio
Plaintext
├── data/               # Registro consolidado (2005-2022) y fuentes oficiales
├── notebooks/          # Scripts de Python para limpieza, entrenamiento y evaluación
├── models/             # Archivos guardados de los modelos entrenados
├── docs/               # Documentación técnica adicional y bibliografía
└── requirements.txt    # Dependencias necesarias (Pandas, Prophet, Statsmodels, etc.)
🛠 Tecnologías Utilizadas
•	Lenguaje: Python 3.x
•	Análisis y Ciencia de Datos: Pandas, NumPy, Scikit-learn
•	Modelamiento Estadístico: Statsmodels (ARIMA), Prophet
•	Visualización: Matplotlib, Seaborn
•	Entorno: Jupyter Notebooks / VS Code
________________________________________
📧 Contacto
Para consultas sobre el alcance técnico o colaboración en futuras líneas de investigación, puede contactarme a través de este repositorio o los canales académicos correspondientes.
________________________________________
Este proyecto forma parte de la línea de investigación en Energética y Data Science aplicada al sector eléctrico peruano.

