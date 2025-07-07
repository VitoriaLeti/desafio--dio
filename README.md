# 💰 Sistema Bancário - Desafio DIO 💻

Este repositório contém um sistema bancário desenvolvido como parte do desafio do curso de **Backend em Python** promovido pelo **Santander** em parceria com a **DIO (Digital Innovation One)**.

## 🧱 Estrutura de Classes

- `Cliente`: Classe base para clientes, com endereço e contas.
- `PessoaFisica`: Herda de `Cliente`, adiciona nome, CPF e data de nascimento.
- `Conta`: Classe base para contas bancárias, com saldo, número, agência e histórico.
- `ContaCorrente`: Herda de `Conta`, com limites de saque e número máximo de saques.
- `Transacao`: Classe abstrata para operações bancárias.
  - `Saque` e `Deposito`: Implementações concretas de `Transacao`.
- `Historico`: Armazena todas as transações realizadas em uma conta.

## ⚙️ Funcionalidades

- Criar clientes e contas.
- Realizar depósitos e saques com validações.
- Registrar transações com data e tipo.
- Limitar número de saques e valor máximo por saque.
- Histórico de transações por conta.

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/VitoriaLeti/desafio--dio.git
   cd desafio--dio
   ```
2.Execute o script principal:

python desafio.py




