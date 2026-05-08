/*


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





24 / 03 / 2026


/*
//Exercício 1
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
val1 = Convert.ToDouble(Console.ReadLine());
Console.WriteLine("Informe o segundo valor: ");
val2 = Convert.ToDouble(Console.ReadLine());

//Processamento
media = (val1 + val2) / 2;

//Saída
Console.WriteLine($"A média entre {val1} e {val2} é {media}");

/*
 * 
 * 
 * 
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
/*
 * Escreva um programa que leia um número inteiro de 3 algarismos e imprima o número invertido. Por exemplo, se o usuário digitar 123, o programa deve imprimir 321.
*/
//Variáveis
/*
int N, C, D, U, M;

//Entrada
Console.WriteLine("Informe um número com 3 algarismos:");
N = Convert.ToInt32(Console.ReadLine());

//Processamento

C = N / 100;
D = (N % 100) / 10;
U = (N % 100) % 10;

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
/*
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


06 / 06 / 2026
//Swith Case e IF atividade de 1 a 10


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


//Exercício do dia 06/05/2026

//Exercício 1 
//Variáveis

/*
 * Crie um programa que peça ao usuário para digitar um número de 1 a 5. O programa deve usar um switch
para imprimir o número por extenso (ex: "Um", "Dois", etc.). Se o usuário digitar um número fora deste
intervalo, o default deve exibir "Número fora do limite".
*/
/*
int numero;

//Entrada

Console.WriteLine("Digite um número de 1 a 5:");
numero = Convert.ToInt32(Console.ReadLine());


//Processamento

if (numero == 0)
{
    Console.WriteLine("Número fora do limite,sabe ler não?");
}
else
{
    switch (numero)
    {
        case 1:
            Console.WriteLine("Um");
            break;
        case 2:
            Console.WriteLine("Dois");
            break;
        case 3:
            Console.WriteLine("Três");
            break;
        case 4:
            Console.WriteLine("Quatro");
            break;
        case 5:
            Console.WriteLine("Cinco");
            break;
        default:
            Console.WriteLine("Número fora do limite,sabe ler não?");
            break;
    }
}

*/

//Exercício 2
/*
 * Um restaurante deseja avaliar o atendimento. Peça ao cliente para digitar uma nota de 1 a 5, onde:
● 1: "Péssimo"
● 2: "Ruim"
● 3: "Razoável"
● 4: "Bom"
● 5: "Excelente"
Imprima a classificação correspondente. Adicione um default para notas inválidas.
*/
/*
//Variáveis
int numero;

Console.WriteLine("Informe uma nota de 1 a 5 para nos ajudar a avaliar o nosso atendimento:");
numero = Convert.ToInt32(Console.ReadLine());


//Processamento

if (numero == 0)
{
    Console.WriteLine("Número fora do limite,sabe ler não ou ta se fazendo de sonso(a)?");
}
else
{
    switch (numero)
    {
        case 1:
            Console.WriteLine("Nosso atendimento foi avaliado como: Pésimo!");
            break;
        case 2:
            Console.WriteLine("Nosso atendimento foi avaliado como: Ruim!");
            break;
        case 3:
            Console.WriteLine("Nosso atendimento foi avaliado como: Razoável!");
            break;
        case 4:
            Console.WriteLine("Nosso atendimento foi avaliado como: Bom!");
            break;
        case 5:
            Console.WriteLine("Nosso atendimento foi avaliado como: Excelente!");
            break;
        default:
            Console.WriteLine("Número fora do limite,sabe ler não,resto de aborto?");
            break;
    }
}

*/

//Exercício 3
/*Simule a tela de seleção de classe de um jogo de RPG. Peça ao usuário para escolher uma classe digitando:
● "G" para Guerreiro
● "M" para Mago
● "A" para Arqueiro
Use o switch (verificando uma variável do tipo char ou string) para imprimir uma mensagem de
boas-vindas adequada para a classe escolhida, informando o item inicial daquele personagem (ex:
Mago recebe um Cajado).
*/

