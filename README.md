# Data Lovers
​
## Índice
​
* [1. Definición del producto ](#1-definición-del-producto)
* [2. Historias de usuario](#2-Historias-usuario)
* [3. Diseño de la Interfaz de Usuario](#3-Diseño-de-la-Interfaz-de-Usuario)
* [4. Testeos de usabilidad](#4-Testeos-de-usabilidad)
* [5. Implementación de la Interfaz de Usuario (HTML/CSS/JS)](#5-Implementación-de-la-Interfaz-de-Usuario-(HTML/CSS/JS))
* [6. Pruebas unitarias](#6-Pruebas-unitarias)
​
***
## 1. Definición del producto
​
Candy López y Liliana Hernández diseñamos un producto con el cual tanto fans y no fans 
puedan consultar las películas, los personajes y algunos datos curiosos de Studios Ghibli.
​
Elegimos Studios Ghibli ya que nos consideramos fans de sus películas.
​
Acordamos que la interfaz de usuario fuera sencilla, amigable, para que con pocos elementos logremos mostrar toda la información demandada por nuestras historias de usuarios.
​
## 2. Historias de usuario
​
![historias](src/image/HistoriasdeUsuario.JPG)
![historias1](src/image/HistoriasdeUsuario1.JPG)
![historias2](src/image/HistoriasdeUsuario2.JPG)
![historias3](src/image/HistoriasdeUsuario3.JPG)
​
​
### 3. Diseño de la Interfaz de Usuario
​
### Prototipo de baja fidelidad
​
![p_bajafidelidad1](src/image/Prototipobajafidelidad1.JPG)
![p_bajafidelidad1](src/image/Prototipobajafidelidad2.JPG)
​
### Prototipo de alta fidelidad
​
![p_altafidelidad1](src/image/Prototipoaltafidelidad1.JPG)
![p_altafidelidad2](src/image/Prototipoaltafidelidad2.JPG)
![p_altafidelidad3](src/image/Prototipoaltafidelidad3.JPG)
![p_altafidelidad4](src/image/Prototipoaltafidelidad4.JPG)
​
​
​
#### 4. Testeos de usabilidad
​
A lo largo del desarrollo de nuestra interfaz llevamos a cabo distintos testeos de usabilidad, a continuación 
​
a) Testeo de página la cual contenía solamente el listado de las películas.
Hallazgos. El usuario nos indica que la navegación es complicada ya que solamente mostramos todas las películas pero no hay ninguna interacción con las mismas.A
Mejora. Se implementó un carrusel para mejorar  la navegación.
​
b) Testeo de página con el contenido de personajes.
Hallazgos. El usuario detectó que los filtros contenidos en esta página no funcionaban de manera correcta.
Mejora. Se agregaron condiciones if/elseif dentro de las funciones para poder navegar correctamente por los filtros.
Se agregó botón de scroll para navegar de manera más sencilla todos los personajes.
​
c) Testeo de página ToPCinco.
Hallazgos. El usuario indica que la página tiene poco contenido.
Mejora. Se cambió de nombre la página por Datos Ghibli en la cual agregamos una gráfica con la recurrencia de participación de un director en las distintas películas.
​
##### 5. Implementación de la Interfaz de Usuario (HTML/CSS/JS)
​
En el siguiente link se encuentra publicada nuestra interfaz de usuario.
[Interfaz](https://candycoding.github.io/CDMX012-data-lovers/src/)
​
​
###### 6. Pruebas unitarias
​
Se generó archivo data.spec.js, con el cual llevamos a cabo pruebas unitarias de las funciones implementadas dentro de main.js.
​
Nuestras pruebas unitarias superaron la cobertura requerida para el presente proyecto.
​
![Test](src/image/CapturaPantalla.png)