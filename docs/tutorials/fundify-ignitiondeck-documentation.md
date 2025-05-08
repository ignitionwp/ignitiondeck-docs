# Fundify - IgnitionDeck Documentation

# Fundify

[](javascript:window.print())
#### Before you Install the Fundify Theme

To install this theme you must have a working version of WordPress and the IgnitionDeck Crowdfunding plugins already installed, registered, and set up.

### Installation

Download the Fundify Theme from your IgnitionDeck Dashboard.  There are two ways to install a WordPress theme:

WordPress Upload: Navigate to Appearance > Themes > Add New > Upload Theme. Click the Choose File button, select the fundify.zip file from your computer and click the Install Now button.  Once the theme package has been uploaded, WordPress will prompt you to activate the theme.

FTP Upload: Unzip the fundify.zip package. Using your FTP program, upload the resulting theme folder to your wedsite’s /wp-content/themes/ directory.  Then log into your WordPress Dashboard, navigate to Appearance > Themes and activate Fundify.

For more information on using WordPress themes, see WordPress.org’s Documentation.

### Create a Featured Project Type

To make use of the Fundify’s ‘Staff Picks’ functionality, create a Project Type with the slug  ‘featured’ by going to the Projects > Project Type screen.

Featured Type name and description can be anything you want, as long as the slug is set correctly to ‘featured.’

### Create Pages with Correct Page Templates

When creating each new page, set the page template as follows in the’ ‘Page Attributes’ area of the page’s edit screen.

NOTE: We recommend using the popular Contact Form 7 Plugin for your form builder, but there are many other options.  For instructions on how to build a contact form with Contact Form 7, see their documentation.

### Set Your Home Page in Settings > Reading

Navigate to Settings > Reading.  In the “Front page displays” section, check the box for “a static page.” For “Front page,” select the page “Home” (created in previous step). For “Posts page,” select “Blog.”

### Customize Your Header Logo/Title

Fundify’s Header can be set to use a graphical logo, or to display your site’s title (controlled in Settings > General)

Navigate to Appearance > Header. On this screen, you can enable/disable your header’s logo/image and title text, upload a logo/image, and select the header text color (if the Header Text checkbox is checked).

### Create Two Menus in Appearance > Menus and Assign to Menu Locations

Fundify has two Menu Locations: Primary Left and Primary Right.  They appear to the left and right of the site’s Header Logo/Text in desktop mode, but in responsive mode, they stack to become one continuous menu. In responsive mode, the Primary Left Menu appears above the Primary Right Menu.

Go to Appearance > Menus. Create your two menus and assign them to the “Primary Left Menu” and “Primary Right Menu” locations.

While you are free to use Fundify’s menus however you want, the following are some items we suggest adding to your menus.

Left:

Right:

NOTE: WordPress’ Menu Screen does not show all available content/link types by default.  For instance, if you wish to add Project Categories to your menus, you will need to use the Screen Options to un-hide Project Categories from your Menus Screen.

For more information on how to use menus in WordPress, please refer to WordPress.org’s documentation.

### Customize Your Fundify Crowdfunding Site

We’ve included a number of options in the Appearance > Customize panel of your WordPress installation that will allow you to make your Fundify site unique.

### Customize Your Site’s Footer

The Fundify Theme has three columns which can be populated with WordPress “Widgets.” When no widgets are added to the three Footer Column widget areas, some default, place-holder widgets are displayed instead. In Appearance > Widgets, drag widgets into “Footer Column 1,” Footer Column 2,” and “Footer Column 3,” to customize the content of your footer.  If you need help with how widgets in WordPress work, see WordPress.org’s Documentation on Widgets.

### Customize the Inner Page Headers

The inside pages have a randomly selected texture (4 available) that is applied when the page loads. This can be overridden using CSS (inserted into the Appearance > Customize > Additional CSS) to set set all inner headers with the same colour or image, or each option can be set with their own colour or image to be displayed randomly.

Example CSS of setting all inner headers with the same colour:

```
/* CHANGE INNER HEADERS TO SOLID COLOUR */
.title.pattern-1, 
.title.pattern-2,
.title.pattern-3,
.title.pattern-4 {
	background: #FFFFFF; /* ENTER HEXIDECIMAL OR RGBA VALUE */
}
```

Example CSS of setting all inner headers with the same image:

```
/* CHANGE INNER HEADERS TO SAME IMAGE */
.title.pattern-1, 
.title.pattern-2,
.title.pattern-3,
.title.pattern-4 {
	background: url(../uploads/year/mo/image-name.jpg);
}
```

Example CSS of setting each inner header with a unique image to be loaded randomly:

```
/* CHANGE EACH INNER HEADER TO UNIQUE IMAGE */
.title.pattern-1 {
	background: url(../uploads/year/mo/image-name1.jpg);
}
.title.pattern-2 {
	background: url(../uploads/year/mo/image-name2.jpg);
}
.title.pattern-3 {
	background: url(../uploads/year/mo/image-name3.jpg);
}
.title.pattern-4 {
	background: url(../uploads/year/mo/image-name4.jpg);
}
```

Images will need to be uploaded to the media gallery or to an external source to be linked to. It is not recommended to replace the image directly within the theme's files as these can be replaced with a theme update.



---
**Source:** [https://docs.ignitiondeck.com/article/41-fundify](https://docs.ignitiondeck.com/article/41-fundify)
