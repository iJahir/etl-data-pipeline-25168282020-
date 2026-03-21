# ETL Data Pipeline
 
Este proyecto implementa un proceso ETL completo:
 
## 🔹 Extract
Se cargaron datos desde archivos CSV.
 
## 🔹 Transform
Se limpiaron los datos:
- Eliminación de valores nulos
- Separación en datasets curated y rejects
 
## 🔹 Load
Se integraron los datos mediante joins y se cargaron en PostgreSQL usando Render.
 
## 🔹 Resultado final
Dataset integrado con columnas:
id, nombre, dept, salario
 
## 🔹 Tecnologías
- Python
- Pandas
- SQLAlchemy
- PostgreSQL (Render)
