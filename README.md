# Contador

Este projeto é uma aplicação Java simples que solicita dois parâmetros ao usuário e conta os números de acordo com esses parâmetros. O código valida que o segundo parâmetro é maior que o primeiro e imprime números de 1 até a diferença entre os dois parâmetros.

## Estrutura do Projeto

O projeto possui a seguinte estrutura:

- `Contador`: Classe principal que contém o método `main` e a lógica para solicitar os parâmetros e chamar o método `contar`.
- `ParametrosInvalidosException`: Classe personalizada de exceção que é lançada quando o segundo parâmetro é menor que o primeiro.

## Como Usar

1. Execute a aplicação.
2. Digite o primeiro parâmetro.
3. Digite o segundo parâmetro (deve ser maior que o primeiro).
4. A aplicação imprimirá os números de 1 até a diferença entre os dois parâmetros.

## Exceções

A aplicação valida que o segundo parâmetro é maior que o primeiro. Caso contrário, lança uma exceção `ParametrosInvalidosException` com a mensagem "O segundo parâmetro deve ser maior que o primeiro".

## Exemplo de Uso

```java
Digite o primeiro parâmetro
5
Digite o segundo parâmetro
10
Imprimindo o número 1
Imprimindo o número 2
Imprimindo o número 3
Imprimindo o número 4
Imprimindo o número 5
```
