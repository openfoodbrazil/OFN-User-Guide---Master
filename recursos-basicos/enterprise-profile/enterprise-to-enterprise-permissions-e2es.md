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

Você deverá entrar em contato pessoalmente com seu fornecedor. As informações para contato \(telefone, email, etc.\) estão localizadas na página do perfil dele.

Se o seu objetivo for apenas **vender os  produtos** dele, peça a permissão para **adicionar ao ciclo de pedidos** e permissão para **adicionar ao inventário.** 

Se o fornecedor quiser que você, como uma Central, o auxilie na gestão do perfil dele, ele pode te conceder todas as quatro permissões. Caso isso ocorra, então você será capaz de editar detalhes do perfil e gerenciar os produtos do fornecedor. 

**Minha Central funciona como um grupo de compras. Quais permissões dos produtores a minha iniciativa precisa?**

Neste exemplo, uma Central gerencia \(coordena\) um ciclo de pedidos para uma outra iniciativa, através da qual os consumidores fazem suas compras.

{% hint style="warning" %}
Neste exemplo, uma Central gerencia \(coordena\) um ciclo de pedidos para uma outra iniciativa, através da qual os consumidores fazem suas compras.

_Se a Central A gerencia um ciclo de pedidos para um grupo de compras \(Central B\), o ciclo de pedidos será visualizado na loja virtual da Central B._
{% endhint %}

O Grupo de Compras \(Central B\) vai precisar conceder ao coordernador do ciclo de pedidos \(Central A\) a permissão para adicionar produtos a um ciclo de pedidos \(e preferívelmente permissão para adicionar produtos ao inventário. 

Produtores que fornecem a Central A com produtos que também são vendidos pelo Grupo de Compras \(Central B\) devem conceder permissão para as ambas centrais \(A e B\) para adicionar produtos ao ciclo de pedidos \(e inventário, preferivelmente\). 

## Do ponto de vista do Produtor

Quando um produtor quiser começar a vender seus produtos através de outras iniciativas \(centrais ou grupos de compras\), ele deve estabelecer as permissões apropriadas. Existem diferentes níveis de permissões que um produtore pode conceder, dependendo de quanto poder ele queira dar à uma determinada Central para gerenciar seus produtos e pefil \(veja [acima](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4LUypJW72tjarDjRcK/recursos-basicos/enterprise-profile/enterprise-to-enterprise-permissions-e2es#the-four-permissions)\).

Alguns exemplos comuns:

> **Sou um produtor e gostaria que uma Central local disponibilizasse e vendesse os meus produtos.**

**Essencial:** para que a central adicione seus produtos à loja virtual dela, você precisará conceder-lhe uma 'permissão para adicionar produtos a um ciclo de pedidos'.

**Opcional:** Talvez você também queria conceder à Central permissão para gerenciar seus produtos, editar seu perfil ou adicionar produtos ao inventário dela.

> **Forneço produtos para uma Central que vende através de grupos de compras.**

Para que seus produtos sejam distribuídos pelos grupos de compra, você precisará conceder ao menos a 'permissão para adicionar produtos a um ciclo de pedidos' para a iniciativa do grupo de compras e também para a Central para a qual você fornece diretamente. 

**Sou uma Loja de Produtor que, além vender produtos na minha própria loja virtual, também fornece produtos para uma Central local. A Central gostaria de gerenciar os níveis de estoque e preços dos meus produtos. Eu** _**também**_ **quero gerenciar os níveis de estoque e preços dos meus produtos.**

Esta situação pode ser resolvida concedendo à Central em questão permissão para adicionar produtos ao inventário, além da permissão para adicionar ao ciclo de pedidos. Isso permite que a Central disponibilize seus produtos na loja virtual dela, mas com os próprios preços e níveis de estoque. Quando você adicionar produtos à sua própria loja, eles continuaram refletindo os preços e níveis de estoque que você configurou. 

