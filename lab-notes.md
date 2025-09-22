# Actividad 1 #
## Tabla original: ##
| ID_EMPLEADO | NOMBRE_EMPLEADO | NOM_DEPTO | NOM_PROYECTO   |
|-------------|-----------------|-----------|----------------|
| 1001        | Alicia Gómez    | Finanzas  | Migración SAP  |
| 1002        | Juan Martínez   | IT        | Portal Cliente |
| 1001        | Alicia Gómez    | Finanzas  | Portal Cliente |

# Respuestas: #
- ¿Qué información parece repetirse?
Respuesta: Se repiten valores en las columnas: NOMBRE_EMPLEADO, NOM_DEPTO, NOM_PROYECTO
- ¿Qué datos podrían separarse en distintas tablas?
Podríamos tener una tabla que contenga los empleados, una que contenga los departamentos y una que contenga los proyectos
- ¿Qué columnas podrían servir como identificadores únicos (claves primarias)?
Para empleados, la columna ID_EMPLEADO existente
Para la tabla departamentos, crearíamos una columna nueva que podríamos llamar ID_DEPTO
Para la tabla proyectos, crearíamos una columna nueva que podríamos llamar ID_PROYECTO
- ¿Qué relaciones ves entre los datos?
Un empleado pertenece a un departamento 1:1
Un empleado puede estar asignado a varios proyectos 1:n
