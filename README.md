## Datos del alumno
#### Nombre: Isaac Rojano
#### Matricula: AL02903071
#### Carrera: Desarrollo de software
#### Semestre: Sexto semestre

## Datos de la materia
#### Nombre de la materia: Diseño de aplicaciones web
#### Nombre del profesor: Cristopher Gerardo Gaytán Diaz 

## ¿Para que se utiliza Markdown?
#### Markdown es un lenguaje de marcado simple que nos permite agregar formato, vinculos e imaganes con facilidad al texto 

## Opciones de etiquetado que ofrece Markdown

## Encabezados
### Cada "#" representa los distintos tamaños de encabezados que hay, entre mas # haya, mas pequeño sera el texto
# # Hola (Encabezado 1) 
## ## Hola (Encabezado 2) 
### ### Hola (Encabezado 3)
#### #### Hola (Encabezado 4)
##### ##### Hola (Encabezado 5)
###### ###### Hola (Encabezado 6) 

## Citas
### Las citas se generan utilizando el caracter mayor que ">" al comiendo del bloque de texto 
> La verdadera sabiduría está en reconocer la propia ignorancia. - Socrates

## Elementos de linea
### Tendras que envolver las palabras o textos con asteriscos o guiones bajos para enfatizar.

#### Envorlelo con un asterisco o guion bajo nos da cursiva, y envolverlo con asterisco o guien bajo dos veces nos da subraya la palabra 
*cursiva*
**negrita**

## Links 
### Para anañdir enlaces tenemos que escribir entre corchetes [] la palabra enlazada y el link entre parentesis ()
[Youtube](https://www.youtube.com/)

## Imaganes
### Para añadir imagenes con markdown es muy similar que agregar un link, la diferencia es que es con un signo de exclamación "!" al principio
![Youtube](https://www.google.com/search?sca_esv=cbd8017fdac8de0a&rlz=1C1UEAD_esMX1078MX1078&sxsrf=ACQVn0-gSdBeuKCp4Lrxb5OzyOJyWEduuw:1706413108368&q=youtube+logo&tbm=isch&source=lnms&sa=X&sqi=2&ved=2ahUKEwir5KeZlP-DAxVDkiYFHcXQCm4Q0pQJegQIDBAB&biw=2133&bih=1021&dpr=0.9#imgrc=46UtfJyG7qC9_M)

## Comandos en Git

### Verificar el estado de un repositorio local
#### git status

### Agregar archivos individuales o globalmente.
#### git add <archivo> 
#### git add -A

### Agregar comentarios a la confirmación.
#### git commit -m "mensaje de confimracion"

### Cargar sus cambios en el repositorio remoto.
#### git push <nombre-remoto> <nombre-de-tu-rama>

### Crear, explorar y eliminar ramas.
#### Para crear un rama utilice git branch <nombre-de-la-rama>
#### Para explorar una rama utilice git branch
#### Para eliminar una rama utilice git branch -d <nombre-de-la-rama>

### Revertir un repositorio a una confirmación específica.
#### Primero necesitaremos ver nuestro historial de commits, para ver esto utilizar git log--oneline. Ahora solo necesitaremos especificar el codigo de comprobacion que encontraras junto al commit que queremos eliminar, ejemplo: git revert 3321844, para ultimo presionar **shift + q** para salir 