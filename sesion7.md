<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 7 


<!-- Su documentación aquí -->
# EJERCICIO ARRAY:

```java

import java.util.Scanner;
         
public class Mavenproject1 {
  
 public static void main(String[] args) {
     
int[] numeros = {10, 20, 30, 40, 50};
      
int suma = 0;
          
for (int i = 0; i < numeros.length; i++) {
suma += numeros[i];
        }
double promedio = (double) suma / numeros.length;
      
System.out.println("El promedio de los números en el arreglo es: " + promedio);
          
           
  }

}


```

# ejercicio ARRRAYLIST:

```java

import java.util.ArrayList;

public class Mavenproject1 {
  
 public static void main(String[] args) {
     
ArrayList<String> nombres = new ArrayList<>();
          
nombres.add("Juan");

nombres.add("María");

nombres.add("Carlos");

nombres.add("Ana");  

System.out.println("Nombres en la lista:");

for (String nombre : nombres) {
    
System.out.println(nombre);

        }

  }

}

```












