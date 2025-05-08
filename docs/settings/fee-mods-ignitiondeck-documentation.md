# Fee Mods - IgnitionDeck Documentation

# Fee Mods

[](javascript:window.print())
Fee Mods is designed specifically for platforms owners that have enabled creator accounts and wish to provide additional checkout options for a donation to the platform and/or cover the fees for the creator, and the ability to charge crowdfunding fees on a project-by-project basis instead of a flat rate across all projects.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/679d31ebd01b456ea1cacaf1/file-n3nNLS0qj1.png)

  Enable Fee Mods on supported payment gateways
 

Good to know

Fee Mods is currently supported by Stripe Checkout and CoinPayments payment gateways when enabled for creators.

#### Customizing Project Fees

Good to know

If a fee is not set on a project individually, the system will default to the fee saved in the payment gateway settings.

For example, if the default fee is 5%, the project with a 10% fee will be charged 10%. Any other projects without a custom fee will be charged at the 5%.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/605e1ae03f70ab34d9ba39c7/file-VOJS50nflO.png)

  Setting a custom fee on a project
 

#### Donations on Checkout

This feature makes it possible to collect platform donations on checkout. All donations go straight to the platform's payment account. The label and checkout text can be used to add an optional custom description.

The platform donation will be collected based on the dollar value entered on the checkout form, regardless of any other fees enabled.

#### Cover Fees on Checkout

This option allows backers to cover the creator’s platform fee during checkout. The label and checkout text can be used to add an optional custom description.

When active, this option will create a checkbox on the checkout form that when checked, will automatically increase a backer’s pledge to cover the base fee.

Heads up!

Covering the fees will increase the platform fee by a marginal amount, and that this increase will not be covered. For example, a 10% fee coverage on a $10 transaction would increase the purchase price to the backer to $11. The creator will see a fee of $1.10 charged but would receive $9.90 of the original $10 pledge instead of $9.00 had the backer not covered the fees.



---
**Source:** [https://docs.ignitiondeck.com/article/72-modules-fee-mods](https://docs.ignitiondeck.com/article/72-modules-fee-mods)
