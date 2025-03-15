# Proyecto de Análisis Exploratorio y Descriptivo de Eventos en un Ecommerce 📊🛍

Este proyecto transforma datos brutos de eventos en un ecommerce en insights accionables, apoyándose en la potencia de Python y SQL (DuckDB) para generar una narrativa visual que facilite la toma de decisiones estratégicas.

---

## Tabla de Contenidos  
1. [Introducción 🌟](#introducción-🌟)  
2. [Objetivos 🎯](#objetivos-🎯)  
3. [Fuente de Datos 📂](#fuente-de-datos-📂)  
4. [Tecnologías Utilizadas 🛠](#tecnologías-utilizadas-🛠)  
5. [Metodología 📑](#metodología-📑)  
   - [1. Conexión y Preparación de Datos ⚙](#1-conexión-y-preparación-de-datos-⚙)  
   - [2. Análisis Descriptivo 📋](#2-análisis-descriptivo-📋)  
   - [3. Exploración y Visualización 📊](#3-exploración-y-visualización-📊)  
   - [4. Análisis de Conversión y Segmentación 📈](#4-análisis-de-conversión-y-segmentación-📈)  
6. [Conclusiones 🏁](#conclusiones-🏁)  
7. [Colaboradores 🤝](#colaboradores-🤝)

---

## Introducción 🌟

En este repositorio se documenta el proceso de análisis de datos a partir de eventos capturados en un ecommerce. Utilizando datos reales de interacciones en la plataforma, exploramos cómo se traducen las visualizaciones en compras, evaluando la tasa de conversión y otros indicadores clave que orientan la estrategia comercial.

---

## Objetivos 🎯

- **Acceder y preparar el dataset:**  
  Cargar, limpiar y transformar los datos de eventos para asegurar su calidad y confiabilidad.

- **Realizar un análisis descriptivo:**  
  Calcular métricas clave y examinar la distribución de variables como visualizaciones, compras, precios y categorización de productos.

- **Explorar la conversión de visualizaciones a compras:**  
  Identificar la tasa de conversión y analizar cuántas visualizaciones se requieren en promedio para generar una compra.

- **Segmentar la información:**  
  Analizar diferencias en la conversión según marcas, rangos de precio y otras variables relevantes.

- **Generar visualizaciones y una narrativa visual:**  
  Utilizar gráficos interactivos para descubrir patrones, tendencias y relaciones ocultas en el dataset.

---

## Fuente de Datos 📂

- **Dataset:**  
  Datos de eventos de un ecommerce, que incluyen tanto visualizaciones ("view") como compras ("purchase").

- **Variables Clave:**  
  - **EventTime:** Fecha y hora del evento (UTC).  
  - **UserSession:** Identificador temporal de la sesión del usuario.  
  - **UserID:** Identificador permanente del usuario.  
  - **ProductID:** Identificador del producto.  
  - **CategoryID:** Identificador de la categoría del producto.  
  - **EventType:** Tipo de evento (por ejemplo, "view" o "purchase").  
  - **Price:** Precio del producto.  
  - **BrandImputed:** Marca del producto (en minúsculas).  
  - **CategoryImputed, PrincipalCategory, SubCategory, SubCategory2, SubCategory3:** Información adicional sobre la taxonomía y subcategorías del producto.

---

## Tecnologías Utilizadas 🛠

- **Python:**  
  Para procesamiento, análisis y visualización de datos.

- **SQL con DuckDB:**  
  Para la carga, depuración y transformación eficiente de la información.

- **Bibliotecas de Visualización:**  
  Plotly, Matplotlib y Seaborn para crear gráficos interactivos y descriptivos.

---

## Metodología 📑

### 1. Conexión y Preparación de Datos ⚙
- **Acceso al Dataset:**  
  Se obtuvieron los datos de eventos del ecommerce a través de fuentes internas o APIs.

- **Carga y Limpieza:**  
  Se utilizaron Python y SQL para cargar la información, eliminar registros duplicados e inconsistencias, y estandarizar los formatos de las variables.

### 2. Análisis Descriptivo 📋
- **Variables Numéricas y Categóricas:**  
  Cálculo de medidas estadísticas (media, mediana, desviación estándar) y análisis de frecuencias en variables como Precio, EventType y categorías.

### 3. Exploración y Visualización 📊
- **Visualización de la Tasa de Conversión:**  
  Creación de gráficos para analizar la conversión de visualizaciones a compras, incluyendo histogramas, gráficos de barras y análisis temporal.

- **Análisis de Segmentación:**  
  Exploración de la influencia de marcas y rangos de precio en la conversión, utilizando filtros y gráficos interactivos.

### 4. Análisis de Conversión y Segmentación 📈
- **Cálculo de la Tasa de Conversión:**  
  Medición del porcentaje de eventos de compra en relación a las visualizaciones.
  
- **Análisis del Promedio de Visualizaciones por Compra:**  
  Determinación de cuántas visualizaciones se requieren, en promedio, para generar una compra.

- **Segmentación por Marca y Precio:**  
  Evaluación de diferencias en la conversión en función de la marca del producto y el rango de precio.

---

## Conclusiones 🏁

El análisis permitió transformar datos crudos en insights que ayudan a comprender el comportamiento de los usuarios en un ecommerce y a identificar oportunidades para optimizar estrategias de marketing y ventas. La integración de diversas técnicas de análisis y visualización facilitó la identificación de patrones clave en la conversión de visualizaciones a compras.

---


---

## Colaboradores 🤝

- [Juan Daniel Vergara Nieto](https://www.linkedin.com/in/daniel-vergara-nieto/)
- [Andres Felipe Lemus V](https://www.linkedin.com/in/andres-felipe-lemus-v-7943882a9/)  

---

¡Gracias por visitar este repositorio!  
Si tienes sugerencias o preguntas, no dudes en abrir un issue o enviarme un mensaje.
