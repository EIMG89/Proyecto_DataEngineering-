# Proyecto_DataEngineering
Desafío Final del curso Data Engineering de Coderhouse
# ETL completo en Airflow
Para finalizar el curso y poner en práctica todos los conocimientos adquiridos se propone crear un pipeline que extraiga datos de una API pública de forma constante combinándolos con información extraída de una base de datos y colocándolos en un Data Warehouse.


### Objetivos
- Crear un pipeline que extraiga datos de una API pública de forma
constante combinándolos con información extraída de una base de
datos
- Colocar los datos extraídos en un Data Warehouse
- Automatizar el proceso que extraerá, transformará y cargará datos
cuantitativos.
- Automatizar el proceso para lanzar alertas (2 máximo) por e-mail en
caso de que un valor sobrepase un límite configurado en el código.

### Desafios: Entregables
Para lograr los objetivos se presentarán tres entregables a lo largo del curso, cada uno con sus respectivos avances:

#### Entregable 1 / Desafío 1
Script que extraiga datos de una API pública y crear la tabla en Redshift para posterior carga de sus datos.
- Objetivos especificos:
 1. El script debería extraer datos en JSON y poder leer el formato en un diccionario de Python.
 2. La entrega involucra la creación de una versión inicial de la tabla donde los datos serán cargados posteriormente.
