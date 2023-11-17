## Diferencia entre clase y objeto:
La clase es una plantilla en la que se definen comportamientos y las características a través de métodos y atributos, mientras que los objetos son instancias que siguen el comportamiento dado por la clase. 

## Diferencia entre clase e Interfaz:
Las interfaces definen comportamientos para las clases pero sin implementaciones, son abstracciones. Por otro lado, las clases definen comportamientos también pero para los objetos y sí tienen implementaciones.

## ¿Qué es poliformismo?
Es cuando una referencia se comporta como el objeto al que apunta.
#Ejemplo: 
Podría aplicarse a través de la representación de diferentes diplomados con distintos métodos para evaluar a los estudiantes. Esto permitiría extender el sistema para manejar diferentes diplomados con métodos de evaluación diferentes, ya que solo se necesita crear una nueva clase que implemente una interfaz.

## ¿Qué representan las asocianes en un DC? 
Representa la relación estructurada entre dos o más clases. Proporciona información sobre cómo las clases interactúan entre sí y cómo están relacionadas en el modelo del sistema.
#Ejemplo:
La clase que agrega las calificaciones de los alumnos está relacionada con la clase que hace la conexión a la base de dato para que se guarden las calificaciones de cada alumno.

## Diferencia entre composición vs Agrupación
En la composición hay una relación más fuerte y directa entre el objeto principal y los objetos que lo componen. Mientras que en la agrupación la relación es más simple y general. Los objetos se agrupan en una estructura de datos, pero no hay una dependencia estrecha.

## ¿Qué es encapsulamiento? ¿Qué ventaja representa?
El encapsulamiento es la ocultación de métodos, los cuales pueden ser públicos o privados.
#¿Qué ventaja representa?
Evita que se realicen cambios en los métodos.
#Ejemplo:
Ocultar los detalles internos de las clases y proporcionar una interfaz clara para interactuar con ellas.

## ¿De qué manera se representa la modularidad en POO?
A través de la creación de módulos o unidades independientes que contienen funcionalidades específicas.
#Ejemplo
Dividir el sistema en módulos que gestionan diferentes aspectos, como estudiantes, diplomados y el registro de calificaciones.

## Considera poliformismo ¿Cuál es la diferencia de usar Herencia Vs Interfaces? 
En la herencia se promueven implementaciones (reciben código) y las interfaces promueven abstracciones (métodos abstractos), además de que solo definen comportamientos (qué se hace pero no cómo).
#Ventajas y Desventajas:
Depende de lo que se necesite, la herencia permite pasar tanto métodos como atributos; se pasa todo. Mientras que la interfaz tiene métodos pero no están implementados.
