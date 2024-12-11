Análisis de Precios, Demanda y Producción de Electricidad en Italia
Este proyecto lleva a cabo un análisis detallado sobre el mercado de electricidad en Italia, centrándose en los precios, demanda y producción, y cómo estos factores se ven influenciados por la producción de gas. El dataset utilizado fue descargado desde Kaggle, y contiene cuatro archivos CSV que se analizaron para obtener información relevante sobre la evolución del mercado eléctrico italiano.

Descripción del Proyecto
Dataset utilizado:
El dataset fue descargado desde Kaggle: Italian Electric Market Data y contiene los siguientes archivos CSV:

Precios de electricidad en Italia: Datos sobre los precios de la electricidad en distintas zonas de Italia.
Demanda de electricidad en Italia: Información sobre la demanda de electricidad en varias regiones italianas.
Producción de gas en Europa: Este archivo contiene información sobre el gas holandés, que es uno de los precios más representativos en el mercado energético europeo.
Producción de electricidad por fuente en Italia: Datos históricos de la producción de electricidad en Italia, desglosados por fuentes (nuclear, eólica, hidroeléctrica, solar, gas, etc.).
Flujo de trabajo:
Preprocesamiento de datos: En el primer notebook se realizó el preprocesamiento de los cuatro archivos CSV. Este proceso incluyó:

Limpieza de los datos (eliminación de valores nulos, tratamiento de valores atípicos).
Conversión de las columnas y asegurarse de que los tipos de datos fueran adecuados para el análisis.
Agregación de los datos por fecha o por región según fuera necesario.
Análisis de precios y demanda de electricidad: En el segundo notebook se analizó la relación entre precios de la electricidad y la demanda de electricidad en Italia. Este análisis incluyó:

Exploración de la correlación entre precios y demanda a lo largo del tiempo.
Evaluación del impacto de eventos significativos (como la pandemia de COVID-19 y la guerra en Ucrania) en los precios y la demanda.
Análisis de la producción de electricidad por fuente en Italia: En el tercer notebook se trabajó con los datos de la producción de electricidad por fuente en Italia. Este análisis incluyó:

La evolución de la participación de las energías renovables en la matriz energética italiana.
El impacto de la reducción de la producción nuclear a partir de 1988 debido al referéndum en Italia.
El aumento de la producción de electricidad de fuentes no renovables (gas, carbón, petróleo).
Análisis del precio del gas holandés: En el cuarto notebook se trabajó con los datos sobre el precio del gas holandés. El gas natural es fundamental para la producción de electricidad, especialmente en Italia, y sus precios tienen una gran influencia en el costo de la electricidad. Este análisis incluyó:

Evolución del precio del gas a lo largo de los años (2018-2022).
Cálculo de la volatilidad de los precios del gas.
Identificación de patrones estacionales en los precios del gas.
Herramientas utilizadas:
Python: Lenguaje de programación utilizado para realizar el análisis.
Pandas: Librería principal utilizada para la manipulación y análisis de los datos.
Matplotlib: Librería para la visualización de gráficos y resultados.
Cómo ejecutar el proyecto:
Clonar el repositorio:

bash
Copiar código
git clone https://github.com/tu-usuario/nombre-del-repositorio.git
Instalar dependencias:

Asegúrate de tener Python 3.6 o superior instalado.
Crea un entorno virtual (opcional pero recomendado):
bash
Copiar código
python -m venv env
Activa el entorno virtual:
En Windows:
bash
Copiar código
.\env\Scripts\activate
En macOS/Linux:
bash
Copiar código
source env/bin/activate
Instala las dependencias necesarias:
bash
Copiar código
pip install -r requirements.txt
Ejecutar los notebooks:

Abre los Jupyter Notebooks para realizar el análisis. Puedes abrirlos con:
bash
Copiar código
jupyter notebook