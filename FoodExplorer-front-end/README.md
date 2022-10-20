<h1 align="center">
	FoodExplorerFront-End
</h1>

<h3 align="center">
	A aplicação desenvolvida é um cardápio digital para um restaurante fictício, conhecido como foodExplorer.
</h3>

<p align="center">
	<a href="#about">About</a> •
	<a href="#tech-stack">Tech Stack</a> •
	<a href="#installation">Installation</a> •
	<a href="#usage">Usage</a> • 
	<a href="#contact">Contact</a> 
</p>

## About

Critérios de avaliação.

Atende a todas as especificações descritas

✔️ Um projeto estruturado, com uma boa organização das pastas, divisão de componentes no front-end, etc.

✔️ Um arquivo README.md com as especificações sobre como executar o projeto em um ambiente dev.

✔️ Os usuários deverão se autenticar para entrar na aplicação através da tela de login, você pode aplicar o que aprendeu nas aulas de autenticação JWT. A autenticação deve ser validada com senha.

✔️ O admin irá fazer upload de imagens para cadastrar os pratos.

✔️ Para finalizar, faça o deploy da sua aplicação.

✔️ Dê nomes significativos para as suas funções e variáveis: trabalhe um pouco com os conceitos do Clean Code.

✔️ Os dados do admin, do restaurante e dos usuários serão armazenados em um banco de dados.

✔️ Possibilidade de fazer uma busca pelo nome do prato, pelos ingredientes ou por prato favorito

✔️ É essencial que a sua interface consuma a sua própria API.

⌛ Interessante deixar a aplicação responsiva: utilize o conceito de Mobile First que foi aprendido em aula.

✔️ Fica a seu critério onde aplicar animações, transições e transformações.

✔️ Atende ao modelo proposto no Figma e contém elementos indicativos de ação e estado.

<img src="/src/assets/Screenshot_1.png"/>

## Tech Stack

<img src="https://img.shields.io/badge/Javascript-05122A?style=flat&logo=javascript" alt="javascript Badge" height="25">&nbsp;
<img src="https://img.shields.io/badge/React-05122A?style=flat&logo=react" alt="react Badge" height="25">&nbsp;

## Installation

A aplicação e composta por 2 partes, back-end e front-end use os seguintes comandos para a aplicação rodar.

## Usage

To use this project, follow the steps above:

// rodar o back-end
$ npm install

$ npx knex migrate:latest

$ npx knex seed:run

// rodar o servidor
$ npm run dev

// usuário adm para fazer os testes
email: admin@teste.com
senha: 123456789

// rodar o front-end
// instalar todas as dependências
npm install

// rodar o front da aplicação
npm run dev
