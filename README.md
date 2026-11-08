# 📊 Análisis de Ventas de Adventure Works (Adventure Works Sales Analytics)

## 🎯 Objetivo del Proyecto
Diseñar e implementar un proyecto analítico completo de extremo a extremo, abarcando la ingeniería de datos en SQLite para la limpieza, cruce (*JOINs*) y transformación de registros transaccionales, y la construcción de un panel visual ejecutivo (dashboard) en Power BI Desktop con un diseño moderno adaptado para un portafolio profesional.

---

## 🖼 Visualización del Dashboard
El proyecto está dividido en tres paneles principales para un análisis detallado:
* **Página 1 (Bikes / Ventas Generales):** Enfocada en el rendimiento de productos, colores y tendencias de ventas.
* **Página 2 (Demografía / Clientes):** Enfocada en el perfil de los clientes, estado civil, ingresos anuales y géneros.
* **Página 3 (Geografía / Regiones):** Enfocada en la distribución geográfica de las ventas, territorios e histórico de devoluciones.

![Dashboard Screenshot 1](./Adventure%20Works%20Sales%201.png)
![Dashboard Screenshot 2](./Adventure%20Works%20Sales%202.png)
![Dashboard Screenshot 3](./Adventure%20Works%20Sales%203.png)

---

## 🛠 Herramientas Utilizadas

SQLite & DBeaver: Gestión de base de datos relacional, ejecución de consultas SQL complejas (*JOINs*, agregaciones), creación de vistas (*views*) para integrar las tablas transaccionales de ventas, clientes, productos y territorios, y filtrado de datos para garantizar la integridad analítica.

Power BI Desktop: Modelado de datos en Star Schema, creación de medidas DAX avanzadas (Total Revenue, Total Profit, Total AVG, Total Cost, Total Transactions y control de contexto de filtro con la función ALL) y diseño de interfaz gráfica (UI/UX) optimizada.

Git & GitHub: Control de versiones y documentación del portafolio.

---

## 💡 Principales Insights

Métricas Financieras Generales: El volumen de negocio auditado alcanzó una facturación total (Total Revenue) de $34.11M, con un beneficio total (Total Profit) de 14.84M, un coste acumulado de 19.27M, un ticket medio (Total AVG) de 489.92 y 70K transacciones realizadas.

Preferencias de Productos: El ranking de ventas destaca los productos de la línea Mountain-200 (como el Mountain-200 Black, 42) en la cima de la facturación, mientras que el color Black lidera de forma aislada las preferencias de consumo con $15.83M en ventas, seguido por los colores Silver ($7.65M) y Red ($4.76M).

Canales de Venta y Pagos: La distribución de ingresos muestra un equilibrio casi perfecto entre clientes femeninos (51%) y masculinos (49%), con un volumen superior de ventas en clientes casados (37K) frente a solteros (33K). El ranking del Top 3 de clientes está liderado por WILLIE XU con $38,707.91.

Tendencia Temporal: La región del Pacífico (Pacific) representa el mayor motor de ventas con el 59% de los ingresos totales ($2.04bn en el segmento de ingresos anuales), seguida por Norteamérica (24%) y Europa (17%), destacando a Australia como el mercado con mayor representación individual.

---

## 📁 El archivo del informe (.pbix), los scripts de bases de datos y los recursos visuales están disponibles en este repositorio para su consulta y revisión técnica.
