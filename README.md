C#

20/03/2026

//Aula introdutória de Programação
//variáveis
string nome;
int ano, idade;

//entrada de dados
Console.Write("Informe seu nome: ");
nome = Console.ReadLine();
Console.Write("Informe seu ano de nascimento: ");
ano = Convert.ToInt32(Console.ReadLine());

//Processamento
idade = 2026 - ano;  //calculo da idade

 //saída
Console.WriteLine($"Bom dia, {nome}, seja bem Vindo!");
Console.WriteLine($"{nome}, você tem {idade} anos!");
Console.WriteLine($"{nome}, ano que vem você fará {idade + 1} anos!");





24/03/2026


/*//Exercício 1
//Variáveis
int numA, numB;

//Entrada de Dados
Console.WriteLine("Informe o número para  NumA:");
numA = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Informe o número para NumB:");
numB = Convert.ToInt32(Console.ReadLine());

//Saída de Dados
Console.WriteLine($"Os números que você digitou foi:{numB} e {numA}");



//Exercício 2

//Variáveis
double HT, VH, PD, SB, TD, SL;

//Entrada de Dados
Console.Write("Informe a quantidade de horas trabalhadas no mês:");
HT = Convert.ToDouble(Console.ReadLine());
Console.Write("Informe o valor da hora trabalhada:");
VH = Convert.ToDouble(Console.ReadLine());
Console.Write("Informe o percentual de desconto:");
PD = Convert.ToDouble(Console.ReadLine());

//Processamento

SB = HT * VH;
TD = (PD / 100) * SB;
SL = SB - TD;

//Saída de Dados
Console.WriteLine("\n******RESUMO******\n");
Console.WriteLine($"horas trabalhadas:{HT} horas");
Console.WriteLine($"Salário Bruto: R${SB:F2}");
Console.WriteLine($"Total de descontos: R${TD:F2}");
Console.WriteLine($"Salário Líquido: R$ {SL:F2}");

*/
//Exercício 3

//Variáveis
double C, F;

//Entrada de Dados
Console.Write("Informe a temperatura em Graus Celsius: ");
C = Convert.ToDouble(Console.ReadLine());

//Processamento
F = (9 * C + 160) / 5;

//Saída
Console.WriteLine($"{C}° Graus Celsius são {F}° Fahrenheit");

DIA 07 04 2026



//Exercício 4 

//Exercício 3 Dia 07 04

//Variáveis
double val1, val2, media;

//Entrada
Console.WriteLine("Informe o primeiro valor: ");
val1 =Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Informe o segundo valor: ");
val2 = Convert.ToDouble(Console.ReadLine());

//Processamento
media = (val1 + val2) / 2;

//Saída
Console.WriteLine($"A média entre {val1} e {val2} é {media}");
/*
//Exercício 4 Dia 07 04 2026

//Variáveis

Double velocidadeKmh, velocidadems;

//Entrada
Console.WriteLine("Informe a velocidade em Km/hora :");
velocidadems = Convert.ToDouble(Console.ReadLine());

//Processamento

velocidadeKmh = velocidadems / 3.6;



//Saída

Console.WriteLine($" {velocidadeKmh} Km/h são {velocidadems} metros / segundo");

/*


//Exercício 5    07/04/2026

//Variáveis

double SB, PrevSocial, Imposto, SL;


//Entrada

Console.WriteLine("Informe o seu salário bruto:");
SB = Convert.ToDouble(Console.ReadLine());

//Processamento
PrevSocial = SB * 0.10;     //SB * (10/100)
Imposto = (SB - PrevSocial) * 0.05;
SL = SB - PrevSocial - Imposto;

//Saída
Console.WriteLine("**********Resumo Final*********");
Console.WriteLine($"Salário Bruto ...: R$ {SB:F2}");
Console.WriteLine($"Previdência Social...:R${PrevSocial:F2}");
Console.WriteLine($"Imposto....:{Imposto:F2}");
Console.WriteLine($"Salário Líquido.....:R$ {SL:F2}");

*/
//Exercício 6 

