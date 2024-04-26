# SQL-en-Python-Project
Para el siguiente ejercicio contamos con tres tablas (departments, jobs, hired_employees) con la siguiente estructura:

hired_employees structure
![image](https://github.com/yadelisgv/SQL-en-Python-Project/assets/40398052/3e3098f9-67a2-465c-8324-b6058f31301d)

departments structure
![image](https://github.com/yadelisgv/SQL-en-Python-Project/assets/40398052/b3d4a6d5-6969-4645-baa8-e15fe1340aa4)

jobs structure
![image](https://github.com/yadelisgv/SQL-en-Python-Project/assets/40398052/25dd3636-44e6-4d9a-9928-91f6102b287f)

Se pide explorar los datos introducidos contenidos en las tres tablas. Se piden algunas métricas específicas que se necesitan. 
Se debe crear un punto final para cada requisito.

Requirements1
Number of employees hired for each job and department in 2021 divided by quarter. The
table must be ordered alphabetically by department and job.
------------------------------------------------------------------------------------------------------------------
![image](https://github.com/yadelisgv/SQL-en-Python-Project/assets/40398052/e6bc6bbd-e943-4ddb-b182-d6343043ad19)

Para obtener el número de empleados contratados para cada puesto y departamento en 2021 dividido por trimestre, primero necesitamos unir las tres tablas utilizando las claves de las relaciones entre ellas. Luego, puedemos filtrar los registros por el año 2021 y agruparlos por departamento, puesto de trabajo y trimestre. Finalmente, se puede contar el número de empleados contratados en cada grupo.



Requirements 2
List of ids, name and number of employees hired of each department that hired more
employees than the mean of employees hired in 2021 for all the departments, ordered
by the number of employees hired (descending).
---------------------------------------------------------------------------------------
![image](https://github.com/yadelisgv/SQL-en-Python-Project/assets/40398052/8c05f613-2412-4049-8f42-f8c3ed3eb18d)


Para resolver este problema, necesitamos realizar varias operaciones SQL. Primero, necesitamos: calcular la media de empleados contratados en 2021 para todos los departamentos. Luego, utilizar esa media para filtrar los departamentos que contrataron más empleados que la media. Finalmente, contaremos el número de empleados contratados por cada departamento seleccionado y los ordenaremos en orden descendente por el número de empleados contratados. 

