Desafio Refinando um Projeto Conceitual de Banco de Dados – E-COMMERCE
Instrutora: Juliana Mascarenhas

Objetivo do diagrama:
O sistema gerencia uma plataforma online de vendas onde produtos de diferentes vendedores e terceiros são oferecidos.
Cada produto está associado a um fornecedor e compõe um ou mais pedidos. 
O sistema permite o cadastro de clientes, a criação de pedidos e o gerenciamento de informações relacionadas à entrega, estoque e devoluções.

![E-COMMERCE](https://github.com/user-attachments/assets/3c3a57ae-80ab-4608-81cf-07b5f581f176)

Narrativas:

Cliente:
O cliente pode se cadastrar utilizando CPF ou CNPJ.
O valor do frete é calculado com base no endereço cadastrado.
Um cliente pode realizar múltiplos pedidos e tem direito a um período de devolução dos produtos.

Produto:
Os produtos são vendidos exclusivamente pela plataforma.
Cada produto está vinculado a um fornecedor e pode ser incluído em mais de um pedido.

Pedido:
Criados pelos clientes, os pedidos contêm informações de compra, endereço de entrega e status.
Um pedido pode conter um ou mais produtos e pode ser cancelado.

Fornecedor & Estoque:
Cada produto é associado a um fornecedor.
O gerenciamento de estoque é fundamental para o controle da disponibilidade dos produtos na plataforma.





