# WooCommerce & IgnitionDeck - IgnitionDeck Documentation

# WooCommerce & IgnitionDeck

[](javascript:window.print())
IgnitionDeck integrates with WooCommerce so that you can build a powerful self-hosted crowdfunding system on top of your WooCommerce-based site. For instance, this might be a good choice if your project contribution rewards are strictly physical goods (like t-shirts or other items that require shipping) within your existing shop.

Important note

WooCommerce can not be used as the commerce platform if the site is intended to allow 3rd party/non-admin users to become project creators.

In order for the front end project creator feature and the associated payment functionality (creator accounts and crowdfunding fees), IgnitionDeck must use the IgnitionDeck Commerce platform.

## Creating and Connecting WC Products to IgnitionDeck Projects

The following steps explain how to link your crowdfunding levels to WooCommerce “Product Attributes.”

If you do not see the WooCommerce Shortcode field, make sure to set and save your Commerce Platform as WooCommerce (step 1 above).

## Checkout URL

When the WooCommerce plugin was installed and activated, the default pages for the commerce platform would likely have been created automatically during the setup wizard. The Cart and Checkout pages should be set within WooCommerce » Advanced tab:

Go to IgnitionDeck » Settings and select either the Cart URL or the Checkout URL from the drop menu.

Good to know

Either option will work and which you choose is dependent on what the expected behaviour of the supports is on the site.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/67a3bc1c91c15f57c834e147/file-fFr8xJlICX.png)

  WC checkout page URL selection
 

## Troubleshooting

### Blank checkout/cart pages

If your cart or checkout pages are blank, make sure that the shortcodes [woocommerce_cart] and [woocommerce_checkout] have been included, respectively.

### Mismatched reward and product prices

If the prices at the checkout do not match the reward level prices listed on the project page, review the alignment the product variables and reward levels (step 8 of Creating WC Products, above)

IgnitionDeck does not provide support for WooCommerce. For help with WooCommerce in general, please refer to WooCommerce’s Documentation.

## Tips and Tricks

### Hiding reward products from the shop

Hiding reward products so they do not appear in the WC shop as normal products require two steps to hide them.

Useful resource: WooCommerce documenation on hiding products



---
**Source:** [https://docs.ignitiondeck.com/article/133-woocommerce-ignitiondeck](https://docs.ignitiondeck.com/article/133-woocommerce-ignitiondeck)
