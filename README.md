# Análisis de Segmentación de Clientes con PCA y K-Means en Spark

## 🚀 Visión General
Análisis de segmentación de clientes para el dataset de compras Hunter's e-grocery usando Apache Spark. Aplicamos PCA para reducción dimensional y K-Means para clustering, identificando patrones de consumo y segmentos homogéneos para estrategias de marketing dirigidas.

## ✨ Características y Tecnologías
- Reducción de dimensionalidad con PCA y clustering con K-Means.
- Evaluación con Silhouette Score para optimizar número de clústeres.
- Implementación con PySpark para manejo eficiente de grandes datos.
- Visualización con Python (Matplotlib/Seaborn).
  
## 📊 Dataset
- Archivo: `ECommerce_consumer behaviour.csv` (Hunter’s e-grocery, disponible en Kaggle).
- Datos: órdenes, productos, usuarios y comportamiento de compra.

## 🚀 Cómo Ejecutar
1. Descargar el dataset y colocarlo en la carpeta del proyecto.
2. Abrir el notebook `.ipynb` en Google Colab o entorno local con Spark.
3. Ejecutar las celdas en orden para preprocesar datos, aplicar PCA, entrenar K-Means y analizar resultados.

## 🎯 Perfiles de Clientes Identificados

| Clúster | Órdenes Totales | Prod. por Pedido | Ratio Reorden | Días entre Órdenes | Hora Pedido |
|---------|-----------------|------------------|---------------|--------------------|-------------|
| 0       | 1.35            | 8.08             | 0.45          | 15.97              | 17.20       |
| 1       | 1.67            | 22.74            | 0.54          | 14.36              | 13.19       |
| 2       | 1.35            | 7.45             | 0.49          | 17.07              | 10.13       |
| 3       | 3.16            | 8.32             | 0.76          | 6.73               | 13.31       |

**Perfiles:**

- **Clúster 0:** Compradores ocasionales nocturnos (pocos pedidos, baja recurrencia, compras por la tarde/noche).  
- **Clúster 1:** Compradores de carrito grande (volumen alto por compra, frecuencia media).  
- **Clúster 2:** Compradores únicos matutinos (muy infrecuentes, baja reorden, compras en la mañana).  
- **Clúster 3:** Compradores frecuentes y leales (alta frecuencia y lealtad).

## 📈 Visualización
Gráficos de dispersión de los clústeres en el espacio PCA para mejor interpretación.

## 💡 Conclusiones
Esta segmentación permite diseñar campañas personalizadas, optimizar productos y anticipar abandono. Próximos pasos incluyen análisis granular y modelos predictivos basados en estos segmentos.

---

Trabajo con fines académicos
