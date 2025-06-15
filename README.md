# Desafio Java - Controle de Fluxo - DIO

Este repositório foi criado para resolver um dos desafios propostos na **Trilha Java Básico** da DIO (Digital Innovation One), com foco em estruturas de controle de fluxo em Java.

## Descrição do Desafio

O desafio consiste em desenvolver um programa Java que receba dois números inteiros via terminal e utilize uma estrutura de repetição `for` para imprimir no console a contagem entre eles.

### Regras do sistema

- O programa deve receber **dois parâmetros inteiros** via linha de comando.
- Se o **primeiro número for menor que o segundo**, o programa imprimirá a quantidade de interações com base na diferença entre os dois números.
   
- Se o **primeiro número for maior que o segundo**, o sistema deve lançar a **exceção customizada** `ParametrosInvalidosException` com a mensagem: **O segundo parâmetro deve ser maior que o primeiro**


### Estrutura do projeto

- `DesafioControleFluxo` (nome do projeto)
- `Contador.java`: classe principal responsável pela lógica do sistema.
- `ParametrosInvalidosException.java`: exceção customizada que representa erro de negócio.

## Tecnologias Utilizadas

- Java 21
