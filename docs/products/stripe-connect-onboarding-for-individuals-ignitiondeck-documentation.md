# Stripe Connect Onboarding for Individuals - IgnitionDeck Documentation

# Stripe Connect Onboarding for Individuals

[](javascript:window.print())
In the increasingly common scenario, crowdfunding platforms are being used for raising funds for personal causes such as medical and/or life expenses, versus the traditional backing for a product or business launch. As such, onboarding with Stripe, which considers credit card payments as being part the realm of business entities, becomes a bit challenging for end users that aren't registered businesses or non-profit organizations.

To this end, the following code snippet can be used to set some defaults on the onboarding process toward an "Individual / sole proprietor" business type instead of a "company" or "non-profit" business type. The code snippet can be added to the site's functions.php file or by using a code snippet plugin to inject custom PHP and other scripts.

Proceed at your own risk.

This code snippet is appropriate for US-based businesses. Identity requirements for other countries may not be compatible.

### Sample Code:

```
<?php
/**
 * Modify Stripe Connect URL parameters to set the business type as a sole proprietor, 
 * and add additional fields for creator profile, product description, and physical product.
 *
 * This function hooks into the 'md_sc_url_redirect_params' filter to add the 'stripe_user[business_type]'
 * parameter with the value 'sole_prop', which indicates that the user is an individual (sole proprietor).
 *
 * @param array $params The existing array of URL parameters for Stripe Connect.
 * @return array Modified array of URL parameters with additional fields set.
 */
function my_custom_stripe_connect_params( $params ) {
    // Set business type as a sole proprietor
    $params['stripe_user[business_type]'] = 'sole_prop';

    // Set creator profile URL
    $current_user_id = get_current_user_id();
    $site_url = get_site_url();
    $params['stripe_user[url]'] = esc_url( "{$site_url}/dashboard/?creator_profile={$current_user_id}" );

    // Set product description for the creator in a crowdfunding platform
    $params['stripe_user[product_description]'] = __( 'An individual providing creative and impactful projects for themselves and their community through an ecommerce platform.', 'memberdeck' );

    // Set physical product to false
    $params['stripe_user[physical_product]'] = 'false';

    return $params;
}
// Path: idcommerce/classes/modules/stripecheckout/class-stripecheckout.php
add_filter( 'md_sc_url_redirect_params', 'my_custom_stripe_connect_params' );
```

The code snippet will set the required onboarding fields of Business Name and Website address to the crowdfunding platform's Site Title and the creator's profile URL .

The code snippet provides a business description (product_description ) of the business entity. This can be edited to better reflect the site's purpose.

The default value is:

```
An individual providing creative and impactful projects for themselves and their community through an ecommerce platform.
```

Warning: Despite Stripe's documented support for crowdfunding, the use of terms such as "crowdfunding" and "fundraising" has caused issues for account verification/activation in the past. Using terminology around ecommerce transactions and marketplaces is best.

The snippet also defaults to no physical products. Change this to true if there will be physical rewards offered by the project creators.

```
$params['stripe_user[physical_product]'] = 'false';
```



---
**Source:** [https://docs.ignitiondeck.com/article/177-stripe-onboarding-for-individuals](https://docs.ignitiondeck.com/article/177-stripe-onboarding-for-individuals)
