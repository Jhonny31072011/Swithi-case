using System;

class Program
{
    static void Main(string[] args)
    {
        int opcao;

        do
        {
            Console.Clear();
            Console.WriteLine("╔════════════════════════════════════════════════════════════════════════════╗");
            Console.WriteLine("║           TODOS OS EXERCÍCIOS DE C# - MENU ÚNICO COM SWITCH-CASE           ║");
            Console.WriteLine("╠════════════════════════════════════════════════════════════════════════════╣");
            Console.WriteLine("║  1 - Calcular idade a partir do ano de nascimento                           ║");
            Console.WriteLine("║  2 - Ler dois números e imprimir na ordem inversa                           ║");
            Console.WriteLine("║  3 - Calcular Salário Líquido com percentual de desconto                    ║");
            Console.WriteLine("║  4 - Converter Celsius para Fahrenheit                                      ║");
            Console.WriteLine("║  5 - Calcular média de dois valores                                         ║");
            Console.WriteLine("║  6 - Converter km/h para m/s                                                ║");
            Console.WriteLine("║  7 - Salário com Previdência (10%) e Imposto (5%)                           ║");
            Console.WriteLine("║  8 - Inverter número de 3 algarismos                                        ║");
            Console.WriteLine("║  9 - Aumento de salário se <= R$ 150                                        ║");
            Console.WriteLine("║ 10 - Aprovação por média (3 notas)                                          ║");
            Console.WriteLine("║ 11 - Qual é o maior entre dois números                                      ║");
            Console.WriteLine("║ 12 - Dia da semana (1 a 7)                                                  ║");
            Console.WriteLine("║ 13 - Vogal ou Consoante (fallthrough)                                       ║");
            Console.WriteLine("║ 14 - Lanchonete (código do produto)                                         ║");
            Console.WriteLine("║ 15 - Calculadora Simples                                                    ║");
            Console.WriteLine("║ 16 - Categoria por idade (Infantil/Juvenil/Sênior)                          ║");
            Console.WriteLine("║ 17 - Imposto por Estado (SP, RJ, MG, ES)                                    ║");
            Console.WriteLine("║ 18 - Peso em outros planetas                                                ║");
            Console.WriteLine("║ 19 - Desafio RH TechCorp (bônus por cargo)                                  ║");
            Console.WriteLine("║ 20 - Soma de números menores que 20 (até 0)                                 ║");
            Console.WriteLine("║ 21 - Média de idades (até negativo)                                         ║");
            Console.WriteLine("║ 22 - Validação de senha (1234)                                              ║");
            Console.WriteLine("║ 23 - Encontrar o maior número (até negativo)                                ║");
            Console.WriteLine("║ 24 - Menu interativo (Olá / Ano / Sair)                                     ║");
            Console.WriteLine("║ 25 - Contagem Regressiva com Beep                                           ║");
            Console.WriteLine("║ 26 - Somador de números (até 0)                                             ║");
            Console.WriteLine("║ 27 - Validação de nota (0 a 10)                                             ║");
            Console.WriteLine("║ 28 - Adivinhar número aleatório                                             ║");
            Console.WriteLine("║ 29 - Tabuada com DO-WHILE                                                   ║");
            Console.WriteLine("║ 30 - Exercício 1: 30 números > 100                                          ║");
            Console.WriteLine("║ 31 - Exercício 2: 10 valores múltiplos de 3                                 ║");
            Console.WriteLine("║ 32 - Exercício 3: Média até digitar 0                                       ║");
            Console.WriteLine("║ 33 - Exercício 4: Média dos positivos até negativo                          ║");
            Console.WriteLine("║ 34 - Exercício 5: Média + qtd pos/neg até 0                                 ║");
            Console.WriteLine("║ 35 - Exercício 6: Somatório dos negativos até 0                             ║");
            Console.WriteLine("║ 36 - Exercício 7: Funcionários salário >= 1000                              ║");
            Console.WriteLine("║ 37 - Exercício 8: Média de alunos com status                                ║");
            Console.WriteLine("║ 38 - Exercício 9: Novo preço produtos +15%                                  ║");
            Console.WriteLine("║  0 - Sair                                                                  ║");
            Console.WriteLine("╚════════════════════════════════════════════════════════════════════════════╝");
            Console.Write("\nDigite a opção desejada: ");

            if (!int.TryParse(Console.ReadLine(), out opcao))
                opcao = -1;

            Console.Clear();

            switch (opcao)
            {
                // ==================== CASO 1 ====================
                case 1:
                    // Exercício: Calcular idade a partir do ano de nascimento
                    Console.WriteLine(">>> Calcular idade a partir do ano de nascimento.\n");
                    Console.Write("Informe seu nome: ");
                    string nome1 = Console.ReadLine();
                    Console.Write("Informe seu ano de nascimento: ");
                    int ano1 = Convert.ToInt32(Console.ReadLine());
                    int idade1 = 2026 - ano1;
                    Console.WriteLine($"\nBom dia, {nome1}, seja bem-vindo!");
                    Console.WriteLine($"{nome1}, você tem {idade1} anos!");
                    Console.WriteLine($"{nome1}, ano que vem você fará {idade1 + 1} anos!");
                    break;

                // ==================== CASO 2 ====================
                case 2:
                    // Exercício: Ler dois números e imprimir na ordem inversa
                    Console.WriteLine(">>> Ler dois números e imprimir na ordem inversa.\n");
                    Console.Write("Informe o número para NumA: ");
                    int numA2 = Convert.ToInt32(Console.ReadLine());
                    Console.Write("Informe o número para NumB: ");
                    int numB2 = Convert.ToInt32(Console.ReadLine());
                    Console.WriteLine($"\nOs números que você digitou foram: {numB2} e {numA2}");
                    break;

                // ==================== CASO 3 ====================
                case 3:
                    // Exercício: Salário Líquido com percentual de desconto
                    Console.WriteLine(">>> Calcular Salário Líquido com percentual de desconto.\n");
                    Console.Write("Informe a quantidade de horas trabalhadas no mês: ");
                    double HT3 = Convert.ToDouble(Console.ReadLine());
                    Console.Write("Informe o valor da hora trabalhada: ");
                    double VH3 = Convert.ToDouble(Console.ReadLine());
                    Console.Write("Informe o percentual de desconto: ");
                    double PD3 = Convert.ToDouble(Console.ReadLine());
                    double SB3 = HT3 * VH3;
                    double TD3 = (PD3 / 100) * SB3;
                    double SL3 = SB3 - TD3;
                    Console.WriteLine("\n****** RESUMO ******");
                    Console.WriteLine($"Horas trabalhadas: {HT3} horas");
                    Console.WriteLine($"Salário Bruto: R$ {SB3:F2}");
                    Console.WriteLine($"Total de descontos: R$ {TD3:F2}");
                    Console.WriteLine($"Salário Líquido: R$ {SL3:F2}");
                    break;

                // ==================== CASO 4 ====================
                case 4:
                    // Exercício: Converter Celsius para Fahrenheit
                    Console.WriteLine(">>> Converter temperatura de Celsius para Fahrenheit.\n");
                    Console.Write("Informe a temperatura em Graus Celsius: ");
                    double C4 = Convert.ToDouble(Console.ReadLine());
                    double F4 = (9 * C4 + 160) / 5;
                    Console.WriteLine($"\n{C4}° Celsius são {F4:F2}° Fahrenheit");
                    break;

                // ==================== CASO 5 ====================
                case 5:
                    // Exercício: Calcular média de dois valores
                    Console.WriteLine(">>> Calcular a média entre dois valores.\n");
                    Console.Write("Informe o primeiro valor: ");
                    double val1_5 = Convert.ToDouble(Console.ReadLine());
                    Console.Write("Informe o segundo valor: ");
                    double val2_5 = Convert.ToDouble(Console.ReadLine());
                    double media5 = (val1_5 + val2_5) / 2;
                    Console.WriteLine($"\nA média entre {val1_5} e {val2_5} é {media5:F2}");
                    break;

                // ==================== CASO 6 ====================
                case 6:
                    // Exercício: Converter km/h para m/s
                    Console.WriteLine(">>> Converter velocidade de km/h para m/s.\n");
                    Console.Write("Informe a velocidade em km/h: ");
                    double kmh6 = Convert.ToDouble(Console.ReadLine());
                    double ms6 = kmh6 / 3.6;
                    Console.WriteLine($"\n{kmh6} km/h são {ms6:F2} metros/segundo");
                    break;

                // ==================== CASO 7 ====================
                case 7:
                    // Exercício: Salário com Previdência e Imposto
                    Console.WriteLine(">>> Calcular salário com Previdência Social (10%) e Imposto (5%).\n");
                    Console.Write("Informe o seu salário bruto: ");
                    double SB7 = Convert.ToDouble(Console.ReadLine());
                    double Prev7 = SB7 * 0.10;
                    double Imp7 = (SB7 - Prev7) * 0.05;
                    double SL7 = SB7 - Prev7 - Imp7;
                    Console.WriteLine("\n********** Resumo Final *********");
                    Console.WriteLine($"Salário Bruto ........: R$ {SB7:F2}");
                    Console.WriteLine($"Previdência Social ...: R$ {Prev7:F2}");
                    Console.WriteLine($"Imposto ..............: R$ {Imp7:F2}");
                    Console.WriteLine($"Salário Líquido ......: R$ {SL7:F2}");
                    break;

                // ==================== CASO 8 ====================
                case 8:
                    // Exercício: Inverter número de 3 algarismos
                    Console.WriteLine(">>> Inverter número de 3 algarismos (ex: 123 → 321).\n");
                    Console.Write("Informe um número com 3 algarismos: ");
                    int N8 = Convert.ToInt32(Console.ReadLine());
                    int C8 = N8 / 100;
                    int D8 = (N8 % 100) / 10;
                    int U8 = (N8 % 100) % 10;
                    int invertido8 = (U8 * 100) + (D8 * 10) + C8;
                    Console.WriteLine($"\nO número inverso é {invertido8}");
                    break;

                // ==================== CASO 9 ====================
                case 9:
                    // Exercício: Aumento de salário se <= R$ 150
                    Console.WriteLine(">>> Aumento de salário se menor ou igual a R$ 150.\n");
                    Console.Write("Informe seu nome: ");
                    string nome9 = Console.ReadLine();
                    Console.Write("Informe o seu salário: ");
                    double sal9 = Convert.ToDouble(Console.ReadLine());
                    if (sal9 <= 150)
                        sal9 += 30;
                    Console.WriteLine($"\n{nome9}, seu salário é R$ {sal9:F2}");
                    break;

                // ==================== CASO 10 ====================
                case 10:
                    // Exercício: Aprovação por média (3 notas)
                    Console.WriteLine(">>> Verificar aprovação por média (3 notas).\n");
                    Console.Write("Informe a 1ª nota: ");
                    double n1_10 = Convert.ToDouble(Console.ReadLine());
                    Console.Write("Informe a 2ª nota: ");
                    double n2_10 = Convert.ToDouble(Console.ReadLine());
                    Console.Write("Informe a 3ª nota: ");
                    double n3_10 = Convert.ToDouble(Console.ReadLine());
                    double media10 = (n1_10 + n2_10 + n3_10) / 3;
                    if (media10 <= 7)
                        Console.WriteLine($"\nAluno reprovado com média {media10:F2}");
                    else
                        Console.WriteLine($"\nAluno aprovado com média {media10:F2}");
                    break;

                // ==================== CASO 11 ====================
                case 11:
                    // Exercício: Qual é o maior entre dois números
                    Console.WriteLine(">>> Descobrir qual é o maior entre dois números.\n");
                    Console.Write("Informe o primeiro valor: ");
                    int num1_11 = Convert.ToInt32(Console.ReadLine());
                    Console.Write("Informe o segundo valor: ");
                    int num2_11 = Convert.ToInt32(Console.ReadLine());
                    if (num1_11 > num2_11)
                        Console.WriteLine($"\nO número {num1_11} é o maior!");
                    else if (num2_11 > num1_11)
                        Console.WriteLine($"\nO número {num2_11} é o maior!");
                    else
                        Console.WriteLine($"\nOs números {num1_11} e {num2_11} são iguais!");
                    break;

                // ==================== CASO 12 ====================
                case 12:
                    // Exercício: Dia da semana (1 a 7)
                    Console.WriteLine(">>> Dia da semana correspondente ao número (1 a 7).\n");
                    Console.Write("Informe o número do dia da semana: ");
                    int dia12 = Convert.ToInt32(Console.ReadLine());
                    switch (dia12)
                    {
                        case 1: Console.WriteLine("Domingo"); break;
                        case 2: Console.WriteLine("Segunda-feira"); break;
                        case 3: Console.WriteLine("Terça-feira"); break;
                        case 4: Console.WriteLine("Quarta-feira"); break;
                        case 5: Console.WriteLine("Quinta-feira"); break;
                        case 6: Console.WriteLine("Sexta-feira"); break;
                        case 7: Console.WriteLine("Sábado"); break;
                        default: Console.WriteLine("Número inválido!"); break;
                    }
                    break;

                // ==================== CASO 13 ====================
                case 13:
                    // Exercício: Vogal ou Consoante (fallthrough)
                    Console.WriteLine(">>> Identificar se a letra é vogal ou consoante (fallthrough).\n");
                    Console.Write("Informe uma letra: ");
                    char letra13 = Convert.ToChar(Console.ReadLine().ToUpper());
                    switch (letra13)
                    {
                        case 'A':
                        case 'E':
                        case 'I':
                        case 'O':
                        case 'U':
                            Console.WriteLine("A letra é uma VOGAL.");
                            break;
                        default:
                            Console.WriteLine("A letra é uma CONSOANTE.");
                            break;
                    }
                    break;

                // ==================== CASO 14 ====================
                case 14:
                    // Exercício: Lanchonete (código do produto)
                    Console.WriteLine(">>> Lanchonete - Escolha pelo código.\n");
                    Console.WriteLine("100 - Cachorro Quente - R$ 15,00");
                    Console.WriteLine("101 - Bauru - R$ 18,00");
                    Console.WriteLine("102 - Hambúrguer - R$ 20,00");
                    Console.WriteLine("103 - Cheeseburguer - R$ 22,00");
                    Console.WriteLine("104 - Refrigerante - R$ 8,00");
                    Console.Write("\nDigite o código do produto: ");
                    int cod14 = Convert.ToInt32(Console.ReadLine());
                    Console.Write("Digite a quantidade: ");
                    int qtd14 = Convert.ToInt32(Console.ReadLine());
                    double preco14 = 0;
                    string prod14 = "";
                    switch (cod14)
                    {
                        case 100: prod14 = "Cachorro Quente"; preco14 = 15.00; break;
                        case 101: prod14 = "Bauru"; preco14 = 18.00; break;
                        case 102: prod14 = "Hambúrguer"; preco14 = 20.00; break;
                        case 103: prod14 = "Cheeseburguer"; preco14 = 22.00; break;
                        case 104: prod14 = "Refrigerante"; preco14 = 8.00; break;
                        default: Console.WriteLine("Código inválido!"); break;
                    }
                    if (preco14 > 0)
                        Console.WriteLine($"\n{prod14} x {qtd14} = R$ {preco14 * qtd14:F2}");
                    break;

                // ==================== CASO 15 ====================
                case 15:
                    // Exercício: Calculadora Simples
                    Console.WriteLine(">>> Calculadora Simples.\n");
                    Console.Write("Digite o primeiro número: ");
                    double n1_15 = Convert.ToDouble(Console.ReadLine());
                    Console.Write("Digite o operador (+, -, *, /): ");
                    char op15 = Convert.ToChar(Console.ReadLine());
                    Console.Write("Digite o segundo número: ");
                    double n2_15 = Convert.ToDouble(Console.ReadLine());
                    double res15 = 0;
                    bool valido15 = true;
                    switch (op15)
                    {
                        case '+': res15 = n1_15 + n2_15; break;
                        case '-': res15 = n1_15 - n2_15; break;
                        case '*': res15 = n1_15 * n2_15; break;
                        case '/':
                            if (n2_15 != 0) res15 = n1_15 / n2_15;
                            else { Console.WriteLine("Erro: Divisão por zero!"); valido15 = false; }
                            break;
                        default:
                            Console.WriteLine("Operador inválido!");
                            valido15 = false;
                            break;
                    }
                    if (valido15)
                        Console.WriteLine($"\nResultado: {n1_15} {op15} {n2_15} = {res15:F2}");
                    break;

                // ==================== CASO 16 ====================
                case 16:
                    // Exercício: Categoria por idade
                    Console.WriteLine(">>> Categoria por idade (Infantil / Juvenil / Sênior).\n");
                    Console.Write("Digite a idade: ");
                    int idade16 = Convert.ToInt32(Console.ReadLine());
                    string cat16;
                    if (idade16 >= 0 && idade16 <= 12) cat16 = "Infantil";
                    else if (idade16 >= 13 && idade16 <= 17) cat16 = "Juvenil";
                    else if (idade16 >= 18) cat16 = "Sênior";
                    else cat16 = "Idade inválida";
                    Console.WriteLine($"\nA categoria é: {cat16}");
                    break;

                // ==================== CASO 17 ====================
                case 17:
                    // Exercício: Imposto por Estado
                    Console.WriteLine(">>> Cálculo de imposto por Estado (SP, RJ, MG, ES).\n");
                    Console.Write("Informe o valor base do produto: R$ ");
                    double base17 = Convert.ToDouble(Console.ReadLine().Replace(',', '.'));
                    Console.Write("Informe a sigla do estado (SP, RJ, MG, ES): ");
                    string est17 = Console.ReadLine().ToUpper();
                    double taxa17 = 0;
                    switch (est17)
                    {
                        case "SP": taxa17 = 0.10; break;
                        case "RJ": taxa17 = 0.15; break;
                        case "MG": taxa17 = 0.12; break;
                        case "ES": taxa17 = 0.08; break;
                        default: Console.WriteLine("Estado inválido!"); break;
                    }
                    if (taxa17 > 0)
                    {
                        double imp17 = base17 * taxa17;
                        Console.WriteLine($"\nEstado: {est17}");
                        Console.WriteLine($"Imposto: R$ {imp17:F2}");
                        Console.WriteLine($"Valor final: R$ {base17 + imp17:F2}");
                    }
                    break;

                // ==================== CASO 18 ====================
                case 18:
                    // Exercício: Peso em outros planetas
                    Console.WriteLine(">>> Calcular peso em outros planetas do Sistema Solar.\n");
                    Console.Write("Informe seu peso na Terra (kg): ");
                    double peso18 = Convert.ToDouble(Console.ReadLine().Replace(',', '.'));
                    Console.WriteLine("\n1-Mercúrio 2-Vênus 3-Marte 4-Júpiter 5-Saturno 6-Urano");
                    Console.Write("Escolha o planeta (1-6): ");
                    int p18 = Convert.ToInt32(Console.ReadLine());
                    double grav18 = 0; string nomeP18 = "";
                    switch (p18)
                    {
                        case 1: grav18 = 0.37; nomeP18 = "Mercúrio"; break;
                        case 2: grav18 = 0.88; nomeP18 = "Vênus"; break;
                        case 3: grav18 = 0.38; nomeP18 = "Marte"; break;
                        case 4: grav18 = 2.64; nomeP18 = "Júpiter"; break;
                        case 5: grav18 = 1.15; nomeP18 = "Saturno"; break;
                        case 6: grav18 = 1.17; nomeP18 = "Urano"; break;
                        default: Console.WriteLine("Opção inválida!"); break;
                    }
                    if (grav18 > 0)
                        Console.WriteLine($"\nSeu peso em {nomeP18} seria de {peso18 * grav18:F2} kg");
                    break;

                // ==================== CASO 19 ====================
                case 19:
                    // Exercício: Desafio RH TechCorp
                    Console.WriteLine(">>> Desafio RH TechCorp - Salário Final com Bônus.\n");
                    Console.Write("Nome do funcionário: ");
                    string nome19 = Console.ReadLine();
                    Console.Write("Salário Base: R$ ");
                    double base19 = Convert.ToDouble(Console.ReadLine().Replace(',', '.'));
                    Console.WriteLine("\n1 - Desenvolvedor Júnior   2 - Desenvolvedor Pleno");
                    Console.WriteLine("3 - Desenvolvedor Sênior   4 - Gerente de Projetos");
                    Console.Write("Código do cargo: ");
                    int cargo19 = Convert.ToInt32(Console.ReadLine());
                    string cargoNome19 = "";
                    double final19 = 0;
                    switch (cargo19)
                    {
                        case 1:
                            cargoNome19 = "Desenvolvedor Júnior";
                            Console.Write("Possui certificação em C#? (S/N): ");
                            string r1 = Console.ReadLine().ToUpper();
                            final19 = (r1 == "S") ? base19 * 1.15 : base19 * 1.05;
                            break;
                        case 2:
                            cargoNome19 = "Desenvolvedor Pleno";
                            Console.Write("Quantos anos de empresa? ");
                            int anos2 = Convert.ToInt32(Console.ReadLine());
                            final19 = (anos2 >= 3) ? base19 * 1.20 : base19 * 1.10;
                            break;
                        case 3:
                            cargoNome19 = "Desenvolvedor Sênior";
                            Console.Write("Atua como Líder Técnico? (S/N): ");
                            string r3 = Console.ReadLine().ToUpper();
                            final19 = (r3 == "S") ? base19 * 1.30 + 500 : base19 * 1.25;
                            break;
                        case 4:
                            cargoNome19 = "Gerente de Projetos";
                            Console.Write("Bateu a meta no prazo? (S/N): ");
                            string r4 = Console.ReadLine().ToUpper();
                            final19 = (r4 == "S") ? base19 * 1.40 : base19 * 1.10;
                            break;
                        default:
                            Console.WriteLine("Código inválido!");
                            break;
                    }
                    if (final19 > 0)
                    {
                        Console.WriteLine("\n========== HOLERITE ==========");
                        Console.WriteLine($"Nome: {nome19}");
                        Console.WriteLine($"Cargo: {cargoNome19}");
                        Console.WriteLine($"Salário Final: R$ {final19:F2}");
                    }
                    break;

                // ==================== CASO 20 ====================
                case 20:
                    // Exercício: Soma de números menores que 20 (até 0)
                    Console.WriteLine(">>> Soma de números menores que 20 (até digitar 0).\n");
                    int v20, soma20 = 0;
                    Console.Write("Informe um valor inicial: ");
                    v20 = Convert.ToInt32(Console.ReadLine());
                    while (v20 != 0)
                    {
                        if (v20 < 20) soma20 += v20;
                        Console.Write("Informe outro valor (0 para sair): ");
                        v20 = Convert.ToInt32(Console.ReadLine());
                    }
                    Console.WriteLine($"\nA soma dos números menores que 20 é: {soma20}");
                    break;

                // ==================== CASO 21 ====================
                case 21:
                    // Exercício: Média de idades (até negativo)
                    Console.WriteLine(">>> Calcular média de idades (negativo para sair).\n");
                    int id21, somaId21 = 0, qtd21 = 0;
                    Console.Write("Informe uma idade: ");
                    id21 = Convert.ToInt32(Console.ReadLine());
                    while (id21 >= 0)
                    {
                        somaId21 += id21;
                        qtd21++;
                        Console.Write("Informe outra idade (negativo para sair): ");
                        id21 = Convert.ToInt32(Console.ReadLine());
                    }
                    if (qtd21 > 0)
                        Console.WriteLine($"\nA média de todas as idades é: {(double)somaId21 / qtd21:F2}");
                    else
                        Console.WriteLine("\nNenhuma idade válida informada.");
                    break;

                // ==================== CASO 22 ====================
                case 22:
                    // Exercício: Validação de senha (1234)
                    Console.WriteLine(">>> Validação de senha (senha correta = 1234).\n");
                    int senha22;
                    Console.Write("Informe a senha: ");
                    senha22 = Convert.ToInt32(Console.ReadLine());
                    while (senha22 != 1234)
                    {
                        Console.Write("Senha incorreta. Tente novamente: ");
                        senha22 = Convert.ToInt32(Console.ReadLine());
                    }
                    Console.WriteLine("\nSenha correta! Acesso concedido.");
                    break;

                // ==================== CASO 23 ====================
                case 23:
                    // Exercício: Encontrar o maior número (até negativo)
                    Console.WriteLine(">>> Encontrar o maior número digitado (negativo para sair).\n");
                    Console.Write("Informe um número para começar: ");
                    int num23 = Convert.ToInt32(Console.ReadLine());
                    int maior23 = num23;
                    while (num23 >= 0)
                    {
                        Console.Write("Informe outro número (NEGATIVO PARA SAIR): ");
                        num23 = Convert.ToInt32(Console.ReadLine());
                        if (num23 > maior23 && num23 >= 0)
                            maior23 = num23;
                    }
                    Console.WriteLine($"\nO maior número digitado foi: {maior23}");
                    break;

                // ==================== CASO 24 ====================
                case 24:
                    // Exercício: Menu interativo (Olá / Ano / Sair)
                    Console.WriteLine(">>> Menu interativo com WHILE.\n");
                    int op24;
                    do
                    {
                        Console.WriteLine("\n1 - Dizer Olá");
                        Console.WriteLine("2 - Mostrar Ano Atual");
                        Console.WriteLine("3 - Sair");
                        Console.Write("Opção: ");
                        op24 = Convert.ToInt32(Console.ReadLine());
                        switch (op24)
                        {
                            case 1: Console.WriteLine("Olá!"); break;
                            case 2: Console.WriteLine("O ano atual é 2026"); break;
                            case 3: Console.WriteLine("Saindo..."); break;
                            default: Console.WriteLine("Opção inválida"); break;
                        }
                    } while (op24 != 3);
                    break;

                // ==================== CASO 25 ====================
                case 25:
                    // Exercício: Contagem Regressiva com Beep
                    Console.WriteLine(">>> Contagem Regressiva com Beep.\n");
                    Console.Write("Digite o número inicial: ");
                    int cont25 = Convert.ToInt32(Console.ReadLine());
                    while (cont25 >= 0)
                    {
                        Console.WriteLine(cont25);
                        Console.Beep(800, 300);
                        System.Threading.Thread.Sleep(600);
                        cont25--;
                    }
                    Console.WriteLine("Foguete Lançado!");
                    break;

                // ==================== CASO 26 ====================
                case 26:
                    // Exercício: Somador de números (até 0)
                    Console.WriteLine(">>> Somador de números (digite 0 para parar).\n");
                    int soma26 = 0, n26;
                    do
                    {
                        Console.Write("Digite um número (0 para parar): ");
                        n26 = Convert.ToInt32(Console.ReadLine());
                        soma26 += n26;
                    } while (n26 != 0);
                    Console.WriteLine($"\nA soma total é: {soma26}");
                    break;

                // ==================== CASO 27 ====================
                case 27:
                    // Exercício: Validação de nota (0 a 10)
                    Console.WriteLine(">>> Validação de nota (0 a 10).\n");
                    int nota27;
                    do
                    {
                        Console.Write("Digite uma nota (0 a 10): ");
                        nota27 = Convert.ToInt32(Console.ReadLine());
                        if (nota27 < 0 || nota27 > 10)
                            Console.WriteLine("Nota inválida. Tente novamente.");
                    } while (nota27 < 0 || nota27 > 10);
                    Console.WriteLine($"\nNota válida: {nota27}");
                    break;

                // ==================== CASO 28 ====================
                case 28:
                    // Exercício: Adivinhar número aleatório
                    Console.WriteLine(">>> Adivinhe o número aleatório (1 a 100).\n");
                    Random rnd28 = new Random();
                    int secreto28 = rnd28.Next(1, 101);
                    int palpite28;
                    do
                    {
                        Console.Write("Seu palpite: ");
                        palpite28 = Convert.ToInt32(Console.ReadLine());
                        if (palpite28 > secreto28) Console.WriteLine("Errou! Tente um número MENOR.");
                        else if (palpite28 < secreto28) Console.WriteLine("Errou! Tente um número MAIOR.");
                    } while (palpite28 != secreto28);
                    Console.WriteLine("\nParabéns! Você acertou!");
                    break;

                // ==================== CASO 29 ====================
                case 29:
                    // Exercício: Tabuada com DO-WHILE
                    Console.WriteLine(">>> Tabuada de um número (negativo para sair).\n");
                    int num29;
                    do
                    {
                        Console.Write("Digite um número para a tabuada (negativo para sair): ");
                        num29 = Convert.ToInt32(Console.ReadLine());
                        if (num29 > 0)
                        {
                            Console.WriteLine($"\n--- TABUADA DO {num29} ---");
                            int c = 1;
                            while (c <= 10)
                            {
                                Console.WriteLine($"{num29} x {c} = {num29 * c}");
                                c++;
                            }
                        }
                    } while (num29 > 0);
                    break;

                // ==================== CASO 30 ====================
                case 30:
                    // Exercício 1 dos 9: 30 números > 100
                    Console.WriteLine(">>> Exercício 1: Lê 30 números e conta quantos são maiores que 100.\n");
                    int count30 = 0;
                    for (int i = 1; i <= 30; i++)
                    {
                        Console.Write($"Digite o {i}º número: ");
                        if (int.TryParse(Console.ReadLine(), out int n) && n > 100)
                            count30++;
                    }
                    Console.WriteLine($"\nQuantidade de números maiores que 100: {count30}");
                    break;

                // ==================== CASO 31 ====================
                case 31:
                    // Exercício 2 dos 9: 10 valores múltiplos de 3
                    Console.WriteLine(">>> Exercício 2: Lê 10 valores e imprime os múltiplos de 3.\n");
                    for (int i = 1; i <= 10; i++)
                    {
                        Console.Write($"Digite o {i}º valor: ");
                        if (int.TryParse(Console.ReadLine(), out int v) && v % 3 == 0)
                            Console.WriteLine($"→ {v} é múltiplo de 3");
                    }
                    break;

                // ==================== CASO 32 ====================
                case 32:
                    // Exercício 3 dos 9: Média até digitar 0
                    Console.WriteLine(">>> Exercício 3: Lê vários números até 0 e calcula a média.\n");
                    int s32 = 0, q32 = 0, n32;
                    do
                    {
                        Console.Write("Digite um número (0 para sair): ");
                        n32 = Convert.ToInt32(Console.ReadLine());
                        if (n32 != 0) { s32 += n32; q32++; }
                    } while (n32 != 0);
                    if (q32 > 0)
                        Console.WriteLine($"\nMédia dos {q32} números: {(double)s32 / q32:F2}");
                    else
                        Console.WriteLine("\nNenhum número foi lido.");
                    break;

                // ==================== CASO 33 ====================
                case 33:
                    // Exercício 4 dos 9: Média dos positivos até negativo
                    Console.WriteLine(">>> Exercício 4: Média dos valores positivos até negativo.\n");
                    int sPos33 = 0, qPos33 = 0, n33;
                    do
                    {
                        Console.Write("Digite um número (negativo para sair): ");
                        n33 = Convert.ToInt32(Console.ReadLine());
                        if (n33 > 0) { sPos33 += n33; qPos33++; }
                    } while (n33 >= 0);
                    if (qPos33 > 0)
                        Console.WriteLine($"\nMédia dos positivos: {(double)sPos33 / qPos33:F2}");
                    else
                        Console.WriteLine("\nNenhum valor positivo digitado.");
                    break;

                // ==================== CASO 34 ====================
                case 34:
                    // Exercício 5 dos 9: Média + qtd pos/neg até 0
                    Console.WriteLine(">>> Exercício 5: Média + quantidade de positivos e negativos até 0.\n");
                    int soma34 = 0, qT34 = 0, qP34 = 0, qN34 = 0, n34;
                    do
                    {
                        Console.Write("Digite um número (0 para sair): ");
                        n34 = Convert.ToInt32(Console.ReadLine());
                        if (n34 != 0)
                        {
                            soma34 += n34; qT34++;
                            if (n34 > 0) qP34++; else qN34++;
                        }
                    } while (n34 != 0);
                    if (qT34 > 0)
                    {
                        Console.WriteLine($"\nMédia: {(double)soma34 / qT34:F2}");
                        Console.WriteLine($"Positivos: {qP34} | Negativos: {qN34}");
                    }
                    break;

                // ==================== CASO 35 ====================
                case 35:
                    // Exercício 6 dos 9: Somatório dos negativos até 0
                    Console.WriteLine(">>> Exercício 6: Somatório dos números negativos até 0.\n");
                    int somaNeg35 = 0, n35;
                    do
                    {
                        Console.Write("Digite um número (0 para sair): ");
                        n35 = Convert.ToInt32(Console.ReadLine());
                        if (n35 < 0) somaNeg35 += n35;
                    } while (n35 != 0);
                    Console.WriteLine($"\nSomatório dos números negativos: {somaNeg35}");
                    break;

                // ==================== CASO 36 ====================
                case 36:
                    // Exercício 7 dos 9: Funcionários com salário >= 1000
                    Console.WriteLine(">>> Exercício 7: Funcionários com salário >= R$ 1000,00.\n");
                    string cont36;
                    do
                    {
                        Console.Write("Nome do funcionário: ");
                        string nm36 = Console.ReadLine();
                        Console.Write("Salário: R$ ");
                        double sal36 = Convert.ToDouble(Console.ReadLine());
                        if (sal36 >= 1000)
                            Console.WriteLine($"→ {nm36} ganha R$ {sal36:F2}");
                        Console.Write("Deseja continuar? (S/N): ");
                        cont36 = Console.ReadLine().ToUpper();
                    } while (cont36 == "S");
                    break;

                // ==================== CASO 37 ====================
                case 37:
                    // Exercício 8 dos 9: Média de alunos com status
                    Console.WriteLine(">>> Exercício 8: Média de alunos com status (reprovado/exame/aprovado).\n");
                    string cont37;
                    do
                    {
                        Console.Write("Nota 1: ");
                        double nt1_37 = Convert.ToDouble(Console.ReadLine());
                        Console.Write("Nota 2: ");
                        double nt2_37 = Convert.ToDouble(Console.ReadLine());
                        double med37 = (nt1_37 + nt2_37) / 2;
                        string status37 = (med37 < 5) ? "REPROVADO" : (med37 < 7) ? "EXAME" : "APROVADO";
                        Console.WriteLine($"Média: {med37:F2} → {status37}");
                        Console.Write("Deseja cadastrar outro aluno? (S/N): ");
                        cont37 = Console.ReadLine().ToUpper();
                    } while (cont37 == "S");
                    break;

                // ==================== CASO 38 ====================
                case 38:
                    // Exercício 9 dos 9: Novo preço produtos +15%
                    Console.WriteLine(">>> Exercício 9: Novo preço de produtos (+15% sobre o custo).\n");
                    string cont38;
                    do
                    {
                        Console.Write("Nome do produto: ");
                        string prod38 = Console.ReadLine();
                        Console.Write("Preço de custo: R$ ");
                        double custo38 = Convert.ToDouble(Console.ReadLine());
                        double novo38 = custo38 * 1.15;
                        Console.WriteLine($"→ {prod38} | Novo preço: R$ {novo38:F2}");
                        Console.Write("Deseja cadastrar outro produto? (S/N): ");
                        cont38 = Console.ReadLine().ToUpper();
                    } while (cont38 == "S");
                    break;

                case 0:
                    Console.WriteLine("Programa finalizado. Até mais!");
                    break;

                default:
                    Console.WriteLine("Opção inválida! Tente novamente.");
                    break;
            }

            if (opcao != 0)
            {
                Console.WriteLine("\n────────────────────────────────────────────────────────────");
                Console.WriteLine("Pressione qualquer tecla para voltar ao menu...");
                Console.ReadKey();
            }

        } while (opcao != 0);
    }
}
