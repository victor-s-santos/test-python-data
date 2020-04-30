# Estudo Python e Data

O objetivo desse exercício é buscar todos os livros sobre o Tema "Python" 
na API do [Open Library](https://openlibrary.org) e salvar a resposta 
em um arquivo JSON para processamento posterior.

Para fazer isso é recomendado utilizar o método 
[Search](https://openlibrary.org/dev/docs/api/search), especificando o
parametro "subject" como "python".

Não é necessário tratar a paginação da API, é suficiente apenas uma
requisição!

## Exemplo de chamada para a API

```
GET http://openlibrary.org/search.json?subject=python 
```
