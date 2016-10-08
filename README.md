# Tutorial para crear R packages

Este repo contiene un tutorial que muestra el proceso de creación de un R package que sirva de apoyo para una asignatura en la que se use R.  El tutorial se preparó para las 8 Jornadas de Usuarios de R (Albacete 2016)

## Objetivo 

El objetivo es mostrar el proceso de creación de un R package "sencillo" de forma "sencilla". 


Sí, crear un R package sencillo pero funcional que sirva para distribuir los materiales docentes de un curso en el que se usa R. El package se alojará en Github para facilitar su instalación.  

El package contendrá lo siguiente:

- 2 funciones (con su correspondiente documentación)  

- Una de las 2 funciones usará funciones de otro(s) package, así que habrá que importar esa función a nuestro package

- 2 ficheros de datos  

- Un archivo con documentación más extensa (vignette), donde se podrían incluir los scripts a usar en los ejercicios/prácticas de clase


Se hará de la forma más rápida y simple, que a mi juicio es usando un "Rproject de RStudio" y el package `devtools`. Gestionar todo en un `Rproject` facilita muchos las cosas, sobre todo cuando más adelante subamos nuestro package a Gitbub. `devtools` es un package desarrollado por Hadley Wickham que sirve para crear R packages, facilita mucho la tarea de crear y gestionar packages.



Es imposible en 20 minutos explicarlo todo, así que seré fundamentalmente práctico: me centraré en el proceso de creación. Es evidente que para entender muchos/todos los detalles y posibilidades en la creación de un package hay que leer algunas referencias. Al final de este tutorial daré referencias donde se explica con distinto nivel de detalle el proceso de creación de un R package.   


El tutorial para crear el package puede verse [aquí](./tutorial_creacion_R_package.md)  o [aquí](https://perezp44.github.io/pkg4albacete/)

Finalmente el repo del que se habla en este tutorial se alojó en Github en <https://perezp44.github.io/pkg4albacete/>
