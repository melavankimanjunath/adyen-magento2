# Adyen_Magento2
Adyen Payment plugin for Magento2


## Install with Composer

Make sure you have "minimum-stability": "dev" in your magento composer.json set.
Because the repositories are private you need to do the folowing:

1. composer config repositories.adyen-adyen-magento2 vcs git@github.com:Adyen/adyen-magento2.git 
2. composer config repositories.adyen-php-api-library vcs git@github.com:Adyen/adyen-php-api-library.git
3. composer require adyen/module-payment

## API Library
Not yet used but communication through the API will go through this library. If you not have access to this repo please let us know.