//Variáveis

int N, C, D, U, M;

//Entrada
Console.WriteLine("Informe um número com 3 algarismos:");
N=Convert.ToInt32(Console.ReadLine());

//Processamento

C = N / 100;
D = (N % 100) / 10;
U= (N % 100) % 10;

M = (U * 100) + (D * 10) + C;

//Saída 
Console.WriteLine($"O número inverso é {M}");


Dia 10/04/2026

/*
//Exemplo 1
//variáveis

string nome;
double salario;

//Entrada

Console.WriteLine("Informe seu nome:");
nome = Console.ReadLine();
Console.WriteLine("Informe o seu salário:");
salario = Convert.ToDouble(Console.ReadLine());

//Processamento
if (salario <= 150) ;
{

    salario = salario + 30;
}

//Saída

Console.WriteLine($"{nome}, seu salário é {salario:F2}");
/*

//Exemplo 2
//Varíaveis

double nota1, nota2, nota3, media;

//Entrada
Console.WriteLine("Informe a sua 1º nota:");
nota1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Informe a sua2º nota:");
nota2 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Informe a sua3º nota:");
nota3 = Convert.ToDouble(Console.ReadLine());

//Processamento
media = (nota1 + nota2 + nota3) / 3;

//Saída

if (media <= 7)
{

    Console.WriteLine($"Aluno reprovado com média {media:F2}");

}

else 
{


    Console.WriteLine($"Aluno aprovado com média  {media:F2}");

}


*/
//Exemplo 3
//Varíaveis

int num1, num2;

//Entrada

//Entrada
Console.WriteLine("Informe o primeiro valor: ");
num1 = Convert.ToInt32(Console.ReadLine());
Console.WriteLine("Informe o segundo valor: ");
num2 = Convert.ToInt32(Console.ReadLine());


if (num1 > num2)
{

    Console.WriteLine($"o número {num1} é o maior!");

}
else
{
    if (num2 > num1)
    {
        Console.WriteLine($"O número {num2} é maior!");

    }
    else
    {
        Console.WriteLine($"Os números {num1} e {num2} são iguais!");
    }

}



//Swith Case dia 06 05 2026




//Variáveis
//Atividade 1

/*

//Ler número de 1 a 7 e imprimir o dia correspondente

int numero;

//Entrada

Console.WriteLine("Informe o número para o dia da semana conrrespondente:");
numero = Convert.ToInt32(Console.ReadLine());

//Processamento e Saída

switch (numero)
{
    case 1:
        Console.WriteLine("Domingo");
        break;
    case 2:
        Console.WriteLine("Segunda-feira");
        break;
    case 3:
        Console.WriteLine("Terça-feira");
        break;
    case 4:
        Console.WriteLine("Quarta-feira");
        break;
    case 5:
        Console.WriteLine("Quinta-feira");
        break;
    case 6:
        Console.WriteLine("Sexta-feira");
        break;
    case 7:
        Console.WriteLine("Sábado");
        break;
    default:
        Console.WriteLine("Número inválido. Por favor, informe um número entre 1 e 7.");
        break;
}
*/

/*
 
//Variáveis
//Atividade 2 

//Ler letra e identificar usando fallthrough para agrupar vogais

char letra;

Console.WriteLine("Informe uma letra:");
letra = Convert.ToChar(Console.ReadLine());

switch (letra)
{
    case 'a':
    case 'e':
    case 'i':
    case 'o':
    case 'u':
    case 'A':
    case 'E':
    case 'I':
    case 'O':
    case 'U':
        Console.WriteLine("A letra é uma vogal.");
        break;
    default:
        Console.WriteLine("A letra é uma consoante !");
        break;
}
*/



//Variáveis
//Atividade 3

//Ler código do produto e exibir nome e preço

