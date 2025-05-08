# Better Sharing & IgnitionDeck Addon - IgnitionDeck Documentation

# Better Sharing & IgnitionDeck Addon

[](javascript:window.print())

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/655f79c479594218b99bbef6/file-R0WoNgY6kA.png)

The Better Sharing by CloudSponge IgnitionDeck Addon allows you to leverage that plugin's social media and email sharing tools to promote crowdfunding projects to social media platforms and your email contact list.

The Better Sharing IgnitionDeck Addon would be an alterative option to the ID Social module.

The Better Sharing IgnitionDeck integration automatically inserts the sharing buttons in the three most strategic locations for sharing crowdfunding projects and prepopulates the share modal with pertinent messaging. The locations are as follows:

## Enabling the integration is simple as 1-2-3.

## Customizing the Sharing Options

Better Sharing automatically creates a sharing block and email template that can be further customized.

### The Block

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/65ef2a42204f3e7caeb738df/file-v6Jner5Z1c.png)

  IgnitionDeck Sharing Block
 

The sharing Block is populated with four icons:

These options can be disabled in the corresponding tabs under Better Sharing » Blocks.

In the Main tab, there are the options to adjust the layout of the sharing icons under the Style section. For best presentation with the IgnitionDeck projects, the Inline style is recommended.

The URL to share defaults to Page/Post URL. This will automatically use the project's URL for sharing in all user cases and it is recommended that this default is not changed.

A shortcode is also provided for inserting the sharing options to other pages

### The Email Template

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/65ef2aa59fe3115eda3933fc/file-V24FrZyxkV.png)

  IgnitionDeck Sharing Email template
 

The email template can be edited to accomodate your own custom messaging and has a set variables that are populated from the IgnitionDeck integration automatically.

*recipient details are accessible via an upgrade to the CloudSponge Contact Picker

For further instructions on how to customize the block and email template options, please see the Better Sharing documentation.

## Styling the Better Sharing icons

Better Sharing provides CSS classes for each of the social sharing buttons within the email and blocks that can be used to style the buttons with the site's branding. The general CSS classes are:

Example CSS:

```
/* STYLE BSWP BTN TO THEME */
/* BSWP BTN RESTING STATE */
 .bswp-twitter-btn, 
 .bswp-facebook-btn, 
 .bswp-link-btn, 
 .bswp-email-btn {
	background-color: #1E6CBD; /* may need to add !important to rule */
 }

/* BSWP BTN HOVER STATE */
 .bswp-twitter-btn:hover,
 .bswp-facebook-btn:hover,
 .bswp-link-btn:hover,
 .bswp-email-btn:hover {
	background-color: #049B8C; /* may need to add !important to rule */
 }
```

If there are other instances of Better Sharing in use on the site, it is possible to target only those buttons within the crowdfunding projects using the Layout Wrapper CSS Class automatically assigned when the Sharing Blocks are generated.

Example of targeted CSS:

```
/* STYLE BSWP BTN TO THEME FOR CROWDFUNDING BLOCK ### ONLY */
/* BSWP BTN RESTING STATE */
 .bswp-### a {
	background-color: #1E6CBD; /* may need to add !important to rule */
 }

/* BSWP BTN HOVER STATE */
 .bswp-### a:hover {
	background-color: #049B8C; /* may need to add !important to rule */
 }
```



---
**Source:** [https://docs.ignitiondeck.com/article/165-ignitiondeck-better-sharing](https://docs.ignitiondeck.com/article/165-ignitiondeck-better-sharing)
