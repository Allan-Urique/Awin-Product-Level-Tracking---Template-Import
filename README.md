# Awin-Product-Level-Tracking---Template-Import
The necessary file to import the PLT only tag.

* Simply download the file via zip archive using the green button.
* Extract the file to anywhere in your computer and import it in your GTM container

# Features
The tag will use DataLayer parameters to call the Awin Product Level Tracking request to record the product data in the Awin Platform.

The tag also allows you to map product properties to custom DataLayer paths. For example, if you have a DataLayer that does not follow the default enhanced ecommerce structure for product properties arrays, you can override the path and the PLT tag will retrieve the data correctly.

Here is an example of a default enhanced ecommerce product array:

"products": [
  {
    "id": "925678982567899",
    "name": "Test Product 1",
    "price": "100",
    "quantity": "1",
    "sku": "987654674859650",
    "category": "First Test Category",
  }
]

If however your products array has custom properties, like the following:

"products": [
  {
    "item_id": "925678982567899",
    "item_listing": "Test Product 1",
    "price": "100",
    "quantity": "1",
    "sku": "987654674859650",
    "category": "First Test Category",
  }
]

You can override the product properties to map the Product ID to "item_id", and the Product Name to "item_listing", like the following:

![image](https://github.com/Allan-Urique/Awin-Product-Level-Tracking---Template-Import/assets/31394670/0a2565d9-1f14-4fec-9ca3-86aee8f12f96)

