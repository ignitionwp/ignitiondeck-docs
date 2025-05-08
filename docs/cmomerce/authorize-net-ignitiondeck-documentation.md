# Authorize.net - IgnitionDeck Documentation

# Authorize.net

[](javascript:window.print())
Authorize.Net is a popular payment gateway portal for accepting credit card payments. IgnitionDeck integrates seamlessly with Authorize.Net and setup is for this is very easy.

Good to know

You must already have a payment processor to handle the credit card charges before you proceed such as Cybersource or Payment Cloud. Authorize.net's full reseller directory can be found here: https://www.authorize.net/sign-up/reseller-directory/.html

Heads up

Site owners cannot charge crowdfunding fees via Authorize.Net as the gateway does not support connected accounted.

For a comparison of different payment gateways that work with creator accounts, see our FAQ Choosing Payment Gateways.

IMPORTANT

Due to a dependency on the SDK provided by AuthorizeNet, the gateway requires a server running on PHP version 7+.

The SDK will not work with versions earlier than 7 nor with PHP 8 at this time.

To accept payments with your Authorize.Net account:

Once you’ve set up your payment gateway(s), you will want to perform some test transactions to make sure everything is working properly. For some tips on testing your payments gateway(s), see our documentation on Payment Gateway Testing.

Heads up!

Authorize.net will not work with Guest Checkout because of the customer verification required to complete the transaction. If Guest Checkout is enabled, the checkout will throw a No Payment Options Available message if there are no other payment gateways (i.e. PayPal, etc.) available.



---
**Source:** [https://docs.ignitiondeck.com/article/98-authorize-net](https://docs.ignitiondeck.com/article/98-authorize-net)
