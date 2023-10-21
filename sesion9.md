<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->
# Ejercicios de Lógica de Programación -  Calculadora de resistencias eléctricas

# solución:

```java

public static void main(String[] args) {
      
         String color1 = menu();
        System.out.println("El primer color seleccionado es: " + color1);

        String color2 = menu();
        System.out.println("El segundo color seleccionado es: " + color2);

        String color3 = menu();
        System.out.println("El tercer color seleccionado es: " + color3);

        String tolerancia = menutolerancia();
        System.out.println("La tolerancia seleccionada es: " + tolerancia + "%");

       
        int valor1 = Integer.parseInt(color1);
        int valor2 = Integer.parseInt(color2);
        int multiplicador = Integer.parseInt(color3);

        
        int valor = ((valor1 * 10) + valor2) * (int) Math.pow(10, multiplicador);

        
        System.out.println("El valor de la resistencia es: " + valor + " ohms");
    }

    public static String menu() {
        Scanner input = new Scanner(System.in);

        System.out.println("0 = negro");
        System.out.println("1 = cafe");
        System.out.println("2 = rojo");
        System.out.println("3 = naranja");
        System.out.println("4 = amarillo");
        System.out.println("5 = verde");
        System.out.println("6 = azul");
        System.out.println("7 = morado");
        System.out.println("8 = gris");
        System.out.println("9 = blanco");

        System.out.println("Seleccione un color: ");
        return input.nextLine();
    }

    public static String menutolerancia() {
        Scanner input = new Scanner(System.in);

        System.out.println("Seleccione la tolerancia:");
        System.out.println("1 = Marrón (1%)");
        System.out.println("2 = Rojo (2%)");
        System.out.println("3 = Oro (5%)");
        System.out.println("4 = Plata (10%)");

        System.out.println("Seleccione una opcion: ");
        String opcion = input.nextLine();
        
        switch (opcion) {
            case "1":
                return "1";
            case "2":
                return "2";
            case "3":
                return "5";
            case "4":
                return "10";
            default:
                return "5"; 
        }
    }

        
    }

```












