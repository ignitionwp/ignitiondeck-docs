# The [project_purchase_form] shows up instead of the checkout - IgnitionDeck Documentation

# The [project_purchase_form] shows up instead of the checkout

[](javascript:window.print())
The [project_purchase_form] shortcode shows up if the project or payment settings are incomplete. The most likely cause is that the products needed to complete the project have not been created and linked to the reward levels for the payment gateway to use to complete a transaction.

First, make sure that you have set up the purchase page correctly and assigned it as the default checkout page: Default Purchase Page

Once you have created your project under Projects > Add New and have created your reward levels (at least one is required), you will need to:

If you are using the IgnitionDeck Enterprise version of the plugins, steps 1 through 3 are made automatically when creating a project via the front end project submission form, but must be done manually when projects are created from the admin side of the site.

Finally, make sure that at least one payment method available that will support the funding type being used (i.e. PayPal will not support pre-order transactions and will result in an error at the checkout page).



---
**Source:** [https://docs.ignitiondeck.com/article/180-the-projectpurchaseform-shows-up-instead-of-the-checkout](https://docs.ignitiondeck.com/article/180-the-projectpurchaseform-shows-up-instead-of-the-checkout)
