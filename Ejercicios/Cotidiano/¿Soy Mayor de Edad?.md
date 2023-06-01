Algoritmo DarEdades

	Definir Edad, DiaA, MesA, AnioA Como Entero 
	Definir DiaN, MesN, AnioN Como Entero 
	Definir Nombre, L Como Caracter
	Para i<-1 Hasta 5 Con Paso 1 Hacer
		Escribir "Hola Usuario Ingrese su nombre"
		Leer Nombre
		Nombre<-Mayusculas(Nombre)
		Escribir"Su Nombre es: ",Nombre
		Escribir"Bien ",Nombre," Vamos a ver cuantos años tienes, por favor ingresa los siguientes datos"
		Escribir "Escribe la fecha Actual (Dia)"
		Leer DiaA
		Escribir "Escribe la fecha Actual (Mes)"
		Leer MesA
		Escribir "¿El año actual es 2023? SI o NO"
		Leer L
		L<-Mayusculas(L)
		Si L= "SI" Entonces
			AnioA<-2023
			Escribir "Escribe tu dia de nacimiento"
			Leer DiaN
			Escribir "Escribe tu mes de nacimiento"
			Leer MesN
			Escribir "Escribe tu año de nacimiento"
			Leer AnioN
			Edad = AnioA - AnioN
			Si MesN > MesA Entonces
				Edad = Edad - 1
			SiNo
				Si MesN == MesA Entonces
					Si DiaN > DiaA Entonces
						Edad = Edad - 1
					FinSi
				FinSi
			FinSi
			Escribir Nombre," Su edad es de: ",Edad," Años"
			Si Edad >= 18 Entonces
				Escribir "Usted Ya es Mayor de Edad"
			SiNo 
				Escribir "Usted es Menor de Edad"
			FinSi
		Sino L = "NO" 
			Leer AnioA
			Escribir "Escribe tu dia de nacimiento"
			Leer DiaN
			Escribir "Escribe tu mes de nacimiento"
			Leer MesN
			Escribir "Escribe tu año de nacimiento"
			Leer AnioN
			Edad = AnioA - AnioN
			Si MesN > MesA Entonces
				Edad = Edad - 1
			SiNo
				Si MesN == MesA Entonces
					Si DiaN > DiaA Entonces
						Edad = Edad - 1
					FinSi
				FinSi
			FinSi
		FinSi
	Fin Para
  
FinAlgoritmo
