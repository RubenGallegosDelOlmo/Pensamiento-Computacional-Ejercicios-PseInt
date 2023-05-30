Algoritmo Recomendaciones
	Definir Recomendacion Como Entero
	
	Escribir "Hola bienvenido a mis recomendaciones"
	Escribir "Ingresa que recomendacion te gustaria consultar"
	Escribir "1: Musica"
	Escribir "2: Comida"
	Escribir "3: Series"
	Escribir "4: Peliculas"
	Escribir "5: Libros"
	Leer Recomendacion
		Segun Recomendacion Hacer //Comando Switch que evita escribir muchos SI/SINO y te da multiples Opciones para elegir
		1:
			Escribir " Elige la recomendacion sorpresa 1 o 2"
			Leer Recomendacion
			Si Recomendacion = 1 Entonces //Escribi el comando Si/SiNo para darle a elegir al usuario 2 opciones 
				Escribir "1: Time for Us - Nicolas Jaar / Spotify"
			Sino Recomendacion = 2 
				Escribir "2: Red Like Roses - Jeff Williams, Casey Lee Williams / Spotify"
			FinSi
		2:
			Escribir " Elige la recomendacion sorpresa 1 o 2"
			Leer Recomendacion
			Si Recomendacion = 1 Entonces
				Escribir "1: Unos tacos de SUAperro"
			Sino Recomendacion = 2 
				Escribir "2: Una buena LirulSisa"
			FinSi
		3:
			Escribir " Elige la recomendacion sorpresa 1 o 2"
			Leer Recomendacion
			Si Recomendacion = 1 Entonces
				Escribir "1: Arcane / Netflix"
			Sino Recomendacion = 2 
				Escribir "2: The Boys / Amzaon Prime"
			FinSi
		4:
			Escribir " Elige la recomendacion sorpresa 1 o 2"
			Leer Recomendacion
			Si Recomendacion = 1 Entonces
				Escribir "1: El Increible castillo Vagabundo / Netflix"
			Sino Recomendacion = 2 
				Escribir "2: Your Name / Amazon Prime"
			FinSi
		5:
			Escribir " Elige la recomendacion sorpresa 1 o 2"
			Leer Recomendacion
			Si Recomendacion = 1 Entonces
				Escribir "1: El Arte de la Guerra / Sun Tzu"
			Sino Recomendacion = 2 
				Escribir "2: Revelion en la Granja / George Orwell "
			FinSi
			
		De Otro Modo:
			Escribir Recomendacion," Opcion de Recomendacion NO Valida "
		Fin Segun
FinAlgoritmo
