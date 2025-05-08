# Stripe Connect - IgnitionDeck Documentation

# Stripe Connect

[](javascript:window.print())

Stripe Connect allows you, as a crowdfunding portal or e-commerce website owner, tocharge a fee on top of transactions made on your site. Stripe Connect enables fees on a flat or percentage basis, and is available as part of the IgnitionDeck Enterprise package.

Users can authenticate (via OAuth) for your application by visiting their payment settings page, viewable once they have submitted a project or product for review, provided it has been enabled in the gateway settings menu.

Once you’ve set up your payment gateway(s), you will probably want to perform some test transactions to make sure everything is working properly. For some tips on testing your payments gateway(s), see our documentation page called Payment Gateway Testing.

Heads up!

In order to permit the creators to connect their Stripe account, you must first enable the Stripe payment gateway for the platform.

See documentation on setting up your Stripe payment gateway.

## Create Your Stripe Connect Application

The next step is to set the required webhook(s) for the Connected accounts.

### Required Webhooks

### Going Live

## Common Errors

No such customer or similar objects exist in live mode. But test mode key was used to make this request

This error happens when a project creator’s Stripe account has been connected during the Test mode of the payment gateway but then a payment is attempted when the gateway has been switched into Live mode.  To fix this error the project creator’s Stripe credentials must be revoked from the site so that they can reconnect in the Live mode.

## Important notes about the Stripe Connect Application approval process

There are a series of questions asked about how you intent to use Stripe Connect with your website. Here are some recommendations on how to complete that process

Note: recommendations do not guarantee that your application will be approved



---
**Source:** [https://docs.ignitiondeck.com/article/31-stripe-connect](https://docs.ignitiondeck.com/article/31-stripe-connect)
