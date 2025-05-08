# PayPal - IgnitionDeck Documentation

# PayPal

[](javascript:window.print())
PayPal is appropriate to use if you wish to provide Immediate Capture funding and/or simple subscription payments. It can be used in conjunction with a credit card processor such as Stripe.

For pre-authorized payments (100% threshold / all-or-nothing) funding option, a credit card gateway such as Stripe should be used instead.

For IDE users, capturing crowdfunding fees are not supported with PayPal so Stripe Connect should be enabled in order to charge a transaction fee regardless of the project funding type.

To read more about the capabilities of the different payment gateway options in IgnitionDeck Commerce (IDC), please see our documentation page called Choosing Payment Gateways.

NOTE: Taking IDC payments via PayPal requires at least a business-level PayPal account. To learn more about PayPal account types, see PayPal’s documentation on account types.

## Set up the PayPal payment gateway in IgnitionDeck

## Set up the payment gateway in PayPal dashboard

### Return URL Configuration

The Return URL set in PayPal redirects your supporters back to your site after completing their transaction.

### Instant Payment Notification (IPN) Configuration

In your PayPal account, set up the Instant Payment Notification.  This is a good tool for troubleshooting any payment issues.

Congratulations: your payment gateway is now ready to use.

Once you’ve set up your payment gateway(s), you will probably want to perform some test transactions to make sure everything is working properly. For some tips on testing your payments gateway(s), see our documentation for Payment Gateway Testing.



---
**Source:** [https://docs.ignitiondeck.com/article/29-paypal](https://docs.ignitiondeck.com/article/29-paypal)
