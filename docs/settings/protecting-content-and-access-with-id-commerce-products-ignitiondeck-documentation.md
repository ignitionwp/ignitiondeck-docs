# Protecting Content and Access with ID Commerce Products - IgnitionDeck Documentation

# Protecting Content and Access with ID Commerce Products

[](javascript:window.print())
Controlling how visitors interact with your site can be a challenging process. While many mainstream crowdfunding platforms provide an all-access pass, it is not necessarily the right solution for everyone. The "one size" approach doesn't really "fit all".

Here are a few scenarios where different control might apply to your situation:

Controlling access to content, projects, and even creator functionality can all be easily accomplished by using the ID Commerce products assigned to a user’s account.

Let’s break down the process of how this can be accomplished.

Tutorial Table of Contents

## Define a Registration Product

In all scenarios, the starting place is to assign a free product to the user account on registration. This will be assigned automatically when any new user account is created on your site.

While technically this is not needed for scenario #3 and #4, it is a good way to ensure there is always a method to control access on user accounts should the user bypass the preferred onboarding path.

To begin, create the product to be assigned to the new account upon successful registration.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d72ccfceae9468399d39a4/file-6Kmz2ZI2OG.jpg)

  Create a Registration Product
 

Next, the product needs to be assigned to the registration process.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d72cdeceae9468399d39a5/file-KYwrAcTxBG.jpg)

  Assign the Registration Product
 

Once this process has been completed, whenever a user registers on the site, they will appear on the IDC » Members screen with the "Registration" product assigned to them. This is a vital step in managing users on your site and controlling their access and permissions.

Did you know: automatically assigning a product on the registration also allows you to add the user to your MailChimp mailing list?

## Controlling Access with Assigned ID Products

### Verified Backers and/or Creators

Congratulations! A user has successfully registered on your site. Now you can direct them to submit any additional requirements to gain further access to the site. The simplest method to accomplish this is to use a third-party form builder or an offsite application if legal or financial verification is required.

To assign additional access or permissions to their user account, you will need a second ID product to update their current account status.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d72da2dd5b956281ae41cc/file-C7ahov0h03.jpg)

  Create a Creator Permission product
 

### Setting Creator Permissions

Creator Permissions requires an IgnitionDeck Enterprise license

Next, the product needs to be assigned to control user permissions to access the project creator functionality.

The logged in user with the Creator Permission assigned to their account will now have access to the Project Creator tools on their dashboard.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d72e1b15d0b8223306329e/file-0PRLhdgyS8.jpg)

  Assign Creator Permissions in IDC » General Settings » Project Submission Privileges
 

### Displaying Projects to Verified Backers

Displaying projects to verified backers is a simple process that utilizes WordPress’s core “Protect Post” functionality. To protect pages and posts from public view and only display them to the select users:

Projects will now be hidden from view for the general public and for any logged-in users who do not have the Verified product assigned to their account.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d7362544628317ef9030c0/file-TYqKoZcjrI.jpg)

  Display projects to verified Backers
 

#### Updating User Accounts

But wait! Now that the criteria have been set to protect these areas of the site, how are these Verified and Creator Permission products assigned to the users' accounts? Since we initially set up a Registration product that was automatically assigned when the user signed up on the site, they will now appear in the IDC » Members table.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d7366a15d0b822330632a3/file-CkpMdcBrFw.jpg)

  IDC » Members table showing a Registration product assigned to a user account
 

To update the account to include the new permissions:

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d7367944628317ef9030c2/file-nOBh8AtYQO.jpg)

  Edit the user's account to add or remove products
 

Multiple products can be added in a single session with this method. If permissions need to be revoked, the ID product can also be removed this way. Additionally, after saving the initial update to the user’s account, you can set expiry dates if you wish to grant access for a limited time.

## Controlling Access with Paid Products

Perhaps you are a creative and want to offer exclusive access to your content, or your fee strategy calls for charging a nominal fee to start a crowdfunding project instead of charging per transaction fees. Having your users complete a transaction—either one time or recurring—and then using those products to control their access is the way to go.

In the previous section, we set up a registration product. This isn't strictly necessary in the following examples; however, it does provide a failsafe in case someone registers on the site without completing a transaction.

### Creating a Paid Product

Setting up the paid product is very similar to the previously created "Verified" and "Creator Permission" products, but this time there will be a price associated with it, and possibly also an expiration date. Essentially, this is creating a paid "membership" on the site. A checkout page will also need to be created to direct the user to.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d73ed444628317ef9030ce/file-rKrGbPrjfe.jpg)

  Creating a paid product for controlling access to project creation features
 

If the option to create a checkout page was selected, the page will appear under the regular WP Pages which you can then add to the site’s navigation, widgets, etc.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d73bf144628317ef9030c9/file-ULadWHHTHU.jpg)

  The auto-created checkout page location
 

If a checkout page was not selected, then the shortcode that was generated when the product was created will need to be entered onto a page, post, or widget manually to create the checkout option for the user to interact with.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d73c63811a2434cb6d2eb8/file-LWmsZC09oF.jpg)

  The paid product checkout shortcode
 

### Displaying Content to Paying Users

Just like the previous section where we discussed protecting Projects from view of non-verified potential Backers, likewise content such as pages and posts can be protected and only made viewable by the subscribing user.

In this case, a Content Subscriber product, which is an ongoing monthly recurring subscription, has been created.*

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d73bdddd5b956281ae41de/file-gwrIoUikz2.jpg)

  Subscription product for access to protected content
 

This product can then be set as the required permission for a logged in user to own in order to view the protected content.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d73d13e6b2356def908bf1/file-54lsHLK2YR.jpg)

  Assigning the required product to access the protected content
 

### Protecting Downloads to Paying Users

The same subscription product can also be used to protect downloadable content that may be offered to supporters / patrons by assigning it a requirement on the user account. The downloadable content will only appear on the user's account dashboard if they have a valid purchase.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/66d748c4811a2434cb6d2ec3/file-2qZ89QGz8T.jpg)

  Subscription product assigned to protect downloadable content
 

* Subscription support is dependent on payment gateway selection.



---
**Source:** [https://docs.ignitiondeck.com/article/174-protecting-content-access-with-idc-products](https://docs.ignitiondeck.com/article/174-protecting-content-access-with-idc-products)
