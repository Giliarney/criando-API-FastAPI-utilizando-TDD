# StoreAPI: Gerenciando Produtos com FastAPI e TDD

![Diagrama de Arquitetura](docs/images/architecture.png)

Este repositório abriga o código-fonte da StoreAPI, uma API RESTful construída com FastAPI que permite gerenciar produtos de uma loja. A aplicação foi desenvolvida com foco em Test-Driven Development (TDD), garantindo código de alta qualidade e confiabilidade.

## Descrição do Projeto

A StoreAPI oferece endpoints para:

- **Criar novos produtos:** Incluindo nome, descrição, preço e outras informações relevantes.
- **Listar produtos:** Exibir todos os produtos cadastrados ou filtrar por critérios específicos.
- **Obter detalhes de um produto:** Acessar informações completas de um produto específico.
- **Atualizar produtos:** Modificar informações de um produto já existente.
- **Excluir produtos:** Remover produtos do banco de dados.

## Benefícios do TDD

O desenvolvimento orientado por testes (TDD) trouxe diversos benefícios para o projeto:

- **Código limpo e modular:** A necessidade de escrever testes primeiro incentiva a criação de código mais legível e fácil de manter.
- **Prevenção de erros:** A detecção precoce de falhas durante o desenvolvimento reduz o tempo gasto com correções e depurações.
- **Documentação automática:** Os testes servem como documentação viva do comportamento da API.
- **Confiança na evolução:** As alterações no código podem ser feitas com maior segurança, pois os testes garantem que a funcionalidade original seja mantida.

## Arquitetura do Projeto

A StoreAPI é estruturada em camadas para facilitar a organização e o desenvolvimento:

- **Camada de API:** Implementa os endpoints da API com FastAPI, utilizando rotinas de validação e tratamento de erros.
- **Camada de Negócio:** Contém a lógica de negócio da aplicação, como regras de validação e manipulação de dados.
- **Camada de Persistência:** Interage com o banco de dados MongoDB para armazenar e recuperar informações dos produtos.

## Documentação Completa

Para uma visão detalhada da arquitetura, diagramas de sequência, funcionalidades e exemplos de código, consulte a documentação completa no diretório `/docs`.

## Pré-requisitos

Para executar o projeto localmente, você precisará ter os seguintes softwares instalados:

- **Python 3.7+** (recomenda-se utilizar pyenv para gerenciamento de versões)
- **Poetry:** Para gerenciar dependências do projeto

## Instalação e Execução

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

A API estará disponível em `http://127.0.0.1:8000/docs` para visualização e interação.

## Contribuições

Contribuições são bem-vindas! Para colaborar com o projeto:

1. **Fork** o repositório.
2. **Crie um branch** com suas alterações.
3. **Envie um pull request** com uma descrição clara das suas modificações.

## Licença

Este projeto está licenciado sob a licença MIT.

## Conclusão

A StoreAPI é um exemplo prático de como utilizar o TDD para construir uma API RESTful robusta e confiável com FastAPI. Esperamos que este projeto inspire outros desenvolvedores a adotar o TDD em seus projetos e experimentar os benefícios de um código de alta qualidade.
