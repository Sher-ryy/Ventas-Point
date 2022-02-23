# Ventas-Point
Algoritmo calculadoraMercadoPago

	Definir resultadoComision Como Numerica;
	
	Definir Ganancia Como Numerica;
	
	Definir Cobro Como Numerica;
	
	Escribir ":;;:°:;;:*:;;:°:;;:*:;;:°:;;:*:;;:°:;;:*:;;:";
	Escribir " Calcula tus ganancias en ventas por Point";
	Escribir ":;;:°:;;:*:;;:°:;;:*:;;:°:;;:*:;;:°:;;:*:;;:";
	
	Escribir "¿Cuánto le cobrarás a tu cliente?: ";
	Leer Cobro;
	
	Escribir "La comisión de cada transacción es de: 3.5% + IVA";
	
	//Vamos a colocar el proceso para determinar la comisión
	resultadoComision = Cobro * 0.0406;
	
	Escribir "La comisión que se te cobra es: ", resultadoComision;
	
	Ganancia = Cobro - resultadoComision;
	Escribir "Está cantidad recibirás en tu cuenta: ", Ganancia;
	
	
FinAlgoritmo
