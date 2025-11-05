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
  - ⏱️**Duración estimada**: 20 - 25 min.

### [Práctica 3.3. Inicio y cierre de bases de datos](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_3.html)
  - **Descripción**: Durante esta práctica, ejecutarás los comandos necesarios para **iniciar y cerrar instancias de base de datos Oracle**, reconociendo los diferentes estados de la instancia (`NOMOUNT`, `MOUNT`, `OPEN`) y los modos de cierre (`NORMAL`, `IMMEDIATE`, `ABORT`). Aprenderás a verificar la conexión del servicio mediante el **Listener** y a interpretar los mensajes del proceso de arranque.
  - ⏱️**Duración estimada**: 25 - 30 min.

### [Práctica 3.4. Visualización de parámetros de inicialización](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_4.html)
  - **Descripción**: Esta práctica te guiará en la consulta e interpretación de los **parámetros de inicialización** de Oracle Database. Aprenderás a distinguir entre parámetros dinámicos y estáticos, identificar su origen (`SPFILE`, `PFILE` o valores por defecto) y comprender cómo influyen en la memoria, la gestión de procesos y el rendimiento general del sistema.
  - ⏱️**Duración estimada**: 40 - 55 min.

### [Práctica 3.5. Copia de SPFILE](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_5.html)
  - **Descripción**: En esta práctica, crearás y gestionarás copias del archivo **SPFILE (Server Parameter File)**, comprendiendo su papel en la configuración de la instancia y el arranque del sistema. Se te guiará en la creación de respaldos, restauración y uso de copias alternativas para iniciar la base de datos en escenarios de mantenimiento o recuperación.
  - ⏱️**Duración estimada**: 30 min.

### [Práctica 3.6. Modificación de parámetros](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo3/Practica3_6.html)
  - **Descripción**: Esta práctica te permitirá experimentar con la **modificación de parámetros del sistema**, aplicando los diferentes alcances disponibles (`MEMORY`, `SPFILE`, `BOTH`) para realizar ajustes temporales o persistentes. Analizarás los efectos de los cambios sobre la instancia en ejecución y aprenderás a validar su persistencia tras el reinicio de la base de datos.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 4.1. Creación de usuarios](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo4/Practica4_1.html)
  - **Descripción**: En esta práctica aprenderás a **crear usuarios en Oracle Database**, asignarles **tablespaces por defecto y temporales** y establecer sus **cuotas de espacio** según las políticas de administración. También configurarás los privilegios básicos de conexión y operación, garantizando un entorno seguro y controlado para cada usuario.
  - ⏱️**Duración estimada**: 30 min.
 
### [Práctica 4.2. Creación y gestión de roles](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo4/Practica4_2.html)
  - **Descripción**: Durante esta práctica, comprenderás cómo **crear, asignar y administrar roles** en Oracle Database. Analizarás su función como mecanismo de agrupación de privilegios y aplicarás buenas prácticas de seguridad para facilitar la **delegación y control centralizado de permisos** entre múltiples usuarios.
  - ⏱️**Duración estimada**: 30 min.

### [Práctica 4.3. Gestión integral de usuarios, roles y cuotas](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo4/Practica4_3.html)
  - **Descripción**: Esta práctica te permitirá **integrar la administración completa de la seguridad** en Oracle 19c, abarcando la creación y verificación de **usuarios, roles, privilegios y cuotas de tablespaces**. Pondrás en práctica la resolución de errores comunes como **ORA-01031** y **ORA-01950**, asegurando que los usuarios cuenten con los privilegios y el espacio necesarios para crear y gestionar sus propios objetos dentro de la base de datos.
  - ⏱️**Duración estimada**: 60 - 75 min.

