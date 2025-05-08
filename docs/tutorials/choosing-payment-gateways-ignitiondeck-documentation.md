# Choosing Payment Gateways - IgnitionDeck Documentation

# Choosing Payment Gateways

[](javascript:window.print())
For specific instructions on setting up the preferred payment gateway, please see the Payment Gateway section of the docs.

## Choosing Payment Gateways

ID Commerce (IDC) integrates with several different payment gateways in order to accommodate a wide variety of Crowdfunding and E-commerce scenarios. Refer to the table below to determine which gateways are best for you. Be sure to keep in mind that not all gateways work in all parts of the world and not all gateways support every possible currency.

Good to know

Only one gateway for credit card processing at a time is permitted, but this does not exclude other gateways from being used. For instance, you can use Stripe for credit cards and still allow offline payments, PayPal, and/or cryptocurrencies for payments through the same checkout.

## ID Commerce Gateway Capabilities, Countries, and Currencies

Payment Gateway
Crowdfunding  Fee 1 
Pre-order Payments
Recurring Payments
Instant Checkout
Countries
Currencies

PayPal Standard
No
No
Yes 2
No
[link](https://developer.paypal.com/docs/classic/api/country_codes/)
[link](https://developer.paypal.com/webapps/developer/docs/classic/api/currency_codes/)

Stripe 3, 4
Yes
Yes
Yes 5
Yes
[link](https://support.stripe.com/questions/what-countries-does-stripe-support)
[link](https://support.stripe.com/questions/which-currencies-does-stripe-support)

Authorize.net
No
Yes
Yes
Yes
[link](https://www.cybersource.com/en-us/solutions/payment-acceptance.html)
[link](https://www.cybersource.com/en-us/solutions/payment-acceptance.html)

FirstData
No
Yes
No
Yes
[link](https://www.firstdata.com/en_us/products/merchants/card-and-check-acceptance/dynamic-currency-conversion-dcc.html)
[link](https://www.firstdata.com/en_us/products/merchants/card-and-check-acceptance/dynamic-currency-conversion-dcc.html)

Square
No
No
No
Yes
[link](https://squareup.com/help/ca/en/article/4956-international-availability)
[link](https://squareup.com/help/ca/en/article/5415)

PayTM
No
No
No
Yes
India
INR 

CoinPayments
Yes
No
No
No
[link](https://www.coinpayments.net/help-restricted)
[link](https://www.coinpayments.net/supported-coins) 

1 IgnitionDeck Core (paid) only

2 Recurring Payments with PayPal cannot be limited to a pre-defined number of payments.

3 Strong Customer Authentication (SCA) support using the Stripe Checkout

4 Mobile payments such as GPay, Apple Pay, and Link are available though Stripe Checkout

5 Pay-What-You-Want with Recurring Payments turned on is not possible with Stripe. If a customer changes their payment amount, Stripe will no longer be available as a payment gateway, so you will want to have at least one additional payment gateway activated. This is due to the fact that Stripe handles recurring payments based on a unique “Stripe Plan Name,” which has a set price assigned to the plan.

Interested in using WooCommerce and it's payment gateways? Please see our WooCommerce & IgnitionDeck documentation on how to use and the limitations of WC with IgnitionDeck.



---
**Source:** [https://docs.ignitiondeck.com/article/46-choosing-payment-gateways](https://docs.ignitiondeck.com/article/46-choosing-payment-gateways)
