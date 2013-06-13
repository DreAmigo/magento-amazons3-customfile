magento-amazons3-customfile
===========================

### **Upload any Custom File Option from a Magento product Amazon S3.**

**Instead of saving the Product "Custom File" from a product during the checkout locally it will upload the file to Amazon S3.**


Required Extension: [One Pica](http://www.magentocommerce.com/magento-connect/6274.html)

Replace the variable for the bucket that you would like to save on S3.

`protected $_bucketArtwork = "artworks";`


Please replace the file into: **/app/code/core/Mage/Catalog/Model/Product/Option/Type/File.php**


