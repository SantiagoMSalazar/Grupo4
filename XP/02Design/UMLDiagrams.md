<h1 align="center">
    Escuela Politécnica Nacional<br>
    Facultad de Ingeniería en Sistemas<br>
    Metodologías Ágiles<br>
</h1>

### Grupo: 4

### Integrantes
- Kevin Revelo
- Paúl Román
- Jonathan Salazar
- Santiago Salazar
- Sebastián Sanchez
- Nathaly Simba

# Diagramas UML 
El diagrama de casos de uso mostrado en la Figura 1 permite identificar a los actores que van a interactuar con el sistema y a su vez las funcionalidades con las que deberá contar el sistema. La traducción a español e inglés al ingresar una palabra en sanscrito y la posterior visualización de los morfemas son las funcionalidades con las que el sistema deberá contar. 

<p align="center">
  <img src="assets/UseCaseDiagram.png" alt="Diagrama de casos de uso">
</p>

<p align="center">
  <em>Figura 1: Diagrama de casos de uso del sistema de traducción</em>
</p>

En la Figura 2 se puede apreciar el diagrama de clases del sistema de traducción. Se puede observar que se tendrán dos clases base llamadas morpheme y yogaPosture. Estas dos serán usadas por la clase YogaPostureService, que posteriormente se usará como el elemento "modelo" dentro de un modelo vista controlador. 

Considerando esto, se puede apreciar que la clase YogaPostureController es el nexo entre la vista(clase que se encarga de mostrar los elementos en pantalla) y el modelo(Clase encargada de gestionar los datos y la lógica del negocio).

<p align="center">
  <img src="assets/ClassDiagram.png" alt="Diagrama de clase">
</p>

<p align="center">
  <em>Figura 2: Diagrama de clases del sistema de traducción</em>
</p>