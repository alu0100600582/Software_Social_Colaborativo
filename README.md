# Software Social y Colaborativo

### ¿Qué es el Software Social?

El software social engloba a un conjunto de herramientas de comunicación que facilitan la interacción y colaboración por medio de convenciones sociales.
"Software Social" es una metáfora que hace referencia a métodos de organización que favorecen la integración de las personas, la información, el trabajo y la tecnología (PITT) en una dinámica constructiva, con el fin de prestar un servicio de máxima calidad, independientemente del ámbito de actuación. Con la web 2.0 o Social Media, los últimos avances en la materia son impresionantes y decisivos. El desarrollo de nuevos sistemas de información es fundamental para el control y la utilidad de las organizaciones.

### ¿Qué es el Software Colaborativo?

Software colaborativo o groupware se refiere al conjunto de programas informáticos que integran el trabajo en un sólo proyecto, con muchos usuarios concurrentes, que se encuentran en diversas estaciones de trabajo, conectadas a través de una red.

En su función más básica, las organizaciones establecen equipos tanto para responder a problemas que hayan ocurrido como para prevenir que en primer lugar ocurran.
El término groupware hace referencia a los métodos y herramientas de software que facilitan el trabajo en grupo, mejorando su rendimiento, y contribuyen a que personas que están localizadas en puntos geográficos diferentes puedan trabajar a la vez, ya sea directamente o de forma anónima, a través de las redes.

La colaboración se está convirtiendo en un elemento cada vez más importante en la economía de hoy, el compartir información y conocimiento son componentes vitales de una verdadera relación de colaboración. El groupware busca apoyar el trabajo que se realiza por grupos y equipos, teniendo en cuenta los aspectos de la colaboración que son necesarios para cosechar el máximo de ventajas. Es una herramienta tecnológica muy útil en nuestros tiempos ya que podemos integrar nuestros conocimientos teóricos con la tecnología.

El software colaborativo se puede dividir en tres categorías :
- Herramientas de colaboración-comunicación.
- Herramientas de conferencia
- Herramientas de gestión colaborativa o en grupo.

### Web 2.0

El término Web 2.0 comprende aquellos sitios web que facilitan el compartir información, la interoperabilidad, el diseño centrado en el usuario y la colaboración en la Web.
Un sitio Web 2.0 permite a los usuarios interactuar y colaborar entre sí como creadores de contenido generado por usuarios en una comunidad virtual. Ejemplos de la Web 2.0 son las comunidades web, los servicios web, las aplicaciones Web, los servicios de red social, los servicios de alojamiento de videos, las wikis, blogs, mashups y folcsonomías. Es la evolución de las aplicaciones estáticas a dinámicas donde la colaboración del usuario es necesaria.  

La Web 2.0 no es más que la evolución de la Web o Internet en el que los usuarios dejan de ser usuarios pasivos para convertirse en usuarios activos, que participan y contribuyen en el contenido de la red siendo capaces de dar soporte y formar parte de una sociedad que se informa, comunica y genera conocimiento.

En conclusión, la Web 2.0 nos permite realizar trabajo colaborativo entre varios usuarios o colaboradores.


#### Algunas Herramientas


# [Tutorial Cloud9](https://www.youtube.com/watch?v=hqzOwM8aXdI)

En esta sección vamos a ver una introducción a diversas funcionalidades de la herramienta Cloud9

### [Crear un Espacio de Trabajo (Workspace)](https://www.youtube.com/watch?v=4Qqt1cvjsOc)

En primer lugar para empezar a trabajar en Cloud9 tenemos que crear un Workspace, para ello simplemente vamos a la sección "Create a new workspace" del inicio y ahí configuraremos nuestro Espacio de trabajo.

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/CreateWorkspaces.png)

En esta sección podremos darle nombre y descripción a nuestro proyecto, configurar la privacidad, clonar otro proyecto y establecer la plantilla que queremos para nuestro proyecto.

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/CreateWorkspaces2.png)
![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/CreateWorkspaces3.png)

Una vez creado nuestro Workspace ya podremos empezar a trabajar con nuestra aplicación. Como hemos elegido la plantilla de NodeJS se nos ha generado un servido 'express' para empezar a trabajar con nuestra aplicación.

Cloud9 nos permite ejecutar nuestra aplicación a través de su menú o si lo preferimos por medio de comandos de consola.

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/Inicializacion.png)

La plataforma de Cloud9 nos ofrece la posibilidad de crear nuestra porpia Base de Datos. Como introducción vamos a empezar creando una en MySQL de la siguiente forma:

Desde la Terminal ejecutamos los siguientes comandos para instalar MySQL:

**$ mysql-ctl install**

Esto nos generará una Base de Datos con unos credenciales por defecto que se mostrarán en la Terminal.
Luego de esto ya podremos conectarnos a dicha BBDD y empezar a trabajar con ella a través de comando:

