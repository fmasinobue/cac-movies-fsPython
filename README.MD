# Pequeño taller de git y github 

La idea es poner en practica lo aprendido y que se rompa lo que se deba romper y entre todos poder solucionarlo, asi que sin miedo, quien guste participar se asegna una tarea, por el hilo de discord.

## Procedimiento
- En el hilo de discord me asigno una tarea, copio el mensaje y pongo mi nombre de discord y el usuario de github (para luego agregarlo como colaborador del repositorio)
- clono el proyectoen mi PC 
```sh
git clone <pegamos url del proyecto>
```
no olvidar cambiar a la carpeta del repo recien clonado !!!
```sh
cd <carpeta-repositorio>
```
- Desde main creo mi rama de trabajo en local
```sh
git branch -C <nombre-rama-trabajo>
```
Y para trabajar en la rama creada no olvidar:
```sh
git checkout <nombre-rama-trabajo>
```
- Si ya llegaste aca es momento de trabajar en la tarea que te asignaste y luego comitear los cambios.
- Para subir estos cambios al repositorio remoto, **no olvidar estos pasos**
    - volver a mi rama main (que es la que subiremos)
    ```sh
    git checkout main
    ```
    - Realizar un git pull para asegurarnos que tenemos la ultima version (Puede pasar que alguien mas haya subido algo nuevo)
    ```sh
    git pull
    ```
    - ahora si mergeamos nuestra rama con main
    ```sh
    git merge <nombre-rama-trabajo>
    ```
    En este paso se pueden generar conflictos, que no sea un dolor de cabeza, sino un desafio, lo resolvemos en local desde nuestro VSC por ejemplo.
    - y ahora si subimos los cambios (Asegurarnos que somos colaboradores!)
    ```sh
    git push origin main
    ```


# Tareas para realizar colaborativamente

Header
- H01 centrar correctamente elementos (Logo y boton) 
- H02 Implementar enlace de tendencia a donde corresponde. 
- H03 Cambiar TALLER GIT a FS Python

Main
- M01 Dejar implementado las leyendas, bien centradas.
- M02 En la seccion de search mejorar un poco lo visual
- M03 Dejar todas las peliculas con el formato correcto (como estan las primeras) y colocar leyendas acorde cuando se brinda la informacion de la peli.

Footer
- F01 eliminar colores de los links que estan demas.

Detail Movie
- D01 Colocar la barra de navegacion que se encuantra mejorada en el index. 
- D02 Quitar bordes en detalles e implementar una publicidad, que sea una imagen random de fondo y una leyenda bien centrada.
- D03 Estilar la seccion del trailer
- D04 implementar el footer siguiendo el del index.  

Otras
- O01 Eliminar archivo pepito.html que no corresponde