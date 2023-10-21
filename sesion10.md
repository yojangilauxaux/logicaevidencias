<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->
# Actividad: Prueba, ejecución y explicación de ejercicios de lógica de programación.
 ## Selecciona dos ejercicios de la sesión 10, impleméntalos, ejecútalos y proporciona una explicación detallada de cada uno


## ejercicio 1: este ejercicio Solicita al usuario ingresar el monto del deposito, la tasa de interes anual y el plazo en meses, luego calcula el interes mensual y muestra un resumen que incluye el monto del deposito, la tasa de interes, el plazo en meses, el interes mensual y el monto total al vencimiento del cdt

 ```java

 import java.util.Scanner;
import java.text.DecimalFormat;

public class Main {
    public static void main(String[] args) {
        DecimalFormat decimalFormat = new DecimalFormat("#,###");
        Scanner scanner = new Scanner(System.in);

        System.out.println("Bienvenido al calculador de CDT!");

        // Pedir al usuario que ingrese los datos del CDT
        System.out.print("Ingrese el monto del depósito: ");
        double montoDeposito = scanner.nextDouble();

        System.out.print("Ingrese la tasa de interés anual (%): ");
        double tasaInteresAnual = scanner.nextDouble();

        System.out.print("Ingrese el plazo en meses: ");
        int plazoMeses = scanner.nextInt();

        // Calcular el interés y el monto total al vencimiento
        double tasaInteresMensual = tasaInteresAnual / 12 / 100;
        double interesMensual = montoDeposito * tasaInteresMensual;
        double montoTotalVencimiento = montoDeposito + (interesMensual * plazoMeses);

        // Mostrar el resumen del CDT
        System.out.println("Resumen del CDT:");
        System.out.println("- Monto del depósito: $" + decimalFormat.format(montoDeposito));
        System.out.println("- Tasa de interés anual: " + tasaInteresAnual + "%");
        System.out.println("- Plazo en meses: " + plazoMeses);
        System.out.println("- Interés mensual: $" + interesMensual);
        System.out.println("- Monto total al vencimiento: $" + decimalFormat.format(montoTotalVencimiento));
    }
}

 ```


## ejercicio2: este ejercicio, solicita al usuario ingresar su peso en kilogramos y su altura en metros, luego se calcula em IMC dividiendo el peso entre la altura al cuadrado, Finalmente se muestra el resultado en la consola con dos decimales utilizando el método printf de la clase System.out.

 ```java

 import java.util.Scanner;

public class IMC {
   public static void main(String[] args) {
      Scanner input = new Scanner(System.in);
      double weight, height, imc;
      
      // Solicita el peso y la altura
      System.out.print("Ingrese su peso en kilogramos: ");
      weight = input.nextDouble();
      System.out.print("Ingrese su altura en metros: ");
      height = input.nextDouble();

      // Calcula el IMC
      imc = weight / (height * height);

      // Muestra el resultado en la consola
      System.out.printf("Su IMC es %.2f", imc);
   }
}

```



