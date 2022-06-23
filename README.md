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

8)	Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre o mais barato. 

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Preço do produto 1: ");
    double p1 = scanner.nextDouble ();
    System.out.println ("Preço do produto 2: ");
    double p2 = scanner.nextDouble ();
    System.out.println ("Preço do produto 3: ");
    double p3 = scanner.nextDouble ();
    
      if((p1 < p2) && (p1 < p3)) {
      System.out.println ("Esse é o produto ideal: " + p1);
    } else if((p2 < p1) && (p2 < p3)) {
        System.out.println("Esse é o produto ideal: " + p2);
    } else if((p3 < p1) && (p3 < p2)) {
        System.out.println("Esse é o produto ideal: " + p3);
    } 
    }
    }
    
 9) Faça um programa que leia três números e mostre-os em ordem decrescente:
 
import java.util.Scanner;
public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira: ");
    int n1 = scanner.nextInt ();
    System.out.println ("Insira: ");
    int n2 = scanner.nextInt ();
    System.out.println ("Insira: ");
    int n3 = scanner.nextInt ();
    
    if((n1 > n2) && (n1 > n3) && (n2 > n3)) {
    System.out.println ("= " + n1);
    System.out.println ("= " + n2);
    System.out.println ("= " + n3);
    } else if ((n2 > n1) && (n2 > n3) && (n1 > n3)) {
    System.out.println ("= " + n2);
    System.out.println ("= " + n1);
    System.out.println ("= " + n3);
    } else if ((n3 > n1) && (n3 > n2) && (n2 > n1)) {
    System.out.println ("= " + n3);
    System.out.println ("= " + n2);
    System.out.println ("= " + n1);
    } else if ((n2 > n1) && (n2 > n3) && (n3 > n1)) {
    System.out.println ("= " + n2);
    System.out.println ("= " + n3);
    System.out.println ("= " + n1);
    }
    }
    }

10)	 Faça um programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-vespertino ou N-noturno. Imprima a mensagem “Bom dia!” ou  “Boa Noite” ou “Valor inválido”, conforme o caso.  

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Em qual turno você estuda? Digite M, V ou N: ");
    String t = scanner.nextLine ();
    
    if(t.equalsIgnoreCase("m")) {
    System.out.println ("Bom dia! ");
    
    }  else if (t.equalsIgnoreCase("v")) {
    System.out.println ("Boa tarde! ");
    
    } else if (t.equalsIgnoreCase("n")) {
    System.out.println ("Boa noite! ");
    
    } else {
    System.out.println("Valor inválido ");
    }
    }
    }
  
11) As organizações CSM resolveram dar um aumento de salário aos seus colaboradores e lhe contrataram para desenvolver o programa que calculará os reajustes.  
•	a. Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério, baseado no salário atual;
•	b. Salários até R$ 280,00 (incluindo): aumento de 20%;
•	c. Salários entre R$ 280,00 e R$700,00: aumento de 15%;
•	d. Salários entre R$ 700,00 e R$ 1500,00: aumento de 10%;
•	e. Salários de R$ 1500,00 em diante: aumento de 5%
Após o aumento ser realizado; informe na tela;
•	a. O salário antes do reajuste;
•	b. O percentual de aumento aplicado;
•	c. O valor do aumento;
•	d. O novo salário, após o aumento.  

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    
    
    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira aqui seu salário: ");
    double s = scanner.nextDouble ();
    
    if(s <= 280) {
    System.out.println("Salário antes do reajuste: " + s);
    System.out.println("Percentual aplicado: 20%");
    System.out.println("Valor do aumento: " + (s * 20 / 100));
    System.out.println("Novo salário: " + (s + (s * 20 / 100)));
    
    } else if((s > 280) && (s <= 700)) {
    System.out.println("Salário antes do reajuste: " + s);
    System.out.println("Percentual aplicado: 15%");
    System.out.println("Valor do aumento: " + (s * 15 / 100));
    System.out.println("Novo salário: " + (s + (s * 15 / 100)));
    
    } else if((s > 700) && (s <= 1500)) {
    System.out.println("Salário antes do reajuste: " + s);
    System.out.println("Percentual aplicado: 10%");
    System.out.println("Valor do aumento: " + (s * 10 / 100));
    System.out.println("Novo salário: " + (s + (s * 10 / 100)));
    
    } else if(s > 1500) {
    System.out.println("Salário antes do reajuste: " + s);
    System.out.println("Percentual aplicado: 5%");
    System.out.println("Valor do aumento: " + (s * 5 / 100));
    System.out.println("Novo salário: " + (s + (s * 5 / 100)));
    }
    }
    }
    
 
 12) Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do imposto de Renda, que depende do salário bruto (conforme tabela abaixo) e 3% para o Sindicato e que o FGTS corresponde a 11% do salário bruto, mas não é descontado (é a empresa que deposita.)

