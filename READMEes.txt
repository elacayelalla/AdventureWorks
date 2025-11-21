# 🧩 Proyecto AdventureWorks – Análisis de Datos Empresariales

## 📘 Descripción General
Este proyecto tiene como objetivo realizar un **análisis integral del conjunto de datos AdventureWorks**, una base de datos de ejemplo proporcionada por Microsoft que simula la operación de una empresa dedicada a la **venta de productos deportivos y de ciclismo**.  
El análisis se centró en identificar **tendencias comerciales, desempeño de ventas, eficiencia operativa y comportamiento de los clientes**.

---

## 🎯 Objetivos del Proyecto
- Explorar y transformar los datos utilizando **SQL y Power BI**.  
- Crear un modelo de datos relacional optimizado para análisis de negocio.  
- Diseñar dashboards interactivos que permitan identificar:
  - Productos más vendidos y categorías más rentables.  
  - Desempeño de ventas por territorio y por empleado.  
  - Rentabilidad por región, tipo de producto y canal de venta.  
  - Tendencias de crecimiento y oportunidades comerciales.

---

## 🏗️ Tecnologías y Herramientas Utilizadas
| Categoría | Herramienta |
|------------|--------------|
| Base de datos | SQL Server (AdventureWorksDW2022) |
| Lenguaje de consulta | SQL / DAX |
| ETL / Modelado | Power Query |
| Visualización | Power BI |
| Documentación | Markdown / GitHub |
| Control de versiones | Git |

---

## 🧮 Proceso Analítico

### 1️⃣ Preparación y Limpieza de Datos
- Importación de tablas principales: `DimProduct`, `DimCustomer`, `DimSalesTerritory`, `FactResellerSales`, `FactInternetSales`.  
- Eliminación de duplicados y campos nulos.  
- Creación de columnas calculadas (DAX) para métricas clave como:
  - *Profit Margin*
  - *Total Sales*
  - *Year-to-Date Sales*
  - *Sales Growth YoY*

### 2️⃣ Modelado de Datos
- Relaciones entre tablas **Dimensionales (Dim)** y **de Hechos (Fact)**.
- Creación de una tabla calendario dinámica mediante DAX (`CALENDAR()` + columnas de fecha extendidas).
- Normalización de jerarquías: Producto → Subcategoría → Categoría → Línea de producto.

### 3️⃣ Análisis Exploratorio
- Ranking de los productos más vendidos.  
- Ventas promedio por cliente y territorio.  
- Identificación de tendencias de crecimiento y estacionalidad en ventas.  

### 4️⃣ Visualización en Power BI
- **Dashboard 1: Rendimiento Comercial Global**
  - Ventas por país y por año.
  - Margen de utilidad y top productos.  
- **Dashboard 2: Comportamiento del Cliente**
  - Análisis demográfico y frecuencia de compra.  
- **Dashboard 3: KPI de Ventas**
  - Total Sales, Profit, YoY Growth, Units Sold.

---

## 📊 Principales Hallazgos
- El **segmento de Reseller Sales** representa la mayor proporción de ingresos.  
- Las regiones **North America y Europe** muestran márgenes más altos y mejor crecimiento sostenido.  
- Los meses de **verano (junio–agosto)** reflejan los picos más fuertes de ventas.  
- La categoría **Bikes** domina las ventas, pero con un margen menor frente a **Clothing** o **Accessories**.  
- Los empleados del territorio *Pacific* mostraron mayor crecimiento en comparación con *Southwest*.

---

## 🚀 Conclusiones
El análisis de AdventureWorks permitió entender el comportamiento de ventas y rentabilidad global, sentando las bases para estrategias comerciales basadas en datos.  
El modelo desarrollado puede escalarse fácilmente para incorporar **nuevas fuentes de información (inventarios, marketing, clientes)** y aplicar **técnicas de machine learning** para predicciones de demanda y segmentación avanzada.

---

## 🧠 Autor
**Julio César López Mendoza**  
📧 julio@juegofinanciero.com  
📅 Proyecto académico – Bootcamp Data Analytics (Henry)  
💬 *“Transformando datos en decisiones estratégicas.”*