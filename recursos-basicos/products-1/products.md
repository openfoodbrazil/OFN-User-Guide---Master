# Adicionar produtos

Você pode adicionar produtos ao seu catálogo um a um \(como detalhado abaixo\) ou por [importação em massa](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/products-1/product-and-inventory-import/@drafts), se você tiver todas as informações organizadas em um arquivo .csv.

## Adicionando produtos

Uma vez feito o login no Painel de Controle do Administrador, acesse a página "**Produtos**" no menu azul horizontal, e então clique em **+ Novo Produto.**

![](../../.gitbook/assets/add-new-product.png)

Você será levado para a página 'Novo Produto'.

![](../../.gitbook/assets/new-product2.png)

**Fornecedor**

Selecione a iniciative que produz e fornece o produto que você vai inserir no catálogo.

{% hint style="info" %}
Se você for um produtor, então este pode ser você. Se você for uma Central, lembre-se que você só será capaz de adicionar produtos de produtores cujo perfil você mesmo criou, ou se você tiver recebido permissão para administrar os produtos do perfil do produtor. Para mais informações, veja [aqui](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/enterprise-profile/create-or-connect-with-your-supplying-producers/@drafts).
{% endhint %}



**Nome do Produto:** este é o nome que vai identificar o produto na loja virtual. 

**Unidades:** Escolha em que tipo de unidade o produto é vendido. Exemplos: **g, kg, L** ou **molho, garrafa, saco, etc...**

Se você selecionar 'g' e inserir 1000, o produto será visualizado como 1 kg pelo consumidor. Leve em consideração que algumas unidades de medida vão impactar na operação de certas [taxas de iniciativa.](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/shopfront/enterprise-fees/@drafts)

Por exemplo, uma [taxa fixa por peso](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/shopfront/enterprise-fees#fee-calculators/@drafts) só pode ser aplicada a produtos com unidades em quilos \(kg\). Nesse caso, você pode colocar números decimais, como 0.2 kg, e o produto será mostrado na loja como 200 g mas será registrado nos relatórios em kg quando os preços forem calculados. 

**Quantidade:** Insira a quantidade em que esse produto é vendido. Por exemplo, se for vendido por '100 g' então digite 100 aqui e escolha 'g' nas unidades de medida; ou se for vendido em molhos, digite 1 aqui e nas unidades de medida escolha 'itens'.

**Mostrar como:** Este campo te mostra como será visualizada a quantidade conjuntamente com a unidade de medida escolhida, após esse campos terem sido preenchidos \(exemplo: unidade de medida = kg, quantidade = 2, mostrar como = 2 kg\). 

{% hint style="info" %}
Atenção: Se você selecionar **'itens'** como sua unidade de medida; o campo **mostrar como** mudará para o    **nome do item**. Adicione o nome correspondente \(exemplo: molho, garrafa, saco, etc..\) 
{% endhint %}

**Categoria do produto:** Selecione a categoria mais apropriada para este produto. Indicar uma categoria de produto facilita para o consumidor encontrar os produtos que ele quer comprar. Os consumidores podem filtrar sua lista de produtos por categoria na sua loja virtual. 

**Preço:** Insira o valor para a quantidade determinada acima. Atenção, este é o preço base cobrado pelo produtor e a quantidade que ele vai receber por cada compra. Taxas \(de serviço, transporte, etc.\) e margem de lucro são adicionadas nas [Taxas da Iniciativa](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/shopfront/enterprise-fees/@drafts), [Taxas de Entrega](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/shopfront/shipping-methods#fee-calculators/@drafts) e [Métodos de Pagamento](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/shopfront/payment-methods#fee-calculators/@drafts).

{% hint style="info" %}
Se você selecionar que o produto carrega um imposto, então o preço que você colocar aqui tem **impostos inclusos.** Se você selecionar que este produto não inclui impostos, então o preço definido será o preço livre de impostos.
{% endhint %}

**Disponível:** Informe a quantidade do produto que você tem disponível em estoque e pronto para a venda. Use este campo se você quiser rastrear seu nível de estoque. A medida que os consumidores fizerem os pedidos, o nível de estoque vai reduzir automaticamente, e quando chegar a zero, o produto não será mais visível na sua loja virtual. Se você não quiser que isso aconteça, clique em 'sob encomenda'.

**Sob demanda:** Selecionando esta opção, você indica que o produto está sempre disponível no estoque. Isto faz com que o software pare de rastrear o nível do estoque no catálogo, e o mostre sempre como disponível na loja. 

**Imagem:** Faça o upload de uma foto para este produto.

{% hint style="success" %}
Recomendamos o  uso de fotos de boa qualidade, no formato quadrado \(1:1\), e preferívelmente uma boa foto real dos produtos ao invés de uma foto genérica retirada da internet. Se você usar uma foto da internet, certifique-se de que seja de licensa livre.

If you use an image of the web, check that it is free of rights.
{% endhint %}

**Categoria de Imposto:** esta opção não se aplica à Open Food Brasil, já que os impostos são declarados no informe de imposto de renda, e não na fonte, como em outros países.

**Descrição do Produto:** Conte a seus consumidores um pouco mais sobre este produto. Talvez você queria contar alguma curiosidade sobre como ele foi produzido. Inclua links para outras páginas sobre qualquer tipo de certificação que o produto possa ter. 

{% hint style="info" %}
Não se esqueça de clicar no botão 'criar' ou 'criar e adicionar novo' no pé da página, quando tiver preechido todos os campos obrigatórios \(indicados pelo asterisco em vermelho\). 
{% endhint %}

Um pequena demonstração dos passos detalhados acima:

![](../../.gitbook/assets/productsadd.gif)

Quando você tiver terminado de criar um produto, você será redirecionado à página 'produtos', onde estaram listados todos os produtos que você criou.



![](../../.gitbook/assets/productspage.jpg)

## Criando produtos parecidos ou 'variantes' do produto. 

Se você está criando um produto que vem em diferentes opções \(por exemplo, diferentes tamanhos ou sabores, que podem ter um preço diferente ou não\), o melhor a se fazer é criar uma variante deste produto, ao invés de criar múltiplos produtos separados. Este recurso será melhor detalhada na [página seguinte](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/products-1/product-variants).

{% hint style="success" %}
Variantes são úteis se, por exemplo, você vende limões a granel e em pacotes de 5 limões. Ao invés de listar as duas opções como produtos separados, as duas opções pode estar disponíveis para o mesmo produto.
{% endhint %}

Se voce quiser criar um produto parecido, então você pode duplicar produtos clicando no ícone 'duplicar' à direita do item em questão \(caixa vermelha\). Em seguida, selecionando o ícone 'editar' \(caixa verde\) o produto copiado pode ser editado para inserir alterações.

![](../../.gitbook/assets/productspagecopy.jpg)

## Refinando atributos de produtos. 

Na OFB você pode adicionar **propriedades** ou **selos** para seus produtos. Isto permite aos consumidores que encontrem produtos buscando por critérios específicos \(ex.: agroecológicos, orgânicos certificados\)  e também destaca as qualidades específicas que seu cultivo ou fabricação pode ter. Saiba mais [aqui.](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/products-1/product-properties)

Para dicas de como administrar vendas de **produtos 'irregulares'** como carne ou grandes legumes vendidos por unidade mas precificados de acordo com o peso, por favor leia [aqui. ](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/products-1/pricing-irregular-items-kg)

Nossa ferramenta para **Grupo de Compras** permite que você administre e organize vendos de produtos em atacado. Saiba mais [aqui.](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M4aA1P9PN2d138rOjAt/recursos-basicos/products-1/group-buy-for-bulk-ordering)

