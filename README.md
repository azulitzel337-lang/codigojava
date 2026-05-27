//Programacion con doble diagonal coloco comentarios de una linea
//Profesor: Jaciel Luna

/*
Materia: Programacion
Alumno: Azul Itzel Lopez Epifanio
Ejercicio 01

ej01- Crea un comentario en el código y coloca el nombre de la asignatura 
- Representa las diferentes sintaxis que existen de crear comentarios en el lenguaje (en una línea, varias...). Escribe el nombre del profesor y tus datos generales
- Crea una variable (y una constante si el lenguaje lo soporta). 
- Crea variables representando todos los tipos de datos primitivos del lenguaje (cadenas de texto, enteros, booleanos...).  
- Imprime por terminal el texto: "¡Hola, [y el nombre del lenguaje]!"


Primeros pasos de codigo
*/

import java.util.Scanner; //permite leer datos del teclado

public class Main {

    public static void main(String[] args) {

        //declaracion de una constante y una variable
        int variable = 25; //declaracion de una variable
        final double constante = 3.1416; //declaracion de una constante

        //declaracion de tipos de datos
        int entero = 5; //almacena numeros enteros
        float flotante = 6.13f; //almacena numeros decimales simples
        double decimaldoble = 6.1325; //almacena decimales con mayor precision
        char caracter = 'A'; //almacena un caracter
        boolean booleano = true; //almacena verdadero o falso
        String cadenadecaracteres = "Jaciel";

        //imprimir saludo en la consola 
        System.out.println("Hola,Java");
    }
}
