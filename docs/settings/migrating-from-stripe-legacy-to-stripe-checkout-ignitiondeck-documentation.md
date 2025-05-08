# Migrating from Stripe (legacy) to Stripe Checkout - IgnitionDeck Documentation

# Migrating from Stripe (legacy) to Stripe Checkout

[](javascript:window.print())
Our default Stripe payment gateway (located in IDC » Gateways) is going away in favour of the modern, feature rich Stripe Checkout module we introduced in 2020. Making the switch is an easy process!

### To make the switch:

Important notes for Stripe Connect

The Stripe Connect settings will appear in the same settings page as the Stripe Checkout, rather than a separate tab as with the legacy version.

No changes are needed on the Stripe Connect application itself (unless Subscription funding is in use, see below).

### Important notes for Immediate Capture transactions

Follow the steps 1-7 above and you are done!

No changes are needed on the Stripe account itself. All end points and webhooks are the same between the legacy Stripe gateway and Stripe Checkout.

### Important notes for 100% Threshold / All-or-nothing / Pre-order transactions

If you are using the 100% Threshold / pre-authorization funding method, you will need to process any uncaptured pre-authorization tokens in the current gateway before proceeding to make the switch.

Once those transactions have been completed, follow steps 1 through 7, above.

No changes are needed on the Stripe account itself. All end points and webhooks are the same between the legacy Stripe gateway and Stripe Checkout.

### Important notes for Recurring / Subscription transactions

Please contact us before making the transition over to the Stripe Checkout module.

If you are using the Recurring / subscription funding method, any subscriptions that were previously completed through the payment gateway will be unaffected as subsequent scheduled payments are initiated through Stripe.



---
**Source:** [https://docs.ignitiondeck.com/article/171-migrating-stripe-legacy-stripe-checkout](https://docs.ignitiondeck.com/article/171-migrating-stripe-legacy-stripe-checkout)
