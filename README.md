# Refinando-um-Projeto-Conceitual-de-Banco-de-Dados-E-COMMERCE

Descrição do Projeto:
Este projeto apresenta um modelo conceitual de banco de dados para um sistema de e-commerce, com foco no gerenciamento de clientes, pedidos, pagamentos e entregas. O objetivo é representar de forma clara como os dados se relacionam dentro de um fluxo de compra online.

Entidades principais:
Cliente: Pode ser Pessoa Física (PF) ou Pessoa Jurídica (PJ), mas nunca ambos ao mesmo tempo.
Conta: Associada a um cliente. Centraliza informações como número e agência.
Forma de Pagamento: Uma conta pode ter várias formas de pagamento cadastradas.
Entrega: Cada pedido possui uma entrega com status e código de rastreio.
Pedido: Relaciona conta, pagamento e entrega.

Relacionamentos:
Um cliente tem exatamente uma conta.
Uma conta pode ter vários pedidos.
Cada pedido possui uma entrega.
Cada conta pode ter várias formas de pagamento.
