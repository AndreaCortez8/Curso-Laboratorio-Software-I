#Entrega: Laboratorio N°08
####1.	Datos académicos
***Universidad:*** Universidad Nacional de San Antotio Abad del cusco
***Facultad:*** ingenieria electrica, electronica, informatica y mecanica
***Escuela profesional:*** Ingenieria informática y de sistemas
####2.	Docentes
***Docente Tutoria:*** Ing. Roxana Lisette Quintanilla Portugal
***Docente Laboratorio:***** Ing. Vittali Quispe Surco
####3.	Tema
Administracion de tutorias para la carrera de ingenieria informatica y de sistemas de la Universidad de San Antonio Abad del Cusco

####4.	Colaboradores
- Aparicio Castillo Brayan Gustavo
- Cardenas Huaman Fabricio Yared
- Cortez Ccahuantico Paola Andrea
- Mercado Huaycho Adelmecia
- Noa LLascanoa Eliazar 

####5.	Implementado en
Lenguaje: PHP, HTML, MySQL
####6.	Herramientas
XAMPP
Visual Studio Code
Github, Git
sublime

####7.	Introducción
El presente proyecto de desarrollo de software I tiene como finalidad mostrar a alumnos que no se han matriculado por lo tanto no llevan tutoría el semestre actual, también podremos ver a los alumnos repartidos equitativamente en las tutorías y descargar el archivo csv en ambos casos, se explicara el procedimiento de cómo hacer funcionar el programa y se explicara el algoritmo.

####8.	Documentación
- Se realizó el análisis de las funciones y acciones a realizar en el presente proyecto.
- Se evaluan los archivos .csv viendo los tipos de datos de entrada con los que cuenta para trabajar de manera acertiva.
- Se crea la base de datos en el software MySql.
- Se investiga sobre la importación de archivos .csv a la base de datos.
- Se realizan las funciones necesarias para satisfacer con éxito las consultas solicitadas.
- Se investiga sobre las exportaciones de las consultas en tipo .csv.
- Se realiza la refactorización en el código.

####9.	Archivos de entrada

- Docentes.csv
- Matriculados2022-1.csv
- Tutorado2021-2.csv

####10.	Archivos de salida o descarga

- AlumnosNoMatriculados_2022-1.csv
- DistribuciónBalanceadaDeTutoria_2022-1.csv

####11.	Procedimiento
#####1er paso

Encender el xampp en apache y sql para después ir al localhost y luego al phpmyadmin, estando en el phpmyadmin creamos una base de datos llamada “bdtutoria” e importamos el archivo bdtutoria.sql.

#####2do paso

Vaya al localhost y posteriormente a la carpeta en la que guardo los archivos le aparecerá una pantalla, la cual es el interfaz grafico del proyecto.

#####3er paso

Se tienen que cargar los archivos .csv en el respectivo lugar que nos indica el programa, primero nos pedirá que seleccionemos el archivo csv de los alumnos matriculados el cual se llama “Matriculados2022-1.csv”, ya seleccionado el archivo presionaremos el botón rojo que dice “cargar alumnos matriculados” y asi mismo lo haremos con el boton “cargar docentes” seleccionando previamente el archivo “Docentes.csv” y  el botón “cargar tutorias del anterior semestre” seleccionando el archivo “Tutorado2021-2.csv”.

#####4to paso

Tendremos que elegir alguna de las dos opciones la que necesitemos entre “Mostrar alumnos que no serán tutorados en 2022-I” y ”Mostrar distribución balanceada por tutoria”, nos llevara a otra ventana donde podremos ver los resultados de la consulta y además descargar un archivo csv con los datos que necesitamos.
