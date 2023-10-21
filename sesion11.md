<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->
# Actividad: Ejercicios de Lógica de Programación
 ## Basándose en el algoritmo 1 de la sesión 11, aplicar la siguiente variante: Dado un conjunto de números enteros, se debe determinar si existe algún número que aparezca más de una vez. Si es así, se deben imprimir todos los números que aparezcan más de una vez.

 # solucion 1:

 
```java

import java.util.ArrayList;

/**
 *
 * @author yojan
 */

public class Mavenproject3 {

    public static void main(String[] args) {
    int[] numeros = {1, 2, 3, 4, 5, 2};

    // Creamos una lista para almacenar los números que aparecen más de una vez
    ArrayList<Integer> numerosRepetidos = new ArrayList<>();

    // Recorremos el conjunto de números
    for (int i = 0; i < numeros.length; i++) {
            
    // Comprobamos si el número actual ya ha aparecido
    for (int j = 0; j < i; j++) {
            
    if (numeros[i] == numeros[j]) {
    // el número actual ya ha aparecido
    // Agregamos el número a la lista de números repetidos
        
    numerosRepetidos.add(numeros[i]);
     break;
      }
        }
    }

    // Si hay números repetidos, los imprimimos
    if (!numerosRepetidos.isEmpty()) {
    System.out.println("Los números repetidos son: " + numerosRepetidos);
    } else {
    // No hay ningún número repetido
    System.out.println("No hay ningún numero repetido");
    }
    }
}
       
   
 
```












