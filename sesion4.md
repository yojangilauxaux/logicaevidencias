<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 4


<!-- Su documentación aquí -->
# actividad 4 Ejercicios de control de flujo con expresiones compuestas - Yojan gil y nicolar garcia.

Con la información anterior, implementa los siguientes ejercicios:

1 -Determinar si el estudiante es mayor de edad y tiene un estado activo.
2 -Determinar si el estudiante tiene una beca o una carrera relacionada con el desarrollo de software.
3 -Determinar si el estudiante está en el último semestre de su carrera y tiene un estado activo.
4 -Determinar si el estudiante tiene una carrera relacionada con el desarrollo de software y un promedio superior a 4.0.
5 -Mostrar toda la información del estudiante si está matriculado en el Cesde.
6 -Asignar una beca del 50% si el estudiante está matriculado en el Cesde, tiene un promedio superior a 4.0 y está activo.
7 -Determinar la cantidad de beca que recibe el estudiante según su promedio:
0.0 - 3.4: El estudiante no recibe beca.
3.5 - 3.9: El estudiante recibe una beca parcial del 25%.
4.0 - 4.4: El estudiante recibe una beca parcial del 50%.
4.5 - 5.0: El estudiante recibe una beca completa.

```java

String nombre = "Juan Pérez";
String apellido = "González";
String identificación = "1000000001";
String correo = "juan.perez@ejemplo.com";
String carrera = "Desarrollo de Software";
String universidad = "Cesde";
int edad = 20;
boolean esActivo = true;
boolean becado = false;
char género = 'M';
double promedio = 4.5;
int semestre = 2;
  
  
 System.out.println( "...........................");
 
 
 System.out.println( "ejercicio 1.");

int edad = 20;
boolean esActivo = true;

if (edad >= 18 && esActivo) {
 System.out.println( " es mayor de edad y esta activo.");


 System.out.println( "...........................");
System.out.println( "ejercicio 2 .");

String carrera = "Desarrollo de Software";
boolean becado = false;

if (becado || carrera.equals("Desarrollo de Software")) {
System.out.println( " tiene una beca o está en la carrera de Desarrollo de Software.");


System.out.println( "...........................");
System.out.println( "ejercicio 3 .");

int semestre = 2;
boolean esActivo = true;

 if (semestre == 10 && esActivo) {
   
 System.out.println( " está en el último semestre de su carrera y tiene un estado activo.");
   
} else {
 System.out.println( " no cumple con ambos requisitos.");
 }

System.out.println( "...........................");
System.out.println( "ejercicio 4 .");

String carrera = "Desarrollo de Software";
double promedio = 4.5;

 if (carrera.equals("Desarrollo de Software") && promedio > 4.0) {
   
 System.out.println( " tiene una carrera relacionada con el desarrollo de software y un promedio superior a 4.0.");
   
 } else {
System.out.println( " no cumple con ambos requisitos.");


System.out.println(+ "...........................");
System.out.println( "ejercicio 5 .");

String nombre = "Juan Pérez";
String apellido = "González";
String identificación = "1000000001";
String correo = "juan.perez@ejemplo.com";
String carrera = "Desarrollo de Software";
String universidad = "Cesde";
int edad = 20;
boolean esActivo = true;
boolean becado = false;
char género = 'M';
double promedio = 4.5;
int semestre = 2;

 if (universidad.equals("Cesde")) {
System.out.println("Información del estudiante:"); System.out.println("Nombre: " + nombre);
System.out.println("Apellido: " + apellido); System.out.println("Identificación: " + identificacion);
System.out.println("Correo: " + correo);
System.out.println("Carrera: " + carrera);
System.out.println("Universidad: " + universidad);
System.out.println("Edad: " + edad);
System.out.println("Activo: " + esActivo);
System.out.println("Becado: " + becado);
System.out.println("Género: " + genero);
System.out.println("Promedio: " + promedio);
System.out.println("Semestre: " + semestre);
   


   
System.out.println(+ "...........................");
System.out.println( "ejercicio 6 .");

if(universidad == "Cesde"  && promedio >= 4.1 && esActivo){

System.out.println("Tienes una beca del 50%");


System.out.println(+ "...........................");
System.out.println( "ejercicio 7 .");

if(promedio >= 4.5){
System.out.println("el estudiante recibe una beca");
        
                
 public class Actividadlogicadepg {

public static void main(String[] args) {
        
 System.out.println("-----------------------------------------------------------------------------------");
System.out.println("Ejercicio 8");

String mensaje = (género == 'F') ? "El estudiante es mujer" : (género == 'M') ? "El estudiante es hombre" : "El género del estudiante es desconocido";

System.out.println(mensaje);
        
System.out.println("------------------------------------------------------------------------------------");
        
System.out.println("Ejercicio 9");
        
System.out.println("Escoja la talla de la camisa: 1.S, 2.M, 3.L, 4.XL, 5.XXL");
        
int talla = input.nextInt ();
        
switch(talla){
        
case 1:
System.out.println("Eleigio la talla S");
break;
                
case 2:    
System.out.println("Eligio la talla M");
break;
                
case 3:     
System.out.println("Elegio la talla L");
break; 
                
case 4:    
System.out.println("Eligio la talla XL");
break; 
                
case 5:    
System.out.println("Eligio la talla XXL");
break;
                
default:    
System.out.println("Talla no disponible");
                
        }      
      
System.out.println("-----------------------------------------------------------------------------------------------------");

System.out.println("Ejercicio 10");
        
System.out.println("Ingrese su edad");
int edad = Scanner.nextInt();     

```
                
        
        











