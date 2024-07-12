# StoreAPI: Gerenciando Produtos com FastAPI e TDD 🚀

![Diagrama de Arquitetura](https://www.freecodecamp.org/news/content/images/2021/06/rest-api-architecture.png)

## Construindo uma API robusta com foco em testes

Este repositório abriga o código-fonte da StoreAPI, uma API RESTful desenvolvida com FastAPI que permite gerenciar produtos de uma loja. **Com foco em Test-Driven Development (TDD)**, garantimos código de alta qualidade e confiabilidade para sua aplicação.

## O que a StoreAPI oferece?

- **Crie novos produtos:** Incluindo nome, descrição, preço e outras informações relevantes.
  ![Criar Produto](https://www.shutterstock.com/image-vector/add-button-plus-sign-icon-vector-2011443885)
- **Liste produtos:** Exiba todos os produtos cadastrados ou filtre por critérios específicos.
  ![Listar Produtos](https://www.shutterstock.com/image-vector/list-icon-vector-illustration-flat-style-1438643575)
- **Obtenha detalhes de um produto:** Acesse informações completas de um produto específico.
  ![Detalhes do Produto](https://www.shutterstock.com/image-vector/information-icon-vector-sign-symbol-1003768784)
- **Atualize produtos:** Modifique informações de um produto já existente.
  ![Atualizar Produto](https://www.shutterstock.com/image-vector/update-icon-refresh-symbol-arrow-circle-1081419759)
- **Exclua produtos:**  Remova produtos do banco de dados.
  ![Excluir Produto](https://www.shutterstock.com/image-vector/delete-trash-can-icon-vector-illustration-flat-style-1103865526)

## Benefícios do TDD:

- **Código limpo e modular:** Escrever testes primeiro incentiva a criação de código mais legível e fácil de manter.
  ![Código Limpo](https://www.shutterstock.com/image-vector/clean-code-concept-illustration-programming-1990377245)
- **Prevenção de erros:** A detecção precoce de falhas durante o desenvolvimento reduz o tempo gasto com correções e depurações.
  ![Prevenção de Erros](https://www.shutterstock.com/image-vector/bug-icon-vector-illustration-1444028392)
- **Documentação automática:** Os testes servem como documentação viva do comportamento da API.
  ![Documentação](https://www.shutterstock.com/image-vector/document-icon-vector-illustration-flat-style-600103589)
- **Confiança na evolução:** Alterações no código podem ser feitas com maior segurança, pois os testes garantem que a funcionalidade original seja mantida.
  ![Confiança na Evolução](https://www.shutterstock.com/image-vector/continuous-integration-and-continuous-delivery-1788780612)

## Arquitetura da StoreAPI:

A StoreAPI é estruturada em camadas para facilitar a organização e o desenvolvimento:

- **Camada de API:** Implementa os endpoints da API com FastAPI, utilizando rotinas de validação e tratamento de erros.
- **Camada de Negócio:** Contém a lógica de negócio da aplicação, como regras de validação e manipulação de dados.
- **Camada de Persistência:** Interage com o banco de dados MongoDB para armazenar e recuperar informações dos produtos.
  ![Arquitetura em Camadas](https://www.freecodecamp.org/news/content/images/2021/06/rest-api-architecture.png)

## Explore a Documentação Completa!

Para uma visão detalhada da arquitetura, diagramas de sequência, funcionalidades e exemplos de código, consulte a documentação completa no diretório `/docs`.

## Comece agora mesmo!

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

## Contribua com a StoreAPI!

Contribuições são bem-vindas! Para colaborar com o projeto:

1. **Fork** o repositório.
2. **Crie um branch** com suas alterações.
3. **Envie um pull request** com uma descrição clara das suas modificações.

## Conclusão

A StoreAPI é um exemplo prático de como utilizar o TDD para construir uma API RESTful robusta e confiável com FastAPI. Esperamos que este projeto inspire outros desenvolvedores a adotar o TDD em seus projetos e experimentar os benefícios de um código de alta qualidade.

**Lembre-se de substituir `seu-usuario` no comando `git clone` pelo seu nome de usuário no GitHub.**


