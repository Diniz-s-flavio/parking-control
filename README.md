# Parking-control API
 API Spring que usa de Spring Framework, Spring Data JPA, Spring Web.
## O que é que a parking-control?
A função dessa API e fazer o controle das  vagas de estacionamento de um condomineo por exemplo.

A conexão com o banco de dados é realizada pelo connector/j com MySql, trocar o banco de dados responsavel é simple basta trocar a dependencia do driver do connector/j do MySql para o do banco desejado.
E no application.properties trocar a URL de conexão também para o banco desejado.

# O que ela faz?
Atualmente cadastro de vaga, listar as Vagas cadastradas, buscar por uma vaga expecifica, atualizar o cadastro de uma vaga e deletar uma vaga. 

# API para Sitema de delivery

A função dessa API e fazer o controle das  vagas de estacionamento de um condomínio por exemplo.
para fins de estudos de algumas funcionalides.
Desenvolvido em Spring Boot, utilizando Java 11, foi implementada uma API RESTful, com tratamentos de erros de forma simples
e especificada, realização de operações POST, DELETE, GET, PUT, PATCH e retorno de códigos de status apropriados. Também foi
utilizado o LOMBOK visando reduzir o boilerplate.
Foram explorados a utilização da especificação Bean Validation para criação de Annotations e customização de validadores e
a configuração de Internacionalização.

## Tecnologias Utilizadas

- Java 11
- Padrão MVC
- Spring Boot
- LOMBOK
- MySQL 8
- Padrão DTO

## Recursos e Funcionalidades

- **Gestão de vagas(Parking Spots):** Adicione, atualize, consulte e exclua vagas.

## Configuração do Ambiente

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/Diniz-s-flavio/parking-control
   ```

2. **Compilação e Execução:**

   ```shell
   mvn spring-boot:run
   ```

## Teste da API

Os testes foram realizado pelo Postman.

## Endpoints da API

Para testar a API adentre pela URL: http://localhost:8080/ o Guia de End-Points pelo Swagger-UI deve ser implementado em breve.


## Contato

Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato:

- Nome: Flávio Diniz de Sousa
- Email: dinizdesousaflavio@gmail.com
- LinkedIn: https://www.linkedin.com/in/flavio-diniz-de-sousa-bb7729259/