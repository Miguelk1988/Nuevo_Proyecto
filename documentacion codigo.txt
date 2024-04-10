//Se importa la libreria de Scanner
import java.util.Scanner;

//Se crea la clase 
 class miprograma
{
//se crea la clase main
    public static void main(String[] args) {
//se inicializa el objeto de scanner

Scanner scanner = new Scanner(System.in);

//Se imprime mensaje solicitando correo electronico
System.out.print("Introduce tu correo Electronico: ");
//se guarda en el objeto scanner la variable tipo String de correo
String correo = scanner.nextLine();

//Se imprime mensaje solicitando el nombre de la marca 
        System.out.print("Introduce el nombre de la marca: ");
// se crea la variable y se guarda en el objeto scanner la variabole tipo string marca
        String marca = scanner.nextLine();

//se imprime el mensaje solicitando el modelo
        System.out.print("Introduce el nombre del modelo: ");
//se crea la variable y se guarda en el objeto scanner la variable tipo string modelo 
        String modelo = scanner.nextLine();

//se imprime el mensaje solicitando el numero de la cilindrada
        System.out.print("Introduce el numero de la cilindrada: ");
//se crea la variable y se guarda en el objeto scanner la variable tipo int cilindrada
        int cilindrada = scanner.nextInt();

//se imprime el mensaje solicitando el tipo de combustible
        System.out.print("Introduce el tipo de combustible: ");
//se crea la variable y se guarda en el objeto scannner la variable tipo string combustible
        String combustible = scanner.nextLine();

// se imprime el mensaje solicitando el numero de pasajeros 
        System.out.print("Introduce el numero de la cantidad de pasajeros: ");
//se crea la variable y se guarda en el objeto scanner la variable tipo int de pasajeros 
        int pasajeros = scanner.nextInt();

       

        // se imprimen los resultados
        System.out.println("Usuario: " + correo);
        System.out.println("Marca: " + marca);
        System.out.println("Modelo: " + modelo);
        System.out.println("Cilindrada: " + cilindrada);
        System.out.println("Tipo de Combustible: " + combustible);
        System.out.println("Pasajeros: " + pasajeros);
        

//se cierra el objeto Scanner para que no continue con la lectura
        scanner.close();
    }
}