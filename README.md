# ecommerce-api

a [Sails v1](https://sailsjs.com) application


### Links

+ [Sails framework documentation](https://sailsjs.com/get-started)
+ [Version notes / upgrading](https://sailsjs.com/documentation/upgrading)
+ [Deployment tips](https://sailsjs.com/documentation/concepts/deployment)
+ [Community support options](https://sailsjs.com/support)
+ [Professional / enterprise options](https://sailsjs.com/enterprise)


### Version info

This app was originally generated on Sat Aug 13 2022 01:22:23 GMT-0300 (hora estándar de Argentina) using Sails v1.5.3.

<!-- Internally, Sails used [`sails-generate@2.0.7`](https://github.com/balderdashy/sails-generate/tree/v2.0.7/lib/core-generators/new). -->



<!--
Note:  Generators are usually run using the globally-installed `sails` CLI (command-line interface).  This CLI version is _environment-specific_ rather than app-specific, thus over time, as a project's dependencies are upgraded or the project is worked on by different developers on different computers using different versions of Node.js, the Sails dependency in its package.json file may differ from the globally-installed Sails CLI release it was originally generated with.  (Be sure to always check out the relevant [upgrading guides](https://sailsjs.com/upgrading) before upgrading the version of Sails used by your app.  If you're stuck, [get help here](https://sailsjs.com/support).)
-->
<hr>
<br>
## Desafío: clase 46: Reformar para usar otro framework
#### Como ejecutar el programa en su computadora:

Una vez descargado o clonado y descomprimido, ingresar a la carpeta del proyecto y escribir `npm install` para instalar todas las dependencias.
Luego iniciar el servidor escribiendo `sails lift`.

* Para las pruebas se seleccionó el framework `Sails` y se hicieron pruebas con la entidad `Users` cuyos campos son: `email`, `username` y `password`.

* Para la persistencia de datos se eligió `MongoDB Atlas`.

Utilizando la extensión Thunder Client de VS Code se probaron los endpoints que forman el CRUD.

* Listar Usuarios:
<img src="/assets/images/screenshots/get_users.jpg" alt="create_user"/>

* Crear Usuario:
<img src="/assets/images/screenshots/create_user.jpg" alt="create_user"/>

* Actualizar Usuario:
<img src="/assets/images/screenshots/put_users.jpg" alt="create_user"/>

* Borrar Usuario:
<img src="/assets/images/screenshots/delete_user.jpg" alt="create_user"/>

* Vista de ejemplo en MongoDB Atlas usando `Compass`
<img src="/assets/images/screenshots/mongo_atlas.jpg" alt="create_user"/>
