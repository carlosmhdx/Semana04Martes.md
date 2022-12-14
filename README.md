# Semana04Martes.md
Semana 04 - Día Martes - 13/12/2022

# Nombre Completo

Algoritmo NombreCompleto
	
	Imprimir " Introduzca su nombre: "
	Leer Nombre
	Imprimir " Introduzca su apellido: "
	Leer Apellido
	
	LongNombre = Longitud( Nombre )
	LongApellido = Longitud( Apellido )
	
	PLNombre1 = Mayusculas( Subcadena(Nombre, 1, 1) )
	PLApellido1 = Mayusculas( Subcadena(Apellido, 1, 1) )
	PLNombre2 = Minusculas(( Subcadena(Nombre, 2, LongNombre) ))
	PLApellido2 = Minusculas(( Subcadena(Apellido, 2, LongApellido) ))
	
	NombreComp = Concatenar(PLNombre1, PLNombre2)
	ApellidoComp = Concatenar(PLApellido1, PLApellido2)
	
	Imprimir " El nombre completo es: "
	Imprimir NombreComp, " ", ApellidoComp
	
FinAlgoritmo


# Dados

Algoritmo Dados
	
	Para i <- 1 Hasta 10 con paso 1
		
		AX = Aleatorio(1,6)
		AZ = Aleatorio(1,6)
		
		Si AX <> AZ Entonces
			
			Imprimir AX, "  ", AZ
			
		FinSi
		
		Si AX = AZ Entonces
			
			Imprimir AX, "  ", AZ, "  Los dados son iguales"
			
		FinSi
				
	FinPara
		
FinAlgoritmo

