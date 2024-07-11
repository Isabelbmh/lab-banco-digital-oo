# Criando um Banco Digital com Java e Orientação a Objetos


Desafio: Criar um banco digital considerando o que foi aprendido no domínio bancário, iremos abstrair uma solução Orientada a Objetos em Java. 
Cenário oferecido:
“Um banco oferece aos seus clientes dois tipos de contas (corrente e poupança), as quais possuem as funcionalidades de depósito, saque e transferência (entre contas da própria instituição).”

### Abstração: O sistema abstrai as operações básicas de um banco, focando nos tipos de contas e operações comuns (depósito, saque, transferência).

### Encapsulamento: Atributos das classes são privados e acessíveis via métodos públicos.

### Herança: ContaCorrente e ContaPoupanca herdam da classe base Conta.

### Polimorfismo: Operações em Conta podem ser realizadas tanto em ContaCorrente quanto em ContaPoupanca.



Esta estrutura fornece um sistema simples e extensível para um banco digital, facilitando a manutenção e evolução do código.