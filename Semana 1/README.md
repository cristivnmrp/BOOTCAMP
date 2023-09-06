<h1> Configurar un repositorio nuevo desde terminal</h1>
<ol>
    <li> git init </li> <!--Inicializa un repositorio vacío en nuestra carpeta-->
    <li> git add . </li> <!-- Agregar archivos nuevos y con cambios a la versión actual -->
    <li> git commit -m "Dejar un mensaje </li> <!-- Crea la versión nueva con los cambios actuales -->
    <li> Ir a Github y crear un repositorio vacío </li> <!-- Inicializa el repositorio en nuestra cuenta de Github-->
    <li> git add remote origin url del git hub vacío https://github.com/usuario/nombre-del-repositorio.git  </li> <!--Enlaza el repositorio de nuestra cuenta con el repositorio de nuestra carpeta -->
     <li> git push -u origin master </li> <!-- Actualiza la versión actual de nuestra carpeta en el repositorio de nuestra cuenta de Github-->
</ol>

<h1> Generar una nueva versión y actualizar el repositorio </h1>
<ol>
    <li> git add . </li>
    <li> git commit -m "Un nuevo mensaje </li> 
    <li> git push -u origin main </li>
