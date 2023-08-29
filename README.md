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
   
## Como Usar

### Pré-requisitos

Certifique-se de ter o Docker e o Docker Compose instalados no seu sistema.

### Passos para Executar a API

1. Clone este repositório para o seu sistema.

2. Navegue até o diretório do projeto:

3. Execute o seguinte comando para construir e executar a aplicação: docker-compose up

Isso criará e executará os contêineres necessários para a aplicação.

4. Aguarde até que todos os contêineres estejam em execução. Você verá os logs no terminal indicando que a aplicação está pronta.

5. Acesse a API em `http://localhost:8080`.

6. Você pode usar ferramentas como o Postman ou o cURL para fazer requisições para a API.

### Encerrando a Execução

Quando você terminar de usar a API, você pode parar os contêineres executando o seguinte comando: docker-compose stop


## Endpoints da API

- `GET /books Retorna a lista de todos os livros.
- `GET /books/{id}`: Retorna informações detalhadas sobre um livro específico com base no ID.
- `POST /books`: Cadastra um novo livro na biblioteca.
- `PUT /books/{id}`: Atualiza as informações de um livro específico com base no ID.
- `DELETE /books/{id}`: Remove um livro da biblioteca com base no ID.

## Contribuições

Contribuições para a melhoria desta API são bem-vindas. Se você deseja contribuir, sinta-se à vontade para criar pull requests no repositório.
