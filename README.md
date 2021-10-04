# Template para creación de proyectos de servidor http
### versión 1.0

Proyecto personal para iniciar cualquier proyecto **backend**.  COntiene todo lo necesario:
 - **index.js**: inicia el servidor http y llama al archivo enrutador
 - **package.json**: plantilla básica para JSON con la información mínima del proyecto.
 - **.env.example**: archivo con las constante necesarias según el tipo de backend a realizar
 - **.gitignore**: información para gestor de veriones GIT
 - ***routes***: contiene los archivos necesarios para realizar la enrutación en el servidor.  Hay un archivo ya creado llamado **routes.js** que permite mostrar un archivo html y sus archivos conectados, desde la raiz del servidor.
 - ***public***: contiene los archivos html a ser servidos por el backend, incluyen las carpetas con los archivos css, js e img de los html.
 - ***db***: Servicio de inicialización de objetos *Client* y *Pool* de la librería ***pg*** bajo un patron de diseño *Singleton* para crear instancias únicas de dichos objetos
 - **controllers**: carpeta donde se guardan los controladores necesarios para el manejo del servidor
 - **models**: carpeta donde se guardan los modelos (suelen ser archivos JSON) para la persistencia de la data
 - **files**: carpeta para guardar archivos adicoinales necesarios


 Este es un proyecto en desarrollo y será actualizado cuando aprenda cosas nuevas.

 Realizado por *Darío Valenzuela*, octubre 2021
