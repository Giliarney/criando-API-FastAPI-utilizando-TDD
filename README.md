# StoreAPI: Gerenciando Produtos com FastAPI e TDD 🚀


## Construindo uma API robusta com foco em testes

Este repositório abriga o código-fonte da StoreAPI, uma API RESTful desenvolvida com FastAPI que permite gerenciar produtos de uma loja. **Com foco em Test-Driven Development (TDD)**, garantimos código de alta qualidade e confiabilidade para sua aplicação.

## O que a StoreAPI oferece?

- **Crie novos produtos:** Incluindo nome, descrição, preço e outras informações relevantes.
- **Liste produtos:** Exiba todos os produtos cadastrados ou filtre por critérios específicos.
- **Obtenha detalhes de um produto:** Acesse informações completas de um produto específico.
- **Atualize produtos:** Modifique informações de um produto já existente.
- **Exclua produtos:**  Remova produtos do banco de dados.

## Benefícios do TDD:

- **Código limpo e modular:** Escrever testes primeiro incentiva a criação de código mais legível e fácil de manter.
- **Prevenção de erros:** A detecção precoce de falhas durante o desenvolvimento reduz o tempo gasto com correções e depurações.
- **Documentação automática:** Os testes servem como documentação viva do comportamento da API.
- **Confiança na evolução:** Alterações no código podem ser feitas com maior segurança, pois os testes garantem que a funcionalidade original seja mantida.

## Arquitetura da StoreAPI:

A StoreAPI é estruturada em camadas para facilitar a organização e o desenvolvimento:

- **Camada de API:** Implementa os endpoints da API com FastAPI, utilizando rotinas de validação e tratamento de erros.
- **Camada de Negócio:** Contém a lógica de negócio da aplicação, como regras de validação e manipulação de dados.
- **Camada de Persistência:** Interage com o banco de dados MongoDB para armazenar e recuperar informações dos produtos.

## Explore a Documentação Completa!

Para uma visão detalhada da arquitetura, diagramas de sequência, funcionalidades e exemplos de código, consulte a documentação completa no diretório `/docs`.

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/seu-usuario/store-api.git
   cd store-api
   ```

2. **Instale as dependências:**

   ```bash
   poetry install
   ```

3. **Inicie o servidor da API:**

   ```bash
   poetry run uvicorn main:app --reload
   ```


## Conclusão

A StoreAPI é um exemplo prático de como utilizar o TDD para construir uma API RESTful robusta e confiável com FastAPI. Esperamos que este projeto inspire outros desenvolvedores a adotar o TDD em seus projetos e experimentar os benefícios de um código de alta qualidade.



