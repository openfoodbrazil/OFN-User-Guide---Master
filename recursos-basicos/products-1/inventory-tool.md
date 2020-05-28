# A ferramenta 'Inventário'

## Introdução 

O _Inventário_ permite que as iniciativas tenham mais controle e flexibilidade na gestão dos produtos, caso necessário. Este recurso será de interesse para as Centrais e seus gestores.

Ao utilizar o_Inventário_ a Central A pode modificar os preços e a quantidade em estoque de produtos que ela tem permissão para comercializar, sem modificar os valores originais. Logo, se tanto a Central A quanto a Central B estiverem comercializando os mesmos produtos, ao usar o _Inventário,_ a Central A pode alterar preços e outros detalhes fundamentais destes produtos sem impactar a Central B.

## Configuração do Inventário 

Para acessar o _Inventário,_ clique em _Iniciativa \(_no menu horizontal azul_\)_ e então _Configurações._ No menu à esquerda, selecione _'Configurações do Inventário'._

![](../../.gitbook/assets/inventory-settings.png)

Nesta tela você tem duas opções:

* **Todos os produtos dos meus fornecedores podem ser disponibilizados na minha loja virtual \(recomendado\):**   Os produtos do seu fornecedor podem ser disponibilizados na sua loja virtual _sem que antes seja preciso adicioná-los ao seu Inventário_. Quando você for criar um novo ciclo de pedidos, todos os produtos dos seus fornecedores estarão disponíveis na lista. Esta é a opção padrão e é recomendada para lojas ou Centrais que não desejam modificar o preço ou nível de estoque dos produtos vendidos. 

{% hint style="warning" %}
ATENÇÃO - se você selecionar esta opção padrão mas ao mesmo tempo adicionar produtos ao seu _Inventário_, modificando preços e níveis de estoque, então as informações modificadas serão mostradas na sua loja ao invés das originais. 
{% endhint %}

* **Somente produtos que eu adicionar ao meu Inventário podem ser disponibilizados na minha loja virtual:**



  Somente os produtos previamente adicionados ao 'Inventário' estarão disponíveis para serem selecionados ao criar um novo ciclo de pedidos. 

## Navegando pelo seu _Inventário_

Clique no menu _Produtos_ no menu horizontal azul do Painel de Controle, e em seguida clique em '_Inventário',_ no submenu verde. Se você gerencia múltiplas iniciativas, selecione aquela para a qual você quer editar o _Inventário._

![](../../.gitbook/assets/inventory1.jpg)

Se os fornecedores da iniciativa selecionada tiverem disponibilizado novos produtos desde a sua última visita, você verá a seguinte mensagem:

![](../../.gitbook/assets/new-products-alert.png)

Até que você tenha adicionado estes produtos ao _Inventário,_ eles permanecerão na categoria 'Novos Produtos' e não estarão disponíveis ao criar um novo ciclo de pedidos. Ao clicar em '**Avaliar Agora'** você será redirecionado para a lista de novos produtos.

## Avaliando novos produtos

Os novos produtos podem ser **adicionados** à lista do seu _Inventário_ ou **escondidos.**  Se há algum produto na lista do qual você queira modificar os detalhes, voce precisará adicioná-lo à lista do seu _Inventário._ Se houver algum produto que você nunca irá vender na sua loja, ao menos em um futuro breve, você pode optar por escondê-lo \(veja abaixo na seção _**Produtos Escondidos**\)._

![](../../.gitbook/assets/new-products.png)

{% hint style="info" %}
Lembre-se: se nas **Configurações de Inventário** você selecionar a opção '_somente produtos que eu adicionar ao meu Inventário podem ser disponibilizados na minha loja virtual' ,_ qualquer produto que você deixar na categoria _Novo Produto_ será automaticamente escondido. Se, ao invés disso, a opção selecionada for **todos os produtos dos meus fornecedores podem ser disponibilizados,'** então os produtos  da  lista de N_ovos Produtos_ também estarão disponíveis no seu ciclo de pedidos.
{% endhint %}

## Gerenciando os produtos do seu inventário

Na lista de produtos do seu inventário você pode modificar detalhes de um produto como quantidade disponível no estoque e esconder produtos. 

![](../../.gitbook/assets/viewing-inventory-settings.png)

No botão 'colunas', à direita da tabela, você pode escolher quais informações você gostaria de ver e modificar.

![](../../.gitbook/assets/columns-1.png)

### Modificar SKU, preços e níveis de estoque para produtos da sua loja virtual 

Quaisquer mudanças que você fizer aqui serão visíveis na sua loja virtual, isto é, elas vão sobrepor as informações originalmente configuradas pelo fornecedor. Você pode modificar  os seguintes campos:



