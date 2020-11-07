# Codepen en local

Repositorio con ejercicios de frontend utilizando recursos en local para trabajar rápido y offline.

## Recursos
+ Visual Studio Code
  + Live server
  + Live SASS Compiler
+ ~~NPM~~

## Workflow
Actualizar y versionar cada ejercicio en el repositorio local y en Github en el día a día.

##### Crear nuevo ejercicio
1. Ubicarme en la carpeta playground
2. `mkdir nombre-ejercicio`
3. `cd nombre-ejercicio`
4. `touch index.html style.scss README.md`

##### Control de versiones
1. Ubicarme en la carpeta Playground con `cd ..`
2. `git status`
3. `git add .`
4. `git commit -m "-Nombre de carpeta- agregado"`
5. `git push`

## Mobile
La extensión **Live server** nos permite, por medio de la IP V4 de la PC y el puerto asignado, conectarnos desde el navegador del celular y poder probar los diseños en vivo. Cualquier cambio en el codigo se ve reflejado en el movil :)
En el caso de KDE Neon con la aplicación **Network interfaces** podemos acceder a la información de la IP.
Al mismo tiempo, utilizando el comando `ifconfig` en la terminal podriamos obtener la información referente a la IP. En mi caso no pude utilizar este comando :( 
**FUENTE:**
+ https://github.com/ritwickdey/vscode-live-server/blob/master/docs/faqs.md#how-to-access-the-server-from-mobile
+ https://www.kdeblog.com/como-saber-la-ip-de-tu-ordenador-en-linux.html

### TODO
+ Armar Área de Trabajo con plugins en VSCode para este tipo de ejercicios.
+ 
