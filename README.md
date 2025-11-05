<img src="images/neteclogo.png" alt="logo" width="300"/>
 
# Base de Datos Oracle: SQL y Administración
 
## Plataforma de laboratorios
 
Te damos la bienvenida a la **plataforma de laboratorios** del curso **Base de Datos Oracle: SQL y Administración**. Aquí podrás explorar diferentes tecnologías a través de prácticas guiadas. ¡Desarrolla tus habilidades y lleva tus conocimientos al siguiente nivel!
 
## Lista de laboratorios
 
Cada uno de estos laboratorios está diseñado para ofrecerte una experiencia práctica. Haz clic en los enlaces para comenzar.
 
### [Práctica 1.1. Acceso al entorno de Curso](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo1/Practica1_1.html) 
  - **Descripción**: comprobar el acceso y funcionamiento del entorno asignado para el curso, validando el inicio de sesión, la apertura de terminal, los permisos de usuario y las características básicas del sistema operativo Oracle Linux.
  - ⏱️ **Duración estimada**: 20 min.

### [Práctica 1.2. SQL Básicos](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo1/Practica1_2.html)
  - **Descripción**: en esta práctica se ejecutarán consultas SQL básicas sobre el esquema HR. El participante aprenderá a aplicar filtros y operadores lógicos, utilizar variables de sustitución (`&` y `&&`) y manejar correctamente los valores `NULL` dentro de las consultas, comprendiendo su impacto en los resultados.
  - ⏱️ **Duración estimada**: 60 - 80 min.

### [Práctica 1.3. Funciones de una sola fila, fechas y conversión](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo1/Practica1_3.html) 
  - **Descripción**: durante esta práctica se trabajará con funciones de una sola fila, incluyendo funciones de carácter, número y fecha. El participante aplicará funciones de conversión (`TO_CHAR`, `TO_DATE`, `TO_NUMBER`) con *format models*, utilizará funciones para el manejo de valores nulos (`NVL`, `NVL2`, `NULLIF`, `COALESCE`), y comprenderá cómo anidar funciones manteniendo el tipo de dato resultante. Además, realizará operaciones aritméticas con fechas y usará funciones de calendario (`ADD_MONTHS`, `NEXT_DAY`) considerando el parámetro regional (`NLS_TERRITORY`) y las diferencias entre los formatos `YY` y `RR`.
  - ⏱️ **Duración estimada**: 90 - 110 min.
 
### [Práctica 1.4. Agregación y operadores de conjuntos](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo1/Practica1_4.html)
  - **Descripción**: en esta práctica se aplicarán funciones de grupo y operadores de conjunto utilizando el esquema HR. El participante ejecutará consultas que incluyan `GROUP BY` y `HAVING`, comparará los resultados entre `UNION`, `UNION ALL`, `INTERSECT` y `MINUS`, y aprenderá a evitar errores comunes de agrupamiento (`ORA-00979`) eligiendo el operador o función más adecuada según el caso..
  - ⏱️ **Duración estimada**: 70 min.

### [Práctica 1.5. Joins en Oracle SQL](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo1/Practica1_5.html)
  - **Descripción**: Esta práctica se enfoca en el uso de diferentes tipos de `JOIN` para combinar datos de múltiples tablas dentro del esquema HR. El participante construirá consultas utilizando `NATURAL JOIN`, `USING`, `ON`, así como equijoins, outer joins (`LEFT`, `RIGHT`, `FULL`), el producto cartesiano y el **self join** con uso obligatorio de alias, comprendiendo cuándo y cómo aplicar cada uno según la relación entre las tablas.
  - ⏱️ **Duración estimada**: 70 - 85 min.

### [Práctica 1.6. Subqueries](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo1/Practica1_6.html) 
  - **Descripción**: A lo largo de esta práctica se desarrollarán consultas SQL que incorporen subconsultas básicas y correlacionadas. El participante aplicará los predicados `IN`, `EXISTS`, `ANY` y `ALL`, analizará el comportamiento de las subconsultas en distintos contextos y aprenderá a interpretar correctamente su semántica y cardinalidad para optimizar el resultado de las consultas.
  - ⏱️ **Duración estimada**: 60 min.

