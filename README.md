<h1>Git y GitHub: 🧩</h1>
<h2>Subir repositorio a GitHub 🌐</h2>
<p>git init</p>
<p>git status</p>
<p>git add .</p>
<p>git status</p>
<p>git commit -m "Primer commit"</p>
<p>git branch -M main</p>
<p>git remote add origin (link de tu repositorio)</p>
<p>git push origin main</p>
<h2>Comandos Git 🖥️</h2>
<ul>
  <li><strong>Inicializar repositorio:</strong><br> git init</li>
  <li><strong>Estado de los archivos:</strong><br> git status</li>
  <li><strong>Añadir archivos:</strong><br> git add ((nombre del archivo) o (.))</li>
  <li><strong>Crear un commit:</strong><br> git commit -m "Nombre del commit"</li>
  <li><strong>Unir el commit actual con el anterior:</strong><br> git commit -amend</li>
  <li><strong>Ver las ramas y la rama activa:</strong><br> git branch</li>
  <li><strong>Crear una rama:</strong><br> git branch (nombre de la nueva rama)</li>
  <li><strong>Cambiar el nombre de la rama principal:</strong><br> git branch -M (nuevo nombre)</li>
  <li><strong>Conectarse a un repositorio remoto:</strong><br> git remote add origin (link del repositorio)</li>
  <li><strong>Enviar el contenido local:</strong><br> git push origin (nombre de la rama)</li>
  <li><strong>Historial de commits:</strong><br> git log</li>
  <li><strong>Cambios de un archivo:</strong><br> git show (nombre del archivo)</li>
  <li><strong>Comparar entre commits:</strong><br> git diff (numero que sale en log) (numero que sale en log)</li>
  <li><strong>Volver a un punto especifico:</strong><br> git checkout (numero que sale en log)</li>
  <li><strong>Resetear a un punto especifico:</strong><br> git reset (numero que sale en log) --hard</li>
  <li><strong>Unir ambas ramas:</strong><br> git merge (nombre de la rama)</li>
  <li><strong>Ver la configuracion del repositorio:</strong><br> git config -l</li>
  <li><strong>Ver mejor las ramas y commits</strong><br> git log --all --graph --decorate --oneline</li>
  <li><strong>Ver interfaz de las ramas y commits</strong><br> gitk</li>
  <li><strong>Crear shortcuts:</strong><br> Alias (nombre del alias)=("Codigo que quiero que se ejecute con el alias")</li>
  <li><strong>Crear tags:</strong><br> git tag -a (nombre del tag) -m "nombre del commit" (numero que sale en log)</li>
  <li><strong>Enviar tags:</strong><br> git push origin --tags</li>
  <li><strong>Borrar tag:</strong><br> git tag -d (nombre del tag)</li>
  <li><strong>Guardar cambios temporales:</strong><br> git stash</li>
  <li><strong>Ver cambios temporales:</strong><br> git stash pop</li>
  <li><strong>Eliminar cambios temporales</strong><br> git stash drop</li>
  <li><strong>Traer un commit de otra rama:</strong><br> git cherry-pick (numero que sale en log)</li>
  <li><strong>Buscar palabra en especifico:</strong><br> git grep -n (palabra que quiero buscar)</li>
</ul>
