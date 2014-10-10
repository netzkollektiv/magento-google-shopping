Magento Google Content API for Shopping
=============================

Source [http://www.magentocommerce.com/magento-connect/google-content-api-for-shopping.html](http://www.magentocommerce.com/magento-connect/google-content-api-for-shopping.html)

## Installation

To use this extension your Google Account must be configured to allow deprecated authentication mechanisms.
You can to this by enabling the setting "Allow less secure apps" located in your account settings:
https://www.google.com/settings/security/lesssecureapps

Another caveat is setting the correct credentials:

Account ID: Merchant Center ID of your merchant center account
Account Username: your Google account email address (NOT: oAuth Credentials, Merchant Center Users)
Account Password: your Google account password
Account Type: Hosted or Google

## Changes so far ...

- code pool from core to community
- code reformatted
- composer ready


## About

Google has retired its old Google Base Data API and replaced it with its new Google Content API for Shopping to let back-end staff more effectively
upload and manage product and catalog information. This extension allows developers to migrate their eCommerce stores into the new API to ensure that
they come up in Google searches.

- Replaces current Google Base API logic in Magento
- Allows developers to define which products are sent to Google
- Enables definition of how product attributes are mapped to Google

## License

[OSL v3.0](http://www.opensource.org/licenses/osl-3.0.php)
