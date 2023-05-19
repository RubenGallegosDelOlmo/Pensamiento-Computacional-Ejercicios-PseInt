Algoritmo Lista_de_Alumnos
	Definir Folio Como Caracter
	Definir Nombre, Curso Como Caracter
	Escribir "Bienvenido al sistema de consulta de cursos aqui en Pilares"
	Escribir "Por favor, ingrese su folio (Maximo 8 digitos): "
	Leer Folio
	
	Mientras Longitud(Folio) > 8 Hacer
		Escribir "El folio que usted ingreso no es valido, por favor ingrese su Folio (Maximo 8 digitos)"
		Leer Folio
	FinMientras
	Si Folio = "12345678" Entonces
		nombre <- "Juan Pérez"
        curso <- "Escuela de Código"
	SiNo
		Si Folio = "23456789" Entonces
			nombre <- "María Rodríguez"
			curso <- "Taller de Ajedrez"
		SiNo
			Si Folio = "34567890" Entonces
				nombre <- "María Rodríguez"
				curso <- "Taller de Ajedrez"
			SiNo
				Si Folio = "45678909" Entonces
					nombre <- "Luis Gómez"
					curso <- "Taller de Plomería"
				SiNo
					SI Folio = "56789098" Entonces
						nombre <- "Ana López"
						curso <- "Taller de Carpintería"
					SiNo
						Si Folio = "67890987" Entonces
							nombre <- "Pedro Martínez"
							curso <- "Taller de Yoga"
						SiNo
							Si Folio = "78909876" Entonces
								nombre <- "Laura Torres"
								curso <- "Mecánica"
							SiNo
								Si Folio = "89098765" Entonces
									nombre <- "Carlos Sánchez"
									curso <- "Taekwondo"
								SiNo
									Escribir "El folio ingresado no corresponde a ningún estudiante registrado."
								FinSi
							FinSi
						FinSi
					FinSi
				FinSi
			FinSi
		FinSi
		
	FinSi
	Escribir "Estimado/a: " ,Nombre, " Usted esta en el siguiente curso: ",curso 
FinAlgoritmo
