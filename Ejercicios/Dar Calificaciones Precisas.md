Algoritmo Dar_Calificaciones_De_Forma_Precisa
	Definir Profesor, Alumno, Materia Como Caracter 
	Definir Cal1, Cal2, Cal3, Cal4, CalF Como Real
	Escribir "Bienvenido Profesor, ingrese su nombre y el nombre de su materia"
	Escribir "Soy el/la Profesor/a: "
	Leer Profesor
	Escribir "Mi materia es: "
	Leer Materia
	Para i<-1 Hasta 5 Con Paso 1 Hacer //Sirve para repetir el proceso, o en otras palabras para que el profesor pueda ingresar las calificaciones de sus alumnos en un solo programa xDxDxD
		Escribir "Ingrese el nombre del Alumno"
		Leer Alumno
		Escribir "Bien Profesor: ",Profesor, " ingrese las calificaciones del/la Alumno/a ",Alumno
		Escribir "Ingrese la Calificacion 1: "
		Leer Cal1
		Si Cal1>=0 y Cal1<=10 Entonces //Aqui se define una acalificacion mayor a 0 y menor a 10
			Escribir "Ingrese la Calificacion 2: "
			Leer Cal2
			Si Cal2>=0 y Cal2<=10 Entonces
				Escribir "Ingrese la calificacion 3: "
				Leer Cal3 
				Si Cal3>=0 y Cal3<=10 Entonces
					Escribir "Ingrese la calificacion 4: "
					Leer Cal4
					Si Cal4>=0 y Cal4<=10 Entonces
						CalF <- redon((Cal1+Cal2+Cal3+Cal4)/4) //Redon sirve para redondear una calificacion con decimal 
						Si CalF>=6 Entonces
							Escribir "Promedio Final:",CalF, " El/La Alumno/a: ",Alumno, " esta Aprovado....QUE PRO!"
						SiNo
							Escribir "Promedio Final: ",CalF," El/La Alumno/a: ",Alumno, " esta Reprovado...QUE NOOB!"
						FinSi
					SiNo
						Escribir "La clificacion es Invalida"
					FinSi
				SiNo
					Escribir "La Calificacion es Invalida"
				FinSi
			SiNo
				Escribir "La Calificacion es Invalida"
			FinSi
		SiNo
			Escribir "La calificacion es Invalida"
		FinSi
	FinPara	
FinAlgoritmo
