# Aulas_JAVA

ex20 lista01:


import java.util.Scanner;

///20. Leia um número e exiba todos os números de 0 até esse número.

public class Main {
    public static void main(String[] args) {
        Scanner leitor = new Scanner(System.in);

        System.out.print("Digite um número: ");
         int valorDigitado = leitor.nextInt();

         for (int index=0; index<valorDigitado; index++){
             System.out.println(index);
         }
    }
}
