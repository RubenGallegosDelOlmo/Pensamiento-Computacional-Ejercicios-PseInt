Algoritmo sin_titulo

    Definir Profesor, Alumno, Materia Como Caracter
    Definir Punto Como Caracter
    Definir Cal, Suma Como Real
    Definir CalFP, CalF Como Entero
    
    Escribir "Hola Profesor, ingrese su nombre"
    Leer Profesor
    Profesor <- Mayusculas(Profesor)
    
    Escribir "Bienvenido Profesor: ", Profesor, " Ingrese el nombre de su Asignatura"
    Leer Materia
    Materia <- Mayusculas(Materia)
    
    Para i <- 1 Hasta 5 Con Paso 1 Hacer
        Escribir "Ingrese el nombre del Alumno/a: " 
        Leer Alumno 
        
        Escribir "Ingrese las calificaciones del/la Alumno/a: ", Alumno
        Suma <- 0  // Reiniciar la suma en cada iteración
        
        Para j <- 1 Hasta 4 Con Paso 1 Hacer
            Leer Cal
            Si Cal >= 0 y Cal <= 10 Entonces
                Suma <- Suma + Cal
            SiNo
                Escribir "Calificacion no valida, inténtelo de nuevo"
                J <- J - 1  // Restar 1 a J para repetir la lectura de calificación
            FinSi
        FinPara
        
        CalF <- redon(Suma / 4)
        
        Escribir "La calificacion Final en la asignatura de: ", Materia, " del Alumno/a: ", Alumno, " es de: ", CalF
        
        Escribir "¿El alumno cuenta con 1 punto Extra?.. Si es así escriba SI o No"
        Leer Punto
        Punto<-Mayusculas(Punto)
        Si Punto = "SI" Entonces
            CalFP <- CalF + 1
            Si CalFP >= 6 Entonces
                Escribir "Promedio Final:", CalFP, " El/La Alumno/a: ", Alumno, " está Aprobado.... ¡QUE PRO!"
            SiNo
                Escribir "Promedio Final: ", CalFP, " El/La Alumno/a: ", Alumno, " está Reprobado... ¡QUE NOOB!"
            FinSi
        Sino 
            Si CalF >= 6 Entonces
                Escribir "Promedio Final:", CalF, " El/La Alumno/a: ", Alumno, " está Aprobado.... ¡QUE PRO!"
            SiNo
                Escribir "Promedio Final: ", CalF, " El/La Alumno/a: ", Alumno, " está Reprobado... ¡QUE NOOB!"
            FinSi
        FinSi
        
    FinPara
    
FinAlgoritmo
