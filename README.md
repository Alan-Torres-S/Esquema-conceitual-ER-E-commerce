# Projeto Conceitual de Banco de Dados – E-COMMERCE

Neste repositório encontra-se o projeto do Bootcamp Unimed BH da Digital Innovation One (DIO) sobre a elaboração de esquema conceitual de entidade relacionamento (ER) para o cenário de e-commerce.

# Sobre o Projeto

O esquema conceitual de ER foi elaborado inicialmente pela Data Scientist da Dio Juliana Mascarenhas.
Posteriormente, com base nos conceitos abordados no decorrer do curso, foram realizados o desenvolvimento e refinamento deste modelo.

Para a elaboração deste esquema conceitual de ER foi utilizada a ferramenta MySQL Workbench.

# Premissas do Projeto

Criação de esquema conceitual de modelagem de dados ER para reprodução de um cenário de comercialização de produtos através de e-commerce.

## Narrativa - Produto

* Os produtos são vendidos por uma única plataforma online. Contudo, estes podem ter vendedores distintos (terceiros).
* Cada produto possui um fornecedor.
* Um ou mais produtos podem compor um pedido.

## Narrativa - Cliente

* O cliente pode se cadastrar no site com seu CPF ou CNPJ. 
* O Endereço do cliente irá determinar o valor do frete.
* Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto.

## Narrativa - Pedido

* O pedidos são criados por clientes e possuem informações de compra, endereço e status da entrega.
* Um produto ou mais compõem o pedido.
* O pedido pode ser cancelado.

## Refinamento do modelo

* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações.
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento.
* Entrega – Possui status e código de rastreio.

