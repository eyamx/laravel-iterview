# Prueba técnica Laravel para EYA
Hola, Bienvenido a tu prueba técnica para la vacante como desarrollador en **Laravel**, a continuación encontrarás una serie de requerimientos con los cuales deberás realizar un ejercicio práctico.

La prueba general se divide en pequeños ejercicios con los cuales se evaluará en práctica:
* Pensamiento lógico.
* Resolución de problema.
* Tiempo de desarrollo.
* Otros

> **Importante:** Para el proyecto debes utilizar un proyecto con la instalación del framework **laravel** última versión, es necesario manejar **migraciones, rutas, modelos, controladores**.

> **Extra:** puedes utilizar alguna libreria o framework de diseño para css por ej. Bootstrap, Tailwind etc.

> **Extra:** usar validación en tiempo real con ayuda de Laravel Livewire

Finalizada la prueba recuerda enviar link del proyecto y tu repositorio a tecnologia@eya.mx con tu información de contacto y en el asunto colocar: **DEVELOPER-INTERVIEW-EYA**

## Problema a resolver:

***REQUERIMIENTO 1:** Desarrollar un formulario con los campos que indica el mockup debes crear una tabla de base de datos para guardar los datos de este formulario, tambien es necesario validar los campos previo a guardar la información, despues de guardar los datos mandar un mensaje de confirmación al usuario de que los datos se guardaron correctamente y tambien limpiar el formulario.

![Formulario](/img/screen01.png "Formulario")

***REQUERIMIENTO 2:** Despues de generar el formulario anterior generar la siguiente tabla para visualizar el listado de los datos almacenados

> Sugerencia: usar una url similar a esta **http://<APP_URL>/admin/solicitudes** donde **APP_URL** es la url base de la aplicación

En la tabla se deben mostrar las columnas de todos los datos guardados mostrando en la última columna botones de acciones por cada registro los botones de acciones deben ser:
* Borrar registro
* **Extra:** Editar formulario

> **Extra:** proteger rutas de admin con una cuenta la cual debe ingresar por un formulario de login (email, contraseña)

La tabla se debe mostrar con una paginación de 15 registros por página

Al eliminar un registro de la tabla se debe preguntar al usuario si esta seguro de eliminar el registro

![Tabla](/img/screen02.png "Tabla")

***REQUERIMIENTO 3:** Agregar un campo de texto con el objetivo de poder buscar y filtrar los resultados por **nombre,email,telefono o contenido del paquete**.

**EXTRA REQUERIMIENTO 4:** Si llegaste hasta este punto este requerimiento extra es desplegar tu aplicación en algun servidor como **Heroku** o en cualquier servidor de tu preferencia.

¡Gracias por participar!
