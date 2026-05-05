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



