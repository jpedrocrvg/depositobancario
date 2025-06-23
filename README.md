# 💰 Sistema Bancário em Python

Este é um projeto simples de terminal que simula um **sistema bancário**, permitindo ao usuário realizar operações como **depósito**, **saque** e visualizar o **extrato bancário**.

## 📌 Funcionalidades

- Depósito de valores (apenas positivos)
- Saque com:
  - Limite de valor por saque (R$ 500,00)
  - Limite de 3 saques diários
  - Verificação de saldo disponível
- Visualização do extrato com histórico de operações
- Interface simples via terminal

---

## 🧠 Regras de Negócio

- O saldo inicial é R$ 0,00
- O usuário pode realizar até **3 saques por execução**
- O limite por saque é de **R$ 500,00**
- O extrato mostra todas as operações realizadas, com formatação
- Saques e depósitos inválidos são tratados com mensagens claras

---

## ▶️ Como Executar

1. Instale o Python (versão 3.x): https://www.python.org/downloads/
2. Clone este repositório ou copie o código para um arquivo `sistema_bancario.py`
3. Abra o terminal na pasta onde está o arquivo
4. Execute o script com:

```bash
python sistema_bancario.py
