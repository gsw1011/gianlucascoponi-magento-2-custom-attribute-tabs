# gianlucascoponi-magento-2-custom-attribute-tabs

Tested on Magento 2.3

Add custom product attribute tab

Add custom product attribute tabs with condition if attrubute exist and hide tabs if attribute not found

Upload app folder in you Magento Root


Edit \app\code\GianlucaScoponi\CustomAttributeTab\view\frontend\layout\catalog_product_view.xml and add edit blocks with your custom attribute and define the phtml files

Edit \app\code\GianlucaScoponi\CustomAttributeTab\view\frontend\templates all phtml file name with your custom attributes

Edit all phtml files in   \app\code\GianlucaScoponi\CustomAttributeTab\view\frontend\templates  with your custom attrributes

Edit \app\code\GianlucaScoponi\CustomAttributeTab\Observer\RemoveBlockCustomTab.php  with your custom attrributes


Open ssh in your magento root and type:

php bin/magento setup:upgrade

php bin/magento setup:di:compile
 
php bin/magento setup:static-content:deploy -f

php bin/magento cache:flush 















