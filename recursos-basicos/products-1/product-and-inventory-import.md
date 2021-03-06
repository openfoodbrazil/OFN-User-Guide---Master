---
description: >-
  Esta página explica como produtores e gestores podem importar uma planilha com
  a lista detalhada de produtos.
---

# Importar lista de produtos.

Este recurso permite importar um arquivo .csv para atualizar a lista de produtos e estoque, o que pode ser muito mais rápido e eficiente do que adicionar produtos um por um. 

Há quatro maneiras de usar essa ferramenta:

1. Importar novos [produtos](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M8SSSACq0zWVc_eG_TG/recursos-basicos/products-1/@drafts)
2. Atualizar os detalhes de produtos existentes
3. Importar produtos para o[ Inventário](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M8SSSACq0zWVc_eG_TG/recursos-basicos/products-1/inventory-tool/@drafts) de uma nova loja ou Central.
4. Atualizar produtos do Inventário de uma loja ou Central.

Para todos os casos, o primeiro passo é fazer o download de um _template_ \(arquivo modelo\) de planilha .csv, preencher os campos e depois fazer o _upload_ do arquivo novamente na plataforma,

{% hint style="warning" %}
**Informação importante sobre arquivos CSV:** o Microsoft Excel não abre arquivos .csv diretamente. Se puder, sugerimos que você baixe gratuitamente o programa Libre Office Calc:  
****[https://www.libreoffice.org/download/download/](https://www.libreoffice.org/download/download/)

Com o Libre Office Calc, voce pode abrir e editar arquivos .csv facilmente, e salvar no formato correto UTF-8. Se você não puder usar o Libre Office, você precisará seguir os seguintes passos: 

[https://support.office.com/en-gb/article/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba](https://support.office.com/en-gb/article/import-or-export-text-txt-or-csv-files-5250ac4c-663c-47ce-937b-339e391393ba)
{% endhint %}

{% hint style="danger" %}
Nem todos os detalhes do produto poderão importados e atualizados usando este recurso. No momento, as configurações de [imagens](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M8SSSACq0zWVc_eG_TG/recursos-basicos/products-1/products/@drafts),[ propriedades ](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M8SSSACq0zWVc_eG_TG/recursos-basicos/products-1/product-properties/@drafts)e [Compras em Grupo](https://app.gitbook.com/@ofn-brasil/s/guide-ofn/~/drafts/-M8SSSACq0zWVc_eG_TG/recursos-basicos/products-1/group-buy-for-bulk-ordering/@drafts) precisam ser definidas manualmente para cada produto. Esperamos incluir esses campos em futuras atualizações.
{% endhint %}

## Importar Novos Produtos

Siga estes passos para adicionar novos produtos a um perfil de produtor.

{% hint style="success" %}
You can simultaneously upload new products and update existing products with a single CSV upload. The instructions in this guide are separated for clarity but you can combine new products and updates in the same spreadsheet.
{% endhint %}

### Prepare the CSV file for import

Firstly, download the **Product List Template CSV** file from the **Product Import** page and open it with Libre Office \(Excel or equivalent\).

You'll see that the template gives all the column headings required to successfully import a product. Each row is for a new product or variant. Below is a description of how to fill in each column.

{% hint style="danger" %}
Note that all fields are case sensitive. E.g. you must use mL not ml , or Dairy not dairy.
{% endhint %}

| Column Title | Required? | Description | Example |
| :--- | :--- | :--- | :--- |
| producer | Y | This is the name of the producer profile that this product will be assigned to | Four Mile Farm |
| sku | N | The SKU code for this product | AD001265 |
| name | Y | This is the name of the product | Yoghurt |
| display name | N | This field applies if you are creating variants \(see instructions below\). If you're not creating a variant leave this field blank. | Rasberry Yoghurt |
| category | Y | Which category does this product sit in? The categories available are listed on the Product Import page | Dairy |
| units | Y | The weight, volume or quantity value | 500 |
| unit\_type | Maybe | What unit is it sold in \(g, kg, T, mL, L\)? If sold as an item \(e.g. bunch\) leave blank | g |
| variant\_unit\_name | Maybe | If the product is sold as an item \(e.g loaf, bunch, pumpkin\) write the item type here | Bunch |
| price | Y | The price of the product. If the item carries tax, this must be the tax inclusive price. | 3.70 |
| in\_stock | Maybe | If you have limited stock for the product type the stock level here. If you have infinite stock available \(you can always source it\) enter 0 and use the unlimited column | 40 |
| available\_on | N | Leave blank |  |
| unlimited | Y | If you have infinite stock available for this product, type 1, if you're using on\_hand leave blank. If you enter a number in in\_stock _and_ 1 in unlimited, the product will be unlimited. | 1 |
| shipping\_category | Y | Which shipping category does this product sit in? The shipping categories available are listed on the Product Import page |  |
| tax\_category | N | If the price of your product includes tax type GST, if not leave blank | GST |
| description | N | You can create a description, but you cannot update one. Please make sure that the text you wrote matches the current description in case of an update. | This Yoghurt is made from local raspberries |

#### Import Product Variants

In the import process, variants are distinguished by the units \(such as salad sold as 500 g and 750 g bags\) or display\_name fields \(such as a yoghurt sold in multiple flavours\). As long as the product name is the same, the rows will be imported as variants. The example below shows a salad that comes in 500g and 750g variants, and a yoghurt that comes in multiple flavours.

| name | display\_name | price | units | unit\_type |
| :--- | :--- | :--- | :--- | :--- |
| Salad Bag |  | 3.50 | 500 | g |
| Salad Bag |  | 5.50 | 750 | g |
| Yoghurt | Banana | 4 | 500 | g |
| Yoghurt | Strawberry | 4 | 500 | g |

The image below shows how these products will display in the shop. Note that the 'name' field becomes the primary heading, and the 'display\_name' field becomes the secondary heading. In the case of the Salad Bag, the 'display\_name' field is blank, so the 'name' is used by default.

![](../../.gitbook/assets/image%20%281%29.png)

#### Unit type examples

Below are some examples to show how products with different units \(g, ml, kg and items\) should be uploaded.

| producer | **name** | **category** | **price** | **units** | **unit\_type** | **variant\_unit\_name** |
| :--- | :--- | :--- | :--- | :--- | :---: | :---: |
| Sue's Salads | Salad Bag | Vegetables | 3.50 | 500 | g |  |
| Henry Orchards | Fruit Juice | Drinks | 3.50 | 300 | ml |  |
| Fernwell Produce | Potatoes | Vegetables | 9.50 | 5 | kg |  |
| Tom's Bakery | Wholemeal Bread | Baked goods | 3.00 | 1 |  | loaf |

### Import the CSV

Once you have filled out the **Product List Template CSV** you are ready to upload it into OFN.

1. Go to **Products** &gt;  **Product Import.**
2. **Select import type:** Select Product List
3. **Select a spreadsheet to upload:** Find the csv file you wish to upload.

   Because you are uploading new products, you can leave the '_Set stock to zero for all exiting products not present in the file_' checkbox unchecked.

4. Click **Upload**.

You'll be shown a summary of your upload, including any errors. You'll also be told how many products you are creating and how many you are updating. If you're happy with the upload results, click **save**.

{% hint style="success" %}
It's good practice to check that the products uploaded/updated as you intended.
{% endhint %}

You can then upload another spreadsheet or go to the products page to view your new products.

## Update Existing Product Details

The instructions below relate to updating the details of an existing product. This tool is intended as a quick way to update product prices and stock levels.

{% hint style="info" %}
You can simultaneously upload new products and update existing products with a single CSV upload. The instructions in this guide are separated for clarity but you can combine new products and updates in the same spreadsheet.
{% endhint %}

### Prepare the CSV file for import

The process for updating product details is similar to [uploading new products](product-and-inventory-import.md#import-new-products). The first step is to download the **Product List Template** and fill in the product names and the supplier names. If you have this spreadsheet on hand from a previous upload even better.

The system requires seven fields to correctly identify the product you want to update. There are four fields which can be updated and four fields which cannot using this tool.

| Required fields \(you can't update\) | Fields you can update | Fields that won't update and aren't required |
| :--- | :--- | :--- |
| \*producer | sku | ^variant\_unit\_name |
| \*name | price | ^tax\_category |
| ^category | in\_stock | ^shipping\_category |
| \*units | unlimited | ^description |
| ^unit\_type \(if applicable\) |  |  |
| ^variant\_unit\_name \(if applicable\) |  |  |
| \*display\_name |  |  |

_^ if you try to update these fields you'll see an error message_

_\*If you try to update these fields you'll actually create new products or variants, rather than update an existing product._

Once complete, the .csv can be [imported](product-and-inventory-import.md#import-the-csv) in the same manner as for new products.

{% hint style="info" %}
**Set stock to zero for all exiting products not present in the file:**  
If you select this tickbox the system will set the 'In Stock' value to zero for _all products already your product list_.  
If a product was 'Unlimited' it will remain 'Unlimited'.  
The Products in this import will retain the stock level set in the .csv
{% endhint %}

## Import New Inventory or update your inventory

Use these instructions if you want to add or update new products to your [inventory](inventory-tool.md).

### Prepare the CSV file for import

Firstly, download the **Inventory Template CSV** file from the **Product Import** page.

You'll see that the template gives all the column headings required to successfully import a product. Each row is for a new product or variant. Below is a description of how to fill in each column.

{% hint style="info" %}
Note that all fields are case sensitive. E.g. you must use mL not ml , or Dairy not dairy.
{% endhint %}

| Column Title | Required? | Description | Example |
| :--- | :--- | :--- | :--- |
| producer | Y | This is the name of the producer profile that this inventory item will be assigned to | Four Mile Farm |
| distributor | Y | This is the name of the hub profile the inventory item will be assigned to | Demo Hub |
| name | Y | This is the name of the product | Yoghurt |
| display name | N | This field applies if you are creating variants \(see instructions below\). If you're not creating a variant leave this field blank. | Rasberry Yoghurt |
| variant\_unit\_name | Y | If the product is sold as an item \(e.g loaf, bunch, pumpkin\) write the item type here | Bunch |
| units | Y | The weight, volume or quantity value | 500 |
| unit\_type | Y | What unit is it sold in \(g, kg, T, mL, L\)? If sold as an item \(e.g. bunch\) leave blank | g |
| price | Y | The price of the product. If the item carries tax, this must be the tax inclusive price. | 3.70 |
| in\_stock | Y | Please check the rules for unlimited below | leave blank as unlimited is set to 1 |
| unlimited | Y | If blank - Read as "Use producer stock settings", so "in\_stock" should be blank.   If you set it to "1" - Read as unlimited of "Yes", so "in\_stock" should be blank.     If you set it to "0" - Read as unlimited of "No", so "in\_stock" is required. | 1 |
| sku | N | The SKU code for this product | AD001265 |

### Import the CSV <a id="import-the-csv"></a>

Once you have filled out the **Inventory Template CSV** you are ready to upload it into OFN.

1. Go to **Products** &gt;  **Product Import.**
2. **Select import type:** Select Inventories
3. **Select a spreadsheet to upload**
4. Click **Upload**.

You'll be shown a summary of your upload, including any errors. You'll also be told how many products you are creating and how many you are updating. If you're happy with the upload results, click **save**.

{% hint style="success" %}
It's good practice to check that the products uploaded/updated as you intended.
{% endhint %}

