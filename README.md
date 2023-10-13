Sistema de Biblioteca Simples:
Este é um projeto de sistema de biblioteca simples em Java. O projeto consiste em duas classes principais: Livro e Biblioteca. A classe Livro é usada para representar informações sobre livros individuais, enquanto a classe Biblioteca gerencia um catálogo de livros e permite operações como adicionar, remover, reservar e listar livros.

Classes Principais:

*Livro*

A classe Livro tem os seguintes atributos:
titulo: O título do livro.
autor: O autor do livro.
ISBN: O International Standard Book Number, um identificador único para o livro.
emprestado: Um indicador booleano que mostra se o livro está emprestado.

A classe oferece os seguintes métodos:
reservar(): Permite a reserva de um livro, definindo-o como emprestado.
devolver(): Permite a devolução de um livro, marcando-o como não emprestado.
exibir_info(): Retorna informações detalhadas sobre o livro, incluindo título, autor, ISBN e seu status de empréstimo.

*Biblioteca*

A classe Biblioteca é responsável por manter um catálogo de livros usando um ArrayList de objetos da classe Livro. Ela oferece as seguintes funcionalidades:
adicionar_livro(String titulo, String autor, String ISBN): Adiciona um novo livro ao catálogo da biblioteca.
remover_livro(String ISBN): Remove um livro do catálogo com base no seu ISBN.
buscarPorTitulo(String titulo): Retorna uma lista de livros que contenham o título especificado.
emprestarLivro(String ISBN): Permite o empréstimo de um livro do catálogo.
devolverLivro(String ISBN): Permite a devolução de um livro emprestado.
listarLivros(): Retorna todos os livros no catálogo.
listarLivrosEmprestados(): Retorna uma lista de livros atualmente emprestados.
