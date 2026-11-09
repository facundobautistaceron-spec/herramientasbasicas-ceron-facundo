# Dashboard de Ventas y Rendimiento Operativo - Adidas US (2020-2021)

## Título y descripción general
**Análisis de ventas y rendimiento operativo de Adidas US (2020-2021)**

Este proyecto analiza el desempeño comercial de Adidas en Estados Unidos durante el período 2020-2021. A partir de un dataset de más de 9.000 registros, se aplicaron técnicas de limpieza, análisis exploratorio y visualización en Python, culminando en el diseño de un dashboard interactivo en Power BI Desktop.

## Objetivo del proyecto
* Explorar la evolución mensual y estacional de las ventas.
* Identificar los canales de venta (*In-store*, *Online*, *Outlet*) y productos más rentables.
* Analizar diferencias regionales y la eficiencia operativa por distribuidor clave (*retailer*).

## Dataset utilizado
* **Fuente:** Dataset público [Adidas Enterprise Sales Dataset en Kaggle](https://www.kaggle.com/datasets/heeraldedhia/adidas-enterprise-sales-dataset). Archivo local disponible en [`/DATA/RAW/adidas_us_sales_limpio.csv`](./DATA/RAW/adidas_us_sales_limpio.csv).
* **Formato:** CSV con 13 variables principales (fecha, región, estado, ciudad, retailer, producto, precio, unidades, ventas totales, margen operativo, método de venta).
* **Cantidad de registros:** 9.648 filas.

## Herramientas utilizadas
* **Python** (pandas, matplotlib, seaborn)
* **Google Colab**
* **Power BI**
* **GitHub**

## Dashboard
Incluye la vista previa y el proyecto interactivo ejecutable:
* Captura del tablero: [`/DASHBOARD/dashboard_preview.png`](./DASHBOARD/dashboard_preview.png)
* Archivo ejecutable de Power BI: [`/DASHBOARD/adidas_sales_dashboard.pbix`](./DASHBOARD/adidas_sales_dashboard.pbix)

## Estructura del proyecto
* `DATA/RAW/` → dataset en formato CSV
* `NOTEBOOKS/` → cuaderno de análisis exploratorio (EDA) en Python ([`/NOTEBOOKS/eda_adidas_sales.ipynb`](./NOTEBOOKS/eda_adidas_sales.ipynb))
* `DASHBOARD/` → tablero interactivo en Power BI y capturas de pantalla

## Licencia y autoría
© 2026 - Proyecto académico realizado por **Cerón Facundo Bautista**  
**Curso:** Herramientas Básicas para el Análisis de Datos (UTN.BA)  
**Cohorte:** Virginia Marich, Miércoles 18:30  
Licencia: Creative Commons Attribution 4.0 International
