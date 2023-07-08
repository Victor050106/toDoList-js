# toDoList-js

Este es un proyecto de To-Do List desarrollado utilizando JavaScript, CSS y endpoints. Proporciona una aplicación web simple que permite a los usuarios crear y administrar sus tareas pendientes. 
 
# Características 
Crear una nueva tarea 
Marcar una tarea como completada 
Eliminar una tarea 
Actualizar una tarea existente 
 
## Tecnologias Usadas
- NodeJs
- Express-Js
- MongoDB
- CSS

## Librerias 
- Moongose
- Dotenv 
- Body Parser
- Nodemon
- Ejs
## Instalacion

1 Clona el repositorio en tu maquina local
```bash
$ git clone git@github.com:Victor050106/toDoList-js.git
```

2 Navega en el directorio del proyecto 
```bash
$ cd Todo_List
```

3 Puedes cambiar el origen del proyecto con los siguientes comand

```bash
$ git remote -v
$ git remote remove origin
$ git remote add origin <nueva_url_del_repositorio>
```

4 Instalar las dependecias necesarias
- Recuerda tener el package.json y el package-lock.json en el root de la carpeta y ejecutas

```bash
$ npm i
```
5 Debe crear un archivo (.env) en la ruta raiz del proyecto y en el crear una variable de entorno llamada (MONGO_DB_URI) y se le agrega la conexion a su cluster de Mongo

## Uso

1 Inicia la app con 
```bash
$ npm start nodemon
```

2 Puedes acceder a ella desde el puerto configurado:

http://localhost:3000

3 Prueba las diferentes rutas disponibles para realizar operaciones CRUD en el ToDo-List
# Estructura del proyecto 
 
El proyecto está estructurado de la siguiente manera: 
 
index.ejs: el archivo ejs principal que contiene la estructura de la página web y carga los archivos CSS y JS necesarios. 
style.css: el archivo CSS que define los estilos de la interfaz de usuario. 
script.js: el archivo JavaScript que contiene la lógica principal del To-Do List. 
index.js: el archivo JavaScript que define los endpoints utilizados para comunicarse con el servidor y realizar operaciones CRUD en las tareas. 
 
# Contribución 
 
Si deseas contribuir a este proyecto, puedes seguir los siguientes pasos: 
 
Haz un fork de este repositorio. 
Crea una rama con la nueva funcionalidad: git checkout -b nueva-funcionalidad 
Realiza los cambios y realiza commit de tus modificaciones: git commit -m "Agrega nueva funcionalidad" 
Envía tus cambios al repositorio remoto: git push origin nueva-funcionalidad 
Abre un pull request en el repositorio original. 
Licencia 
Este proyecto está bajo la Licencia MIT. Puedes ver el archivo de licencia para más detalles. 
 
# Contacto 
Si tienes alguna pregunta o sugerencia acerca de este proyecto, puedes contactarme en vimatoca050106@gmail.com. 
 
¡Gracias por usar nuestro To-Do List! Esperamos que sea útil para ti.
