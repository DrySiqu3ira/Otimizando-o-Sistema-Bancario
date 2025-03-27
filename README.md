# Otimizando Sistema Bancário

## Descrição
Este projeto consiste em um sistema bancário desenvolvido em Python com foco na modularização e reutilização de código. Ele permite realizar operações básicas de um banco, como:

- **Depósito**
- **Saque**
- **Visualização de Extrato**
- **Cadastro de Usuário**
- **Criação de Conta Corrente**

## Funcionalidades

### 1. **Depósito**
- Permite adicionar valores ao saldo bancário.
- Recebe argumentos por **posição**.

### 2. **Saque**
- Realiza o saque do valor desejado, respeitando o limite e o número máximo de saques diários.
- Recebe argumentos por **nome** (keyword only).

### 3. **Extrato**
- Mostra o histórico de transações e o saldo atual.
- Recebe argumentos por **posição e nome**.

### 4. **Cadastrar Usuário**
- Armazena dados do cliente: nome, CPF, data de nascimento e endereço.
- Impede o cadastro de dois usuários com o mesmo CPF.

### 5. **Criar Conta Corrente**
- Cria uma nova conta vinculada a um usuário existente.
- Utiliza um número de conta sequencial e fixa a agência em **0001**.

## Regras de Negócio
- Limite de saque por transação: **R$ 500,00**.
- Limite de **3 saques** diários.
- Apenas valores positivos são aceitos para depósito e saque.


## Tecnologias Utilizadas
- **Python 3.x**

## Como Contribuir
1. **Fork** este repositório.
2. Crie uma **branch** com a nova funcionalidade ou correção de bug.
3. Envie um **Pull Request**.

