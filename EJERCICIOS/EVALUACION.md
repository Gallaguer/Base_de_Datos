## Práctica 1.

1. Introducción a base de datos

Objetivo: Identificar el nivel de comprensión de los conceptos de base de datos,
mediante preguntas abiertas.
 
Preguntas:

1. ¿Cuáles son las cinco funciones principales del administrador de bases de datos?
(valor 1.5)

* Definición del esquema; El ABD crea un esquema original de la base de datos escribiendo un conjunto de instrucciones de definición de datos en el LDD.

* Definición de la Estructura y del Método de Acceso.

* Modificación del Esquema y de la Organización Física; Los ABD realizan cambios en el esquema y en la organización física para reflejar las necesidades cambiantes de la organización, o para alterar la organización física para mejorar el rendimiento.

* Concesión de Autorización para el Acceso a los Datos; La concesión de diferentes tipos de autorización permite al administrador de la base de datos determinar a qué partes de la base de datos puede acceder cada usuario. La información de autorización se mantiene en una estructura del sistema especial que el sistema de base de datos consulta cuando se intenta el acceso a los datos en el sistema.

* Mantenimiento Rutinario. Copia de seguridad periódica de la base de datos, bien sobre cinta o sobre servidores remotos, para prevenir la pérdida de datos en caso de desastres como inundaciones.

2. Indíque cinco responsabilidades del sistema gestor de bases de datos (valor 1.5)

* Definición de los datos.
* Manipulación de los datos.
* Establecer y mantener trayectorias de acceso a la BD.
* Respaldo y recuperación.
* Seguridad e integridad.
* Control de concurrencia.
* Consulta y actualización.

3. En una BD al usuario del sistema se le brindarán recursos para realizar diversas
operaciones sobre estos archivos, tales como: (valor 1.5)

* Agregar archivos nuevos en la BD.
* Actualizar, eliminar y obtener datos de archivos existentes.

4. ¿Qué es un Sistema de Información? (valor 1.5)

* Serie ó conjunto de datos que interactúan entre sí con un fin común.
* Entrada, Procesamiento, Almacenamiento y Salida.

## Práctica 2.

2. Diseño de un modelo relacional

Objetivo: Representar desde un modelo entidad relación un problema


Ejercicio:

Tenemos que diseñar una base de datos sobre proveedores y disponemos de la siguiente
información:

Realiza el modelo entidad relación. (valor 6)

Tenemos esta información sobre una cadena editorial:

● La editorial tiene varias sucursales, con su domicilio, teléfono y un código de
sucursal.

● Cada sucursal tiene varios empleados, de los cuales tendremos su nombre,
apellidos, NIF y teléfono. Un empleado trabaja en una única sucursal.

● En cada sucursal se publican varias revistas, de las que almacenaremos su título,
número de registro, periodicidad y tipo.

● Una revista puede ser publicada por varias sucursales.

● La editorial tiene periodistas (que no trabajan en las sucursales) que pueden
escribir artículos para varias revistas. Almacenaremos los mismos datos que para
los empleados, añadiendo su especialidad.

● También es necesario guardar las secciones fijas que tiene cada revista, que
constan de un título y una extensión.

● Para cada revista, almacenaremos información de cada ejemplar, que incluirá la
fecha, número de páginas y el número de ejemplares vendidos.
