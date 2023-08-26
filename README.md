# Catalog/Ko

- Product Inquiry Form and Notification Module. 

- Adds a product inquiry form to the product detail page. When customers submit an inquiry, the module should notify the store admin via email. Additionally, the admin should be able to view and reply to inquiries from the backend, sending email responses to the customers.

- Tested on Magento Community Edition  `Magento 2.4.6`.

## Composer install

- `composer config repositories.product_Inquiry vcs https://github.com/vashy89/product_Inquiry`
- `composer require PWC/productInquiry`

## Composer uninstall

- `composer remove PWC/productInquiry`

## Preview will be added

![timer-in-categoryPage](/readme-images/Timer-at-categoryPage.png "timer-in-categoryPage")


## Settings

- Option `will be updated ..` - Under Construction

## Known issues

- **Notification E-Mails could go to spam folder in gmail or any other mail platform**\

### Install module
1. Run `composer require PWC/productInquiry`
2. Run `php bin/magento setup:upgrade`
3. Run `php bin/magento setup:di:compile`
4. Run `php bin/magento s:s:d en_US`
5. Run `php bin/magento c:c`

### Uninstall module
1. Run `composer remove PWC/productInquiry`
2. Run `php bin/magento setup:di:compile`
3. Run `php bin/magento s:s:d en_US`
4. Run `php bin/magento c:c`


## Developer informations
- Vashishtha Chauhan

## Developer informations
- Vashishtha Chauhan
- Email `vashishtha.prime@gmail.com`
- Mobile `+91 9898121095`