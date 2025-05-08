# Custom User Account Links - IgnitionDeck Documentation

# Custom User Account Links

[](javascript:window.print())
For non-IgnitionDeck themes, the IDC Account Links (i.e. Create Account/My Account, Login/Logout) can be added to the designated main navigation menu using the option within the Appearance » Customize » IDC Account Links.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/6802826b1a5d437cf7d5097a/file-C7DEMmdmlq.png)

  Automatic method of adding IDC Account links
 

If you want to add these links to a widget or a custom Elementor Header, then the links must be created using the Custom Link option in Appearance » Menus, and CSS applied to display or hide the links according to the user's status (i.e. logged in vs. logged out).

### How it works

The CSS rules mentioned here using the WP user status and applied class of .logged-in to the body element to dynamically display or hide the appropriate links.

### Example of manually adding dynamic IDC Account links using the user status

Good to know

Before beginning these steps, click on the Screen Options tab at the top of the Appearance » Menus page and ensure that Custom Links under "Screen elements", and CSS Classes under "Show advanced menu properties" have been enabled.

```
/* HIDE LOGGED IN OPTIONS WHEN LOGGED OUT */
body:not(.logged-in) li.hide-loggedout {
	display: none;
}

/* HIDE LOGGED OUT OPTIONS WHEN LOGGED IN */
body.logged-in li.hide-loggedin {
    display: none;
}
```



---
**Source:** [https://docs.ignitiondeck.com/article/203-custom-user-account-links](https://docs.ignitiondeck.com/article/203-custom-user-account-links)
