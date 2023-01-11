# Ordenamientos
En computación el ordenamiento de datos cumple un rol muy importante, ya sea como un fin en sí o como parte de un proceso más complejo, una prueba de esto, son los métodos de búsqueda que requieren, como entrada, secuencias ordenadas. 

Un ordenamiento es la operación mediante la cual se organizan los elementos de una secuencia, basándonos en un criterio de orden. Entenderemos por criterio de orden al utilizado para establecer una relación binaria sobre la secuencia.
# Instrucciones
Se proporciona un  código base para manipular imágenes, se deben implementar los siguientes ordenamientos:
- Selection Sort
- Insertion Sort
- Merge Sort
- Quick Sort
- Shell Sort 

El programa recibe como argumentos de línea de comandos:
- **Nombre** de la imagen a procesar, esta debe estar en la carpeta *resources* 
- **Velocidad**, número entero que indica cada cuantas iteraciones se actualiza la interfaz gráfica.
- **Algoritmo**, el algoritmo a utilizar para ordenar, las opciones son
	 - [ ] bubble
	 - [ ] selection
	 - [ ] insertion
	 - [ ] merge
	 - [ ] quick
	 - [ ] shell

 
# Repositorio
 Se puede clonar el repositorio usando el comando
 

    git clone https://github.com/vrosalesjaimes/Ordenamientos.git

# Ejecución
Ejecutando desde la carpeta *src*, para ejecutamos el comando

    javac sort/Main.java -d ./class
Para ejecutar usamos el comando

    java sort/Main [nombre_imagen_con_extension] [numero_iteraciones] [ordenamiento]
 Ejemplo:
 

    java sort/Main imagen1 40 insertion
Salida:
![enter image description here](https://github.com/vrosalesjaimes/vrosalesjaimes.github.io/blob/main/assets/images/git/e.png?raw=true)
# 
[![forthebadge](https://forthebadge.com/images/badges/made-with-java.svg)](https://forthebadge.com)
