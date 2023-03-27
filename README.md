# Parking-control API
 API Spring que usa de Spring Framework, Spring Data JPA, Spring Web.
## O que é que a parking-control?
A função dessa API e fazer o controle das  vagas de estacionamento de um condomineo por exemplo.

A conexão com o banco de dados é realizada pelo connector/j com MySql, trocar o banco de dados responsavel é simple basta trocar a dependencia do driver do connector/j do MySql para o do banco desejado.
E no application.properties trocar a URL de conexão também para o banco desejado.

# O que ela faz?
Atualmente cadastro de vaga, listar as Vagas cadastradas, buscar por uma vaga expecifica, atualizar o cadastro de uma vaga e deletar uma vaga. 