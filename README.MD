# Comandos utiles de GIT

# Inicializar repositorio
1- git init

# Prepara el repositorio para salvar alteraciones.
#   --> es como se preparara para una foto.
2 - git add .

# Has con que el repositorio no este preparado para foto
3- git reset .

# Salva las aalteraciones en el respositorio.
#   --> es como decir la foto foi tomana y esta salva
4- git commit -m "mensaje commit"

# Regresa el repositorio al punto del ultimo commit
5- git checkout -- .

# Muestra la identificacion de los commits
6 - git log

# Entra a editar los commit's ejecutados

7- git commit --amend

# Crea rama 
8- git checkout -b nombre de la gama

# cambia de rama
9- git checkout nombre de la rama

# deletar rama
10- git branch -d nombre de la rama

# Subir al repositorio en GITHUB
11- git push

# Uni add y commit en un solo comando
12- git commit -am "mensaje commit"

# Muestrar los cambios que han existidosobre un archivo que es muy util para detectar cuando ciertos cambios, que se rompio y como lo podemos solucionar. pero podemos ser mas detallados.
13- git show

# Muestrar la diferencia entre una version y otra, no necesariamente todos los cambios desde la creacion. (Gif diff commitA commitB)
14- git diff

### Reset y checkout

# Podemos volver a cualquier version anterior de un archivo especifico o incluso de nuestro proyecto entero, Esta es tambien la forma de movernos entre ramas
15 - git checkout + Id del commit

# commit descriptico con cantidad de lineas agregadas y removiadas por archuvo
15- git log --stat

# Mantienen los arcchivos en area de Stating para que podamos aplicar nuestos ultimo cambios desde un commit anterior
16- git reset -- soft 'commit'

# Borra toda la informacion que tengamos en el area de Staging (Periendo todo para siempre)
17- git reset --hard 'commit'

# Volvermos a la verdios madre
18- git checkout master 'archivo.txt'#   G i t H u b  
 