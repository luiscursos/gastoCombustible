# gastoCombustible

El programa pedira 3 datos:

*El consumo por 100km; 
	litros100km  --> Variable
*Los kilometros totales del viaje; 
	distancia    --> Variable
*El precio por litro en ese momento;
	precioLitro  --> Variable
*Parametro para realizar la operacion reglade3; 
	cien         --> Constante


1 .-Se importan las librerias:
	1.1 .- Scanner
	1.2 .- Api google
2 .- Se declaran 2 Array de tipo double.
	2.1 .- nombresDatos --> Aqui está el nombre de los conceptos relacionados con los valores
	2.2 .- valoresDatos --> Aqui se almacenará los datos que introduzca el usuario
	2.3 .- Se crea una constante "porcien" con valor 100
3 .- Se crea un bucle for para:
	3.1 .- Pedir los datos al usuario mediante Scanner e ir almacenandolos en el array valoresDatos
		3.1.1 .- Distancia --> n1
		3.1.2 .- Consumo l/100km -->n2
		3.1.3 .- Precio Litro --n3
	3.2 .- Se iterara al mismo tiempo por el array de nombresDatos para indicarle al usuario el dato que se solicita
4 .- Se llama a la función que nos solicitará los 3 datos indicados antes y con return realizamos la siguiente operacion
	4.1 return ((distancia * consumo l/100km) / porcien) * precioLitro



****FUNCIONES DEL METODO****

QUE LA APP PIDA ORIGEN Y DESTINO, Y DESPUÉS QUE HAGA UNA LLAMADA A GOOGLE MAPS PARA RECIBIR LOS KMTRS
DESPUES DE RECIBIR LOS DATOS DE MAPS, HABRIA QUE MULTIPLICAR *2 LOS KMTRS RECIBIDOS (ORIGEN Y DESTINO)
