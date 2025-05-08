# Stripe—deprecated - IgnitionDeck Documentation

# Stripe—deprecated

[](javascript:window.print())

### June 2024 Deprecation Notice

The legacy Stripe payment gateway located in IDC > Gateways is being deprecated in favour of our Stripe Checkout module, and will be removed from the plugin entirely by Q4 of 2024.

If you are a new IgnitionDeck plugin user, please activate the Stripe Checkout module instead to take advantage of modern features such as mobile payments, Stripe Connect, and more. Please see Stripe Checkout documentation.

If you are using the legacy verson of the Stripe payment gateway, please see Migrating from (legacy) Stripe to Stripe checkout

Stripe allows IgnitionDeck owners to process credit cards on their site. To read more about the capabilities of the different payment gateway options in ID Commerce (IDC), please see our documentation page called Choosing Payment Gateways.

You may not see this option if a) you have not validated your license key in the IgnitionDeck » Settings menu or b) another credit card payment gateway is enabled.

NOTE: A Stripe account is required to use this payment gateway. Sign up for an account here: https://dashboard.stripe.com/register

IMPORTANT: If you require Secure Customer Authentication, are located in Europe, or wish to provide additional payment options via Stripe, please enable the Stripe Checkout through the IgnitionDeck » Modules instead of the Stripe integration in IDC » Gateways.

For more information on the Stripe Checkout, please see the Modules | Stripe Checkout documentation.

## Setting up Stripe

To accept payments with your Stripe account:

## Subscriptions / Recurring Payments

If using the Subscription / Recurring funding type, a webhook will need to be setup in Stripe to handle these transaction types.  This is ONLY required for subscription / recurring payments.

You can set up both the test and live webhooks during the setup process and the correct webhook will be used depending on the mode used on the website.

With IgnitionDeck Enterprise and Stripe, you have the option of enabling the payment gateway for creators using Stripe Connect. Enable this option and complete the set up of the payment gateway for creators. See documentation for Stripe Connect .



---
**Source:** [https://docs.ignitiondeck.com/article/30-stripe](https://docs.ignitiondeck.com/article/30-stripe)