### [Práctica 5.1. Visualización del espacio de almacenamiento](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_1.html)
  - **Descripción**: En esta práctica, identificarás las **estructuras físicas y lógicas del almacenamiento** en Oracle Database, como tablespaces, datafiles y bloques de datos. Utilizarás vistas del diccionario de datos (`DBA_TABLESPACES`, `DBA_DATA_FILES`, `DBA_SEGMENTS`, entre otras) para **analizar la distribución del espacio**, verificar la **ubicación física de los archivos** y comprender cómo Oracle asigna el almacenamiento a los objetos de usuario.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 5.2. Creación y gestión de tablespaces en Oracle 19c](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_2.html)
  - **Descripción**: En esta práctica, verás la **creación, configuración y administración de tablespaces** en Oracle Database 19c. Configurarás los directorios físicos para los datafiles, crearás tablespaces de distintos tipos (localmente gestionados, temporales y undo), y probarás la **ampliación de espacio** mediante la adición de archivos y la modificación de parámetros de crecimiento automático. También experimentarás con **errores típicos de almacenamiento** (como `ORA-01653`) y sus soluciones.
  - ⏱️**Duración estimada**: 45 min.

### [Práctica 5.3. Extensión del espacio de la base de datos](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_3.html)
  - **Descripción**: Durante esta práctica, aplicarás técnicas para **incrementar la capacidad de almacenamiento** de la base de datos. Aprenderás a **redimensionar datafiles** mediante `ALTER DATABASE DATAFILE RESIZE` y a **agregar nuevos archivos** a un tablespace existente. Se explorarán también los parámetros de **autoextensión (AUTOEXTEND)** y cómo supervisar el crecimiento del espacio utilizado, asegurando un manejo eficiente del almacenamiento físico y lógico.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 5.4. Eliminación de tablespace](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_4.html)
  - **Descripción**: En esta práctica, realizarás la **eliminación controlada de tablespaces** y sus datafiles asociados, garantizando la **liberación segura del espacio en disco**. Analizarás las diferencias entre eliminar un tablespace con o sin sus contenidos (`INCLUDING CONTENTS AND DATAFILES`) y las implicaciones de esta acción sobre el **diccionario de datos**. Finalmente, verificarás la limpieza del entorno y la correcta actualización de las vistas del sistema tras la eliminación.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 5.5. Gestión del Undo Tablespace](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_5.html)
  - **Descripción**: En esta práctica, aprenderás a **gestionar el espacio de `UNDO` en Oracle Database**, identificando los parámetros configurados, el tamaño actual del tablespace `UNDO` y los periodos de mayor actividad. Además, realizarás la **configuración de la retención de `UNDO`** para permitir operaciones de *Flashback* durante 24 horas.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 5.6. Archivos de control en Oracle Database](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_6.html)
  - **Descripción**: En esta práctica, aprenderás a **identificar la función y el contenido del archivo de control (Control File)** en Oracle Database, analizar sus componentes mediante vistas dinámicas y generar respaldos tanto en formato binario como en texto para fines administrativos y de recuperación del sistema.
  - ⏱️**Duración estimada**: 45 min.

### [Práctica 5.7. Redo Logs (grupos y miembros)](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo5/Practica5_7.html)
  - **Descripción**: Identificar, verificar y administrar los **grupos y miembros del Redo Log online** en Oracle 19c, agregando nuevos grupos/miembros.
  - ⏱️**Duración estimada**: 40 - 55 min.

### [Práctica 6.1. Creación de Network Service](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo6/Practica6_1.html)
  - **Descripción**: En esta práctica, crearás y probarás un **nuevo servicio de red (Network Service)** en Oracle Database, utilizando la herramienta **Oracle Net Manager (netmgr)**. Aprenderás a configurar un *Service Naming* que permita establecer conexión a la base de datos local mediante el protocolo **TCP/IP**, validando la comunicación entre cliente y servidor mediante el usuario **HR**.
  - ⏱️**Duración estimada**: 30 min.

