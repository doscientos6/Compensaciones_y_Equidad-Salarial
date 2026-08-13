# Equidad Salarial y Compensaciones

---
Este proyecto es un análisis de recursos humanos basado en el dataset de 365DS-Practice-Exams-People-Analytics dataset. El objetivo principal de este proyecto es identificar y analisar la equidad salarial y compensaciones en la empresa

---

## 🛠️ Tecnologías y Herramientas
* **SQL (PostgreSQL):** Extracción, modelado de datos, auditoría y consultas exploratorias iniciales.
* **Power BI & DAX:** Modelado relacional, cálculo de métricas y medidas, y diseño del dashboard interactivo.
* **Storytelling de Negocio:** Traducción de métricas técnicas a insights claros para entender la situación de la empresa

---

## 📂 Fases del Proyecto

### Fase 1: Extracción y Preparación (SQL)
Antes de visualizar, se aseguró la integridad de los datos mediante consultas SQL. 
* Podés revisar el código completo en el archivo **[queries.sql]**.
* **Tareas realizadas:** Creación de la estructura de tablas (DDL), validación de valores nulos y redundantes, creación de KPIs descriptivos y de KPIs que permiten responder preguntas de negocio y lograr el objetivo del proyecto

### Fase 2: Visualización y Dashboard (Power BI)
Se desarrolló un reporte interactivo enfocado en la experiencia del usuario y la claridad visual.

### Fase 3: Análisis

---

Resumen

La empresa (300 mil empleados, 9 departamentos) es homogénea en antigüedad, edad y género — ninguna de estas variables explica diferencias salariales. El verdadero problema está en Staff y Senior Staff, los dos puestos con mayor dispersión salarial, sin una causa demográfica clara detrás.

KPIs generales
Total empleados: 300 mil
Salario promedio: $72 mil
Antigüedad promedio: 36,4 años (uniforme entre departamentos)
Brecha salarial de género: 0,09% (prácticamente nula)
Hallazgos

1. Dispersión salarial por puesto Staff (19,2 mil) y Senior Staff (18,8 mil) tienen mucha más variación salarial que el resto de los cargos, como Senior Engineer (13,6 mil). Como la antigüedad es pareja en toda la empresa, esta dispersión no se explica por experiencia — sugiere falta de bandas salariales claras en esos dos puestos.

2. Antigüedad vs. salario por departamento No hay relación entre antigüedad y salario a nivel departamental. Sales y Marketing pagan más sin tener más antigüedad que el resto.

3. Masa salarial vs. dotación La masa salarial escala proporcional al tamaño de cada departamento — no hay áreas chicas con presupuesto desproporcionado.

4. Salario por puesto y género Dentro de cada puesto, a nivel general, hombres y mujeres cobran salarios muy similares. Sin embargo, al filtrar por departamento aparecen excepciones: en Manager de Marketing, el salario promedio de hombres ($84.783) es un 11,4% mayor al de mujeres ($75.114) — una brecha bastante superior al 0,09% global. Al ser una combinación puntual de puesto + departamento, conviene confirmar cuántos empleados componen ese grupo antes de generalizar, pero es un caso a marcar para revisión específica.

Conclusión

A nivel global, ni la antigüedad, ni el tamaño de departamento, ni el género explican la inequidad salarial. El problema principal sigue estando en los puestos de Staff y Senior Staff. Además, se identificó un caso puntual de brecha de género relevante (Manager en Marketing) que no se ve reflejado en los promedios generales y merece revisión aparte.
