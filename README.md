[![issues](https://img.shields.io/github/issues/luizcsbh/server-nodejs)](https://github.com/luizcsbh/server-nodejs/issues)
![forks](https://img.shields.io/github/forks/luizcsbh/server-nodejs)
![stars](https://img.shields.io/github/stars/luizcsbh/server-nodejs)
[![license](https://img.shields.io/github/license/luizcsbh/server-nodejs)](https://github.com/luizcsbh/server-nodejs/blob/master/LICENSE)
![code-size](https://img.shields.io/github/languages/code-size/luizcsbh/server-nodejs)
![GitHub Workflow Status](https://img.shields.io/github/workflow/status/luizcsbh/server-nodejs/Node%20CI)

# Server-Nodejs

Exercício de Nodejs

Curso: Desenvolvimento web Full Stack

Disciplina: Programação web com Nodejs

Professor: Samuel Martins

## Exercício 2.1
Passo 1: entre na documentação do express-generator
[Express-Generator](https://expressjs.com/pt-br/starter/generator.html)
Passo 2: siga as instruções para instalar o express-generator globalmente:
```node
npm i -g express-generator
```

Passo 3: através do terminal, execute o comando:
```node
express --view=hbs my-project
```

Passo 4: entre no projeto criado e execute os seguintes comandos:
```node
npm install
```
Em seguida o comando para inicializar o projeto:
```node
npm start
```

O projeto deverá estar rodando na url http://localhost:3000

Passo 5: construa uma página inicial que receba 2 parâmetros GET: firstName e lastName;

Passo 6: mostre uma mensagem de boas vindas com o nome e sobrenome recebidos via parâmetro;

Passo 7: em uma outra tela, na rota /form , crie um formulário com os seguintes campos: nome, e-mail e
endereço.

## Exercício 2.2

Utilizando o conceito de APIs rest JSON, vamos fazer um CRUD de produtos, utilizando uma variável
local.

Passo 1: crie uma rota /api/products do tipo POST que irá receber no corpo da requisição os campos id ,
name e description . Nessa mesma rota, insira os dados recebidos em uma variável local.

Passo 2: na rota /api/products/list , defina um GET que irá listar um json com a seguinte estrutura
abaixo listando os produtos que você cadastrou:

Passo 3: na rota /api/products/:id , defina um DELETE que irá remover o produto da nossa base local;

Passo 4: na rota /api/products/:id , defina um PUT que irá atualizar os dados do produto com os dados
recebidos.

Para testar o exercício 2.2, utilize o POSTMAN

## Motivação

Projeto PHP onde criada uma aplicação RESTful completa, será implementada uma API para entender a nuances do Framework Symfony e onde será feita a gestão dos "post" de um blog apresentado pelo Professor Tales Augusto [:email:](mailto:tales.augusto.santos@gmail.com?subject=[Github]%20Projeto%20Simphony%20Blog).

## Author

- [Luiz Santos](https://about.me/luizcsbh)

## License

This project is open source and available under the [MIT License](LICENSE).

