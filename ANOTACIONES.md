# Anotaciones

## Qué note

creado_por no es atómico
actualizado_por no es atómico

separar en una tabla de actualizaciones
con uuid usuario como clave primaria
primer nombre
segundo nombre, puede ser null
apellido paterno
apellido materno, puede ser null
fecha_actualizacion
tabla, el nombre de la tabla

separar en una tabla de creaciones
con uuid usuario como clave primaria
primer nombre
segundo nombre, puede ser null
apellido paterno
apellido materno, puede ser null
fecha_actualizacion
tabla, el nombre de la tabla

## Cómo cambiarlo

corregir eso para las tablas:
cat_ciudad
cat_estado
cat_estado_factura
cat_estado_mensaje
cat_estado_pago
cat_pais
cat_rol
cat_tipo_cliente
cat_tipo_token

## Qué más

Para cur_cliente y cur_persona dividir nombre (pues, no es atómico) en primer nombre
segundo nombre, que puede ser null
apellido paterno
apellido materno, puede ser null