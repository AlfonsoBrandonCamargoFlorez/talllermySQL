--- 1. Devuelve un listado con el código de oficina y la ciudad donde hay oficinas.


```sql
SELECT  oficina_id, ciudad_id from oficina order by oficina_id;

```
--- 2. Devuelve un listado con la ciudad y el teléfono de las oficinas de España.

```sql
SELECT  ciu.nombre AS nombre_ciudad, ofi.telefono from oficina AS ofi
INNER JOIN ciudad AS ciu ON ofi.ciudad_id = ciu.ciudad_id
INNER JOIN region AS reg ON ciu.region_id = reg.region_id
INNER JOIN pais AS pa ON reg.pais_id = pa.pais_id
WHERE pa.nombre = 'España';
```
--- 3. Devuelve un listado con el nombre, apellidos y email de los empleados cuyo jefe tiene un código de jefe igual a 7.


```sql
SELECT nombre, apellido1, apellido2, email FROM empleado
WHERE  codigo_jefe = 7;

```
--- 4. Devuelve el nombre del puesto, nombre, apellidos y email del jefe de la empresa.

```sql
SELECT puesto, nombre, apellido1, apellido2, email FROM empleado
WHERE codigo_jefe_id is NULL;

```
--- 5. Devuelve un listado con el nombre, apellidos y puesto de aquellos empleados que no sean representantes de ventas.

```sql
SELECT nombre, apellido1, apellido2, puesto FROM empleado
WHERE puesto != 'representante de ventas';
```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```


```sql

```
