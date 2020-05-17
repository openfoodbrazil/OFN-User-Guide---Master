# Precificando carnes e outros produtos 'inteiros' de peso variável

Chamamos de produtos 'irregulares' os produtos vendidos de acordo com o peso / volume mas cuja quantidade exata é desconhecida até o momento da distribuição do pedido. Exemplos: grandes legumes, fatias de queijo, fatias de carne. 

Há uma série de recursos disponíveis na plataforma que ajudar a lida com esse tipo de produto.

## Opção 01: Definir um peso / preço médio e reembolsar.  

Você pode cobrar pela média de preço do produto e, caso o preço final seja maior, você pode cobrar um valor extra do comprador. Se for menor, você pode reembolsá-lo.

Quando você souber o verdadeiro peso do produto vendido \(ou seja, quando estiver preparando o pedido para ser enviado ou coletado pelo comprador\), acesse o menu ´Encomendas´,  em seguida ´Gestão de Pedidos por Atacado´ e adicione a coluna Peso / Volume à tabela.

![](../../.gitbook/assets/bom1.jpg)

Você pode então mudar o peso referente a cada produto, por cada compra. O preço então será recalculado automaticamente de acordo com a nova quantidade inserida.

{% hint style="info" %}
Não se esqueça de reeviar o email de confirmação de pedido para os seu cliente, para notificá-lo da diferença de valor cobrado.
{% endhint %}

## Opção 02: Mostrar faixa de preço

A mesma lógica da opção 01, mas ao invés de definir um preço médio, indica-se uma faixa de preço. Esta solução tem a vantagem de comunicar claramente ao comprador que o preço final deve variar. 

[Variantes](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M5iVg4Hr748l7-hYgcH/recursos-basicos/products-1/product-variants/@merged) também podem ser utilizadas para criar diferentes faixas de preço.

> **Exemplo 1** \(produto único e uma variante\):  
> Produto = Abóbora \(entre 1 e 3 kg, com preço variando de acordo com o peso, R$ 5,00 / kg\)

> **Exemplo 2** \(duas variantes para um produto\):  
> Produto = Abóbora \(R$ 5,00 / kg\)  
> Variante 1 = Abóbora pequena \(entre 1 e 2 kg, preço final varia com o peso\)  
> Variant 2 = Abóbora grande \(entre 2 e 3 kg, preço final varia de acordo com o peso\)

## Opção 3 : Criar variantes com preços fixos.

Uma opção um pouco mais simples do que opção 2 é criar variantes para seus produtos com base nas faixas de peso, mas cobrar um **valor fixo** para todos as unidades que estejam dentro daquela determinada faixa. Por exemplo, se a abóbora custa R$5,00 / kg, então você poderia listar as variantes com os seguintes preços fixos: 

* Pequena \(500 g - 1 kg\)  R$ 3,50
* Média \(1 kg - 1,5 kg\) R$ 6,50
* Grande \(1,5 kg - 2,0 kg\) R$ 8,50
* Muito Grande \(2,0 kg - 2,5 kg\) R$ 11,50

## Opção 4: Criar variantes com pesos específicos

Se você souber, antecipadamente, o peso de todas as suas abóboras, por exemplo, você pode usar as variantes para mostrar o preço exato de cada unidade a ser vendida:

![](../../.gitbook/assets/bom2.jpg)

## Editando Pedidos

Pode ser difícil para produtores de carne saberem antecipadamente o peso de cada peça. Isto não é um problema já que os pedidos podem ser editados \(adicionando, modificando ou deletando produtos\) caso necessário. Para mais informações, veja [Pedidos](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M5iVg4Hr748l7-hYgcH/recursos-basicos/orders/@merged).

## Como reembolsar compradores ou cobrar um valor extra?

Se o comprador for pagar pelos produtos no momento da entrega ou coleta, então você terá tempo para modificar o pedido de acordo com o peso real das mercadorias e os produtos que de fato serão entregues. Nesse caso, não é preciso reembolsar ou enviar uma nova cobrança ao comprador. 

**Caso o** **pedido seja pago online, antes da entrega**, então você precisará reembolsar ou enviar uma cobrança extra ao comprador. [Clique aqui para saber como](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M5iVg4Hr748l7-hYgcH/recursos-basicos/orders/refund-payments/@merged). 

{% hint style="danger" %}
Uma alternativa é configurar um sistema de pagamento online para temporariamente

An alternative is to use an online payment system to temporarily store the amount "pending" until the order has been validated.

_This feature is not yet implemented in Open Food Network. We are also working on the automated implementation of "credits" allowing a hub to reimburse in the form of a credit note which could be used by the customer as part payment for their next order._
{% endhint %}

## Inform the buyer about your pricing policy

You can notify your customers about your pricing policies for variable weight items \(such as meat\) in the [message box](../enterprise-profile/enterprise-settings.md#shop-preferences) displayed at the top of your shop front. This is found in the Enterprise Settings -&gt; Shop Preferences.

It might be useful to also add a reminder of these pricing policies in the description box of [Payment Methods](../shopfront/payment-methods.md). For example, you may wish to add : "Remember that the final price may vary by 10% depending on weight if you have purchased non-divisible items such as meat or large vegetables.".

