# Proyecto definitivo: De datos a decisiones de negocio

Introducción:

En esta ocasion debo trabajar para RappiPlus: un servicio de suscripción dentro del ecosistema de Rappi diseñado para aumentar la frecuencia de compra y el valor generado por usuario.

Sin embargo, el equipo de negocio no tiene claro si el servicio está cumpliendo su objetivo.

Existen dudas clave:

¿Los usuarios realmente compran más?
¿El modelo está generando ganancias?
¿Se están perdiendo oportunidades en el proceso de compra?
Para responder estas preguntas, trabajare con datos de pedidos, catálogo y marketing.

El análisis permitirá entender el desempeño del servicio y detectar oportunidades concretas de mejora.

---

📂 Dataset del proyecto
El análisis comienza con tres fuentes principales:

rappiplus_orders_raw.csv

   - Cada fila representa un pedido realizado en la plataforma.
 
rappiplus_catalog.csv

   - Cada fila representa un producto disponible en la plataforma.
 
rappiplus_marketing_spend.csv

   - Cada fila representa una inversión en marketing realizada en un país y canal específico.
---

🗂️ Fuente de datos
Para este análisis se utilizará la siguiente tabla:

'events', que se encuentra almacenada en una base de datos.

⚙️ Nota: La conexión a esta base de datos se realizará desde el Jupyter Notebook.

Para este análisis se utilizarán las siguientes tablas:

---

Tabla users → Información de registro de usuarios.

   - Cada fila representa un usuario registrado en la plataforma.
 
Tabla user_activity → Actividad de los usuarios después del registro.

   - Cada fila representa la actividad de un usuario después de su registro.

---


## 📂 Contenido del repositorio

- `data_cleaning_eda_ecommerce.ipynb`
  → Notebook  completo de limpieza y análisis exploratorio de datos (EDA) hasta la generación de insights listos para tomar decisiones de negocio.

- `Dashboard Rappi.pbix`
  → Archivo que contiene el dashboard para descarga/lectura en PowerBI.

- `Dashboard.md`
  → Notebook que describe el proceso de creacion completo y logica del dashboard.

- `screenshots`
  → Referencias visuales para el dashboard.    

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente botón:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Alezgo-ui/Ecommerce_datacleaning_dashboard/blob/main/data_cleaning_eda_ecommerce_ipynb.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

## 📘 Cómo reproducir el análisis

1. Abre `data_cleaning_eda_ecommerce.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

## 🧠 Resumen del análisis

- Limpieza y preparación de datos con pandas
- Pipeline propio de EDA reutilizable
- Análisis de rentabilidad y comportamiento de ventas
- Análisis de retención por cohortes en SQL
- Análisis de funnel de conversión en SQL
- Prueba de hipótesis estadística (A/B test con z-test)
- Modelo de datos en Power BI (esquema de estrella)
- Dashboard 1: Overview Ejecutivo
- Dashboard 2: Detalle / Drill-through
