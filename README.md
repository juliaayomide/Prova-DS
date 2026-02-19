# 📚 Exercício de Programação Orientada a Objetos (POO)

## 📌 Contexto do exercício

Este repositório contém um exercício desenvolvido para uma **avaliação da disciplina de Desenvolvimento de Sistemas**, no qual foi trabalhado o conteúdo de **Programação Orientada a Objetos (POO)** utilizando a linguagem Java.

O objetivo do exercício era aplicar, na prática, conceitos fundamentais da POO por meio da criação de classes, herança entre elas e reutilização de métodos, simulando um sistema simples de publicações.

---

## 🧠 Situação proposta

Durante a prova, foi solicitado o desenvolvimento de um sistema que representasse **publicações**, como livros e revistas, utilizando uma classe base e classes derivadas.

A partir disso, foi necessário:
- Criar uma classe genérica para representar uma publicação
- Criar classes específicas para Livro e Revista
- Utilizar herança para reaproveitamento de código
- Aplicar encapsulamento com getters e setters
- Utilizar sobrescrita e sobrecarga de métodos

---

## 🏗️ Estrutura do projeto

O projeto é composto pelas seguintes classes:

- `Publicacao` – classe base
- `Livro` – classe que herda de Publicacao
- `Revista` – classe que herda de Publicacao
- `Main` – classe responsável por executar o programa

---

## 📘 Classe Publicacao

A classe `Publicacao` é a classe base do sistema.  
Ela contém atributos comuns a qualquer tipo de publicação, como:

- título
- autor
- ano de publicação

Essa classe utiliza **encapsulamento**, mantendo os atributos privados e permitindo o acesso por meio de getters e setters.

Além disso, possui o método `exibirDetalhes()`, responsável por exibir as informações básicas da publicação.

---

## 📗 Classe Livro

A classe `Livro` herda da classe `Publicacao`, aplicando o conceito de **herança**.

Além dos atributos herdados, ela possui:
- número de páginas
- editora

Nessa classe ocorre a **sobrescrita do método `exibirDetalhes()`**, onde são exibidas tanto as informações da classe base quanto as informações específicas do livro.

Também há a **sobrecarga do método `exibirDetalhes(boolean exibicao)`**, permitindo exibir informações completas ou parciais de acordo com o valor booleano informado.

---

## 📰 Classe Revista

A classe `Revista` também herda da classe `Publicacao`.

Ela possui atributos específicos:
- número da edição
- mês da publicação

Assim como na classe Livro, ocorre:
- sobrescrita do método `exibirDetalhes()`
- sobrecarga do método `exibirDetalhes(boolean exibicao)`

Esses métodos permitem diferentes formas de exibição das informações da revista.

---

## ▶️ Classe Main

A classe `Main` é responsável por testar o funcionamento do sistema.

Nela são criados objetos das classes `Livro` e `Revista`, os atributos são definidos utilizando setters e os métodos de exibição são chamados para demonstrar o uso da herança, sobrescrita e sobrecarga de métodos.

---

## ✅ Conceitos de Programação Orientada a Objetos aplicados

Durante o desenvolvimento deste exercício, foram aplicados os seguintes conceitos:

- Encapsulamento  
- Herança  
- Sobrescrita de métodos  
- Sobrecarga de métodos  
- Criação e manipulação de objetos  
- Reutilização de código  

---

## 🎯 Conclusão

Este exercício foi fundamental para a compreensão prática da Programação Orientada a Objetos, permitindo aplicar conceitos teóricos em um cenário simples e organizado.

O projeto demonstra como a POO pode facilitar a estruturação e manutenção do código por meio da reutilização e especialização de classes.
