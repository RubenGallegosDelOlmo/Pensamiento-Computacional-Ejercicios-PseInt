Algoritmo Promedio_Alumnos
	
	Definir X como entero 
	Definir Edad como entero 
	Definir Suma Como Entero
	Definir Contador Como Entero
	Definir Promedio Como Real
	
	Suma=0
	Contador=0
	
	Escribir "Ingrese la cantidad de Alumnos"
	Leer X
	Para i = 1 hasta X hacer 
		Escribir "Ingrese la edad del Alumno ",i,":"
		Leer Edad 
		Si Edad >= 18 Entonces
			Suma = Suma+Edad
			Contador = Contador + 1
		SiNo
			Escribir "La edad del alumno no es aceptada"
			Escribir "(El alumno no puede ser menor de edad)"
			Escribir "Intentelo de nuevo: "
			Leer Edad
		FinSi
	FinPara
	Promedio = Suma / X
	Escribir "El promedio de edad de los ",X," Alumnos es: ",Promedio
	
FinAlgoritmo
