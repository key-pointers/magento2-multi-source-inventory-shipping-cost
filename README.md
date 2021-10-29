# Using Multi Source Inventory module how to calculate shipping cost based on the sources?

    ``keypointers/module-net45``

 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Article](#markdown-header-article)


## Main Functionalities
Magento2 provides Multi Source Inventory module that helps in managing multi warehouses. The MSI module also utilize shipping algorithms that helps in recommending best shipping algorithms based on distance or priority. More details about the MSI management is available on Magento dev docs website.

The scenario that this module don’t provide is shipping cost based on the source/warehouse location of the item. The shipping cost is calculated based on the shipping origin defined at the global level. To fulfill this feature we have to buy extension that will help or use below logic. The main thing to remember is multiple calls to Shipping provider hence we would need to cache the objects.

## Article
https://www.key-pointers.com/magento/shipping-cost-calculator-when-using-multi-source-inventory/
