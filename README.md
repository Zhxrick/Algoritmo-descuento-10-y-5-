### Algoritmo descuentos 

Algoritmo Tarea 

escribir "Zharick Donado y Camilo Lafaurie" 
	
	definir c como entero 
	definir descuento, precio, total como real 
	
	escribir "Digite el valor de producto"
	leer precio 
	escribir "Digite cantidad de articulos"
	leer c 
	total <- c * precio 
	
	si C >= 20 entonces 
		descuento <- total *.10 
		
	sino 
		
		si c > 10 entonces 
			descuento <- total * 0.5
		
		
		fin si 
		
		
	FinSi
	
	escribir "el total a pagar es: ", total - descuento 
FinAlgoritmo