**$ mysql-ctl cli**

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/mysql.png)

### [Compartir un Workspace](https://www.youtube.com/watch?v=k4cC0UntnkI)

Como buena herramienta de Sosftware Colaborativo, Cloud9 nos permite compartir nuestra aplicación con otros usuarios, tanto para un desarrollo conjunto como para simplemente realizar pruebas de desarrollo por usuarios testers. En esta sección vamos a mostrar como realizar cada una de estas opciones.

Para compartir nuestro Entorno de Desarrollo completamente y que otros usuarios puedan desarrollar al mismo tiempo que nosotros podemos realizar uno de los siguientes puntos:

  - Si queremos compartir nuestro proyecto con cualquier persona simplemente tenemos que hacer la URL de nuestro proyecto pública.

  - Si solamente queremos invitar a ciertas personas tenemos que añadirlas en el campo 'Invite people'

  - Y para administrar quién tiene acceso y con que permisos tenemos la sección 'Who has access'

  ![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/compartir.png)


Si en cambio solo queremos que los usuarios prueben o visualicen nuestra aplicación tenemos que poner pública la URL de Preview para que cualquiera pueda acceder o darle permisos de lectura a aquellos usuarios que nosotros deseemos.


### Funcionalidades de un Workspace

En Cloud9 los Espacios de Trabajo poseen muchísimas funcionalidades que nos permiten trabajar libremente con ellos y realizar cualquier tarea que necesitemos.
Entre las funcionalidades más importantes que disponemos podríamos destacar las siguientes:

- **Reseteo de Workspaces**: Podemos resetear nuestro proyecto en cualquier momento como en cualquier otro servidor.

- **Sensitive Data en Workspaces públicos**: Uno de los problemas que nos podría surjir al publicar nuestro Workspace puede ser el de la seguridad (Contraseñas, credenciales, API tokens,etc.)
Para solucionar esto simplemente tenemos que crearnos un directorio en nuestro home en el cuál almacenaremos los datos que no queremos que sean públicos(Sensitive Data).
Lo haríamos de la siguiente manera a través de la Terminal:

  cd ~/

  mkdir sensitive_data

  cd sensitive_data

  echo 'var config = { "db_username": "cloud9", "db_password": "password1234" }; module.exports = config;' > config.js

En este caso estamos almacenando la información que queremos manterner privada en la variable 'config'.
Después de haber creado este fichero, nosotros somos totalemente libres de acceder a esta información pero no las otras personas que accedan a nuestro Workspace.

- **Creación de Workspaces a través de Github y Bitbucket**: Cloud9 nos permite crear Workspaces importando repositorios directamente de Github y Bitbucket. Para ello simplemente tenemos que conectar nuestra cuenta de Github o Bitbucket a la cuenta de Cloud9 y luego desde la sección 'Repositories' clonamos el repositorio que deseemos. Una vez clonado podremos realizar normalmente las operaciones de Git.

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/repos.png)

Como ya vimos en la parte de Compartir un Workspace, Cloud9 permite la colaboración en ramas separadas de Git.

- **Creación de SSH Workspace**: Esta es una de las funcionalidades más útiles que posee Cloud9. Nos permite crear Workspaces SSH a los cuales podemos acceder y trabajar de forma remota a nuestros proyectos.
Para crear este tipo de repositorios simplemente tenemos que marcar la opción 'Remote SSH Workspace' en el menú de creación de Workspace que vimos al inicio y rellenar los campos que nos aparecen.

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/ssh.png)


## Ejecución y Debugging de nuestro código

Cloud9 IDE proporciona la habilidad de ejcutar y depurar nuestro código sin la necesidad de crear un Workspace. En esta guía vamos a mostrar como hacerlo.

### Ejecución

Para ejecutar el código de nuestra aplicación primero tenemos que abrir con Cloud9 el archivo que queramos. Luego de esto tenemos dos opciones para ejecutar nuestra aplicación, que puede ser desde el menú 'Run Panel' o directamente desde el botón 'Run' de la barra de herramientas.

Desde el menú 'Run Panel' tenemos muchas más opciones que simplemente en el botón de 'Run'. Desde este Panel podemos crear y guardar diferentes escenarios para la ejecución de nuestro progama.

### [Debugging](https://www.youtube.com/watch?v=Fg0jJb0n0W4)

El uso del depurador en Cloud9 es muy fácil, al igual que la ejecución, el depurador posee un botón cuando ejecutamos nuestro código que nos permite activar el depurador durante la ejecución de este.

![Alt text](https://github.com/alu0100600582/Software_Social_Colaborativo/blob/master/images/run.png)

Cloud9 permite que se realicen cambios en el código mientra se está depurando y ver los cambios instantáneamente para mostrar las diferencias.


##Despliegue



##Joomla en Cloud9



##[Desarrollo de Wordpress](https://www.youtube.com/watch?v=EdukckFNm2A)




##¡Tu turno!
