# Análisis de Métodos de Venta – Proyecto de Certificación Data Analyst (DataCamp)

###
Este proyecto fue desarrollado como parte del examen práctico para la certificación profesional como **Analista de Datos** en **DataCamp**. El objetivo del análisis es evaluar la efectividad de distintos métodos de venta utilizados para lanzar una nueva línea de productos por parte de la empresa ficticia _Pens and Printers.

---
## Contexto del negocio
Pens and Printers  es una compañía con gran reconocimiento en el mercado que ofrece productos de oficina de alta calidad a grandes empresas y desea evaluar tres canales de venta para su nueva línea de productos:
- **Email**  
- **Llamada telefónica**  
- **Email + llamada combinada**
La meta es identificar cuál canal genera mejores resultados en ventas y tomar decisiones estratégicas basadas en datos.
---
## Proceso de análisis
### 🔹 1. Validación y limpieza de datos
- Detección y tratamiento de valores nulos en la variable `revenue`.
- Estandarización de categorías en `sales_method`.
- Verificación de duplicados y consistencia general del dataset.
- Ajuste de valores anómalos en `years_as_customer`.

Dataset original: 15.000 registros → Filtrado final: 13.926 registros válidos.
---
### 🔹 2. Análisis exploratorio
- Distribución de clientes por método de venta.
- Participación en ingresos por canal.
- Distribución geográfica de clientes.
- Análisis de ingresos por semana y tendencia por canal.
- Evaluación del ingreso promedio y número de productos vendidos por método.
---
### 🔹 3. Definición de KPIs
- **KPI 1:** Participación semanal de ingresos por canal.
- **KPI 2:** Variación porcentual de ingresos semana a semana.
Estos indicadores permiten monitorear el rendimiento en tiempo real y ajustar la estrategia comercial según el comportamiento del mercado.
---
## Conclusiones y recomendaciones
- El canal **combinado (Email + Llamada)** demostró ser el más efectivo en términos de ingresos a partir de la semana 5.
- El canal **Email** es rentable, pero con tendencia a la baja si no se complementa con seguimiento.
- El canal **llamadas telefónicas** mostró menor rendimiento y mayor costo operativo.
- Se recomienda:
  - Usar el canal combinado como principal.
  - Continuar con email como canal secundario.
  - Mejorar la recolección y estandarización de datos para futuros análisis.
---
## Herramientas utilizadas
- Python (pandas, matplotlib, seaborn)
- Jupyter Notebook
- PowerPoint (para la presentación final)
---
## Archivos del repositorio
- `notebook.ipynb` → Análisis completo en Python
- `New Product Sales Methods analysis.pptx` → Presentación final del proyecto
---
### Sobre mí

###
Soy **Ingeniera Química** en transición hacia el análisis de datos, con formación en herramientas como Power BI, SQL y Python. Me interesa resolver problemas reales de negocio mediante el análisis, visualización e interpretación de datos.

<sub> [Mi perfil de LinkedIn](https://www.linkedin.com/in/katherineparrag)</sub>
---

