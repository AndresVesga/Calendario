# 📊 Power BI Toolkit – Dimensiones y Funciones M

Este repositorio contiene un conjunto de **funciones y tablas en lenguaje M (Power Query)**, junto con un archivo de ejemplo en Power BI (`.pbix`), para la construcción de **modelos de datos robustos, escalables y reutilizables**.

---

## 📂 Estructura del Repositorio

- **M/**  
  Carpeta con todos los scripts en **lenguaje M**, documentados y listos para copiar/usar en cualquier proyecto.  

  Incluye:
  - `Calendario.m` → Tabla calendario completa con semanas ISO, YTD, MTD, desviaciones y festivos por país.  
  - `dim_tiempo.m` → Dimensión de tiempo con granularidad de 1 minuto, jornadas, AM/PM, rangos y horas pico.  
  - `CuandoEnElMundo.m` → Función que obtiene festivos desde [cuandoenelmundo.com](https://www.cuandoenelmundo.com).  
  - `CalendarioFestividadesPorRango.m` → Genera calendario consolidado de festividades para un rango de años.  
  - `getISO8601Week.m` → Función para calcular el número de semana ISO-8601.  

- **Ejemplo.pbix**  
  Archivo en Power BI Desktop que implementa todas las funciones y tablas incluidas en `M/`.  
  Sirve como **demo práctica** y referencia de uso.

---

## 🚀 Cómo usar este repositorio

1. Descarga o clona este repositorio.  
   ```bash
   git clone https://github.com/AndresVesga/Calendario
