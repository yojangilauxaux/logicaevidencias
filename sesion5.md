<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->
# Actividad 5: Ejercicios de bucles
Resolver los siguientes ejercicios:.

Ejercicios - while

Pedir al usuario que ingrese un número y mostrar su tabla de multiplicar hasta el número 10.

Pedir al usuario que ingrese una cadena de caracteres y contar la cantidad de caracteres que son números. 

Ejercicios - do while

Escribe un programa en Java que imprima los números del 1 al 100, pero que se detenga si el usuario introduce un número negativo.

Escribe un programa en Java que pida al usuario un número entero e imprima la tabla de multiplicar de ese número, pero que se detenga si el usuario introduce el número 0.


Ejercicios - for
Imprimir los números impares del 1 al 50.

Imprimir los números primos del 1 al 100.

## ejercicios while
```java

1 import java.util.Scanner;

public class Mavenproject1 {

public static void main(String[] args) {
       
Scanner scanner = new Scanner(System.in);
    
System.err.println("ingresa un numero");
int numero = scanner.nextInt();
        
int x = 1;
        
while (x <= 10){
int resultado = numero * x;
        
System.err.println(numero + "x" + x + "=" + resultado);
 x++;
        
    }
    
scanner.close();
        
                
    }    
     }
```

```java
2 import java.util.Scanner;

public class Mavenproject1 {

public static void main(String[] args) {
       
 Scanner scanner = new Scanner(System.in);
    
System.out.print("Ingrese una cadena de numeros: ");
String cadena = scanner.nextLine();
int x = 0;
int contadornumeros = 0;

while (x < cadena.length()) {
char caracter = cadena.charAt(x);
if (caracter == '1' || caracter == '2' || caracter == '3' || caracter == '4' || caracter == '5' || caracter == '6' || caracter == '7' || caracter == '8' || caracter == '9' || caracter == '0'  ) {
 contadornumeros++;
}
 x++;
        }
System.out.println("la cantidad de caracteres que son numeros en la cadena es:)" + contadornumeros + "numero(os");

        
scanner.close();
        
                
    }    
     }
```


 Ejercicio do - while 

 ```java

 1 import java.util.Scanner;

public class Mavenproject1 {

public static void main(String[] args) {
       
 Scanner scanner = new Scanner(System.in);
    
int numero = 0;
       
do {
System.out.println("ingresa un numero (numero negativo para terminar)= ");
 numero = scanner.nextInt();
           
 while (numero >=0 && numero <= 99 ) {
numero +=1;
System.out.println("");
}
       
} while(numero >=0);
System.err.println("se ha detenido el programa");
        
scanner.close();
        
                
    }    
     }
     ```


ejercicio 2

```java

2import java.util.Scanner;

public class Mavenproject1 {

 public static void main(String[] args) {
       
 Scanner scanner = new Scanner(System.in);
    
int numero;
       
do {
 System.out.println("ingresa un numero entero (0 numero para terminar): ");
           
numero = scanner.nextInt();
           
if (numero == 0) {
System.err.println("programa detenido.");
              
} else {
              
 for ( int i = 1; i <= 10; i++) {
 int resultado = numero * i;
  System.err.println(numero + "x" + i + " = " + resultado);
                  
 }
 }
       } while (numero != 0);   
          
         
        
scanner.close();
        
                
    }    
     }
     ```
     
     
  ejercicios for 

```java

1 for ( int x = 1; x <= 50; x+=2) {
System.out.println(x);
     }
     

ejercicio 2

import java.util.Scanner;

public class Mavenproject1 {

public static void main(String[] args) {
       
Scanner scanner = new Scanner(System.in);
    
       
System.out.println("Números primos del 1 al 100:");

for (int numero = 2; numero <= 100; numero++) {
boolean esPrimo = true;

 for (int i = 2; i <= numero / 2; i++) {
 if (numero % i == 0) {
esPrimo = false;
break;
  }
}
 if (esPrimo) {
System.out.print(numero + " ");

            }
        }   
         
        
scanner.close();
        
                
    }    
    
     }
      
```

     
    

      





