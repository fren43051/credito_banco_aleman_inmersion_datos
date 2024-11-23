Análisis de Crédito Bancario Alemán
Este proyecto realiza un análisis de crédito utilizando un conjunto de datos de un banco alemán. El objetivo es predecir si un cliente incumplirá con el pago de su crédito empleando varios modelos de machine learning.

Tabla de Contenidos
Requisitos
Instalación
Uso
Descripción del Proyecto
Resultados
Contribuciones
Licencia
Requisitos
Asegúrate de tener instalados los siguientes elementos:

Python 3.x
Jupyter Notebook
Bibliotecas de Python necesarias:
pandas
numpy
scikit-learn
imbalanced-learn
matplotlib
Instalación
Clona este repositorio:

bash
Copiar código
git clone https://github.com/fren43051/credito_banco_aleman_inmersion_datos.git
Navega al directorio del proyecto:

bash
Copiar código
cd tu_repositorio
Instala las dependencias:

bash
Copiar código
pip install -r requirements.txt
Uso
Abre el Jupyter Notebook:

bash
Copiar código
jupyter notebook
Abre el archivo credito_banco_aleman_inmersion.ipynb y ejecuta las celdas para realizar el análisis.

Descripción del Proyecto
El análisis de crédito incluye los siguientes pasos principales:

Carga de Datos:

Cargar el conjunto de datos proporcionado por el banco alemán.
Selección de Características:

Identificar y seleccionar un subconjunto de variables relevantes para el análisis.
Balanceo de Clases:

Aplicar técnicas como sobremuestreo y submuestreo para balancear las clases desbalanceadas en los datos.
Entrenamiento de Modelos:

Entrenar varios modelos de machine learning, incluyendo:
Regresión Logística
Árbol de Decisión
Random Forest
Naive Bayes
Evaluación de Modelos:

Evaluar los modelos utilizando métricas como:
Precisión
Recall
F1-Score
AUC-ROC
Visualización de Resultados:

Graficar los resultados obtenidos para comparar el rendimiento de los modelos.
Resultados
Los resultados obtenidos muestran una comparación entre los modelos entrenados, identificando cuál es el más efectivo para predecir el incumplimiento de pago de los créditos.

Contribuciones
¡Las contribuciones son bienvenidas!
Por favor, abre un issue o envía un pull request para discutir cualquier cambio que te gustaría realizar.

Licencia
Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más detalles.

