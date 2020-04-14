

### Prestashop 1.6 plugin Kashier 

![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/kashier-prestashop-1.6/master/presta-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service
- IFrame Integration
- 3D secure cards authentication support
- Support acquiring multiple currencies "EGP, USD, GBP, EUR"
- Plug and play
- Customize order state after success payment



[TOCM]
### Installation
- Download kashier.zip https://github.com//Kashier-payments/kashier-prestashop-1.6/raw/master/kashier.zip
- Upload the plugin on prestashop 
- Enable and Configure your plugin

### Obtain Test Credentials
- Login or Sign up on kashier.io https://merchant.kashier.io/
- Navigate to Integrate now section > customizable forms api keys
- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.
- Copy Merchant ID visible under your user name "MID-xx-xx"
- Insert the MID and Test Api Key in the Configuration page of the module.
- Make sure the test mode is on.
- Save configuration

### Test plugin 

- Proceed to make an order on your shop, a new payment method is added "Pay by card". it could be changed from module configuration.
- After proceeding you will find a Kashier "pay now" button, fill in the test card and proceed to make a payment.

### Go live

- After activating your account 
- Make sure you are on live mode
- Navigate to Integrate now section > customizable forms api keys
- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.
- Insert Live Api Key in the Configuration page of the module.
- Remove the test mode check.
- Save configuration

### Support
##### Success Order state change
##### Enable and disable currency