### [Práctica 2.1. Usando DML para gestionar datos y transacciones](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo2/Practica2_1.html)
  - **Descripción**: En esta práctica construirás una tabla temporal basada en el esquema HR para **insertar**, **actualizar** y **eliminar** registros. Aprenderás a **confirmar** (`COMMIT`) y **revertir** (`ROLLBACK`) cambios, así como a establecer **puntos de guardado** (`SAVEPOINT`) para controlar el flujo de una transacción. El objetivo es que domines el ciclo completo de trabajo con **DML** en Oracle (`INSERT`/`UPDATE`/`DELETE` + control transaccional), empleando **variables de sustitución** para crear scripts reutilizables.
  - ⏱️**Duración estimada**: 55 - 70 min.

### [Práctica 2.2. Usando DDL para definir y modificar estructuras de tablas](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo2/Practica2_2.html)
  - **Descripción**: En esta práctica explorarás los principales comandos **DDL (Data Definition Language)** de Oracle, que permiten **crear, modificar y eliminar objetos** en la base de datos. Aprenderás a construir tablas desde cero, duplicar estructuras existentes, agregar y eliminar columnas, establecer restricciones básicas y eliminar objetos de forma segura. También practicarás cómo cambiar el estado de una tabla a **solo lectura (`READ ONLY`)** para evitar modificaciones temporales.
  - ⏱️**Duración estimada**: 60 - 75 min.

### [Práctica 3.1. Quiz](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_1.html)
  - **Descripción**: Esta práctica te permitirá consolidar los conceptos teóricos relacionados con la administración de bases de datos Oracle mediante un breve cuestionario. Servirá como diagnóstico previo para medir tu comprensión sobre instancias, estructuras de almacenamiento, archivos de control y parámetros iniciales antes de realizar las prácticas técnicas del capítulo.
  - ⏱️**Duración estimada**: 15 min.

### [Práctica 3.2. Conexión a la base de datos con SQL*Plus](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_2.html)
  - **Descripción**: En esta práctica establecerás conexión con una base de datos Oracle utilizando **SQL*Plus**, explorando los diferentes modos de acceso (local y remoto) y verificando las variables de entorno que intervienen en la conexión. También identificarás el estado de la instancia y los elementos clave del entorno de trabajo..
  - ⏱️**Duración estimada**: xx min.

### Práctica 3.3. Inicio y cierre de bases de datos](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_3.html)
  - **Descripción**: Durante esta práctica, ejecutarás los comandos necesarios para **iniciar y cerrar instancias de base de datos Oracle**, reconociendo los diferentes estados de la instancia (`NOMOUNT`, `MOUNT`, `OPEN`) y los modos de cierre (`NORMAL`, `IMMEDIATE`, `ABORT`). Aprenderás a verificar la conexión del servicio mediante el **Listener** y a interpretar los mensajes del proceso de arranque.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_4.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_5.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_6.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo4/Practica4_1.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.
 
### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo4/Practica4_2.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo4/Practica4_3.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_1.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_2.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_3.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_4.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_5.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_6.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_7.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo6/Practica6_1.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo6/Practica6_2.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo6/Practica6_3.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo7/Practica7_1.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo7/Practica7_2.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](*https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo8/Practica8_1.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo8/Practica8_2.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

### [Práctica 3. Nombre de la práctica](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo8/Practica8_3.html)
  - **Descripción**: xxx.
  - ⏱️**Duración estimada**: xx min.

---
 
## 📬 **Contacto y más información**
 
Si tienes alguna pregunta o necesitas más detalles, no dudes en [contactarnos](mailto:soporte@netec.com). También puedes encontrar más recursos en nuestra [página](https://netec.com).
 
---
 
¡Gracias por visitar nuestra plataforma! No olvides revisar todos los laboratorios y comenzar tu viaje de aprendizaje hoy mismo.
