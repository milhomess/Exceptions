#Tratamento de exceções em java

Este repositório contém um exemplo simples de tratamento de exceções em Java. O código demonstra como capturar e lidar com exceções que podem ocorrer durante a execução de um programa.

<hr>

##Sobre o código

O código solicita ao usuário que insira um número. Em seguida, tenta dividir 10 pelo número informado. Durante essa operação, podem ocorrer exceções, como a divisão por zero ou entrada inválida. O programa utiliza blocos try, catch e finally para tratar esses casos.

##Explicação

`try`: O código dentro desse bloco é executado e pode gerar exceções.
`catch (ArithmeticException e)`: Captura o erro específico de divisão por zero e exibe uma mensagem ao usuário.
`catch (Exception e)`: Captura qualquer outra exceção não tratada anteriormente.
`finally`: Esse bloco sempre é executado, garantindo que o Scanner seja fechado, evitando vazamento de recursos.
