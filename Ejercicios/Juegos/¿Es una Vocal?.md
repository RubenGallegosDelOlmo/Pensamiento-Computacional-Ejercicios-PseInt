Algoritmo JuegoDeLasVocales 
	
	Definir Letra Como Caracter
	
	Escribir "Ingresa una letra"
	Leer Letra 
	Letra<-Minusculas(Letra) 
	
	Segun Letra Hacer //Comando Switch que evita escribir muchos SI/SINO
		"a":
			Escribir Letra," Es una vocal y es la a"
		"e":
			Escribir Letra," Es una vocal y es la e"
		"i":
			Escribir Letra," Es una vocal y es la i"
		"o":
			Escribir Letra," Es una vocal y es la o"
		"u":
			Escribir Letra," Es una vocal y es la u"
		De Otro Modo:
			Escribir Letra," No es una Vocal!"
	Fin Segun
FinAlgoritmo
