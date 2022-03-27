1-crea un repositorio en un disco local en mi caso lo guarde en el C:
2-dentro de c creamos una carpeta llamado repositorio con mkdir
3-entramos en repositorio
4-ejecutamos el comando git init para inicializar el repositorio
5-creamos 3 archivos el index.html index.js y README.MD . Dentro de los index ya que es una prueba ponemos un html corto y un <script> en index.js
6-luego usamos el comando git add a los dos index
7-luego en README.MD iremos escribiendo los pasos a medida de como a vanzamos en el proyecto (como hago ahora mismo) asi que cada vez que escriba algo nuevo en cualquier archivo tenenmos que usasr el comando git add 
8-despues de esto iniciamos "sesion de git hub" poniendo nuestras credenciales con los comandos: para el usuario: git config --global user.name "Dnnish"  el correo: git config -- user.email "hectorchirinos@estudiante.edib.es"
9-ahora con las credenciales ya puestas nos dejara añadir comentarios cada vez que queramos con el comando git commit -m "comentario de la version"
10-y para ver que se añadio correctamente y para ver una lista de todas las veces que hemos hecho una version usamos el comando git log
11-Ahora creamos un nuevo proyecto en gitlab y mediante el comando git remote add origin https://gitlab.com/nombre_de_tu_usuario/nombre_de_tu_repositorio.git lo enlazamos con gitlab
12-y por ultimo con el comando git push -u origin main aparecera una ventana para poder logearnos y lo enlazamos
--Recomendable cada vez que hagamos un paso usemos el comando git status para comprobar que todo esta bien--