O salário líquido corresponde ao salário bruto menos os descontos O programa deverá pedir ao usuário o valor da sua hora e a quantidade de horas trabalhadas no mês.

a. Imprima salário bruto, desconto do IR; Desconto do INSS, FGTS, Total de descontos e salário liquido.

b. Salário Bruto ate R$900,00 (inclusive) – Isento;
c. Salário Bruto de R$ 1500, 00 (inclusive) – desconto de 5%;
d. Salario bruto até R$ 2500,00 (Inclusive) – desconto de 10%;
e. Salário bruto acima de 2500 – Desconto de 20%.
Imprima na tela as informações, dispostas conforme o exemplo abaixo, no exemplo valor da hora é 5 e a quantidade de horas é 220.  

import java.util.Scanner;

public class Main
{
      public static void main (String[]args)
         {
         
    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira aqui o valor da sua hora: ");
    double hd = scanner.nextDouble ();
    System.out.println ("Insira aqui a quantidade de horas trabalhadas no mês: ");
    double hm = scanner.nextDouble ();
    
    double hdm = (hd * hm);
    
    if(hdm <= 900) {
    System.out.println("Salário bruto: R$ " + hdm);
    System.out.println("IR (-): R$ " + (hdm * 0 / 100));
    System.out.println("INSS (-): R$ " + (hdm * 10 / 100));
    System.out.println("FGTS: R$ " + (hdm * 11 / 100));
    System.out.println("Total de descontos: R$ " + (hdm * 10 / 100));
    System.out.println("Salário liquido: R$ " + (hdm - (hdm * 10 / 100)));

    } else if(hdm <= 1500) {
    System.out.println("Salário bruto: R$ " + hdm);
    System.out.println("IR (-): R$ " + (hdm * 5 / 100));
    System.out.println("INSS (-): R$ " + (hdm * 10 / 100));
    System.out.println("FGTS: R$ " + (hdm * 11 / 100));
    System.out.println("Total de descontos: R$ " + (hdm * 15 / 100));
    System.out.println("Salário liquido: R$ " + (hdm - (hdm * 15 / 100)));

    } else if(hdm <= 2500) {
    System.out.println("Salário bruto: R$ " + hdm);
    System.out.println("IR (-): R$ " + (hdm * 10 / 100));
    System.out.println("INSS (-): R$ " + (hdm * 10 / 100));
    System.out.println("FGTS: R$ " + (hdm * 11 / 100));
    System.out.println("Total de descontos: R$ " + (hdm * 20 / 100));
    System.out.println("Salário liquido: R$ " + (hdm - (hdm * 20 / 100)));
   
    } else if(hdm > 2500) {
    System.out.println("Salário bruto: R$ " + hdm);
    System.out.println("IR (-): R$ " + (hdm * 20 / 100));
    System.out.println("INSS (-): R$ " + (hdm * 10 / 100));
    System.out.println("FGTS: R$ " + (hdm * 11 / 100));
    System.out.println("Total de descontos: R$ " + (hdm * 30 / 100));
    System.out.println("Salário liquido: R$ " + (hdm - (hdm * 30 / 100)));
    }
    }
    }
    
  13) Faça um Programa que leia um número e exiba o dia correspondente da semana. (1- Domingo , 2- Segunda, etc.) se digitar outro valor deve aparecer “valor inválido)

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira o número correspondente ao dia da semana: ");
    int d = scanner.nextInt ();
    
    if(d == 1) {
        System.out.println("Domingo!");
        
    } else if(d == 2) {
        System.out.println("Segunda!");
    } else if(d == 3) {
        System.out.println("Terça!");
    } else if(d == 4) {
        System.out.println("Quarta!");
    } else if(d == 5) {
        System.out.println("Quinta!");
    } else if(d == 6) {
        System.out.println("Sexta!");
    } else if(d == 7) {
        System.out.println("Sábado!");
        
    } else {
        System.out.println("Inválido");
    }
    
    }
    }

14) Faça um programa que lê as duas notas parciais obtidas por um aluno numa disciplina ao longo de um semestre, e calcule a sua média. A atribuição de conceitos obedece à tabela abaixo: Entre 9.0 e 10.0 A

