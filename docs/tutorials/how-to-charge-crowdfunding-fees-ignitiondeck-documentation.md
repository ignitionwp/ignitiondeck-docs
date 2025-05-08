# How to Charge Crowdfunding Fees - IgnitionDeck Documentation

# How to Charge Crowdfunding Fees

[](javascript:window.print())
IgnitionDeck offers payment gateways via ID Commerce that provide IgnitionDeck Enterprise platform owners to charge crowdfunding fees on every* transaction made on projects through their crowdfunding platform.

* Fees can be optionally disabled or customized on individual projects using the Fee Mods module

## Requirements for charging crowdfunding fees:

## Charging Fees with Stripe Connect

See documentation on how to set up Stripe Connect

Crowdfunding fees are collected when the transaction is completed through Stripe. Fees on pre-order transactions will be collected when the pre-authorizations charges are completed, not at the time of the initial authorizing transaction

## Charging Fees with CoinPayments

See documentation on how to set up CoinPayments

When a payment is made on the creator's project, a percentage of those funds will be paid into your own CoinPayments account with the remainder send to the creator's account.

Transfers from the site admin account to the creator account take approximately 1 hour to be completed after the initial transaction has been completed. The fee will be deducted at the same time the transfer is made to the creator's linked merchant account.

CoinPayments does not have the tools to verify a creator has connected their account prior to a project going live and/or receiving funds; however, this can be verified with reviewing a test transaction.



---
**Source:** [https://docs.ignitiondeck.com/article/96-how-to-charge-crowdfunding-fees](https://docs.ignitiondeck.com/article/96-how-to-charge-crowdfunding-fees)
