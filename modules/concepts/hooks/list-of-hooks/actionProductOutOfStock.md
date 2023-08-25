---
menuTitle: actionProductOutOfStock
Title: actionProductOutOfStock
hidden: true
hookTitle: Out-of-stock product
files:
  - Classic Theme: templates/catalog/_partials/product-details.tpl
locations:
  - front office
type: action
hookAliases:
 - productOutOfStock
---

# Hook actionProductOutOfStock

Aliases: 
 - productOutOfStock



## Information

{{% notice tip %}}
**Out-of-stock product:** 

This hook displays new action buttons if a product is out of stock
{{% /notice %}}

Hook locations: 
  - front office

Hook type: action

Located in: 
  - [Classic Theme: templates/catalog/_partials/product-details.tpl](https://github.com/PrestaShop/classic-theme/blob/develop/templates/catalog/_partials/product-details.tpl)

## Call of the Hook in the origin file

```php
{hook h='actionProductOutOfStock' product=$product}
```