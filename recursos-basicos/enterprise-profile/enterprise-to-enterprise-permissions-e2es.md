# Permissões de Iniciativa

Na OFB, as Permissões de Iniciativa são regras que governam as relações de comércio entre os perfis de fornecedores e de distribuidores. Estas regras devem ser configuradas antes que um produtor possa se tornar fornecedor de outras iniciativas \(Centrais\), ou vice versa. Uma permissão é concedida por uma inciativa a outra iniciativa. Ela pode dar direito de acesso / modificação de produtos e perfil. A seguir serão detalhados os diferentes tipos de permissão e como concedê-los.

Para acessar as permissões da sua iniciativa:

![](../../.gitbook/assets/permissions.gif)

Ao final, vamos explorar este tópico do ponto de vista de:

* [uma Central](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/enterprise-profile/enterprise-to-enterprise-permissions-e2es#hub-perspective/@drafts) \(o distribuidor\)
* [um Perfil Simples ou Loja](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/enterprise-profile/enterprise-to-enterprise-permissions-e2es#producers-perspective/@drafts) \(o fornecedor\)

## Os 4 tipos de permissão

Há 4 tipos de permissão diferentes. Eles podem ser combinados entre si para que um perfil conceda a determinadas iniciativas mais ou menos direitos de acesso.

![](../../.gitbook/assets/e2emenu2.jpg)

**Permissão para adicionar produtos a um ciclo de pedidos:** o fornecedor \(produtor\) concede ao distribuidor \(uma Central\) o direito de adicionar produtos aos ciclos de pedidos dele \(distribuidor\). Desta forma, os produtos do fornecedor podem ser vendidos na loja virtual do distribuidor. 

**Permissão para gerenciar produtos:** o fornecedor \(produtor\) concede a outra iniciativa \(normalmente uma Central\) o direito de criar, deletar e editar produtos diretamente no catálogo do fornecedor.

{% hint style="danger" %}
Isto pode impactar todas as Centrais para as quais o produtor em questão fornece mercadorias. 
{% endhint %}

> _Por exemplo, se o Produtor Celso fornece batatas para a Central A e para a Central B, e permite que a Central A gerencie seus produtos, então se a Central A mudar o preço das batatas, esta mudança vai refletir no preço das lojas virtuais tanto da Central A quanto da Central B._

**Permissão para editar perfil:** uma iniciativa permite a outra que modifique suas informações no seu [Perfil de Iniciativa ](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/enterprise-profile/@drafts)\(informações para contato, endereço, descrição ...\).

**Permissão para adicionar produtos ao inventário:** o fornecedor \(produtor\) permite que o distribuidor \(Central\) adicione seus produtos ao catálogo da loja virtual \(ou[ Inventário](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/products-1/inventory-tool/@drafts)\) da Central**.** 

{% hint style="info" %}
Se um você fornece mercadorias a mais de uma Central, então é recomendado que você conceda a permissão para adicionar produtos ao inventário à todas elas, assim cada uma pode gerenciar o preço e o estoque independentemente.
{% endhint %}

## Conceder e Gerenciar Permissões 

Para modificar, adicionar ou deletar permissões, acesse o Painel de Controle, em seguida clique em 'Iniciativas' no menu azul e então em 'Permissões' no sub-menu verde. 

![](../../.gitbook/assets/e2emenu.jpg)

Para conceder permissões:

* Selecione a sua iniciativa no menu suspenso da primeira coluna \(você é um produtor que fornece a outras lojas\). 
* Na segunda coluna, selecione o nome da Iniciativa \(Central\) para a qual você quer fornecer seus produtos. 
* Assinale quais tipos de permissão você quer conceder a esse distribuidor. Para conceder todas as permissões, selecione 'Tudo'.
* Clique em 'Criar'. 

Você pode deletar ou modificar essas permissões a qualquer momento.

{% hint style="warning" %}
Apenas usuários definidos como [Gestores](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/enterprise-profile/enterprise-settings#users/@drafts) de uma iniciativa podem mudar as permissões. 
{% endhint %}

Se você necessite que alguma outra iniciativa conceda uma permissão para você, então você precisa entrar em contato com o gestor dessa iniciativa, por email ou telefone.Não é possível fazer isso através da plataforma.

## Permissões Geradas Automaticamente 

Quando um usuário é o principal gestor de muitas iniciativas na plataforma, [as quatro permissões](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/enterprise-profile/enterprise-to-enterprise-permissions-e2es#the-four-permissions/@drafts) são criadas automaticamente entre cada iniciativa. Este não é o caso quando as iniciativas são gerenciadas por diferentes usuários.

## Do ponto de vista de uma Central 

As seguintes situações mostram quais permissões você talvez precise configurar para a sua iniciativa: 

> **Eu** [**criei um Perfil de Produtor para cada um dos meus fornecedores**](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M3n1ACwrn6TUhyGndiU/recursos-basicos/enterprise-profile/create-or-connect-with-your-supplying-producers#supplier-does-not-have-an-ofn-profile/@drafts)**. Quais tipos de permissão eu preciso configurar antes de disponibilizar os seus produtos na minha loja virtual?**

O sistema está configurado de forma que as Centrais que criarem perfis de produtores já terão as permissões necessárias configuradas por padrão, de modo que elas poderão adicionar produtos e vendê-los imediatamente. 

> **Meu fornecedor já tem uma iniciativa registrada na OFB. EU gostaria de adicionar os seus produtos na minha loja virtual.**

Você deverá entrar em contato pessoalmente com seu fornecedor. As informaç

You must contact your supplier in person. Their contact details \(phone number, address and email address\) will be located in their OFN profile.

If you only intend to _**stock their products**_ and don't wish to help them manage the rest of their OFN profile then ask the producer to grant permission _**to add to order cycle**_ and permission _**to add to inventory.**_

If the supplier wishes for you, as a Hub manager, to help them organise their OFN enterprise then they may grant you all four permissions. Should this occur then you will be able to edit their profile and manage their products.

> **My Hub distributes through buying groups. Which permissions will the buying group need with my hub and my producers?**

{% hint style="warning" %}
This is an example of where the hub managing \(co-ordinating\) an order cycle differs from the enterprise from which customers collect their purchases.

_If Hub A manages \(co-ordinates\) an order cycle for a buying group \(Hub B\) then the order cycle will be displayed on Hub B's OFN shopfront._
{% endhint %}

The buying group \(Hub B above\) will need to grant the order cycle co-ordinator \(Hub A above\) permission to add to order cycle \(and ideally permission to add to inventory\).

Producers who supply Hub A with products that are to also be sold by the buying group \(Hub B\) must grant both Hubs A and B permission to add to order cycle \(and ideally permission to add to inventory\).

## Producer's perspective

When a producer wants to start selling their products through other enterprises \(hubs or buying groups\) the must establish the appropriate enterprise-to-enterprise permissions. There are different levels of permission that a producer can grant, depending on how much power they want to give the hub to manage their products and profile \(see [top of page](enterprise-to-enterprise-permissions-e2es.md#the-four-permissions)\).

These examples explore some common scenarios.

> **I am a producer and would like a local OFN hub to stock and sell my products.**

**Essential:** For the hub to add your products to their shopfront, you’ll need to grant them _'permission to add to order cycle'_.

**Optional:** You might also want to give the hub permission to manage your products, to edit your profile or to add to Inventory.

> **A hub that I supply distributes through buying groups.**

In order for your products to be distributed by the buying groups you will have to add a minimum of permission 'to add to order cycle' for the buying group enterprise _as well as_ the hub you supply directly.

> **I am a Producer Shop who supplies a local Hub as well as running my own shopfront. The hub would like to manage the stock levels and prices of my products. I would like to** _**also**_ **manage stock levels and prices of my products.**

This scenario can be solved by granting the hub permission to add to Inventory as well as permission to add to order cycle.

This allows the hub to stock your products in their shop, but to set their own prices and inventory levels. When you stock your own shop with your products, they will continue to reflect the prices and stock levels that you have set.

