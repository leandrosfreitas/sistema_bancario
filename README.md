# 🏦 Sistema Bancário em Python

Este é um projeto simples de **Sistema Bancário** desenvolvido em Python com foco em aprendizado de lógica de programação, uso de funções, controle de fluxo, e manipulação de dados em memória.

## 📋 Funcionalidades

O sistema permite realizar as seguintes operações via terminal:

- [x] Depósito
- [x] Saque com limite de valor e quantidade
- [x] Exibição de extrato
- [x] Criação de usuários (clientes)
- [x] Criação de contas bancárias
- [x] Listagem de contas
- [x] Validação por CPF
- [x] Interface textual interativa via menu

## 🚀 Tecnologias Utilizadas

- Python 3.10 ou superior
- `textwrap` (módulo padrão do Python) para formatação de texto

## 🧠 Lógica do Projeto

O projeto está dividido em funções reutilizáveis com parâmetros posicionais e nomeados para organizar a lógica de saque, depósito e extrato. Ele também implementa controle de usuários e contas utilizando listas e dicionários.

### 💰 Regras de negócio:

- Cada saque tem um **limite de R$ 500**.
- O usuário pode realizar **até 3 saques por dia**.
- Apenas valores positivos são aceitos para saque e depósito.
- Cada conta está associada a um usuário (validação por CPF).
- O extrato exibe todas as movimentações e o saldo atual.

## 📂 Estrutura de Funções

- `menu()` – Mostra o menu principal.
- `depositar()` – Realiza um depósito no saldo e registra no extrato.
- `sacar()` – Realiza um saque com verificações de regras.
- `exibir_extrato()` – Exibe as movimentações e o saldo atual.
- `criar_usuario()` – Cria um novo usuário com CPF único.
- `filtrar_usuarios()` – Verifica se o usuário já existe.
- `criar_conta()` – Associa uma nova conta a um usuário existente.
- `listar_contas()` – Exibe todas as contas cadastradas.
- `main()` – Loop principal de execução do sistema.

## 📦 Como Executar

1. Clone o repositório:

```bash
git clone https://github.com/seu-usuario/sistema-bancario-python.git
cd sistema-bancario-python
