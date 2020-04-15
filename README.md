

### Prestashop 1.6 plugin Kashier 

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/presta-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service.

- IFrame Integration.

- 3D secure cards authentication support.

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.

- Customize order state after success payment.


### Installation

- Download kashier.zip https://github.com//Kashier-payments/kashier-prestashop-1.6/raw/master/kashier.zip

- Upload the plugin on prestashop.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-1-upload plugin.png)

- Enable and Configure your plugin.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-2-success installation.png)
### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > customizable forms api keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-3-obtain test api keys.png)

- Insert the MID and Test Api Key in the Configuration page of the module.

- Make sure the test mode is on.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-4-insert test configuration.png)

### Test plugin 

- Proceed to make an order on your shop, a new payment method is added "Pay by card". it could be changed from module configuration.

- After proceeding you will find a Kashier "pay now" button, fill in the test card and proceed to make a payment.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-5-Method appears in payment section.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-6-pay now button.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-7-0-iframe- render.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-7-1-Order Accepted screen.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-7-2-Orders payment accepted and transaction id.png)
### Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > customizable forms api keys

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-8-0-Live api keys.png)

- Insert Live Api Key in the Configuration page of the module.

- Remove the test mode check.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-8-1-Live configuration.png)

### Support
##### Success Order state change

- You could choose the success order state change call back from the module configuration. you will find your states for the success order state and click save.

##### Enable and disable currency
- If there is a currency not supported by kashier, you could just disable it from "Modules and Service > Payments".

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/steps/install-9-Enable and disable kashier on currencies.png)

- Leave us an inquiry ticket on https://kashier.io for questions.

