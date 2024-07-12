# StoreAPI com FastAPI e TDD

![Diagrama de Arquitetura](/docs/img/store.drawio.png)

## Descrição do Projeto

Este projeto consiste no desenvolvimento de uma API utilizando FastAPI com foco em Test-Driven Development (TDD). A API permite gerenciar produtos de uma loja, utilizando MongoDB para armazenamento e Pydantic para validação de dados.

## Objetivo

O objetivo deste projeto é demonstrar como aplicar TDD na prática, desenvolvendo uma API robusta e escalável com FastAPI, garantindo qualidade por meio de testes automatizados desde o início do desenvolvimento.

## Funcionalidades

- **Criação de Produto**: Endpoint para criar novos produtos.
- **Listagem de Produtos**: Endpoint para listar todos os produtos cadastrados.
- **Detalhamento de Produto**: Endpoint para obter detalhes de um produto específico.
- **Atualização de Produto**: Endpoint para atualizar informações de um produto existente.
- **Exclusão de Produto**: Endpoint para excluir um produto do sistema.

## Diagramas de Sequência

### Diagrama de Criação de Produto

![Diagrama de Criação de Produto](/docs/img/product.drawio.png)

### Outros Diagramas (Listagem, Detalhamento, Atualização, Exclusão)

Você pode encontrar os diagramas completos no diretório `/docs`.

## Desafios Adicionais

- Implementação de tratamento de exceções específicas.
- Adição de filtros avançados para consultas de produtos (por exemplo, por faixa de preço).

## Pré-requisitos

Para executar este projeto localmente, você precisará ter instalados:

- Python (com pyenv para gerenciamento de versões recomendado).
- Poetry para gerenciamento de dependências.

## Instalação

1. Clone este repositório.

   ```bash
   git clone https://github.com/seu-usuario/store-api.git
   cd store-api