/*

double codigoProduto, preçoproduto;
string nomeProduto;

//Entrada
Console.WriteLine("Cachorro-Quente.....001");
Console.WriteLine("X-Salada.....002");
Console.WriteLine("X-Bacon.....003");
Console.WriteLine("Bauru.....004");
Console.WriteLine("Refrigerante.....005");

Console.WriteLine("\nInforme o código do produto:");
codigoProduto = Convert.ToDouble(Console.ReadLine());
Console.Clear();

//Processamento e Saída

switch (codigoProduto)
{
    case 1:
        nomeProduto = "Cachorro Quente";
        preçoproduto = 10.00;
        Console.WriteLine($"Produto: {nomeProduto}, Preço: R${preçoproduto}");
        break;
    case 2:
        nomeProduto = "X-Salada";
        preçoproduto = 15.00;
        Console.WriteLine($"Produto: {nomeProduto}, Preço: R${preçoproduto}");
        break;
    case 3:
        nomeProduto = "X-Bacon";
        preçoproduto = 18.00;
        Console.WriteLine($"Produto: {nomeProduto}, Preço: R${preçoproduto}");
        break;
    case 4:
        nomeProduto = "Bauru";
        preçoproduto = 12.00;
        Console.WriteLine($"Produto: {nomeProduto}, Preço: R${preçoproduto}");
        break;
    case 5:
        nomeProduto = "Refrigerante";
        preçoproduto = 8.00;
        Console.WriteLine($"Produto: {nomeProduto}, Preço: R${preçoproduto}");
        break;
    default:
        Console.WriteLine("Código de produto inválido,sabe ler não resto de aborto?");
        break;
}

if (codigoProduto == 1 || codigoProduto == 2 || codigoProduto == 3 || codigoProduto == 4 || codigoProduto == 5)
{
    Console.WriteLine("Obrigado pela preferência!");
}
else
{
    Console.WriteLine("Tente novamente com um código válido.");
}
*/
/*
 * 
 *Atividade 4
 *
using System;

namespace CalculadoraSimples
{
    class Program
    {
        static void Main(string[] args)
        {
            double num1, num2, resultado = 0;
            char operador;
            bool operadorValido = true;

            Console.WriteLine("--- Calculadora ---");

            // 1. Ler o primeiro número
            Console.Write("\nDigite o primeiro número: ");
            num1 = Convert.ToDouble(Console.ReadLine());

            // 2. Ler o operador
            Console.Write("Digite o operador (+, -, *, /): ");
            operador = Convert.ToChar(Console.ReadLine());

            // 3. Ler o segundo número
            Console.Write("Digite o segundo número: ");
            num2 = Convert.ToDouble(Console.ReadLine());

            // 4. Processar o cálculo
            switch (operador)
            {
                case '+':
                    resultado = num1 + num2;
                    break;
                case '-':
                    resultado = num1 - num2;
                    break;
                case '*':
                    resultado = num1 * num2;
                    break;
                case '/':
                    // Verifica divisão por zero
                    if (num2 != 0)
                        resultado = num1 / num2;
                    else
                    {
                        Console.WriteLine("Erro: Divisão por zero não permitida.");
                        operadorValido = false;
                    }
                    break;
                default:
                    Console.WriteLine("Operador inválido.");
                    operadorValido = false;
                    break;
            }

            // 5. Exibir resultado
            if (operadorValido)
            {
                Console.WriteLine($"Resultado: {num1} {operador} {num2} = {resultado}");
            }

            Console.ReadKey();
        }
    }
}


*/

/*

//Atividade 5 
using System;

class Program
{
    static void Main()
    {
        Console.Write("Digite a idade: ");
        if (int.TryParse(Console.ReadLine(), out int idade))
        {
            string categoria;

            // Lógica de classificação
            if (idade >= 0 && idade <= 12)
            {
                categoria = "Infantil";
            }
            else
                if (idade >= 13 && idade <= 17)
            {
                categoria = "Juvenil";
            }
            else 
                if (idade >= 18)
            {
                categoria = "Sênior";
            }
            else
            {
                categoria = "Idade inválida";
            }

            Console.WriteLine($"A categoria é: {categoria}");
        }
        else
        {
            Console.WriteLine("Por favor, insira um número válido.");
        }
    }
}


*/



