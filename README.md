Projeto de E-commerce
Módulo 2 - Modelagem de Banco de Dados
Bootcamp Database Experience - Dio.me


Desafio1: Replique e melhore! 

Narrativa - Produto
• Os produtos são vendidos por uma única plataforma online.
Contudo, estes podem ter vendedores distintos (terceiros)
• Cada produto possui um fornecedor
• Um ou mais produtos podem compor um pedido

Narrativa - Cliente
• O cliente pode se cadastrar no site com seu CPF ou CNPJ
• O Endereço do cliente irá determinar o valor do frete
• Um cliente pode comprar mais de um pedido. Este tem um período
de carência para devolução do produto

Narrativa – Pedido
• O pedidos são criados por clientes e possueminformações de
compra, endereço e status da entrega
• Um produto ou mais compoem o pedido
• O pedido pode ser cancelado

Narrativa – Fornecedor & estoque
• O Fornecedor poderá disponibilizar seu produto no site
• No estoque teremos a quaintidade de produtos e o local 
do armazenamento
• O produto selecionado terá sua pesquisa no estoque e 
após no Fornecedor

Refinando
• Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não
pode ter as duas informações
• Pagamento – Pode ter cadastradomais de uma forma de
pagamento
• Entrega – Possui status e código de rastreio