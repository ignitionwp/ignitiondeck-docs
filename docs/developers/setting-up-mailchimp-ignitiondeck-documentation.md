# Setting up MailChimp - IgnitionDeck Documentation

# Setting up MailChimp

[](javascript:window.print())
## Mailchimp Integration

To enable automatic signups to your MailChimp newsletter, you’ll first need to navigate to IgnitionDeck Commerce’s general settings. Here, you’ll see the following box on the right side in CRM settings.

Your API keys are listed under your MailChimp Account Settings. From their account screen, click on Extras > API Keys. You may need to create a new key.

You can find your List ID by selecting the specific list you want to use in MailChimp’s Audience view, clicking on Settings, and then selecting List Names and Defaults. This should display the list ID right at the top.

Make sure the “Enable Mailchimp” checkbox is marked, and then click the Save button at the bottom of the CRM settings box.

## Custom Merge Tags

IgnitionDeck Commerce (IDC) also offers a set of powerful MailChimp merge tags that you can use to segment and customize your email lists. These tags are created and populated by IDC automatically any time a purchase is made, though you can also add them manually inside of MailChimp.

The tags used by IDC are:

*|LEVEL|*

This is populated by the most recent product name purchased by a customer. If they purchase a new product, it will overwrite the current value.

*|IDC_FREE|*

This is set to either YES or NO. It will update to NO if the customer purchases a paid product at any point.



---
**Source:** [https://docs.ignitiondeck.com/article/105-ignitiondeck-commerce-mailchimp-integration](https://docs.ignitiondeck.com/article/105-ignitiondeck-commerce-mailchimp-integration)
