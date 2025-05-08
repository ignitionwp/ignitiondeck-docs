# Default Pages and IDC Account Links - IgnitionDeck Documentation

# Default Pages and IDC Account Links

[](javascript:window.print())
IgnitionDeck requires a few default pages to handle user registration, the user account dashboard, and the checkout.

Important Note: If you are using WooCommerce as your commerce platform, these settings do not apply to your site. Please see WooCommerce's documentation on setting up their default pages and account links: https://woocommerce.com/document/woocommerce-pages/

## ID Commerce Default Pages

Before digging into the rest of the platform set up, a few default pages should be set up which you will be directing your customer to as they interact with projects on your site.

### Checkout page

The checkout page will be used as your default for all project transactions. Create a page using the default WP editor and include the shortcode:

```
[idc_checkout]
```

### Dashboard page

The dashboard page will be the page that project supporters and project creators* will go to for their account profile, copies of invoices, project interaction, and project management and payment account connection*. Create a page using the default WP editor and include the shortcode:

```
[idc_dashboard]
```

* IgnitionDeck Enterprise only

Important: Do not create either of the above pages with a drag and drop page editor as these can interfere with the correct shortcode functionality.

### Membership Registration page

This page is automatically created when you install and activate the plugins and is essential to the PayPal payment gateway. It is a placeholder page for the payment gateway funcationality. While it is not necessary to create this page manually, do not delete it or modify it in any way if you intend to use the PayPal payment gateway. This page should not be included as part of the site's navigation.

## IDC Member Account Links

How to Add IDC Account Links for Login, Registration, and Create Project to your site.

Important: The ID Commerce plugin must be activated before you proceed.

If you are using one of our 500 Framework themes, this process is simpler. See below.

#### Automatic Method:

If you’re not using one of our 500 Framework themes, you need to add IDC Account Links to your site’s navigation menu.

To do this automatically, use the tool we’ve included in Appearance > Customize > IDC Account Links. (See image to the right)

This will automatically add the IDC Account Links to your navigation menu. Just check the box for any menu you want them added to.

#### Manual Method:

If you would like to manually add IDC Account Links anywhere on your site, they are as follows

#### 500 Framework Method:

If you’re using one of our 500 Framework Themes, simply set a custom menu to the ‘Main Menu’ menu location in Appearance > Menus > Menu Locations. The Create Account and Login buttons will be placed on the right side of your menu. When a user is logged into your site, the two buttons are replaced by a single ‘My Account’ button, which goes directly to the Member Dashboard.



---
**Source:** [https://docs.ignitiondeck.com/article/131-default-pages-and-idc-account-links](https://docs.ignitiondeck.com/article/131-default-pages-and-idc-account-links)
