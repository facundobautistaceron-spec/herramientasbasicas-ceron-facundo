Dashboard de Ventas y Rendimiento Operativo - Adidas US (2020-2021)

Autor: Cerón Facundo Bautista  
Curso: Herramientas Básicas Para El Analisis de Datos  
Cohorte: Virginia Marich, Miercoles 18:30  


1. Objetivo del Proyecto
El objetivo de este proyecto es analizar el desempeño comercial y operativo de Adidas en Estados Unidos durante el período 2020-2021. Mediante el procesamiento de datos en Python y el desarrollo de un dashboard interactivo en Power BI, se busca identificar patrones de ventas, evaluar la rentabilidad por canal de distribución (In-store, Online, Outlet) y medir la eficiencia operativa por región y distribuidor clave para la toma de decisiones estratégicas.


2. Dataset y Fuentes
*Fuente de datos original:Dataset público de ventas de Adidas en EE. UU. ubicado en la carpeta [`/data/raw/`](./data/raw/adidas_us_sales_limpio.csv).
*Enlace a la fuente original: [Kaggle - Adidas Enterprise Sales Dataset](https://www.kaggle.com/datasets/heeraldedhia/adidas-enterprise-sales-dataset)


3. Metodología y Pasos Realizados
1. Análisis Exploratorio de Datos (EDA): Limpieza de datos, tratamiento de nulos, estructuración de tipos de datos y análisis preliminar mediante Python en Jupyter Notebook. Consulta el archivo en [`/notebooks/eda_adidas_sales.ipynb`](./notebooks/eda_adidas_sales.ipynb).
2. Modelado y Métricas DAX: Creación de una tabla dedicada `_medidas` en Power BI Desktop para el cálculo dinámico de KPIs:
   * Ventas Totales: `Ventas Totales = SUM(adidas_us_sales_limpio[total_sales])`
   * Ganancia Operativa: `Ganancia Operativa = SUM(adidas_us_sales_limpio[operating_profit])`
   * Margen Operativo %: `Margen Operativo % = DIVIDE([Ganancia Operativa], [Ventas Totales], 0)`
3. Diseño Visual e Interactivo: Construcción del reporte interactivo con tarjetas KPI, gráficos estacionales por mes, barras por retailer y distribución por producto. Consulta el archivo en [`/dashboard/adidas_sales_dashboard.pbix`](./dashboard/adidas_sales_dashboard.pbix).


4. Estructura del Repositorio
* `/data/raw/`: Contiene el archivo fuente de datos en formato CSV.
* `/notebooks/`: Cuaderno Jupyter con el análisis exploratorio (EDA) en Python.
* `/dashboard/`: Archivo ejecutable de Power BI (`.pbix`) y captura de pantalla del reporte (`dashboard_preview.png`).
* `README.md`: Documentación general del proyecto.


5. Referencias y Citas
Dataset: Dedhia, H. (2022). Adidas Enterprise Sales Dataset. Recuperado de [Kaggle](https://www.kaggle.com/datasets/heeraldedhia/adidas-enterprise-sales-dataset).
Documentación Power BI: Microsoft. (2024). Instrucciones de DAX en Power BI Desktop. Recuperado de [Microsoft Learn](https://learn.microsoft.com/power-bi/).