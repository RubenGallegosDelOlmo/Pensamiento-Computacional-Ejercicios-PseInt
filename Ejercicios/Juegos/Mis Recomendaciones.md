Algoritmo Recomendaciones 
	
	Definir Recomendacion Como Entero
	Definir K Como Caracter
	Escribir "Hola bienvenido a mis recomendaciones"
	
	Para i<-1 Hasta 5 Con Paso 1 Hacer
		Escribir "Ingresa que recomendacion te gustaria consultar"
		Escribir "Puede consultarlo hasta 5 veces"
		Escribir "1: Musica"
		Escribir "2: Comida"
		Escribir "3: Series"
		Escribir "4: Peliculas"
		Escribir "5: Libros"
		
		Leer Recomendacion
			Segun Recomendacion Hacer //Comando Switch que evita escribir muchos SI/SINO y te da multiples Opciones para elegir
				1:
					Escribir " Elige la recomendacion sorpresa 1, 2, 3, 4 o 5"
					Leer Recomendacion
					Segun Recomendacion Hacer
						1: Escribir "1: Time for Us - Nicolas Jaar / Spotify"
						2: Escribir "2: Red Like Roses - Jeff Williams, Casey Lee Williams / Spotify"
						3: Escribir "3: BOW - MFS / Spotify"
						4: Escribir "4: More - KDA / Spotify"
						5: Escribir "5: No Phone - Cake / Spotify"
					FinSegun
					
					Escribir "¿Le gusto nuestra recomendacion",": SI o NO"
					Leer K
					K<-Mayusculas(K)
					Si K = "SI" Entonces
						Escribir "Que bueno CRACK"
						Escribir "Tienes buenos gustos"
					SiNo  
						Escribir "Ni pedo CRACK no todo es color rosas"
						Escribir "Payaso!"
					FinSi
					
				2:
					Escribir " Elige la recomendacion sorpresa 1 o 2"
					Leer Recomendacion
					Si Recomendacion = 1 Entonces
						Escribir "1: Unos tacos de SUAperro"
					Sino Recomendacion = 2 
						Escribir "2: Una buena LirulSisa"
					FinSi
					
					Escribir "¿Le gusto nuestra recomendacion",": SI o NO"
					Leer K
					K<-Mayusculas(K)
					Si K = "SI" Entonces
						Escribir "Que bueno CRACK"
						Escribir "Tienes buenos gustos"
					SiNo K = "NO" 
						Escribir "Ni pedo CRACK no todo es color rosas"
						Escribir "Payaso!"
					FinSi
				3:
					Escribir " Elige la recomendacion sorpresa 1 o 2"
					Leer Recomendacion
					Si Recomendacion = 1 Entonces
						Escribir "1: Arcane / Netflix"
					Sino Recomendacion = 2 
						Escribir "2: The Boys / Amzaon Prime"
					FinSi
					
					Escribir "¿Le gusto nuestra recomendacion",": SI o NO"
					Leer K
					K<-Mayusculas(K)
					Si K = "SI" Entonces
						Escribir "Que bueno CRACK"
						Escribir "Tienes buenos gustos"
					SiNo K = "NO" 
						Escribir "Ni pedo CRACK no todo es color rosas"
						Escribir "Payaso!"
					FinSi
				4:
					Escribir " Elige la recomendacion sorpresa 1 o 2"
					Leer Recomendacion
					Si Recomendacion = 1 Entonces
						Escribir "1: El Increible castillo Vagabundo / Netflix"
					Sino Recomendacion = 2 
						Escribir "2: Your Name / Amazon Prime"
					FinSi
					
					Escribir "¿Le gusto nuestra recomendacion",": SI o NO"
					Leer K
					K<-Mayusculas(K)
					Si K = "SI" Entonces
						Escribir "Que bueno CRACK"
						Escribir "Tienes buenos gustos"
					SiNo K = "NO" 
						Escribir "Ni pedo CRACK no todo es color rosas"
						Escribir "Payaso!"
					FinSi
				5:
					Escribir " Elige la recomendacion sorpresa 1 o 2"
					Leer Recomendacion
					Si Recomendacion = 1 Entonces
						Escribir "1: El Arte de la Guerra / Sun Tzu"
					Sino Recomendacion = 2 
						Escribir "2: Revelion en la Granja / George Orwell "
					FinSi
					
					Escribir "¿Le gusto nuestra recomendacion",": SI o NO"
					Leer K
					K<-Mayusculas(K)
					Si K = "SI" Entonces
						Escribir "Que bueno CRACK"
						Escribir "Tienes buenos gustos"
					SiNo K = "NO" 
						Escribir "Ni pedo CRACK no todo es color rosas"
						Escribir "Payaso!"
					FinSi
					
				De Otro Modo:
					Escribir Recomendacion," Opcion de Recomendacion NO Valida "
					
			Fin Segun
			
		FinPara
		
FinAlgoritmo
