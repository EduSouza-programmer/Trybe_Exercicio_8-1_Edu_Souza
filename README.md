<h1 align="center">
    <img alt="Image Trybe" src="https://i.ibb.co/d4W2x4g/trybe.png" width="400px" />
</h1>

<h3 align="center">
  Exercício 8-1: JS_ES6 - Higher Order Functions--forEach, find, some, every, sort - Concluído o/ o/ o/
</h3>

<blockquote align="center">“Quanto mais você estuda, mais aprende e se aproxima de realizar seu sonhos!”</blockquote>

<h1></h1>

<p align="center">

  <a href="https://www.linkedin.com/in/eduardosouzaprogrammer/">
    <img alt="Made by Eduardo Souza" src="https://img.shields.io/badge/made%20by-Edu%20Souza-%23F8952D">
  </a>&nbsp;

 <a href="https://edusouza-programmer.github.io/">
<img alt="Github page Edu Souza " src="https://img.shields.io/badge/Github%20page-Edu_Souza-orange">
</a>&nbsp;

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>

<p align="center">
  <a href="#rocket-Sobre-o-Exercício">Sobre o Exercício</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Entrega">Entrega</a>&nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="#Licença">Licença</a>
</p>

# :rocket: Sobre o Exercício

Estes exercícios praticam os conceitos de Higher Order Functions associados a outros já vistos, como arrow functions, template literals, objetos e temas dos fundamentos. Essa mistura de conceitos é muito importante para seu aprendizado, então use tudo o que sabe para resolver os exercícios!

#

# Entrega

### Sumário

- <p><a href="#1">1.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

- <p><a href="#2">2.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

- <p><a href="#3">3.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

- <p><a href="#4">4.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

- <p><a href="#5">5.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

- <p><a href="#6">6.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

- <p><a href="#7">7.</a> Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947;</p>

#

## Exercícios [Implementações]

### 1°

Encontre o nome da primeira pessoa autora do livro nascida no ano de 1947.

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js
const assert = require("assert");

const books = [
	{
		id: 1,
		name: "As Crônicas de Gelo e Fogo",
		genre: "Fantasia",
		author: {
			name: "George R. R. Martin",
			birthYear: 1948,
		},
		releaseYear: 1991,
	},
	{
		id: 2,
		name: "O Senhor dos Anéis",
		genre: "Fantasia",
		author: {
			name: "J. R. R. Tolkien",
			birthYear: 1892,
		},
		releaseYear: 1954,
	},
	{
		id: 3,
		name: "Fundação",
		genre: "Ficção Científica",
		author: {
			name: "Isaac Asimov",
			birthYear: 1920,
		},
		releaseYear: 1951,
	},
	{
		id: 4,
		name: "Duna",
		genre: "Ficção Científica",
		author: {
			name: "Frank Herbert",
			birthYear: 1920,
		},
		releaseYear: 1965,
	},
	{
		id: 5,
		name: "A Coisa",
		genre: "Terror",
		author: {
			name: "Stephen King",
			birthYear: 1947,
		},
		releaseYear: 1986,
	},
	{
		id: 6,
		name: "O Chamado de Cthulhu",
		genre: "Terror",
		author: {
			name: "H. P. Lovecraft",
			birthYear: 1890,
		},
		releaseYear: 1928,
	},
];

function authorBornIn1947() {
	const author = books.find(({ author }) => author.birthYear === 1947);
	return author.author.name;
}

assert.strictEqual(authorBornIn1947(), "Stephen King");
```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 2°

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js

```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 3°

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js

```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 4°

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js

```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 5°

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js

```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 6°

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js

```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

### 7°

#### Resposta:

<details>
 <summary>Código Javascript</summary>

```js

```

</details>

<p align="right">
    <a href="#Sumário">
    <img alt="Back Sumário" src="https://img.shields.io/badge/Back-Sum%C3%A1rio-orange">
  </a>
</p>

#

## Licença

Este projeto está licenciado sob a Licença MIT - consulte [LICENSE](https://opensource.org/licenses/MIT) para maiores detalhes.
