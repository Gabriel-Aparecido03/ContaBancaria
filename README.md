# BDD - Conta Bancaria
Atividade utilizanod cucumber e junit

## Descrição do repositório
Este repositório guarda o código de uma aplicação de exemplo utilizada para fins de estudos de BDD (Behavior Driven Development) e TDD (Test Driven Development ). <br/>
Usando Cucumber e Junit

##Autor
Gabriel Aparecido da Silva

##Estrutura
- `src/test`: Contém o arquivo do Cucumber e Junit.
- `src/main`: Contém a classe Conta .
- `docs/`: Contém a documentação do projeto utilizando JAVADOCS.


##Cucumber

###Feature
`
Feature:Cliente faz saque de dinheiro como um cliente,
eu gostaria de sacar dinheiro em caixa eletrônico,
para que eu tenha que esperar em uma fila do banco.
`

###Tag1
`
Scenario: Cliente especial com saldo negativo
  Given Um cliente especial com saldo atual de -200 reais
  When for solicitado um saque no valor de 100 reais
  Then deve efetuar o saque e atualizar o saldo da conta para -300 reais
  And check more outcomes
`

###Tag2
`
Scenario Outline: Cliente comum com saldo negativo
  Given Um cliente comum com saldo atual de -200 reais
  When solicitar um saque de 200 reais
  Then não deve efetuar o saque e deve retornar a mensagem Saldo Insuficiente
`

Imagem :
![image](https://github.com/Gabriel-Aparecido03/ContaBancaria/assets/67979742/1515040d-eb25-4cd0-8518-24172dfe34fa) </br >

##Javadoc

![image](https://github.com/Gabriel-Aparecido03/ContaBancaria/assets/67979742/e271baa3-7750-4b8b-b0ca-86ab4d78b5fe)<br/>

##Clase Conta

![image](https://github.com/Gabriel-Aparecido03/ContaBancaria/assets/67979742/f7c3bc6b-3cd4-4c2e-b964-b275b7922677)


Última atualização 30/11/23
