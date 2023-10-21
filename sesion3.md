<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->
# Actividad 3: Ejercicios de operaciones básicas en Java.
1 Suma y multiplicación: Escribe un programa que solicite al usuario dos números enteros y luego imprima la suma y multiplicación de esos números.

2 Resta y división: Escribe un programa que tome dos números enteros ingresados por el usuario y calcule la resta y división de esos números.

3 Operaciones combinadas: Escribe un programa que solicite al usuario tres números enteros y realice las siguientes operaciones: suma de los tres números, multiplicación del primer número por el segundo y división del resultado entre el tercer número.

4 Operaciones con decimales: Escribe un programa que solicite al usuario dos números decimales y realice las siguientes operaciones: suma, resta, multiplicación y división.

5 Incremento y decremento: Escribe un programa que declare una variable entera y la inicialice con un valor. Luego, incrementa su valor en 1 y muestra el resultado. Después, decrementa su valor en 1 y muestra el resultado nuevamente.

6 Operador de asignación compuesta: Escribe un programa que declare una variable entera y la inicialice con un valor. Utiliza el operador de asignación compuesta para sumar 5 a la variable y luego mostrar su valor.

7 Operadores lógicos: Escribe un programa que tome dos valores booleanos ingresados por el usuario y muestre el resultado de las operaciones lógicas AND, OR y NOT entre esos valores.

8 Operador ternario: Escribe un programa que tome un número entero ingresado por el usuario y utilice el operador ternario para determinar si el número es positivo o negativo. Luego, muestra el resultado en la salida.

## ejercicio 1

```java

import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
  
        System.err.println("ingresa el primer numero entero");
        int num1 = scanner.nextInt();
        
        System.err.println("ingresa el segundo numero entero");
        int num2 = scanner.nextInt();
        
        int suma = num1 + num2;
        int multiplicacion = num1 * num2;  
        
        System.err.println("la suma de los numeros es: " + suma);
        System.err.println("la multiplicacion de los numeros es: " + multiplicacion);
        
        scanner.close();
    
      }
      }
     ```
     
```java
     EJERCICIO 2

   import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
  
        System.err.println("ingresa el primer numero entero");
        int num1 = scanner.nextInt();
        
        System.err.println("ingresa el segundo numero entero");
        int num2 = scanner.nextInt();
        
        int resta = num1 - num2;
        
        double division  = (double) num1 / num2;  
        
        System.err.println("la resta de los numeros es:  " + resta);
        System.err.println("el resultados de la division es: " + division);
        
        scanner.close();
    
      }
      }  
```
```java

       Ejercicio 3 

      import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
  
        System.err.println("ingresa el primer numero entero");
        int num1 = scanner.nextInt();
        
        System.err.println("ingresa el segundo numero entero");
        int num2 = scanner.nextInt();
        
        System.err.println("ingrese el tercer numero entero");
        int num3 = scanner.nextInt();
        
        
        int suma = num1 + num2 + num3;
        
        int multiplicacion = num1 * num2;
         
        double resultadodivision  = (double) multiplicacion / num3;  
        
        System.err.println("suma de los tres numeros:  " + suma);
        System.err.println("multiplicacion del primer numero por el segundo: " + multiplicacion);
        System.err.println("division del resultado entre el tercer numero: " + resultadodivision);
       
        scanner.close();
    
      }
      }
```

```java
      Ejercicio 4

      import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
  
        System.err.println("ingresa el primer numero decimal");
        double num1 = scanner.nextInt();
        
        System.err.println("ingresa el segundo numero decimal");
        double num2 = scanner.nextInt();
        
        
        double suma = num1 + num2;
        
        double resta = num1 - num2;
         
        double multiplicacion  =  num1 * num2;
        
        double division = num1 / num2;
        
        
        System.err.println("suma " + suma);
        System.err.println("resta: " + resta);
        System.err.println("multiplicacion: " + multiplicacion);
        System.err.println("division: " + division);
       
        scanner.close();
    
      }
      }
```

```java
  
       Ejercicio 5

       import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
     int numero = 10;
     
     numero++;
        System.err.println("valor incrementado: " + numero);
        
     numero--;
        System.err.println("valor decrementado: " + numero);
       
        scanner.close();
    
      }
      }
```

```java

      Ejercicio 6

      import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
     int numero = 10;
     
     numero+=5;
     
        
        System.err.println("valor despues de sumar 5: " + numero);
       
        scanner.close();
    
      }
      }
```

```java

Ejercicio 7

import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
        System.err.println("ingrese el primer valor booleano (true o false):");
        boolean valor1 = scanner.nextBoolean();
        
        System.err.println("ingrese el segundo valor booleano (true o false):");
        boolean valor2 = scanner.nextBoolean();
        
        boolean resultadoAND = valor1 && valor2;
        boolean resultadoOR = valor1 || valor2;
        boolean resultadoNOT1 = !valor1;
        boolean resultadoNOT2 = !valor2;
        
        System.err.println("resultado de AND:" + resultadoAND);
        System.err.println("resultado de OR:" + resultadoOR) ;
        System.err.println("resultado de NOt para el primer valor: " + resultadoNOT1);
        System.err.println("resultado de NOT para el segundo valor: "+ resultadoNOT2);
        
    
   
      }
      }

```


```java

Ejercicio 8

import java.util.Scanner;

public class Mavenproject1 {

    public static void main(String[] args) {
       
    Scanner scanner = new Scanner(System.in);
    
        System.err.println("ingrese un numero entero");
        int numero = scanner.nextInt();
        
        String resultado = (numero>=0) ? "positivo" : "negativo";
        
        System.err.println("el numero ingresado es: " + resultado);
        
   
      }
      }

```
















