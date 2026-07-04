# telecom-analysis
He preparado el documento estructurándolo con un enfoque muy profesional y estratégico, ideal para destacar en tus entregas del bootcamp de Data Analytics. El archivo incluye exactamente los 5 puntos que solicitaste.

Si prefieres copiar y pegar el texto directamente en lugar de descargar el archivo, aquí tienes el contenido exacto:

***

```markdown
# Análisis de Comportamiento de Clientes - ConnectaTel 📡📊

## 🎯 Objetivo del Proyecto
El objetivo principal de este proyecto es analizar el comportamiento de los clientes de **ConnectaTel**, una empresa de telecomunicaciones en Latinoamérica. A través de la limpieza, exploración y análisis estadístico de los datos registrados hasta el año 2024, se busca construir un perfil claro de los usuarios, identificar patrones de consumo, detectar comportamientos atípicos y proponer una segmentación estratégica. Los insights derivados de este análisis servirán para fundamentar estrategias de marketing, mejorar la retención de clientes y sugerir posibles mejoras en los planes de servicios de la empresa.

---

## 📂 Datasets Utilizados
Para este análisis se procesaron tres conjuntos de datos principales:
- **`plans.csv`**: Información detallada de los planes de telecomunicaciones actuales (precios, minutos y GB incluidos, costo por uso extra).
- **`users.csv`**: Datos demográficos y comerciales de los clientes (edad, ciudad de residencia, fecha de registro al servicio, plan contratado e indicador de churn/abandono).
- **`usage.csv`**: Registro detallado del uso real de los servicios por parte de los clientes, abarcando consumo de llamadas y mensajes de texto.

---

## 🛠️ Etapas del Análisis Realizadas

1. **Importación y Exploración Inicial:**
   - Carga de las librerías necesarias (`pandas`, `matplotlib`, `seaborn`, etc.).
   - Análisis de la estructura general de los datasets (tipos de datos, dimensiones y observaciones preliminares).

2. **Diagnóstico y Limpieza de Datos:**
   - Detección de valores inválidos, nulos y *sentinels* (datos erróneos).
   - Revisión y estandarización de columnas de fechas (`reg_date`, `date`) para asegurar un formato temporal correcto.
   - Tratamiento de datos faltantes e imputación/corrección de errores lógicos.

3. **Análisis Exploratorio de Datos (EDA) y Estadísticas Descriptivas:**
   - Creación de un resumen estadístico del consumo agrupado por usuario para el año 2024.
   - Evaluación de métricas clave y distribución del uso (duración de llamadas y cantidad de mensajes).

4. **Identificación de Outliers (Valores Atípicos):**
   - Análisis de dispersión y detección de usuarios con consumos significativamente fuera del promedio.

5. **Segmentación de Clientes:**
   - Segmentación demográfica de los usuarios (ej. por rangos de edad).
   - Visualización de la segmentación mediante gráficos para interpretar el peso y características de cada grupo de clientes.

6. **Análisis Ejecutivo e Insights:**
   - Consolidación de los hallazgos en recomendaciones de negocio accionables, enfocadas en mejorar el servicio y las acciones estratégicas de la empresa.

---

## 🚀 Cómo Ejecutar el Notebook

Este proyecto está diseñado para ser ejecutado fácilmente en la nube a través de **Google Colab** o en un entorno local usando **Jupyter Notebook**.

### Opción A: Usando Google Colab (Recomendado)
1. Descarga el archivo `.ipynb` de este repositorio o guárdalo en tu Google Drive.
2. Ve a [Google Colab](https://colab.research.google.com/).
3. Selecciona **Archivo > Subir notebook** y carga el archivo `.ipynb`.
4. En el panel izquierdo, haz clic en el ícono de la carpeta (Archivos) y sube los tres datasets: `plans.csv`, `users.csv`, y `usage.csv`.
5. Ejecuta las celdas secuencialmente pulsando `Shift + Enter` o usando el botón **"Entorno de ejecución" -> "Ejecutar todo"**.

### Opción B: Entorno Local (Jupyter Notebook / VSCode)
1. Clona este repositorio o descarga los archivos en una misma carpeta.
2. Asegúrate de tener Python instalado junto con las siguientes dependencias:
   ```bash
   pip install pandas matplotlib seaborn jupyter
