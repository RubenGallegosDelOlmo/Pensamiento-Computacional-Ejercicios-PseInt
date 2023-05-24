Algoritmo Juego_Del_Numero_Secreto
	Definir Numero_Usuario, Numero_Secreto Como Entero
	Definir Nombre Como Caracter
	Escribir "Hola Usuario..¿Como te llamas?"
	Leer Nombre
	Numero_secreto <-Aleatorio(1, 5)
	Escribir " Hola ",Nombre, " Estoy pensando en un numero, adivina cual es"
	Leer Numero_Usuario
	Si Numero_Usuario=Numero_secreto
		Escribir "Felicidades ",Nombre, " Le atinaste "
		Escribir "Que Pro en HD"
	SiNo
		Escribir "Lo siento el numero secreto era el: "+ ConvertirATexto(Numero_secreto)
		Escribir "Que Noob!"
	FinSi
FinAlgoritmo
![image](https://github.com/RubenGallegosDelOlmo/EscuelaDeCodigo-PseInt/assets/133395946/4b8e69ae-c1e9-4e3a-b8a6-2deb313fbf6d)