//Variáveis
/*
string classe;
char itemInicial;

//Entrada
Console.WriteLine("==========================================================================================");
Console.WriteLine("Bem-vindo ao mundo de RPG! Antes de começar sua aventura, escolha sua classe de personagem:");
Console.WriteLine("==========================================================================================");

Console.WriteLine("Escolha sua classe de personagem para começar a aventura :");
Console.WriteLine("G - Guerreiro");
Console.WriteLine("M - Mago");
Console.WriteLine("A - Arqueiro");
Console.Write("Digite a letra correspondente à classe escolhida: ");
classe = Console.ReadLine().ToUpper();

//Processamento

switch (classe)
{
    case "G":
        itemInicial = 'E'; // Espada
        Console.WriteLine("Bem-vindo, Guerreiro! Você começa sua jornada com uma Espada.");
        break;
    case "M":
        itemInicial = 'C'; // Cajado
        Console.WriteLine("Bem-vindo, Mago! Você começa sua jornada com um Cajado.");
        break;
    case "A":
        itemInicial = 'B'; // Arco
        Console.WriteLine("Bem-vindo, Arqueiro! Você começa sua jornada com um Arco.");
        break;
    default:
        Console.WriteLine("Opção inválida. Por favor, escolha G, M ou A.");
        break;
}


*/

//Exercício 4
/*
 * Peça ao usuário que digite uma letra do alfabeto. Usando a técnica de fallthrough (empilhando os casos
vazios do switch), verifique se a letra digitada é uma vogal (A, E, I, O, U minúsculas ou maiúsculas) e
exiba "É uma vogal". No default, exiba "É uma consoante" (assumindo que o usuário digitou uma letra
válida).
*/
/*
 
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

//Exercício 5
/*
 * Peça ao usuário que digite um número de 1 a 7, representando os dias da semana (1 = Domingo, 2 =
Segunda, etc.). Use o switch com fallthrough para:
● Imprimir "Fim de semana" para os dias 1 e 7.
● Imprimir "Dia útil" para os dias de 2 a 6.
*/

//Variáveis
/*
 * 
int numero;

//Entrada

Console.WriteLine("Informe o número para o dia da semana conrrespondente:");
numero = Convert.ToInt32(Console.ReadLine());

//Processamento e Saída

switch (numero)
{
    case 1:
        Console.WriteLine("Fim de semana");
        break;
    case 2:
        Console.WriteLine("Dia útil");
        break;
    case 3:
        Console.WriteLine("Dia útil");
        break;
    case 4:
        Console.WriteLine("Dia útil");
        break;
    case 5:
        Console.WriteLine("Dia útil");
        break;
    case 6:
        Console.WriteLine("Dia útil");
        break;
    case 7:
        Console.WriteLine("Fim de semana");
        break;
    default:
        Console.WriteLine("Número inválido. Por favor, informe um número entre 1 e 7.");
        break;
}

*/

//Exercício 6
/*
 * Solicite ao usuário o número de um mês (1 a 12). Agrupe os casos para imprimir a estação do ano
aproximada correspondente no Brasil:
● 12, 1, 2: Verão
● 3, 4, 5: Outono
● 6, 7, 8: Inverno
● 9, 10, 11: Primavera
*/

//Variáveis

/*

int mês;

Console.WriteLine("Informe o número de um mês conrrespondente (1 a 12):");
Console.WriteLine("=====================================================");
Console.WriteLine("1-Janeiro");
Console.WriteLine("2-Fevereiro");
Console.WriteLine("3-Março");
Console.WriteLine("4-Abril");
Console.WriteLine("5-Maio");
Console.WriteLine("6-Junho");
Console.WriteLine("7-Julho");
Console.WriteLine("8-Agosto");
Console.WriteLine("9-Setembro");
Console.WriteLine("10-Outubro");
Console.WriteLine("11-Novembro");
Console.WriteLine("12-Dezembro");
Console.WriteLine("=======================================================");
mês = Convert.ToInt32(Console.ReadLine());


switch ( mês)
    {
    case 12:
    case 1:
    case 2:
        Console.WriteLine("Verão");
        break;
    case 3:
    case 4:
    case 5:
        Console.WriteLine("Outono");
        break;
    case 6:
    case 7:
    case 8:
        Console.WriteLine("Inverno");
        break;
    case 9:
    case 10:
    case 11:
        Console.WriteLine("Primavera");
        break;
    default:
        Console.WriteLine("Número inválido. Por favor, informe um número entre 1 e 12.");
        break;
}

*/


//Exercício 7

