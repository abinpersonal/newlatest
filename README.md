Overview

The Custom_SaleTag module adds a "Sale" tag on the product image on both Product Detail Page (PDP) and Product Listing Page (PLP) in Magento 2.  and is displayed only when the product has a discount.

Features

Automatically display the "Sale" tag on products with active discounts.
Displays the tag on both PDP and PLP.


Installation

Upload the module files: Upload the module code into the directory: app/code/Custom/SaleTag

Enable the module: Run the following commands from the Magento root directory to enable the module: 
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy -f
php bin/magento cache:clean


