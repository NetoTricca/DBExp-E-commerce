![image](https://user-images.githubusercontent.com/68438464/190282356-7ae20b6b-13fb-4145-8b01-06e84428d66c.png)


# DBExp-E-commerce
Database Experience - DIO

## Projeto de BD de E-commerce com MySQL Workbench

### Projeto de E-commerce - Breve narrativa

* PRODUTOS 
-   vendidos por uma única plataforma on-line, podendo ter vendedores distintos
-   cada produto possui um fornecedor
-   um ou mais produtos podem compor um pedido

* CLIENTE
-   podem ser cadastrado com CPF ou CNPJ
-   o Endereço determinará o valor do frete
-   pode comprar mais de um pedido, e tem carência para devolução do produto

* PEDIDO
-   criados pelos clientes, com informações de compra, endereço e status de entrega
-   um ou mais produtos podem compor um pedido
-   pode ser cancelado

* FORNECEDOR
-   pode fornecer diversos produtos

* ESTOQUE
-   produtos estocados em locais estratégicos para melhor logística

### Objetivo:
- Refine o modelo acrescentando:
- Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
- Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
- Entrega – Possui status e código de rastreio;
