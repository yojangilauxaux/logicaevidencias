<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->
# Actividad: Ejecicios de métodos en Java
Implementar los siguientes métodos:

1- Escribe un método que reciba dos números como parámetros y devuelva el mayor de los dos.

2 -Escribe un método que reciba una cadena de texto como parámetro y devuelva el número de vocales que contiene.
3 -Escribe un método que reciba una cadena de texto como parámetro y devuelva una nueva cadena con todas las letras mayúsculas en minúsculas y viceversa.
4 -Escribe un método que reciba una cadena de texto como parámetro y devuelva el número de palabras que contiene.
5 -Escribe un método que reciba una cadena de texto como parámetro y devuelva una nueva cadena con todas las palabras en orden alfabético.

# Solución:

## Ejercicio 1
    ```java

    public static int obtenerMayor(int num1, int num2) {
     if (num1 > num2) {

     return num1;

     } else {

     return num2;
     }

  }
}
```

## Ejercicio 2
```java

 public int contarVocales(String texto) {
        int x = 0;
        texto = texto.toLowerCase(); 
        for (int i = 0; i < texto.length(); i++) {
        char c = texto.charAt(i);
        if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u') {
                x++;
            }
        }
        return x;


  }
}
```

## Ejercicio 3
```java

public String invertirMayusculasMinisculas(String texto) {
        StringBuilder resultado = new StringBuilder();
        for (int i = 0; i < texto.length(); i++) {
            char c = texto.charAt(i);

        if (Character.isUpperCase(c)) {
                resultado.append(Character.toLowerCase(c));

        } else if (Character.isLowerCase(c)) {
                resultado.append(Character.toUpperCase(c));

        } else {
                resultado.append(c);
            }
        }
        return resultado.toString();
    
   }
}
```


## Ejercicio 4
```java

public static int contarPalabras(String texto) {
   
        String[] palabras = texto.split("\\s+");
        return palabras.length;
    
   }
}

```

## Ejercicio 5
```java

 public String ordenarPalabrasAlfabeticamente(String texto) {
      
        String[] palabras = texto.split("\\s+");
            
        Arrays.sort(palabras);
        
        String textoOrdenado = String.join(" ", palabras);
        
        return textoOrdenado;
    
        
   }
}

```












