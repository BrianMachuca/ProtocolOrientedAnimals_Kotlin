# ProtocolOrientedAnimals_Kotlin
Este proyecto en Kotlin muestra el uso de programación orientada a protocolos mediante interfaces para modelar comportamientos de animales como volar, caminar y nadar. Incluye verificación de tipos y ejecución dinámica de métodos según las habilidades implementadas.
EX3

Question 

You are tasked with designing a system to represent different animals and their abilities using protocol-oriented programming in Kotlin. You have three animal types: Bird, Cat, and Fish. These animals can have different abilities, such as flying, walking, and swimming.



Protocols:

Flyable: Defines a fly() function that prints a message indicating the animal is flying.

Walkable: Defines a walk() function that prints a message indicating the animal is walking.

Swimmable: Defines a swim() function that prints a message indicating the animal is swimming.

Animal Types:

Bird: Can fly and walk.

Cat: Can walk.

Fish: Can swim.

Tasks:

Define the Flyable, Walkable, and Swimmable protocols.

Create the Bird, Cat, and Fish structs, conforming to the appropriate protocols.

Create a function animalActions(animals: [Any]) that takes an array of Any and iterates through it.

Inside the animalActions function, use type casting and protocol conformance checks to call the appropriate fly(), walk(), or swim() functions for each animal.

Provide examples of creating instances of Bird, Cat, and Fish, and call the animalActions function with an array containing these instances.
