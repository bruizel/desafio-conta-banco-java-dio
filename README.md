# Desafio: Conta Banco - Java - DIO

Projeto desenvolvido como parte do **Bootcamp Santander 2025** na plataforma [DIO](https://web.dio.me/track/fbf007ec-42df-4c8b-af3d-e8dea9448693), para praticar os fundamentos da linguagem **Java**.

---

## Descrição

Aplicação simples no terminal que simula a criação de uma conta bancária. O usuário preenche os dados e recebe uma mensagem de boas-vindas com as informações.

- Número da conta
- Número da agência
- Nome do cliente
- Saldo inicial

---

## Tecnologias utilizadas

- Java 
- Terminal (entrada/saída de dados)
- Classe `Scanner`
- Visual Studio Code

---

## Como executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/bruizel/desafio-conta-banco-java-dio.git
2. Navegue até o diretório do projeto:
   ```bash
   cd desafio-conta-banco-java-dio
3. Compile o programa:
   ```bash
   javac ContaTerminal.java
4. Execute o programa:
   ```bash
   java ContaTerminal

---

## Conceitos aplicados

- Leitura de dados com `Scanner`
- Tipos primitivos (`int`, `String`, `double`)
- Concatenação e formatação de strings
- Estrutura de um programa Java (método `main`)

---

## Exemplo de saída no terminal
  ```text
  Por favor, digite o número da Conta:
  1021
  Por favor, digite o número da Agência:
  067-8
  Por favor, digite seu nome:
  MARIO ANDRADE
  Por favor, digite o saldo inicial:
  237.48
```
```text
Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco.
Sua agência é 067-8, conta 1021 e seu saldo 237.48 já está disponível para saque.
