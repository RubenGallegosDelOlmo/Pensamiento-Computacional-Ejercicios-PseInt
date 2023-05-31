Algoritmo CursoInscrito
	Definir Yes Como Caracter
	Definir Nombre Como Caracter
	Escribir "Ingrese su nombre"
	Leer Nombre
    Definir folio como caracter
    Escribir "Ingrese su folio de 6 dígitos:"
    Leer folio
    Mientras Longitud(folio) <> 6 Hacer
		Escribir "El folio debe tener 6 dígitos. Ingrese nuevamente:"
		Leer folio
	FinMientras

    Definir ultimoDigito como Entero
    ultimoDigito <- ConvertirANumero(folio) % 100
    
    Segun ultimoDigito Hacer
        Caso 11:
            Escribir Nombre," Está inscrito en las clases de: Escuela de Codigo"
			Escribir "¿Esta interesado en saber su horario?"
			Escribir "Escriba Si o No"
			Leer Yes
			Si Yes = "Si" Entonces
				Escribir "Indique que dia de la semana le gustaria saber"
				Escribir "NOTA: Los dias de la semana estan ordenados Numericamente del 1 al 7"
				Leer Yes
				Segun Yes Hacer
					"1":
						Escribir "Lunes se descansa Bobo"
					"2":
						Escribir "Martes de 9 de la mañana a 11 de la mañana"
					"3":
						Escribir "Miercoles de 9 de la mañana a 11 de la mañana"
					"4":
						Escribir "Juevez de 9 de la mañana a 11 de la mañana"
					"5":
						Escribir "Viernes de 9 de la mañana a 11 de la mañana"
					"6":
						Escribir "Sabado se descansa Bobo"
					"7": 
						Escribir "El Domingo se descansa Bobo"
				Fin Segun
			Sino Yes = "No"
				Escribir "Gracias por consultar su folio, vuelva pronto"
			FinSi
        Caso 12:
            Escribir Nombre," Está inscrito en las clases de: Plomeria"
			Escribir "¿Esta interesado en saber su horario?"
			Escribir "Escriba Si o No"
			Leer Yes
			Si Yes = "Si" Entonces
				Escribir "Indique que dia de la semana le gustaria saber"
				Escribir "NOTA: Los dias de la semana estan ordenados Numericamente del 1 al 7"
				Leer Yes
				Segun Yes Hacer
					"1":
						Escribir "Lunes de 9 de la mañana a 12 de la tarde"
					"2":
						Escribir "Martes de 10 de la mañana a 1 de la tarde"
					"3":
						Escribir "Miercoles de 9 de la mañana a 12 de la tarde"
					"4":
						Escribir "Juevez de 10 de la mañana a 1 de la tarde"
					"5":
						Escribir "Viernes de 10 de la mañana a 1 de la tarde"
					"6":
						Escribir "Sabado de 11 de la mañana a 2 de la tarde"
					"7": 
						Escribir "El Domingo se descansa Bobo"
				Fin Segun
			Sino Yes = "No"
				Escribir "Gracias por consultar su folio, vuelva pronto"
			FinSi
        Caso 13:
            Escribir Nombre," Está inscrito en las clases de: Ajedrez"
        Caso 14:
            Escribir Nombre," Está inscrito en las clases de: Yoga"
        Caso 15:
            Escribir Nombre," Está inscrito en las clases de: Carpinteria"
        Caso 16:
            Escribir Nombre," Está inscrito en las clases de: Box"
        De Otro Modo:
            Escribir "No se encontró ningún curso correspondiente al folio ingresado."
    FinSegun
    
FinAlgoritmo