### [Práctica 6.2. Creación de un nuevo `LISTENER`](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo6/Practica6_2.html)
  - **Descripción**: En esta práctica, aprenderás a **crear y configurar un nuevo listener en Oracle Database** utilizando la herramienta **Oracle Net Manager (netmgr)**. El Listener es el proceso encargado de gestionar las solicitudes de conexión entre los clientes y la base de datos. Configurarás un listener alterno llamado `LISTENERPRA`, especificando protocolo, host y puerto, y validarás su funcionamiento desde la línea de comandos.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 6.3. Uso del nuevo Listener](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo6/Practica6_3.html)
  - **Descripción**: En esta práctica, aplicarás los conocimientos adquiridos sobre la configuración de listeners en Oracle Database. El objetivo es **asociar la instancia de la base de datos ORCL con el nuevo listener creado previamente (`LISTENERPRA`)**, modificando el parámetro `LOCAL_LISTENER` y verificando la conectividad. Además, dejarás configurado este listener como permanente y probarás su funcionamiento tras reiniciar la base de datos.
  - ⏱️**Duración estimada**: 30 min.

### [Práctica 7.1. Uso de Oracle Data Pump](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo7/Practica7_1.html)
  - **Descripción**: En esta práctica, aprenderás a **utilizar Oracle Data Pump** para exportar e importar objetos de base de datos. Realizarás una exportación completa del esquema **HR**, analizarás los archivos generados (.dmp y .log) y, posteriormente, realizarás la importación de la tabla `EMPLOYEES` hacia otro esquema (`userdp`). Además, reforzarás la comprensión de los **directorios lógicos de Oracle**, los **privilegios de acceso a Data Pump** y las **opciones de remapeo de esquemas**.
  - ⏱️**Duración estimada**: 45 min.

### [Práctica 7.2. Carga de datos con SQL*Loader](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo7/Practica7_2.html)
  - **Descripción**: En esta práctica, aprenderás a **utilizar SQL*Loader** en su modalidad **express y controlada mediante archivo `.ctl`**, para cargar datos desde archivos de texto hacia tablas de Oracle. Ejecutarás scripts de preparación, revisarás archivos de datos (`.dat`), cargarás información en tablas existentes y analizarás los mensajes generados por el proceso, comprendiendo así cómo Oracle maneja la carga masiva de datos desde fuentes externas.
  - ⏱️**Duración estimada**: 45 min.

### [Práctica 8.1. Uso de SQL*Plus](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo8/Practica8_1.html)
  - **Descripción**: En esta práctica, aprenderás a **utilizar la herramienta SQL*Plus** para conectarte a Oracle Database, ejecutar comandos básicos del entorno, personalizar el prompt y el formato de salida y generar reportes legibles a partir de consultas SQL. También practicarás el cambio de sesión entre distintos usuarios y la configuración de parámetros de visualización en SQL*Plus.
  - ⏱️**Duración estimada**: 25 min.

### [Práctica 8.2. Uso de Oracle SQL Developer](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo8/Practica8_2.html)
  - **Descripción**: En esta práctica, aprenderás a **instalar, configurar y utilizar Oracle SQL Developer**, una herramienta gráfica de administración y desarrollo de bases de datos Oracle. Realizarás la configuración inicial del entorno, crearás conexiones hacia la base de datos como administrador y como usuario HR, desbloquearás cuentas bloqueadas si es necesario y ejecutarás operaciones de administración básicas, incluyendo la creación de un **trigger de inicio (startup)**.
  - ⏱️**Duración estimada**: 35 min.

### [Práctica 8.3. Uso de la herramienta ADRCI](https://netecgk.github.io/ORACLE_19c_SQL_ADM_ESS/Capitulo8/Practica8_3.html)
  - **Descripción**: En esta práctica, aprenderás a utilizar la herramienta **ADRCI (Automatic Diagnostic Repository Command Interpreter)**, una utilidad de línea de comandos de Oracle Database que permite administrar el repositorio de diagnósticos (ADR). Explorarás la ubicación de los archivos de traza y alertas, mostrarás problemas e incidentes registrados en la instancia y realizarás tareas de mantenimiento como la **purga de archivos antiguos**.
  - ⏱️**Duración estimada**: 30 min.

---
 
## 📬 **Contacto y más información**
 
Si tienes alguna pregunta o necesitas más detalles, no dudes en [contactarnos](mailto:soporte@netec.com). También puedes encontrar más recursos en nuestra [página](https://netec.com).
 
---
 
¡Gracias por visitar nuestra plataforma! No olvides revisar todos los laboratorios y comenzar tu viaje de aprendizaje hoy mismo.
