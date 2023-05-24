Algoritmo Aprovado_o_Reprovado
	Definir Cal1,Cal2,Cal3,Cal4,promedio Como Real
	Definir Nombre Como Caracter
	// Realiza un algoritmo y diagrama de flujo de un programa que resuelva el sigueinte problema: 
	// Solicitando se ingresen 4 calificaciones, una por periodo, se obtenga el promedio y se imprima una felicitación a quien obtenga un promedio mayor a 6
	// Y se le informe ha reprobado a quien obtenga una calificacion menor a 6.
	Escribir 'Ingresa el nombre del alumno'
	Leer Nombre
	Escribir 'Ingrese la primera calificación:'
	Leer Cal1
	Si Cal1<0 O Cal1>10 O (Cal1*10)-Redon(Cal1*10)<>0 Entonces
		Escribir 'La calificación 1 es inválida.'
	FinSi
	Escribir 'Ingrese la segunda calificación:'
	Leer Cal2
	Si Cal2<0 O Cal2>10 O (Cal2*10)-Redon(Cal2*10)<>0 Entonces
		Escribir 'La calificación 2 es inválida.'
	FinSi
	Escribir 'Ingrese la tercera calificación:'
	Leer Cal3
	Si Cal3<0 O Cal3>10 O (Cal3*10)-Redon(Cal3*10)<>0 Entonces
		Escribir 'La calificación 3 es inválida.'
	FinSi
	Escribir 'Ingrese la cuarta calificación:'
	Leer Cal4
	Si Cal4<0 O Cal4>10 O (Cal4*10)-Redon(Cal4*10)<>0 Entonces
		Escribir 'La calificación 4 es inválida.'
	FinSi
	promedio <- ((Cal1+Cal2+Cal3+Cal4)/4)
	Si promedio>10 Entonces
		Escribir 'El promedio es inválido.'
	SiNo
		Escribir 'El promedio del alumno ',Nombre,' es:',promedio
	FinSi
	Si promedio>=6 Entonces
		Escribir 'Felicidades: ',Nombre,' Usted ha aprovado'
	SiNo
		Escribir 'Usted: ',Nombre, " Ha reprovado..Burro"
	FinSi
FinAlgoritmo
