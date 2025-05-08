# IgnitionDeck API - IgnitionDeck Documentation

# IgnitionDeck API

[](javascript:window.print())
IgnitionDeck is an extensible WordPress plugin that offers a variety of WordPress hooks and WordPress filters in order to make it easy for 3rd party developers to build and deploy extensions and themes.

The following comprises a list of hooks and filters as of IgnitionDeck 1.0 and should be considered a work in progress.

## Modules

IgnitionDeck Module API

## Filters

id_submenu_tab

This filter can be used to modify the tabs in the IgnitionDeck settings header. Pass a content through this variable to add additional tabs.

id_purchaseform_extrafields

This filter can be used to add additional fields to the purchase form after the standard IgnitionDeck purchase form fields.

id_purchase_form($purchase_form, $project_id)

Filters the purchase form returned via shortcode. Also returns project id.

id_shortcode_list

This filter enables modification of the shortcode listing on posts, pages, and projects.

id_project_content ($content, $product_id)

Filter the content returned by the project content shortcodes.

id_project_complete ($content, $product_id)

Filter the content returned by the complete project shortcode.

id_pay_choices($pay_choices, $project_id)

Append or remove pay choice buttons on purchase form.

id_postmeta_boxes($meta_boxes)

Filter the IgnitionDeck CPT meta array.

## Actions

id_after_install

Fires after IgnitionDeck is activated upon end of activation script.

id_set_defaults

Fires after IgnitionDeck defaults are set upon end of script.

id_payment_success

Perform actions after payment is successfully processed.

id_payment_return

Perform actions after buyer is returned via Paypal.

id_submenu

Add additional items to the IgnitionDeck settings menu in the WordPress admin.

id_paysettings_links

Add additional links in the IgnitionDeck payment settings menu.

id_faqs

Add items to appear inside of the IgnitionDeck FAQ box.

id_updates

Add items to appear inside of the IgnitionDeck Updates box.

id_create_project

Perform actions after new project has been created.

id_update_project

Perform actions after project has been saved.

id_content_before ($product_id)

Add content before project content is printed.

id_content_after ($product_id)

Append content to end of project content.

id_widget_before ($product_id)

Add content before widget content is printed.

id_widget_after ($product_id)

Add content to end of widget display.

id_mini_widget_before ($product_id)

Add content before mini widget content is printed.

id_mini_widget_after ($product_id)

Add content to end of mini widget display.

id_after_level

Runs after level before the level-binding class is closed

id_order_update($order_id)

Fires any time an order is manually updated via the IgnitionDeck admin.

id_pre_order_delete($order_id)

Runs before the order is deleted from the pay info table.

id_order_delete($order_id)

Runs after the order has been deleted from the database.

## Variables

### Javascript

id_ajaxurl

Represents the WordPress Ajax url. This variable is available globally on both the front-end and administration sections.

id_siteurl

Represents your site’s URL. This variable is available globally on both the front-end and administration sections.

data-currency

Available on the purchase form, form id ‘form-pay’ and stores the default currency code value (USD, EUR, etc). Helpful when developing gateways requiring on the fly translation.

data-postid

Available on the purchase form, form id ‘form-pay’ and stores the current post ID.

data-projectid

Available on the purchase form, form id ‘form-pay’ and stores the current project ID.

data-projectType

Available on the purchase form, form id ‘form-pay’ and stores the project type (level-based, pwyw).

trigger(‘levelChange’)

This jQuery trigger fires every time a new level is selected in the level dropdown. Returns new price.

trigger(‘validate’)

This jQuery trigger fires after the purchase button is clicked and form is validated. Returns true if true, false if false.



---
**Source:** [https://docs.ignitiondeck.com/article/100-ignitiondeck-api](https://docs.ignitiondeck.com/article/100-ignitiondeck-api)
