/***********************
  Utilizando terminal
************************/

Desde el directorio 'src':

-)  Compilar con:
      javac sort/Main.java

-)  Correr con:
      java sort/Main <archivo de resource> <velocidad> <algoritmo>

    <archivo de resource> = Nombre de archivo de imagen a procesar, debe encontrarse en la carpeta 'resource'
    <velocidad> = Numero de iteraciones que ocurrirán antes de hacer un update a la interfaz grafica
    <algoritmo> = Algoritmo de ordenamiento a utilizar, puede ser 'bubble', 'selection', 'insertion', 'merge', 'quick'

    Por ejemplo:
      java sort/Main Imagen1.jpg 30 bubble
      java sort/Main Imagen2.jpg 100 bubble

