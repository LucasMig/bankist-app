# Bankist App

## Objetivo

Criar uma aplicação que simulasse uma interface e algumas funções básicas de um serviço bancário.

A intenção principal foi entender um pouco melhor os tipos de estruturas de dados, métodos e recursos do JavaScript.

## Como testar
O resultado final do projeto está hospedado [aqui](https://bankist-migliori.netlify.app/). 

Para testar, é preciso fazer o login com alguma das contas existentes. Essas são as combinações:

**user:** js<br>
**pin:** 1111

**user:** jd<br>
**pin:** 2222

**user:** lm<br>
**pin:** 3333

**user:** ss<br>
**pin:** 4444

## Funcionalidades e regras de negócio

Cada usuário representa uma conta, que é um Objeto. Após acessar com o user e o pin, a interface será "construída" com as informações da conta do respectivo usuário. 

### Histórico de movimentações

Mostra valor e data das movimentações, formatados de acordo com a região do usuário.

### Campo para transferência

Nesse campo, é possível transferir valores para alguma das outras contas existentes. Basta digitar o user e o valor desejado.

### Campo para empréstimo

Nesse campo, o usuário pode solicitar um empréstimo. Para que o empréstimo seja "aprovado", o usuário precisa ter alguma movimentação de entrada que seja pelo menos 1/10 do valor solicitado.

Se essa condição for satisfeita, o valor solicitado é adicionado à conta após 3 segundos. Se não for, nada acontece.

### Campo para excluir a conta

Nesse campo, o usuário pode excluir sua conta. Ao fazer isso, o objeto (conta) é excluído da array de contas.

## Sobre esse projeto
A aplicação foi criada com HTML, CSS e JavaScript. Aprendi e pratiquei um pouco mais alguns princípios e práticas como:

- Estruturas de dados
- JavaScript Assíncrono
- Qualidade do código
- Baixo acoplamento
- Componentização e reutilização de código
