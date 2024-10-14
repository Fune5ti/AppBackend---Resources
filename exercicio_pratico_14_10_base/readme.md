# Exercício de Desenvolvimento Backend com Node.js

## Descrição

Neste exercício, você irá desenvolver um sistema básico de gerenciamento de uma pequena biblioteca usando Node.js. Você deverá implementar controladores e rotas para interagir com os dados de livros e autores armazenados em arquivos JSON.

O sistema deve permitir:

1. **Listar todos os livros**: Exibir uma lista de todos os livros disponíveis na biblioteca.
2. **Adicionar um novo livro**: Permitir a criação de um novo registro de livro.
3. **Listar todos os autores**: Exibir uma lista de todos os autores.
4. **Adicionar um novo autor**: Permitir a criação de um novo registro de autor.
5. **Remover um livro**: Permitir a exclusão de um livro existente da biblioteca, com base no seu ID.
6. **Remover um autor**: Permitir a exclusão de um autor existente da lista, com base no seu ID.
7. **Buscar livros por autor**: Permitir a listagem de todos os livros escritos por um autor específico, com base no ID do autor.

Você receberá uma estrutura base contendo funções para leitura e escrita dos arquivos JSON, e sua tarefa será criar os controladores e as rotas que irão utilizar essas funções para manipular os dados.

## Requisitos

- Criar rotas REST para gerenciar livros e autores.
- Implementar controladores para processar as requisições.
- Utilizar as funções de leitura e escrita nos controladores para interagir com os dados da biblioteca.
- Utilizar os códigos de retorno apropriados para cada situação, fazendo também o tratamento de erros

## Estrutura de Dados

### Livro

Cada livro deve conter as seguintes informações:

- `id`: identificador único do livro.
- `titulo`: o título do livro.
- `authorId`: o ID do autor associado.
- `anoPublicacao`: o ano de publicação do livro.

### Autor

Cada autor deve conter as seguintes informações:

- `id`: identificador único do autor.
- `nome`: o nome do autor.
