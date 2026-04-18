# Web-Scraping

📚 Web Scraping y Análisis de Texto

🧠 Descripción

En este proyecto se realiza la extracción y análisis de datos de libros desde Books to Scrape.
Se combinan técnicas de web scraping y procesamiento de lenguaje natural (NLP) para explorar cómo las palabras en los títulos pueden relacionarse con el precio de los libros.

⚙️ Metodología
Web Scraping:
Extracción de títulos y precios de los libros y construcción de un DataFrame.
Limpieza de texto:
Conversión a minúsculas, eliminación de stopwords, números y caracteres especiales → datos_limpios.
Análisis de n-gramas:
Cálculo de frecuencias y generación de una nube de palabras para identificar términos más comunes.
Matriz TF (Term Frequency):
Representación de la frecuencia de palabras por libro, incluyendo el precio como variable adicional.
Variables binarias:
Selección de palabras clave y análisis de su presencia (1) o ausencia (0) en relación con el precio.
Visualización:
Gráficos de barras para comparar cómo influye la aparición de ciertas palabras en el valor de los libros.
🛠️ Tecnologías
Python 🐍
Pandas
BeautifulSoup
Requests
Matplotlib / Seaborn
WordCloud
📊 Objetivo

Identificar patrones en los títulos de libros y analizar si ciertas palabras están asociadas con precios más altos o más bajos.

🚀 Uso
Abrir el cuaderno en Colab (botón arriba)
Ejecutar las celdas paso a paso
Explorar resultados y visualizaciones
