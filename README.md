# Catálogo de Livros (LiterAlura)

Este projeto faz parte de um desafio do programa ONE - Oracle Next Education, uma colaboração educacional entre a Alura e a Oracle.

### Descrição do Desafio

A meta é criar um Catálogo de Livros que permita a interação textual via console com os usuários, oferecendo pelo menos cinco opções de interação. Os dados sobre livros e autores serão obtidos através de uma API específica e armazenados em um banco de dados.

### Funcionalidades

- **Buscar livro pelo título**: Permite que os usuários encontrem livros pelo título.
- **Listar todos os livros registrados**: Exibe todos os livros armazenados no banco de dados.
- **Listar todos os autores**: Mostra uma lista de todos os autores cadastrados.
- **Listar autores vivos em um ano específico**: Filtra e apresenta os autores que estavam vivos em um determinado ano.
- **Listar livros em um idioma específico**: Mostra livros disponíveis em um idioma específico.
- **Mostrar quantidade de livros por idioma**: Exibe o número total de livros disponíveis em um idioma específico.

### Instalação

Para rodar a aplicação localmente, siga os passos abaixo:

1. Clone este repositório.
2. Certifique-se de que a JDK 17 ou superior está instalada.
3. Importe o projeto utilizando o Maven em sua IDE preferida.
4. Configure o PostgreSQL atualizando as informações no arquivo `application.properties`.
5. Execute a classe `CatalogoDeLivrosApplication.java`.

### Tecnologias Utilizadas

- **Java 17**: Linguagem de programação principal.
- **Maven**: Ferramenta para automação de build e gerenciamento de dependências.
- **Spring Boot**: Framework que simplifica o desenvolvimento de aplicações Java.
- **Spring Data JPA**: Framework para persistência de dados usando JPA.
- **PostgreSQL**: Banco de dados relacional.
- **Jackson Databind**: Biblioteca para conversão entre objetos Java e JSON.
- **API Gutendex**: Fonte de dados utilizada para obter informações sobre livros e autores ([Gutendex API](https://gutendex.com/)).

Este projeto visa aplicar na prática os conhecimentos adquiridos no programa, focando na integração de APIs, persistência de dados e interação via console.
