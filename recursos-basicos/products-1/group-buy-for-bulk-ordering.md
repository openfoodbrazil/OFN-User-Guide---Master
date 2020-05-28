# Compra em Grupo - para compras em atacado

A função **Compra em Grupo** foi feita para iniciativas que compram alguns dos seus produtos no atacado e distribuem em quantidades menores \(por exemplo, é feita uma compra de 25kg de arroz, que em seguida é redistribuido aos consumidores, por kg. 

A compra por atacado é uma prática comum de grupos de compra, que dessa forma podem se beneficiar de preços mais acessíveis do que comprando individualmente volumes menores.

Para essas iniciativas, a decisão de comprar uma grande quantidade de algum produto depende da quantidade de pessoas disponíveis a participar da partilha e assim conseguir um bom desconto. A função do grupo de compras torna esse processo mais fácil de administrar.

Quando um produto for disponibilizado para uma compra em grupo, ele será visualizado de maneira diferente na loja virtual \(ver abaixo\), com dois campos a serem preenchidos, um para quantidade mínima \(min\) e outro para quantidade máxima \(max\):

![](../../.gitbook/assets/group-buy%20%281%29.png)

Os consumidores deverão indicar:

* A quantidade **mínima** desejada: esta é a quantidade que o consumidor idealmente vai querer. 
* A quantidade **máxima:** esta é a maior quantidade que o consumidor está disposto a comprar/receber. 

{% hint style="info" %}
Esta é uma maneira do consumidor dizer: '_você tem minha permissão para aumentar o meu pedido até este ponto para completarmos a quantidade mínima necessária para efetivar a compra_. 
{% endhint %}

Em [Gestão de Pedidos em Atacado](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M7y4zuNbeCZJmohSlf3/recursos-basicos/orders/view-orders#bulk-order-management/@drafts) você pode visualizar todos os pedidos feitos, em suas quantidades mínima e máxima. Você pode então aumentar a quantidade do pedido de cada consumidor, até o valor máximo definido por cada um, para chegar ao mínimo necessário para fechar o pedido por atacado. Se mesmo aumentando os valores dos pedidos individuais não for possível alcançar o valor mínimo necessário, você pode deletar todos os pedidos feitos para este produto.

## Ativando a Compra em Grupo para um Produto.

No painel de controle, acesse **'Produtos'** no menu horizontal azul. Para **editar** um produto, selecione o ícone do lápis e papel à direita do produto em questão:

![](../../.gitbook/assets/productedit.jpg)

Então selecione a opção **Compra em Grupo** no menu à direita:.

![](../../.gitbook/assets/groupbuy.jpg)

Abaixo de **Compra em Grupo?**, selecione '**SIM**', para ativar a compra em grupo para este produto.

A **Quantidade Mínima para Compra em Atacado** é o limite mínimo, ou o volume de compra que o grupo precisa alcançar para efetivar o pedido.

{% hint style="warning" %}
A **unidade de medida** para a Compra em Atacado depende da unidade de medida selecionada para venda do produto na loja virtual.

Se o produto for vendido por:

**Peso:** é medido em g \(gramas\). Ex: se a quantidade mínima for de 5kg, então insira 5000 neste campo.

**Volume:** é medido em litros. Ex: se a quantidade mínima for de meio litro, então insira 0.5 neste campo. 

**Itens**: ex: se a quantidade mínima para venda de maços de hortelã forem 100 maços, então insira 100 neste campo. 
{% endhint %}

## Ajustando pedidos para completar a compra.

Em Pedidos &gt; [Gestão de Pedidos em Atacado](%20https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M7y4zuNbeCZJmohSlf3/recursos-basicos/orders/view-orders#bulk-order-management/@drafts) você pode ver e editar os pedidos dos clientes para produtos de Compra em Grupo para fazer com que a soma dos pedidos de todos os consumidores alcance a quantidade mínima necessária para completar a compra.

1. Selecione o ciclo de pedidos ou período específico. 
2. Faça uma busca pelo produto. 
3. Certifique-se de que a coluna 'Max' esteja visível, de modo que você possa ver o limite máximo que cada consumidor está disposto a comprar.
4. Em seguida, clique na informação \('test fish: Fish One' in the example below\) que aparece na coluna **Produto: Unidade** para mostrar os totais dos pedidos para o produto em questão. 
5. Usando a informação da coluna **Max**, você pode aumentar a quantidade do pedido para chegar ao volume necessário para completar a compra.
6. Clique em atualizar para salvar as mudanças nos pedidos dos consumidores. 

![](../../.gitbook/assets/bulkorder2.jpg)

**Pedidos / Limite Mínimo \(Atual\):** mostra o resultado da divisão entre o volume total de pedidos e a quantidade mínima para a compra em atacado. Se o resultado for maior do que 1, significa que o volume dos atuais pedidos é maior do que o mínimo necessário para completar a compra. Se o resultado for menor do que 1, então o volume atuais pedidos não é suficiente para completar a compra. À medida que você aumentar os volumes dos pedidos de cada comprador, este número irá aumentar. 

**Pedidos / Limite Mínimo \(Max\):** mostra o resultado da divisão entre o volume máximo do total de pedidos e a quantidade mínima para a compra em atacado. Se o resultado for maior do que 1, significa que a soma dos volumes máximos de cada pedido é maior do que o mínimo necessário para completar a compra. Se o resultado for menor do que 1, então mesmo a soma dos volumes máximos de cada pedido não é suficiente para alcançar o limite mínimo.

