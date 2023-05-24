Proceso AdivinaElNumero
    Definir Nombre Como Caracter 
	Definir NumeroUsuario, NumeroAleatorio Como Entero
    Definir IntentosRestantes Como Entero
    
    Escribir "Bienvenido al juego de adivinanza de números."
    Escribir "Ingresa tu nombre: "
    Leer nombre
    
    IntentosRestantes = 10  // Asigna cuantos intentos tiene el usuario
	
    Escribir "Hola, "  nombre  ". Estoy pensando en un número del 1 al 5. Adivina cuál es."
    Repetir
		NumeroAleatorio = Aleatorio(1, 5) // Genera un número aleatorio del 1 al (valor que quieras)
		Escribir "Tu numero: "
        Leer NumeroUsuario
        
        Si NumeroUsuario = NumeroAleatorio Entonces
            Escribir "¡Felicidades, "  nombre  "! Has adivinado el número."
			Escribir "Que Pro en HD!"
        Sino
			Escribir "Intentos restantes: "  intentosRestantes - 1 // Se van restando intentos
			intentosRestantes = intentosRestantes - 1
            Escribir "Lo siento, "  nombre  ". El número que buscas no es correcto."
			Escribir "El numero correcto era el: " numeroAleatorio
        FinSi
        
        Si intentosRestantes = 0 Entonces
            Escribir "Ya no te quedan más intentos!...Que Noob en HD"
        FinSi
		
    Hasta Que intento = numeroAleatorio O intentosRestantes = 0
    
FinProceso
