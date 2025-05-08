# Use Cases for Controlling Project Creator Permissions - IgnitionDeck Documentation

# Use Cases for Controlling Project Creator Permissions

[](javascript:window.print())
In most cases, permission to create projects is made to allow all users that sign up on the site; however, that isn't a solution that works for every site. The following are examples of how permissions can be set to only allow specific users that have met a requirement.

#### Scenario 1: Requiring a purchase to submit projects

Chris runs a crowdfunding portal to help people start fitness groups in their home area. They want to let individual training coaches crowdfund the money necessary to begin a local fitness class. However, they only want campaigns started by people who have purchased access to their teacher training program.

Chris has already created a Product in Commerce » Products called “Teacher training materials”. Videos are attached in a series of Downloads, so that owners of the Product have easy access to the videos from their user dashboard. They copy the checkout shortcode that appears when selecting the Product in the Product settings. After creating a new page, they place the shortcode into the text editor, and publishes it. They decide to add some text to the page, providing purchase information about the product, and additionally creates a link to the page on the main menu, entitled “Become a Trainer”. Now, they have a page that anyone can visit to directly purchase the training course.

With that set up, Chris looks for the Project Submission Privileges section under IDC’s general settings located just below where the license key and email address were entered for the receipts. They change the privilege type to “Specific Members” and checks the box for the “Teacher training materials” IDC Product made earlier, then clicks the Save button.

Now the setup is complete, and they're ready to do business! Any users wishing to raise funds for their own fitness class must first visit Chris' purchase page, and buy access to the training course. Only then will they be able to see the Projects tab on the user dashboard, where they can submit their own crowdfunding campaigns.

#### Scenario 2: Limiting project submission to subscribers

At the last minute, Chris has decided that a video course doesn’t provide sufficient training. In order to safeguard the reputation of their business, any active trainers are required to receive ongoing, personal coaching from them on a weekly basis. They wish to charge users $50 every week in exchange for the 1-on-1 training sessions.

To enact the new plan, they create a new IDC Product and calls it “Ongoing Education”. Chris changes the license type of the Product to “recurring”, and selects a week-long period frequency. They've already set up a weekly recurring subscription plan in their Stripe account, so now all they have to do is add the name of the Stripe plan to the IDC Product and hit Save.

Then, returning to Project Submission Privileges, they uncheck the old “Teacher training materials” and selects the new “Ongoing Education” product, making sure to save afterwards.

They make the IDC Product available for direct purchase on a page just as with the previous product. But now, users will subscribe to the Stripe payment plan, and be charged $50 weekly. This will continue unless and until a person decides to cancel their subscription. For as long as a user is subscribed to Chris' “Ongoing Education” Product, they will be able to create and manage their own crowdfunding campaigns on the site. If they cancel their subscription at any point, their privileges will be revoked.

#### Scenario 3: Using multiple payment options

Chris' analyst informs them that their target market is much more likely to subscribe to a service if customers can first make a single, regular purchase. They determines that they're losing business by only offering a subscription.

Chris decides to grant crowdfund campaign rights to anyone who purchases either the video training course OR the subscription plan for ongoing training. Under Project Submission Privilege settings, with Specific Users selected, they ensure that the options for both of the products – “Teacher training materials” as well as “Ongoing Education” are selected.

Any user who purchases either product will now be able to run their own crowdfunding campaign. Chris has their attorney help them craft an updated Terms of Service for the web site, to make sure they won’t be held liable for any mistakes made by a customer.

But Chris isn’t quite finished – they want some way to contact those who made a single purchase, but haven’t yet subscribed to his ongoing training. They decide to sign up for a MailChimp account, create a new mailing list inside of it, and enable MailChimp integration inside of IDC.

Now they know that all new customers will be added to his mailing list. Using the custom merge tags provided by ID Commerce, Chris can now send emails only to customers who went for the one-time purchase of the training videos. Over a period of time, they are able to send informative, content-rich newsletters that also showcase the benefits of ongoing training. With their customers regularly exposed to their expertise, many decide to sign up for their personal coaching sessions.



---
**Source:** [https://docs.ignitiondeck.com/article/200-use-cases-control-creator-permissions](https://docs.ignitiondeck.com/article/200-use-cases-control-creator-permissions)
