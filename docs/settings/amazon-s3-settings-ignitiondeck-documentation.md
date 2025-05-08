# Amazon S3 Settings - IgnitionDeck Documentation

# Amazon S3 Settings

[](javascript:window.print())
## Using Amazon S3 for Downloads

Amazon S3 provides an excellent means for ID Commerce to provide fast, secure downloads to your users. S3 provides several gigabytes in their free usage tier, and scales into very reasonably priced storage as your business grows. This removes the burden of storage and bandwidth off your main site in addition to giving you complete control over how your downloads are accessed. Due to these features, we highly recommend using Amazon S3 in conjunction with IDC.

## Enabling S3

The first step in using S3 is to enable it under ID Commerce’s general settings. Check the box next to “Enable Amazon S3” and click Save. This should introduce a new menu item for ID Commerce called “S3 Settings”. If you do not see this menu immediately, you may need to refresh your admin screen.

## Configuring IDC to work with Amazon S3

Clicking on “S3 Settings” lets you configure IDC to access files hosted on S3. ID Commerce needs two things to access your S3 account – a working access key, and the name of your S3 bucket.

If you haven’t already, you’ll need to sign up for an account with Amazon’s web services.

To create an access key for your AWS account, click the main user menu in AWS (it displays your first name) and select “Security Credentials”. The resulting screen will present you with several options, including an expandable menu for Access Keys. From here, select “Create New Access Key”. Make sure to save the Access Key ID and Secret Access Key in a secure location.

If you don’t already have a bucket, you can create one inside of AWS S3. Full documentation for S3 can be found on the AWS web site.

Once you save your access key ID, secret access key, and bucket name in IDC’s S3 Settings, IDC should be ready to serve secure downloads.

## Setting Up a Download

Even with general access to your S3 account granted, you must specify which downloads will come from your S3 hosting vs a regular web link. This gives you the flexibility to mix and match download sources if desired.

You can configure an individual download for S3 hosting from the Download Settings box under ID Commerce’s main settings. Simply check the “Host on S3” button, and make sure the download link is set to the filename only (eg if you’ve uploaded “coolstuff.zip” to your S3 drive, then the download link should likewise read “coolstuff.zip”). Click Create/Update and your download should be ready to go!



---
**Source:** [https://docs.ignitiondeck.com/article/132-ignitiondeck-commerce-amazon-s3](https://docs.ignitiondeck.com/article/132-ignitiondeck-commerce-amazon-s3)
