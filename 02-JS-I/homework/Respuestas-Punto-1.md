# Homework: Introducción a Javascript

## Instrucciones
---
1. En un archivo de texto separado que debes crear, escribe explicaciones de los siguientes conceptos como si se lo estuvieras explicando a un niño de 12 años. Hacer esto te ayudará a descubrir rápidamente cualquier agujero en tu comprensión.

	* Variables
		Es donde almacenamos algun valor que luego utilizaremos mas tarde.
		Por ejemplo: creo la variable:
						var nombre = "Samuel";
		En adelante cada que utilice la variable nombre, siempre me retornara "Samuel", mientras no le de otro valor.


	* Strings
		Es una cadena te texto que se le asigna a una variable. En el punto anterior describiendo la variable, el valor que se le asigno a la variable nombre, es un String, ya que "Samuel" es una cadena de texto. Un string, siempre se definira entre comillas.
		Por ejemplo: Para reforzar el concepto de variables, yo puedo crear un string llamando la variable que ya defini anteriormente:
						var nombreNino = nombre;
		Anteriormente definimos que nombre="Samuel", y si nombreNino=nombre, entonces nombreNino"Samuel".


	* Funciones (argumentos, `return`)
		Las funciones se utilizan para retornar una respuesta de algo. Por ejemplo, si yo hago una operacion aritmetica como una resta, se espera que de la resta se me de un resultado. Ese resultado es lo que retorna la funcion.
	
		Por ejemplo: Para restar 5-2, espero que la funcion me arroje como resultado 3, que es la respuesta de la operacion. El "return", para decirlo de manera las simple es la respuesta de la funcion.

		Por ejemplo: Continuando con el ejemplo de la variable nombre="Samuel", o la variable nombreNino:
		si creo la siguiente funcion:
			function hola(nombreNino)
			{
				console.log("hola "+ nombreNino);
			}
			*Aqui ya defini la funcion hola

			hola(nombreNino);
			*Cuando llamo la funcion hola, me va a retornar "Hola Samuel", porque dentro de la varibale nombreNino esta la cadena "Samuel".
			
			

	* Declaraciones `if`
		*son condiciones que podemos poner en el código, como por ejemplo: si tenemos dos numeros (5 y 7), podemos condicionar que si 5>7 haga una resta, sino que haga una suma.
		function operacion(a,b)
		{
			if(a>b)
			{
				return(a-b);
			}
			else return(a+b);
		}

	* Valores booleanos (`true`, `false`)
		* son valores que se utilizan donde unicamente es posible dos respuestas, verdadedo o falso.
		Ejemplo: "Samuel"="Samuel", verdadero. De lo contrario es falso, no hay mas opciones.
