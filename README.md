# ExercicioJardelAula06 
A - Escreva um algoritmo que receba dez números do usuário e imprima a metade de cada número.    B - Escreva um algoritmo que imprima todos os números de 1 até 100 e a soma de todos eles.    C - Escreva um algoritmo que peça ao usuário para digitar números até que ele digite 0. Se ele digitar 0, só aí o programa deve parar.

// estrutura com for:

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Double numero;
    
    for(int i=0; i<10; i++){
      System.out.println("Digite um número: ");
      numero = entrada.nextDouble();
      
      System.out.println("A metade de " + numero + " é " +(numero/2));
    }
  }
}

// estrutura com while:

import java.util.Scanner;
class Main {
  public static void main(String[] args) {
    
    Scanner entrada = new Scanner(System.in);
    
    Integer numero;
    Integer contador = 0;
    
    while(contador<5){
      System.out.println("Digite um número: ");
      numero = entrada.nextInt();
      System.out.println("A metade de " +numero+ " é " +(numero/2));
      
      contador++;
    }
     
    
  }
}


