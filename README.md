# Hide Adobe Payment Services

Starting from 2.4.7, Adobe / Magento Payment Services comes bundled in with Magento, which takes up a lot of screen real estate at the top of the Payment Methods configuration section.

Disabling the Payment Services modules throws ACL errors, so we created a very simple module that removes the Adobe Payments section of Payment Methods.

## Compatibility 
- Magento >= 2.4.7

## Installation
Install via composer:
```
composer require comtecs/hide-adobe-payment-services
php bin/magento setup:upgrade
```

# License

[GPL v3](./LICENSE)