Entre 7.5 e 9.0   B
Entre 6.0 e 7.5   C
Entre 4.0 e 6.0   D
Entre 4.0 e 0     E  

O algoritmo deve mostrar na tela as notas, a média, o conceito correspondente e a mensagem “APROVADO” se o conceito for A, B ou C “REPROVADO” se o conceito for D ou E. 

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira a nota 1: ");
    double n1 = scanner.nextInt ();
    System.out.println ("Insira a nota 2: ");
    double n2 = scanner.nextInt ();

    double m = (n1 + n2);
    double M = (m / 2);
    
    if((M >= 9) && (M <= 10)) {
        System.out.println("Nota 1: " + n1);
        System.out.println("Nota 2: " + n2);
        System.out.println("Média: " + M);
        System.out.println("Conceito: A");
        System.out.println("Aprovado!");
        
    } else if((M >= 7.5) && (M < 9)) {
        System.out.println("Nota 1: " + n1);
        System.out.println("Nota 2: " + n2);
        System.out.println("Média: " + M);
        System.out.println("Conceito: B");
        System.out.println("Aprovado!");
        
    } else if((M >= 6) && (M < 7.5)) {
        System.out.println("Nota 1: " + n1);
        System.out.println("Nota 2: " + n2);
        System.out.println("Média: " + M);
        System.out.println("Conceito: C");
        System.out.println("Aprovado!");
        
    } else if((M >= 4) && (M < 6)) {
        System.out.println("Nota 1: " + n1);
        System.out.println("Nota 2: " + n2);
        System.out.println("Média: " + M);
        System.out.println("Conceito: D");
        System.out.println("Reprovado");
        
    } else if((M >= 0) && (M < 4)) {
        System.out.println("Nota 1: " + n1);
        System.out.println("Nota 2: " + n2);
        System.out.println("Média: " + M);
        System.out.println("Conceito: E");
        System.out.println("Reprovado");
    }
    }
    }
 
 15) Faça um programa que peça os 3 lados de um triângulo. O programa deverá informar se os valores podem ser um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno. Dicas:

Três lados formam um triangulo quando a soma de quaisquer dos dois lados é maior que o terceiro.
Triângulo Equilátero: três lados iguais;
Triângulo Isósceles: quaisquer dois lados iguais;
Triângulo Escaleno: três lados diferentes;

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Lado 1: ");
    int t1 = scanner.nextInt ();
    System.out.println ("Lado 2: ");
    int t2 = scanner.nextInt ();
    System.out.println ("Lado 3: ");
    int t3 = scanner.nextInt ();
    
    
    if((t1 + t2 < t3) || (t2 + t3 < t1) || (t3 + t1 < t2)){
        System.out.println("Não é um Triângulo");
        
    } else if((t1 == t2) && (t2 == t3)){
        System.out.println("Triângulo Equilátero");
    
    } else if((t1 == t2) || (t2 == t3) || (t3 == t1)) {
        System.out.println("Triângulo Isósceles");
        
    } else if((t1 != t2) && (t2 != t3)) {
        System.out.println("Triângulo Escaleno");
    } 
    }
    }
    
  16) Faça um Programa que peça um número inteiro e determine se ele e par ou ímpar. Dica: utilize o operador módulo (resto da divisão):

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira um número: ");
    int n = scanner.nextInt ();
    
    int d = (n % 2);
    
    if(d == 0) {
        System.out.println("Par!");
    } else {
        System.out.println("Impar!");
    }
    
    }
    }
    
   17) Faça um Programa que leia 1 número e em seguida pergunte ao usuário qual operação ele deseja realizar. O resultado da operação deve ser acompanhado de uma frase que diga se o número e:

Par ou ímpar;
Positivo ou negativo;

import java.util.Scanner;

public class Main
{
  public static void main (String[]args)
  {

    Scanner scanner = new Scanner (System.in);
    System.out.println ("Insira o número: ");
    int n1 = scanner.nextInt ();
    System.out.println ("Qual operação deseja realizar? Insira 1- saber se é par ou impar ou 2- saber se é positivo ou negativo");
    int op = scanner.nextInt();
    
    int r = (n1 % 2);
    
    if((op == 1) && (r == 0)) {
        System.out.println("O número é par");
        
    } else if((op == 1) && (r != 0)) {
        System.out.println("O número é impar");
    }
    
    if((op == 2) && (n1 > 0)) {
        System.out.println("O número é positivo");
        
    } else if((op == 2) && (n1 < 0)) {
        System.out.println("O número é negativo");
    }
    
    }
    }
