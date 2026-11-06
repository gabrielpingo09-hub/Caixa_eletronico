Simulador de Caixa Eletrônico em C

Um programa de terminal desenvolvido em linguagem C que simula as operações fundamentais de um caixa eletrônico (ATM), incluindo consulta de saldo, saques com validações monetárias e distribuição inteligente de cédulas.

🚀 Funcionalidades

Consulta de Saldo: Visualização do saldo atual disponível na conta (iniciado com um valor padrão para testes).

Saque Inteligente: Realização de saques com cálculo automático da menor quantidade de cédulas possíveis para o valor solicitado.

Validações de Segurança:

Bloqueio de valores negativos ou iguais a zero.

Restrição para saques apenas em múltiplos de R$ 5 (compatível com as notas disponíveis).

Verificação de saldo insuficiente antes de efetivar a transação.

Interface Interativa: Menu em loop contínuo (utilizando do-while e switch-case) até que o usuário escolha sair.

🛠️ Tecnologias Utilizadas

Linguagem C (Padrão C99 ou superior)

Biblioteca padrão <stdio.h> para entrada e saída de dados no console.

📋 Pré-requisitos

Para compilar e executar este programa, você precisará ter instalado em sua máquina:

Um compilador C (como gcc, Clang ou MinGW para Windows).

Um terminal de comando (Prompt de Comando, PowerShell, Git Bash ou Terminal do Linux/macOS).

⚙️ Como Compilar e Executar

Clone este repositório ou baixe o arquivo fonte (caixa_eletronico.c).

Abra o terminal na pasta onde o arquivo está salvo.

Compile o código usando o gcc:

gcc caixa_eletronico.c -o caixa_eletronico


Execute o programa gerado:

No Linux / macOS:

./caixa_eletronico


No Windows:

caixa_eletronico.exe


💡 Como Usar o Sistema

Ao iniciar o programa, o menu principal será exibido:

=== CAIXA ELETRONICO ===
1. Consultar Saldo
2. Sacar Dinheiro
3. Sair
Escolha uma opcao: 


Opção 1: Mostra o saldo atual (padrão inicial de R$ 10.000).

Opção 2: Solicita o valor do saque, valida as regras e exibe quais e quantas notas foram entregues (cédulas de R$ 100, R$ 50, R$ 20, R$ 10 e R$ 5).

Opção 3: Encerra a execução do programa.

✒️ Autor

Desenvolvido para fins de estudo e prática de lógica de programação em C.
