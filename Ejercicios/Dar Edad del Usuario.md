Algoritmo Dar_La_Edad_Del_Usuario
	Definir Edad, DiaActual, MesActual, AnioActual Como Entero
	Definir DiaNacimiento, MesNacimiento, AnioNacimiento Como Entero
	Definir Nombre Como Caracter
	
	AnioActual<-2023
	Escribir "Escribe tu nombre"
	Leer Nombre
	Escribir "Escribe la fecha Actual (Dia)"
	Leer DiaActual
	Escribir "Escribe la fecha Actual (Mes)"
	Leer MesActual
	
	Escribir "Escribe tu dia de nacimiento"
	Leer DiaNacimiento
	Escribir "Escribe tu mes de nacimiento"
	Leer MesNacimiento
	Escribir "Escribe tu año de nacimiento"
	Leer AnioNacimiento
	
	Edad = AnioActual - AnioNacimiento
	
	Si MesNacimiento > MesActual Entonces
		Edad = Edad - 1
	SiNo
		Si MesNacimiento == MesActual Entonces
			Si DiaNacimiento > DiaActual Entonces
				Edad = Edad - 1
			FinSi
		FinSi
		
	FinSi
	
	Imprimir Nombre," tu edad es de ",Edad," años ","...Ya estas viejo"
	
FinAlgoritmo
