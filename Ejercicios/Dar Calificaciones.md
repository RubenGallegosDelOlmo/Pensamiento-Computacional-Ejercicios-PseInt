Algoritmo Dar_Calificaciones
	Definir Cal1, Cal2, Cal3, Cal4, Promedio Como Real
	Definir Nombre Como Caracter
	
	Escribir "Ingresa el nombre del alumno"
	Leer Nombre
	
	Escribir "Ingrese la primera calificación:"
    Leer Cal1
	Si Cal1 < 0 O cal1 > 10 O (cal1 * 10) - Redon(cal1 * 10) <> 0 Entonces
        Escribir "La calificación 1 es inválida."
	FinSi
	
    Escribir "Ingrese la segunda calificación:"
    Leer Cal2
	Si Cal2 < 0 O cal2 > 10 O (cal2 * 10) - Redon(cal2 * 10) <> 0 Entonces
        Escribir "La calificación 2 es inválida."
	FinSi
	
    Escribir "Ingrese la tercera calificación:"
    Leer Cal3
	Si Cal3 < 0 O cal3 > 10 O (cal3 * 10) - Redon(cal3 * 10) <> 0 Entonces
		Escribir "La calificación 3 es inválida."
	FinSi
	
    Escribir "Ingrese la cuarta calificación:"
    Leer Cal4
	Si Cal4 < 0 O cal4 > 10 O (cal4 * 10) - Redon(cal4 * 10) <> 0 Entonces
		Escribir "La calificación 4 es inválida."
	FinSi
	
	Promedio = ((Cal1 + Cal2 + Cal3 + Cal4)/4)
	Si promedio > 10 Entonces
        Escribir "El promedio es inválido."
    Sino
        Escribir "El promedio del alumno",Nombre " es:", promedio
    FinSi
