<div align="center">
    <h1> Gerenciador de produtos </h1>
</div>

## Sobre o sistema

Será um gerenciador de produtos de um super mercado, onde podemos visualizar todos os produtos, visualizar os detalhes do produto, adicionar um produto, editar produto e deletar produto.

## Tecnologias

- Java 17
- Maven
- Spring
- Spring web
- MySql

## Requisitos para utilização

- Ter o java jdk 17 instalado
- Ter o apache maven instalado e configurado
- Ter o MySql server instalado

## Estrutura de pastas

- controller
- - ProdutoController.java
- repository
- - ProdutoRepository.java
- model
- - ProdutoModel.java
- CrudJavaSpringApplication.java

## Diagrama de Classe (Simulação de Tabela)

Este é um exemplo de como simular uma tabela de produtos usando Mermaid no Markdown.

```mermaid
classDiagram
    class Produto {
        -UUID id
        -string nome
        -float preco
        -int quantidade
        +getID() UUID
        +setID(UUID id) void
        +getNome() string
        +setNome(string nome) void
        +getPreco() float
        +setPreco(float preco) void
        +getQuantidade() int
        +setQuantidade(int quantidade) void
    }
```