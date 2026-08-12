## 1. Carga de datos
# Subimos las tablas de nuestra base de datos de PostgreSQL donde se ubican los datos que queremos analizar.

<img width="1919" height="1031" alt="image" src="https://github.com/user-attachments/assets/53103d3a-aca3-4382-aff0-ee2f01fc0713" />

## 2. PowerQuery
# Nos aseguramos que los datos de las tablas estén correctos, yendo a transformar datos para acceder a la herramienta de PowerQuery.

<img width="1919" height="1032" alt="image" src="https://github.com/user-attachments/assets/14172f83-a578-4242-8ff3-8a725b5d1f52" />

Utilizando el perfil de la columna y distribución de la columna para poder verificar si alguna de todas las tablas cargadas presentan algún tipo de error. Nos aseguramos que las columnas que tienen que tener valores únicos no posean un valor repetido y también nos aseguramos que ningún valor figure como error o vacío, que podría generar un error en el análisis.

## 3. Modelo de datos
# Se diseñó un modelo relacional en esquema copo de nieve/estrella, centrado en los empleados, garantizando la integridad referencial y optimizando el rendimiento de las consultas analíticas.

<img width="1919" height="1030" alt="image" src="https://github.com/user-attachments/assets/40e791c0-00ee-488e-9a20-f7ef596af375" />

El modelo sigue el esquema clásico de la base "employees" 
(Postgres), adaptado para análisis de equidad salarial y compensaciones. Está organizado en un esquema de copo de nieve liviano con `employees` como tabla central.
