# PUZZLE "El salto del caballo"
## DESCRIPCIÓN DEL CONTENIDO
Este es un puzzle clásico en para poder desarrollar la estrategia y el pensamiento algorítmico. Este puzzle, se presenta bajo la siguiente premisa: 
>*"Un recorrido del caballo es una secuencia de saltos, sin repetir casillas, desde una casilla inicial hasta otra final, desde la cual no se puede avanzar, sin pasar por una casilla ya visitada."*

Para poder desarrollar este proyecto se han utilizado lenguajes html, css y javascript; además de la utilización de Git y GitHub.
### CÓDIGO
#### HTML
Dado que se están desarrollando las lecciones de DOM, existen elementos HTML generados de manera dinámica desde código JS; por lo que esencialmente con los botones e input a interactuar. Dadas las condiciones de el puzzle, se han generado 3 botones esenciales para la interacción con el usuario; y un input de tipo texto para poder imprimir un tablero de lados iguales, por lo que se obtuvo el siguiente código HTML : 
```html
  <div class="game">
            <h3>Disfrútalo :)</h3>
            <p>Número de lados
                <input type='number' id="lados" />
                <button id='ejecutar'>Generar Tabla</button><br/>
                <button id='btnMostrar'>Solución Completa</button>
                <button id="btnSolucion">Paso a Paso</button>
            </p>
        </div>
        <div id="tablero" align="center">
        </div>
```
#### CSS
Para CSS, se enfatizó en el diseño de los botones, y sus efects necesarios para que la interacción con el usuario sea muchísimo mas óptima.
#### JAVASCRIPT
Ya que es un algoritmo lógico, el aspecto mas resaltante en este tema; es la heuristica utilizada. Adicionalmente, la interacción con los usuarios estaría definida de la siguiente forma:
  * Generar Tabla: En tal caso, se genera un tabla vacía, ya que solo se deben mostrar el tablero.
  * Solución Completa: Muestra, el tablero lleno y resuelto.
  * Paso a Paso: Desarrolla una solución completa colocando los ítems numéricos en las respectivas casillas.

Finalmente *alerta "Eureka"* al terminar todos los paso y pasa a una siguiente solución.
### GIT Y GITHUB
Como primer paso, se organizaron de manera local las carpetas a trabajar.
Seguidamente, se creó un *nuevo repositorio* en **GitHub** con el nombre de *"domII"* incializandose con un ***README.md***, al crearlo se copió la URL del mismo.
Se ingresaron las siguientes comandos de **Git** en la terminal:

```Git
git init
git remote add origin "https://github.com/luisaGonzales/doomII.git"
git pull origin master
git add .
git commit -m "	
1. Subiendo archivos iniciales y código base"
git push origin master
```
Después de cada modificación se utilizaron los siguientes comandos:

```git
git status
git add <archivo modificado>
git commit -m "mensaje pertinente"
git status
git push origin master
```
