# Stripe Checkout (SCA) - IgnitionDeck Documentation

# Stripe Checkout (SCA)

[](javascript:window.print())
Stripe Checkout is a Strong Customer Authentication (SCA) compliant payment portal hosted by Stripe. This gateway supports those businesses operating in regions that require 2-step verification on credit card payments and also provides mobile payment options such as Apple Pay, Google Pay, and more that can be enabled via your Stripe account.

The Stripe integration also works with the Fee Mods feature providing platform fee application on a per-project basis, the option for supporters to cover fees, and the option to request a donation to the platform at the checkout step.

## Setting up Stripe Checkout

### Good to know!

Test mode and HTTPS are set under Commerce » Gateways » Gateway Platform Settings

Heads up!

If there are pending pre-authorization charges / all-or-nothing projects underway with another credit card payment gateway, those transactions must be captured before changing the gateway to Stripe Checkout otherwise the transactions will fail upon processing.

Pre-authorization tokens are specific to the gateway that issued them and are not transferable between gateways.

Important!

Stripe Checkout will not work with Guest Checkout in any country or region that requires Strong Customer Authentication (or other 2 factor authentication) because of the customer verification required to complete the transaction. If Guest Checkout is enabled, the checkout will throw a No Payment Options Available message if there are no other payment gateways (i.e. PayPal, etc.) available.



---
**Source:** [https://docs.ignitiondeck.com/article/92-modules-stripe-checkout-sca](https://docs.ignitiondeck.com/article/92-modules-stripe-checkout-sca)
