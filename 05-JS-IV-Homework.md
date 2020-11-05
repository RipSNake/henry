# Homework: Javascript IV

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

* Objetos: un objeto es un elemento con una serie de caracteristicas (propiedades) y metodos (funciones internas del objeto) que nos sirven para mimetizar nuestra realidad en forma de codigo. Por ejemplo para representar un persona podemos crear un objeto que se llame persona y que tenga caracteristica nombres, apellido, edad, etc.


* Propiedades: las propiedades vendrían a ser como las características del objeto. Por ejemplo si tenemos un objeto "moto" alguna sde sus caracteristicas podrían ser ruedas, color, cilindrada.

* Métodos: son funciones internas de los objetos. Por ejemplo: en un objeto "moto" un metodo podría ser "encender()"

* Bucle `for…in`: sirve para iterar dentro de las propiedades de un objeto y en cada nueva al igual que en el bucle for

* Notación de puntos vs notación de corchetes: son dos formas distintas de acceder a las propiedades o métodos de un objeto. La diferencia principal es que con la notación de corchetes podemos acceder a las propiedades usando variables. Ejemplo:

	function accesoPropiedad(objeto, nombrePropiedad){
		console.log(objeto[nombrePropiedad]);
	}
