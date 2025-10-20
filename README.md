# 🛒 Supermarket Analysis

Este proyecto tiene como objetivo analizar datos reales de un supermercado con el fin de comprender la **dinámica del negocio, sus pérdidas, márgenes y oportunidades de mejora**.  
A partir de múltiples fuentes de información (catálogo de productos, ventas diarias, precios mayoristas y tasas de pérdida), se construye una visión integral del funcionamiento operativo y financiero.

---

## 🎯 Objetivo principal
Desarrollar un análisis que permita entender mejor la historia y realidad del negocio, detectando **patrones de venta, eficiencia logística y rentabilidad**, con el propósito de **apoyar la toma de decisiones basadas en datos**.

---

## 📂 Estructura de los datos

Los datos provienen de cuatro archivos CSV que representan distintas áreas del negocio:

| Archivo     | Descripción                                                  | Columnas clave |
|--------------|--------------------------------------------------------------|----------------|
| **annex1.csv** | Catálogo de productos y sus categorías                      | Item Code, Item Name, Category Code, Category Name |
| **annex2.csv** | Registro de ventas diarias                                 | Date, Time, Item Code, Quantity Sold (kilo), Unit Selling Price (RMB/kg), Sale or Return, Discount (Yes/No) |
| **annex3.csv** | Precio mayorista de compra de cada producto                 | Date, Item Code, Wholesale Price (RMB/kg) |
| **annex4.csv** | Tasa de pérdida o desperdicio estimada por producto         | Item Code, Item Name, Loss Rate (%) |

📦 **Fuente de datos:** [Supermarket Sales Data – Kaggle](https://www.kaggle.com/datasets/yapwh1208/supermarket-sales-data/data)

---

## 💡 Preguntas guía

El análisis busca responder a preguntas como:
- ¿Cuáles son los productos y categorías más rentables?
- ¿Qué impacto tiene el *Loss Rate (%)* en la ganancia real?
- ¿En qué horarios o días se concentran las mayores ventas?
- ¿Qué productos presentan altos niveles de pérdida o desperdicio?
- ¿Cómo se relacionan los descuentos con el volumen de ventas?

---

## 📊 Enfoque analítico

1. **Exploración inicial (EDA):** revisión de estructura, valores nulos y consistencia entre datasets.  
2. **Integración de datos:** unión de los archivos mediante *Item Code*.  
3. **Análisis de ventas:** tendencias, horarios, descuentos y volumen.  
4. **Análisis de rentabilidad:** comparación entre precio de venta y precio mayorista.  
5. **Evaluación de pérdidas:** impacto del *Loss Rate* sobre márgenes.  
6. **Conclusiones:** generación de insights y recomendaciones estratégicas.

---

## 📈 Power BI Dashboard

El dashboard complementa el análisis exploratorio con una **visualización interactiva y ecofriendly**, diseñada en Power BI.  
Permite analizar las métricas clave del negocio, como:

- Ventas por categoría, producto y período.
- Rentabilidad neta considerando las pérdidas.
- Comparativo de márgenes entre productos.
- Impacto de descuentos y retornos en las ganancias.

🌿 El diseño utiliza tonos naturales (verde, beige y madera clara) para reflejar una estética limpia y sostenible.

🔗 [Ver Dashboard en Power BI](https://app.powerbi.com/view?r=eyJrIjoiNTU3MDJiYWQtNWVkMi00NmM4LTllOTEtZDAxOTZjZGUyZmU5IiwidCI6ImJhYjBiNjc5LWJkNWYtNGZlOC1iNTE2LWM2YjhiMzE3Yzc4MiIsImMiOjR9)
---

## 📓 Exploratory Data Analysis (Python)

El análisis exploratorio fue desarrollado en Python utilizando librerías como **Pandas, Matplotlib, Seaborn y Plotly**.  
Incluye visualizaciones detalladas, correlaciones y evaluaciones de rentabilidad.

👉 [Ver notebook EDA](./Supermarket%20EDA.ipynb)  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Nicoplayz58/Supermarket-Analysis/blob/main/Supermarket%20EDA.ipynb)

---

## 🧰 Tecnologías utilizadas

- **Python:** Pandas, Matplotlib, Seaborn, Plotly.  
- **Power BI:** Diseño e interactividad del dashboard.  
- **GitHub:** Publicación y documentación del proyecto.  

---

## 🚀 Propósito final

El propósito es ofrecer **insights claros y accionables** sobre:
- Qué productos generan valor sostenido.  
- Dónde se concentran las pérdidas económicas.  
- Cómo optimizar decisiones de inventario, precios y compras.  

Este análisis busca ser la base para estrategias de **reducción de pérdidas y aumento de rentabilidad** en el supermercado.

---

## 👨‍💻 Autor
**Nicolás Rodriguez**  
Estudiante de Ciencia de Datos — Universidad del Norte  
📧 [nicoplayz58@gmail.com](mailto:nicoplayz58@gmail.com)  
📍 Barranquilla, Colombia  

---

> *“Convertir datos en decisiones claras es tan importante como presentarlos con propósito.”* 🌱
