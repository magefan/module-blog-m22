# [Magento 2.2.x Blog Extension](https://magefan.com/magento2-blog-extension) by Magefan

[![Total Downloads](https://poser.pugx.org/magefan/module-blog/downloads)](https://packagist.org/packages/magefan/module-blog)
[![Latest Stable Version](https://poser.pugx.org/magefan/module-blog/v/stable)](https://packagist.org/packages/magefan/module-blog)

This Magento 2 module fix issue with blog posts media gallery in [Magefan Blog Extension](https://github.com/magefan/module-blog)


## Installation Method 1 - Installing via composer
  * Open command line
  * Using command "cd" navigate to your magento2 root directory
  * Run commands:
```
composer require magefan/module-blog-m22
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```
## Installation Method 2 - Installing using archive
  * Install the [Magefan Blog Extension](https://github.com/magefan/module-blog/)  first
  * Download [ZIP Archive](https://github.com/magefan/module-blog-m22/archive/master.zip)
  * Extract files
  * In your Magento 2 root directory create folder app/code/Magefan/BlogM22
  * Copy files and folders from archive to that folder
  * In command line, using "cd", navigate to your Magento 2 root directory
  * Run commands:
```
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## Support
If you have any issues, please [contact us](mailto:support@magefan.com)
then if you still need help, open a bug report in GitHub's
[issue tracker](https://github.com/magefan/module-blog/issues).

Please do not use Magento Marketplace Reviews or (especially) the Q&A for support.
There isn't a way for us to reply to reviews and the Q&A moderation is very slow.

## License
The code is licensed under [Open Software License ("OSL") v. 3.0](http://opensource.org/licenses/osl-3.0.php).

## Other Magefan Extensions That Can Be Installed Via Composer
  * [Magento 2 Auto Currency Switcher Extension](https://magefan.com/magento-2-currency-switcher-auto-currency-by-country)
  * [Magento 2 Blog Extension](https://magefan.com/magento2-blog-extension)
  * [Magento 2 Login As Customer Extension](https://magefan.com/login-as-customer-magento-2-extension)
  * [Magento 2 Conflict Detector Extension](https://magefan.com/magento2-conflict-detector)
  * [Magento 2 Lazy Load Extension](https://github.com/magefan/module-lazyload)
  * [Magento 2 Rocket JavaScript Extension](https://github.com/magefan/module-rocketjavascript)
  * [Magento 2 CLI Extension](https://github.com/magefan/module-cli)
