# githup_suma
código en java de suma


package suma_githup;

import java.util.Scanner;


public class Suma_githup {

public static void main(String[] args) {
        float numero1 = 0; float numero2 = 0; float resultado;

Scanner reader = new Scanner(System.in);

System.out.println("Introduce el primer número:"); numero1 = reader.nextFloat();

System.out.println("Introduce el segundo número:"); numero2 = reader.nextFloat();

resultado = numero1+numero2; System.out.println("La suma es " + numero1 + " + " + numero2 + " = " + resultado); }   
}
