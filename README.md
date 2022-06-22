# exercicios-if-else

1)	Criando um programa que pede dois números e verifica qual deles é o maior:

import java.util.Scanner;

public class Main {
   public static void main(String[]args) {

   Scanner scanner = new Scanner(System.in);
   System.out.println("Digite um número: ");
   int a = scanner.nextInt();
   System.out.println("Digite um número: ");
   int b = scanner.nextInt();
   
   if (a > b) {
       System.out.println(a);
       
   } else {
       System.out.println(b);
   }
}
}

2)	Criando um programa que peça um número e verifica se é positivo ou negativo:

import java.util.Scanner;

public class Main {
   public static void main(String[]args) {

   Scanner scanner = new Scanner(System.in);
   System.out.println("Digite um número: ");
   int a = scanner.nextInt();
   
   if(a > 0) {
       System.out.println("O número é positivo");
   } else {
       System.out.println("O número é negativo");
   }  
}
}

3)	 Faça um programa que verifique (usando if e else) se uma letra digitada é “F” ou “M”. Conforme a letra escrever: F – Feminino, M- Masculino, Sexo inválido.

import java.util.Scanner;

public class Main {
   public static void main(String[]args) {

   Scanner scanner = new Scanner(System.in);
   System.out.println("Digite uma letra: ");
   String a = scanner.nextLine();
   
   if(a.equalsIgnoreCase("f")) {
       System.out.println("Sexo feminino");
   } else if(a.equalsIgnoreCase("m")) {
       System.out.println("Sexo masculino");
   } else {
       System.out.println("Sexo inválido");
   }
 
}
}

4)	Faça um programa que verifique (usando if e else) se uma letra digitada é vogal ou consoante

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Digite uma letra: ");
    String n1 = scanner.nextLine ();
    
    String a = "a";
    String e = "e";
    String i = "i";
    String o = "o";
    String u = "u";

    if(n1.equalsIgnoreCase(a)) {
      System.out.println ("Vogal");
    } else if(n1.equalsIgnoreCase(e)) {
        System.out.println ("Vogal");
    } else if(n1.equalsIgnoreCase(i)) {
        System.out.println ("Vogal");
    } else if(n1.equalsIgnoreCase(o)) {
        System.out.println ("Vogal");
    } else if(n1.equalsIgnoreCase(u)) {
        System.out.println ("Vogal");
    }
    
    else
    {
      System.out.println ("Consoante");
    }

  }
}

5)	 Faça um programa para a leitura de duas notas parciais de um aluno.

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira a nota: ");
    double n0 = scanner.nextDouble ();
    
    double a = 7;
    double b = 10;
    
    if(n0 == b) {
      System.out.println ("Aprovado com excelência");
    } else if(n0 >= a) {
      System.out.println ("Aprovado");
    } else {
        System.out.println("Reprovado");
    }

  }
}

6)	Faça um programa que leia três números, verifique (usando if e else), e mostre o maior deles.

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira o primeiro número: ");
    int n1 = scanner.nextInt ();
    System.out.println ("Insira o segundo número: ");
    int n2 = scanner.nextInt ();
    System.out.println ("Insira o terceiro número: ");
    int n3 = scanner.nextInt ();
    
    if((n1 > n2) && (n1 > n3)) {
      System.out.println (n1);
    } else if((n2 > n1) && (n2 > n3)) {
        System.out.println(n2);
    } else if((n3 > n1) && (n3> n2)) {
        System.out.println(n3);
    } 
  
  
  }
}

7)	Faça um programa que leia três números, verifique (usando if e else) e mostre o maior e o menor deles;

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira o primeiro número: ");
    int n1 = scanner.nextInt ();
    System.out.println ("Insira o segundo número: ");
    int n2 = scanner.nextInt ();
    System.out.println ("Insira o terceiro número: ");
    int n3 = scanner.nextInt ();
    
    if((n1 > n2) && (n1 > n3)) {
      System.out.println ("O maior é: " + n1);
    } else if((n2 > n1) && (n2 > n3)) {
        System.out.println("O maior é: " + n2);
    } else if((n3 > n1) && (n3> n2)) {
        System.out.println("O maior é: " + n3);
    } 
    
    if((n1 < n2) && (n1 < n3)) {
      System.out.println ("O menor é: " + n1);
    } else if((n2 < n1) && (n2 < n3)) {
        System.out.println("O menor é: " + n2);
    } else if((n3 < n1) && (n3 < n2)) {
        System.out.println("O menor é: " + n3);
    } 
  
  
  }
}
