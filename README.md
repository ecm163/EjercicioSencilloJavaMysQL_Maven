# EjercicioSencilloJavaMysQL_Maven

Esta versión implementa -con la herramienta de software Maven- las funcionalidades del EjercicioSencilloJavaMysQL_ver10  guardado en 
este mismo repositorio github que se hizo de una forma más convencional, mediante librerías. 

Tanto ésta versión como la de EjercicioSencilloJavaMysQL_ver10 son un práctica para gestionar bases de datos en MySQL además de implementar interfaces gráficas, 
un login, un generador de informes ... etc. 

A pesar de que no son necesarias, he subido en carpetas las librerías que serían necesarias para realizar éste ejercicio sin Maven.

Para acceder a la aplicación mediante el login:

USUARIO: usuario

CONTRASEÑA: 123

El programa en Java está desarrollado con NetBeans.

La base de datos -llamada sistema- es de tipo localhost. Para realizarla usé mediante XAMPP el phpmyadmin (la dirección http://localhost/phpmyadmin/ en un navegador, y aparte el XAMPP Control Panel abierto con el Apache y MySQL iniciados).

El puerto es en mi caso el habitual, el 3306.

La base de datos que yo cree se llama 'sistema', y dentro de ella cree una tabla (con la que trabaja el programa) llamada 'usuario'.

La tabla usuario tiene 6 columnas: Id, Nombre, Apellidos, Edad, Correo, Fecha.

Para acceder a la base de datos y su tabla yo tengo de nombre de usuario simplemente 'root' y no puse contraseña.

Si desea probarlo con otro puerto (si no es el habitual 3306 para MySQL) y con otro nombre de base de datos, tabla, usuario o contraseña, tendrá que ir al paquete del programa 'modelo', luego a su clase 'Modelo', y ahí en el método 'Conexion()' hacer las modificaciones pertinentes.

El programa se ejecuta desde la clase Pricipal, no desde el JFrame Form Vista.

Hecho por ecm163.

Un saludo.
