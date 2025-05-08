# Payment Gateways - IgnitionDeck Documentation

# Payment Gateways

[](javascript:window.print())

Recommended

If you’re not sure which gateway(s) to choose, please see our documentation page called Choosing Payment Gateways.

Good to know

For specific instructions on setting up the preferred payment gateway, please see the Payment Gateway section of the docs.

## The Gateways screen

The Gateways screen is broken into two major sections: Gateway Status Settings and the Payment Gateways.

### Gateway Status Settings

Enable Test | Development Mode instructs ID Commerce to use the test keys/emails provided instead of the regular/live keys/emails. This lets you verify that your web site is communicating properly with your payment gateway without having to use real money.

For more information on how to test specific gateways, see Payment Gateway Testing doc.

Enable HTTPS should be checked after you have an SSL certificate installed on your web server. This permits the ID Commerce to establish a secure connection for all financial transactions. Every live site intent on taking payment information from customers should have this enabled; however, it is only required specifically by credit card processors.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/679ba6386b01984692a709cd/file-PnDWeQnzEX.png)

  Gateway Status Settings
 

## Payment Gateways

The Payment Gateways section is broken down to a further four (4) sections: Alternate Payment Gateways, PayPal, Credit and Debit card Payment Gateways, and Cryptocurrency Payment Gateways.

Only one credit card gateway can be enabled at once; however, a payment gateway in each section can be enabled simultaneously to appear on the checkout to provide options to the backer.

Head up!

Not all payment gateways support all funding type options. If the transaction calls for a funding option that is not supported by the selected gateway, that gateway will be hidden at the checkout. If no enabled gateway supports the funding type, then the message "No available payment gateway" will appear. See Choosing Payment Gateways for more details.

Each payment gateway has a slightly different approach, but the result is the same: a set of credentials (API Keys) allows your website to communicate with the payment gateway. Some gateways also have a second set of credentials that can be used for testing purposes.

The specific key or link information for your gateway can generally be found under settings within your account on the payment gateway’s website.

The first checkbox enables or disables the selected gateway for the platform and requires the site owner's payment account information.

The second checkbox, if applicable, allows project creators to connect their own payment accounts to receive funds directly. This also allows for the charging of crowdfunding fees through supporting gateways1.

The third checkbox, enables the Fee Mods extension to modify how crowdfunding fees are charged on the corresponding payment gateway. Fee Mods permits fees to be charged on a per-project basis instead of the default gateway value, donations to the platform, and coverage of fees on behalf of the project creator.

### Alternate Payment Gateways

Alternate Payment Gateways includes the offline and virtual credits payment gateways. The offline gateway will use the Global Currency at the checkout.

### PayPal Payment Gateways

PayPal can be enabled here and set with the currency of the linked PayPal account2.

Credentials entered in the settings modal will be retained even when the gateway has been disabled.

### Credit Card Payment Gateways

One credit card processor can be enabled here at a time. The currency must be set to match the currency of the linked credit card account3.

Credentials entered in the settings modal(s) will be retained even when the gateway(s) are disabled.

### Cryptocurrency Payment Gateways

CoinPayments can be enabled here with multiple accepted coins matching those coins enabled within the payment processor account2.

Credentials entered in the settings modal(s) will be retained even when the gateway(s) are disabled.

Heads up!



---
**Source:** [https://docs.ignitiondeck.com/category/23-payment-gateways](https://docs.ignitiondeck.com/category/23-payment-gateways)


---
**Source:** [https://docs.ignitiondeck.com/article/95-ignitiondeck-commerce-gateways](https://docs.ignitiondeck.com/article/95-ignitiondeck-commerce-gateways)
