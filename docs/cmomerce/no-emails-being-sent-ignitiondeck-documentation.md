# No emails being sent - IgnitionDeck Documentation

# No emails being sent

[](javascript:window.print())
Transactional emails are an important part of operating not only the website but the ecommerce portion of the crowdfunding operation. Transactional emails include registration confirmations, password reset requests, receipts, and other automated email notifications.

### Is the site sending any emails at all?

Test to determine if the site is sending any email by logging out and requesting a WP password reset email. Don't complete the password reset process—we just need to see if the email is sent. Don't forget to check the Spam folder.

Is the email received at the entered address?

If transactional emails are not available thorugh the hosting provider, the WP SMTP Mail plugin can be used with a 3rd party provider such as SendGrid or Gmail to send transactional emails.

### My site sends WP emails but not IgnitionDeck ones

If WooCommerce is being used with IgnitionDeck, troubleshooting of account and ecommerce emails must be done within WooCommerce as that will be the plugin responsible for generating those emails: WC Email Troubleshooting guide.

Often times, the quickest method to resolve transactional email sending issues is to employ a transactional email plugin such as WP SMTP Mail*.

* We are not affiliated with WP SMTP Mail—we just really like the plugin.



---
**Source:** [https://docs.ignitiondeck.com/article/114-no-emails-being-sent](https://docs.ignitiondeck.com/article/114-no-emails-being-sent)