* **SKU** – se você quiser utilizar um SKU \(Stock Keeping Unit ou Unidade de Manutenção de Estoque\) alternativo, você pode inserir o novo código aqui.
* **Price** – Você pode informar o novo preço que o produto vai ter na sua loja. You can set a different price to show in your shop. Lembre-se que a unidade de medida do produto permanecerá a mesma, isto é, se o produto for originalmente precificado por kg, você deverá continuar fornecendo um preço por kg e não um preço fixo por unidade, por exemplo. 
* **Em Estoque** – se o seu estoque deste produto é diferente do estoque oferecido pelo fornecedor, você pode indicá-lo aqui. Uma vez que o nível de estoque chegar a zero, seus produtos não serão mais visíveis na loja. 
* **Ilimitado?** – Você pode preferir herdar os níveis de estoque fornecidos pelo produtor \(neste caso o número na coluna 'em estoque' permanecerá cinza\), ou selecionar sim'  para ter um estoque infinito \(de forma que o produto estará sempre disponível quando for adicionado a um ciclo de pedidos\), ou selecionar 'não' para definir seu próprio estoque \(neste caso o número da coluna 'em estoque' estará sobre fundo branco\). 

![](../../.gitbook/assets/inventorystock.jpg)

Para saber mais sobre as opções 'em estoque' e 'ilimitado' clique [aqui](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M7Xcp8ywgpUeWeluDdf/recursos-basicos/products-1/products#adding-products/@drafts). 

{% hint style="warning" %}
Não é possível alterar o nome, descrição ou imagem do produto.
{% endhint %}

### Ativar Restauração de Estoque?

A coluna **ativar restauração de estoque** permite que o valor da coluna 'Em Estoque' seja restaurado para um valor padrão - no início de cada ciclo de pedidos, por exemplo. A caixa de seleção permite que você selecione os itens cujo estoque você queira restaurar, a qualquer momento. O valor padrão é o número indicado no espaço ao lado da caixa de seleção.

Para restaurar o valor de estoque para estes produtos, clique em 'Ações' no canto superior esquerdo da tabela e então em 'Restaurar os Níveis de Estoque para os Padrões'. Somente os produtos que tiverem a caixa de 'Ativar Restauração de Estoque' marcada serão afetadas por essa ação.

![](../../.gitbook/assets/inventorystockreset.jpg)

> In this example the default stock level of baked beans is 5. There are currently 2 left in stock. If the user, at the beginning of an order cycle wishes to reset to 5 then they must click on 'Reset stock levels to defaults' under 'Actions'

{% hint style="info" %}
Este é um recurso útil para as Centrais que recebam carregamentos periódicos de produtos.
{% endhint %}

### _Herdar?_

Se você não tiver modificado nenhuma informação na tabela do _Inventário_ para um produto, a caixa de seleção _Herdar?_ será, por padrão, automaticamente selecionada. Isto significa que os dados originais do produto e visíveis em cinza serão os dados mostrados na sua loja virtual.

![](../../.gitbook/assets/inventoryinherit.jpg)

Ao modificar um ou mais dados, esta caixa de selecão será automaticamente desmarcada. Para restaurar os dados \(preço, estoque, SKU, etc\) para os dados originais, você pode marcar novamente esta caixa a qualquer momento. 

### Esconder

Como na lista de **Novos Produtos,** você também pode esconder produtos do seu ****_Inventário._ Clicando no botão _Esconder,_ o produto será movido para os _Produtos Escondidos. Se você tiver configurado seu inventário para_ **somente produtos que eu adicionar ao meu** _**Inventário**_ **podem ser disponibilizados na minha loja virtual** \(veja [aqui](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M7Xcp8ywgpUeWeluDdf/recursos-basicos/products-1/inventory-tool#profile-settings-for-the-inventory/@drafts)\) então o produto que você acabou de esconder não estará mais disponível para ser incluído nos seus ciclos de pedido. 

## Produtos Escondidos

Esta é uma lista de todos os produtos que você optou por escconder:

![](../../.gitbook/assets/hidden-products.png)

Ao visualizar sua lista de produtos escondidos, você pode optar por torná-los visíveis mais uma vez ao clicar no botão '**Adicionar**', à direita da tabela.

![](../../.gitbook/assets/inventoryhidden.jpg)

## Inventário e Ciclos de Pedido

Ao configurar os ciclos de pedido você pode escolher entre selecionar todos oso produtos disponíveis ou somente aqueles que estão no _Inventário_ da sua loja.

Isto pode ser feito acessando 'Configurações Avançadas' \(no canto superior dirieto da página do ciclo de pedidos\):

![](../../.gitbook/assets/advanced-oc-settings.png)

Esta opção tem o mesmo efeito que mudar as [configurações do seu inventário](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M7Xcp8ywgpUeWeluDdf/recursos-basicos/products-1/inventory-tool#profile-settings-for-the-inventory/@drafts), mas ela se aplica apenas ao ciclo de pedidos em questão.

{% hint style="danger" %}
Após fazer quaisquer mudanças, lembre-se sempre de clicar em 'Atualizar' ou 'Salvar' antes de prosseguir! 
{% endhint %}

