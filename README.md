GITHUB EJERCICIOS
<br>
Step 1:</br>
Configurar Git definiendo el nombre del usuario, el correo electrónico y activar el coloreado de la salida. Mostrar la configuración final.

<li> git config --global user.name "Your-Full-Name"</li>
<li>git config --global user.email "your-email-address"</li>
<li>git config --global color.ui auto</li>
<li>git config --list</li>

Solución

![](https://github.com/mercyluz/Libro/blob/main/imagen1.png)
<br>
Step 2: </br>
Crear un repositorio nuevo vacío en Github con el nombre “Libro”.

Desde el terminal:
<li>cd <nombre de la carpeta a la que se quiera acceder> (ejemplo: cd Documents/)<li>
<li> mkdir libro<li>
<li>cd libro<li>
<li>touch .gitignore<li>
<li>touch README.md<li>
<li>git init<li>
<li> ls -la<li>
<li> git add .<li>
<li> git commit -m “initialized repository”<li>
<li> git branch -m main<li>

Conectar el proyecto creado con el repositorio “Libro” de Github creado al principio 


(Instrucciones en Github)
> git remote add origin <la url de tu repositorio>
