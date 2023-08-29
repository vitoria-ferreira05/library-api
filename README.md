# library-api
# API Biblioteca - README

Este é o README para a API da Biblioteca, uma aplicação desenvolvida para gerenciar informações sobre livros. A API foi construída utilizando Docker para a containerização e o banco de dados PostgreSQL para armazenar os dados.

## Funcionalidades

A API da Biblioteca oferece as seguintes funcionalidades:

1. **Exibir Todos os Livros:** Esta rota permite visualizar uma lista contendo todos os livros disponíveis na biblioteca.

2. **Exibir um Livro Específico:** Com esta funcionalidade, você pode recuperar informações detalhadas sobre um livro específico. Basta fornecer o ID do livro desejado.

3. **Cadastro de um Novo Livro:** Utilize esta rota para cadastrar um novo livro na biblioteca. 

4. **Alteração de um Livro:** Caso as informações de um livro precisem ser atualizadas, esta funcionalidade permite fazer modificações nos detalhes do livro com base no seu ID.

5. **Deleção de um Livro:** Se um livro não for mais necessário na biblioteca, a API oferece uma rota para remover o livro com base no seu ID.

## Endpoints da API

- `GET /books Retorna a lista de todos os livros.
- `GET /books/{id}`: Retorna informações detalhadas sobre um livro específico com base no ID.
- `POST /books`: Cadastra um novo livro na biblioteca.
- `PUT /books/{id}`: Atualiza as informações de um livro específico com base no ID.
- `DELETE /books/{id}`: Remove um livro da biblioteca com base no ID.

## Contribuições

Contribuições para a melhoria desta API são bem-vindas. Se você deseja contribuir, sinta-se à vontade para criar pull requests no repositório.
