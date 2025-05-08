# Payment Gateway Testing - IgnitionDeck Documentation

# Payment Gateway Testing

[](javascript:window.print())
Jump to specific payment gateway: PayPal | Stripe | Authorize.net | FirstData | Square | Paytm

The Commerce » Gateways has a Test Mode that can be enabled to use sandbox environments with most payment gateways to conduct tests without the need of real money and thereby avoiding any charges or refunds with live gateways.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/679a59a14bfa3334f17de423/file-ZOHdBtYqCR.png)

  Enable gateway testing
 

Recommendation

It is strongly suggested that a payment gateway is tested before the site is launched to avoid any potential hiccups that would create a negative experience for your users.

Good to know

Because testing of some gateways can be complicated requiring the set up a test or “sandbox’ account, sometimes it is faster and easier to simply create a test product or crowdfunding level that has a minimum viable price* and test using live transactions.

* Minimum viable price will depend on the specific gateway but this is generally within the range of $1-5

### PayPal (Standard)

When using PayPal as a gateway, the typical method for testing is to set up two “Sandbox” accounts, one for the buyer and one for the seller. Insert these seller test credentials (instead of your real ones) in the Commerce » Gateways » PayPal menu while your platform is in test mode then make a test payment using the buyer credentials.

### Stripe

Stripe provides each of its users with a test Stripe Publishable Key and a test Stripe Secret Key. Enter these in their respective fields in Commerce » Gateways » Stripe. Then enable test mode at the top of your Gateways screen use the test credentials instead of the live ones.

### Authorize.net

When using Authorize.Net as a gateway, the typical method for testing is to set up a “Sandbox” account. This test account is used to create a test API Login ID and test Transaction Key. Then you use these test credentials (instead of your real ones) in Commerce » Gateways » Authorize.Net.

### FirstData

When using FirstData as a gateway, if you would like to set up up a test account, we recommend that you contact your FirstData account representative for help with this.

### Square

Square also supports sandbox testing and uses the same "Enable Test Mode" in the Commerce » Gateways settings.

### Paytm

Paytm supports test payments through a staging environment and uses the "Enable Test Mode" in the Commerce » Gateway settings.



---
**Source:** [https://docs.ignitiondeck.com/article/44-payment-gateway-testing](https://docs.ignitiondeck.com/article/44-payment-gateway-testing)
