
# Aplicación CRUD de PHP

Este repositorio contiene una aplicación PHP CRUD (Create, Read, Update, Delete) o en español (Creacion, leer, Actualizar, Eliminar) simple. Es una demostración básica de cómo integrar PHP con una base de datos MySQL para gestionar datos de usuarios. La aplicación permite a los usuarios agregar, ver, editar y eliminar información de usuario. Esta demostración no solo ofrece un vistazo a cómo integrar PHP con una base de datos MySQL, sino que también sirve como un punto de partida sólido para entender la interacción entre el servidor y la base de datos.

# Ejemplo

Es esencial para garantizar la integridad de la información y prevenir vulnerabilidades como la inyección SQL. En este contexto, se destacan técnicas como la validación de formularios, donde herramientas como filter_input() o bibliotecas como Valitron desempeñan un papel crucial.
![download](https://github.com/PFLC/624-crus-basicos-Carlosmoramx/assets/114203404/926aa24d-bf5d-4c2e-b049-e76e642f8bb9) 


## Tecnologías Utilizadas

-PHP: Es el lenguaje de script del lado del servidor por excelencia en el desarrollo web. Su versatilidad y robustez lo convierten en una opción ideal para manejar la lógica del servidor y la interacción con la base de datos de manera eficiente y segura.

-MySQL: Como sistema de gestión de base de datos relacional, MySQL ofrece un entorno confiable y escalable para almacenar y gestionar los datos de los usuarios. Su amplia adopción y su sólido rendimiento lo convierten en una opción popular entre los desarrolladores web.

-HTML & CSS: Estas tecnologías son la piedra angular de la web moderna. HTML proporciona la estructura básica de las páginas web, mientras que CSS se encarga de dar estilo y mejorar la experiencia visual del usuario. Juntos, forman la base sobre la cual se construyen interfaces de usuario atractivas y funcionales.

-Tailwind CSS: Este framework de CSS utilitario ofrece una forma innovadora y eficiente de diseñar interfaces de usuario. Al proporcionar una serie de clases prediseñadas que se pueden aplicar directamente en el HTML, Tailwind CSS agiliza el proceso de desarrollo y facilita la creación de diseños consistentes y estilizados.

## Páginas y Funcionalidades

### 1. Página de Inicio (`display.php`)

![Página de Inicio](images/display.png)

- La página de inicio sirve como punto de entrada a la aplicación. Aquí, los usuarios pueden encontrar una descripción general de la aplicación y enlaces a otras secciones importantes.
**Funcionalidades**
-Presentación de la aplicación y su propósito.
-Enlaces rápidos a las funciones principales, como agregar, ver, editar y eliminar usuarios.

### 2. Agregar Usuario (`user.php`)

![Agregar Usuario](images/add.png)

-Esta página muestra una lista completa de todos los usuarios almacenados en la base de datos.
**Funcionalidades**
-Visualización de todos los usuarios con detalles básicos como nombre, correo electrónico, etc.
-Opciones para ordenar y filtrar la lista de usuarios según diferentes criterios, como nombre o fecha de registro.
### 3. Editar Usuario (`edit.php`)

![Editar Usuario](images/edit.png)

-Al hacer clic en un usuario específico en la lista, los usuarios son redirigidos a una página de detalles que muestra información más detallada sobre ese usuario.
**Funcionalidades**
-Visualización detallada de la información del usuario, incluidos datos como nombre completo, correo electrónico, fecha de registro, etc.
-Opción para volver a la lista de usuarios o editar los detalles del usuario.

### 4. Eliminar Usuario (`delete.php`)

-Proporciona una interfaz para que los usuarios eliminen registros de usuarios de la base de datos.
**Funcionalidades**
-Confirmación de eliminación para evitar eliminaciones accidentales.
-Acción de eliminación segura que borra el registro seleccionado de la base de datos.

## Conexión a la Base de Datos (`connect.php`)

- **Propósito:** Establece una conexión con la base de datos MySQL.
- **Credenciales:** Utiliza nombre de host, nombre de usuario, contraseña y nombre de la base de datos para la conexión.

## Cómo Ejecutar

**Clonar el Repositorio**
Descarga o clona el repositorio de la aplicación en tu máquina local. Puedes hacerlo utilizando Git con el siguiente comando:
bash
Copy code
git clone <URL_del_repositorio>
También puedes descargar el código fuente como un archivo ZIP y descomprimirlo en tu máquina.

**Configurar un Entorno PHP y MySQL**
Para ejecutar la aplicación, necesitarás tener un entorno de desarrollo local configurado con PHP y MySQL. Una opción popular es XAMPP, que proporciona un paquete todo en uno que incluye Apache, MySQL, PHP y phpMyAdmin.
Descarga e instala XAMPP desde su sitio web oficial, siguiendo las instrucciones de instalación para tu sistema operativo específico.

**Crear la Base de Datos**
Una vez que tengas XAMPP instalado y ejecutándose, abre tu navegador web y navega a phpMyAdmin. Por lo general, puedes acceder a phpMyAdmin escribiendo http://localhost/phpmyadmin en la barra de direcciones.
Inicia sesión en phpMyAdmin con tus credenciales (por defecto, el nombre de usuario es "root" y la contraseña está en blanco).
Crea una nueva base de datos para la aplicación PHP CRUD. Puedes hacerlo haciendo clic en el enlace "Base de datos" en la barra de navegación y proporcionando un nombre para la nueva base de datos.

**Ejecutar la Aplicación en un Servidor Local**
Copia los archivos de la aplicación PHP CRUD en el directorio raíz de tu servidor web local. En XAMPP, este directorio suele ser htdocs.
Abre tu navegador web y navega a la URL de tu servidor local, por ejemplo, http://localhost/nombre_de_la_aplicacion.
Si todo está configurado correctamente, deberías ver la página de inicio de la aplicación PHP CRUD y poder comenzar a utilizarla para agregar, ver, editar y eliminar información de usuario.

## Nota de Seguridad

Esta aplicación es una demostración básica y no implementa medidas avanzadas de seguridad. Es recomendable utilizar declaraciones preparadas (prepared statements) u ORM para las interacciones con la base de datos para prevenir ataques de inyección SQL.

---

Siéntete libre de contribuir a este proyecto o sugerir mejoras. Para cualquier consulta o problema, por favor abre un issue en este repositorio.