/*
 * Crie um programa que peça ao usuário para digitar dois números decimais (double). Em seguida, exiba um
menu de operadores matemáticos (+, -, *, /). Capture o operador em uma variável char. Use o switch para
realizar o cálculo correspondente e imprimir o resultado. No caso da divisão, tente não permitir divisões
por zero!
*/

/*

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

//Exercício 8
/*
 * Crie um menu de lanchonete exibindo o código, produto e preço:
● 100 - Cachorro Quente (R$ 15,00)
● 101 - Bauru (R$ 18,00)
● 102 - Hambúrguer (R$ 20,00)
● 103 - Cheeseburguer (R$ 22,00)
● 104 - Refrigerante (R$ 8,00)
O programa deve ler o código do item e a quantidade desejada. O switch deve encontrar o preço do
produto selecionado, multiplicar pela quantidade e exibir o valor total a ser pago.
*/

/*

//Variáveis
int codigoProduto, quantidade;
double preçoProduto, valorTotal;

//Entrada
Console.WriteLine("Bem-vindo à Lanchonete! Aqui está o nosso menu:");
Console.WriteLine("===============================================");
Console.WriteLine("Código - Produto - Preço");
Console.WriteLine("100 - Cachorro Quente - R$ 15,00");
Console.WriteLine("101 - Bauru - R$ 18,00");
Console.WriteLine("102 - Hambúrguer - R$ 20,00");
Console.WriteLine("103 - Cheeseburguer - R$ 22,00");
Console.WriteLine("104 - Refrigerante - R$ 8,00");
Console.WriteLine("===============================================");
Console.Write("Digite o código do produto desejado: ");
codigoProduto = Convert.ToInt32(Console.ReadLine());
Console.Write("Digite a quantidade desejada: ");
quantidade = Convert.ToInt32(Console.ReadLine());

//Processamento e saída
switch (codigoProduto)
{
    case 100:
        preçoProduto = 15.00;
        break;
    case 101:
        preçoProduto = 18.00;
        break;
    case 102:
        preçoProduto = 20.00;
        break;
    case 103:
        preçoProduto = 22.00;
        break;
    case 104:
        preçoProduto = 8.00;
        break;
    default:
        Console.WriteLine("Código de produto inválido.");
        return;
        
}
valorTotal = preçoProduto * quantidade;
Console.WriteLine("O valor total a ser pago é: R$" + valorTotal.ToString("F2"));

*/

//Exercício 9
/*
 * Um produto custa um valor base e é vendido para diferentes estados, cada um com uma taxa de imposto
diferente.
Peça o valor base do produto e a sigla do estado destino (SP, RJ, MG, ES). Calcule e mostre o valor final
usando a tabela abaixo:
● SP: +10%
● RJ: +15%
● MG: +12%
● ES: +8%

*/


/*
//Variáveis
using System;
using System.Globalization;

Console.WriteLine("Cálculo do preço final por estado (SP, RJ, MG, ES)\n");

// Leitura do valor base
Console.Write("Informe o valor base do produto (ex: 100,50): ");
string? entrada = Console.ReadLine();
if (string.IsNullOrWhiteSpace(entrada))
{
    Console.WriteLine("Valor inválido.");
    return;
}

// Normaliza vírgula para ponto para permitir entrada com ',' ou '.'
entrada = entrada.Trim().Replace(',', '.');
if (!decimal.TryParse(entrada, NumberStyles.Number, CultureInfo.InvariantCulture, out decimal valorBase) || valorBase < 0)
{
    Console.WriteLine("Valor inválido. Informe um número positivo.");
    return;
}

// Leitura da sigla do estado
Console.Write("Informe a sigla do estado destino (SP, RJ, MG, ES): ");
string? estado = Console.ReadLine()?.Trim().ToUpperInvariant();
if (string.IsNullOrEmpty(estado))
{
    Console.WriteLine("Estado inválido.");
    return;
}

// Determina a taxa via switch
decimal taxa;
switch (estado)
{
    case "SP":
        taxa = 0.10m;
        break;
    case "RJ":
        taxa = 0.15m;
        break;
    case "MG":
        taxa = 0.12m;
        break;
    case "ES":
        taxa = 0.08m;
        break;
    default:
        Console.WriteLine("Estado inválido. Use: SP, RJ, MG ou ES.");
        return;
}

// Cálculo
decimal valorImposto = Math.Round(valorBase * taxa, 2);
decimal valorFinal = Math.Round(valorBase + valorImposto, 2);

// Formata para estilo pt-BR (substitui '.' por ',')
string F(decimal v) => v.ToString("F2", CultureInfo.InvariantCulture).Replace('.', ',');

// Saída
Console.WriteLine("\n***** Resultado *****");
Console.WriteLine($"Estado: {estado}");
Console.WriteLine($"Valor base: R$ {F(valorBase)}");
Console.WriteLine($"Imposto ({(taxa * 100):F0}%): R$ {F(valorImposto)}");
Console.WriteLine($"Valor final: R$ {F(valorFinal)}");
Console.WriteLine("*********************");

Console.WriteLine("\nPressione qualquer tecla para encerrar...");
Console.ReadKey();

*/


