# 📊 Analizador de Ventas - Superstore Dataset

Análisis exploratorio de datos de ventas de una empresa retail estadounidense
con 9,994 transacciones entre 2014 y 2017.

## 🎯 Objetivo

Identificar patrones de ventas, categorías más rentables y el impacto
de los descuentos en la ganancia del negocio.

## 🔍 Hallazgos principales

- Las ventas crecieron consistentemente año a año durante el período analizado
- **Tecnología** es la categoría más rentable
- **Muebles** es la categoría menos rentable a pesar de tener precios altos
- Descuentos superiores al **20% generan pérdidas** en promedio por transacción
- La región **Oeste** lidera en volumen de ventas

## 📝 Lo que aprendí

- Que los datos "limpios" siguen teniendo problemas ocultos
  (fechas guardadas como texto, columnas numéricas que no son numéricas)
- Que el promedio puede mentir — la mediana de ventas ($54) es muy
  diferente al promedio ($229) porque unas pocas ventas grandes lo distorsionan
- Que más descuento no siempre es mejor estrategia comercial

## 📈 Visualizaciones

![Ventas anuales](outputs/graphics/ventas_anuales.png)
![Ganancia por categoría](outputs/graphics/ganancia_categoria.png)
![Descuento vs Ganancia](outputs/graphics/descuento_vs_ganancia.png)
![Ventas por región](outputs/graphics/ventas_region.png)

## 🛠️ Tecnologías

- Python 3.14
- pandas — limpieza y análisis de datos
- matplotlib + seaborn — visualizaciones
- Jupyter Notebook

## 📁 Estructura del proyecto

proyecto-ventas/
├── data/
│   ├── raw/          # datos originales sin modificar
│   └── processed/    # datos limpios listos para análisis
├── notebooks/
│   └── analisis_ventas.ipynb
├── outputs/
│   └── graphics/     # gráficos exportados
└── README.md

## 💡 Recomendación de negocio

Limitar los descuentos a 20%. Mayores descuentos solo afectan a las ganancias de la empresa.
Dar mas apoyo financiero las regiones con mas ventas.