//Exercício 10
/*
 * A gravidade muda dependendo do planeta em que você está. Peça ao usuário que digite seu peso na Terra
(em kg) e, em seguida, exiba um menu com opções de planetas do sistema solar (1 a 6):
1. Mercúrio (Gravidade: 0.37)
2. Vênus (Gravidade: 0.88)
3. Marte (Gravidade: 0.38)
4. Júpiter (Gravidade: 2.64)
5. Saturno (Gravidade: 1.15)
6. Urano (Gravidade: 1.17)
Usando a estrutura switch, pegue a gravidade relativa correspondente ao planeta escolhido, calcule o "novo
peso" (fórmula: PesoTerra * GravidadePlaneta) e exiba para o usuário a mensagem: "Seu peso no planeta
escolhido seria de X kg
*/


using System;
using System.Globalization;

Console.WriteLine("Cálculo do peso em outro planeta\n");

// Leitura do peso na Terra
Console.Write("Informe seu peso na Terra (kg): ");
string? entradaPeso = Console.ReadLine();
if (string.IsNullOrWhiteSpace(entradaPeso))
{
    Console.WriteLine("Peso inválido.");
    return;
}
entradaPeso = entradaPeso.Trim().Replace(',', '.');
if (!double.TryParse(entradaPeso, NumberStyles.Number, CultureInfo.InvariantCulture, out double pesoTerra) || pesoTerra < 0)
{
    Console.WriteLine("Peso inválido. Informe um número positivo.");
    return;
}

// Menu de planetas
Console.WriteLine("\nEscolha o planeta:");
Console.WriteLine("1 - Mercúrio (Gravidade: 0.37)");
Console.WriteLine("2 - Vênus    (Gravidade: 0.88)");
Console.WriteLine("3 - Marte    (Gravidade: 0.38)");
Console.WriteLine("4 - Júpiter  (Gravidade: 2.64)");
Console.WriteLine("5 - Saturno  (Gravidade: 1.15)");
Console.WriteLine("6 - Urano    (Gravidade: 1.17)");
Console.Write("Digite o número (1-6): ");

string? entradaOpcao = Console.ReadLine();
if (!int.TryParse(entradaOpcao, out int opcao))
{
    Console.WriteLine("Opção inválida.");
    return;
}

double gravidade;
switch (opcao)
{
    case 1:
        gravidade = 0.37;
        break;
    case 2:
        gravidade = 0.88;
        break;
    case 3:
        gravidade = 0.38;
        break;
    case 4:
        gravidade = 2.64;
        break;
    case 5:
        gravidade = 1.15;
        break;
    case 6:
        gravidade = 1.17;
        break;
    default:
        Console.WriteLine("Opção inválida. Escolha um número de 1 a 6.");
        return;
}

// Cálculo do novo peso
double novoPeso = Math.Round(pesoTerra * gravidade, 2);

// Formatação em pt-BR sem depender de culturas do sistema
string F(double v) => v.ToString("F2", CultureInfo.InvariantCulture).Replace('.', ',');


/*



//LINH DA LN MACEDO ACABAMENTOS

https://liquid-tan-slwcyvlzzk.edgeone.app/



*/

Console.WriteLine($"\nSeu peso no planeta escolhido seria de {F(novoPeso)} kg");

Console.WriteLine("\nPressione qualquer tecla para encerrar...");
Console.ReadKey();
