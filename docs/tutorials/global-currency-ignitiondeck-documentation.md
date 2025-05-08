# Global Currency - IgnitionDeck Documentation

# Global Currency

[](javascript:window.print())
IgnitionDeck Commerce’s Global Currency setting changes your site’s display currency. This is especially useful if you want to take payments in a currency other than the currency you will actually receive from your payment gateway when orders are processed.

Currency conversion is handled by your payment gateway.  At the time of a transaction, your payment gateway will convert the purchase price (shown to the customer in the Global Currency you have set), to your payment gateway account’s currency amount.

For instance, if your Global Currency is set to USD, throughout your site, product prices, crowdfunding levels, and crowdfunding goals will be displayed as USD.  But if your payment gateway account is actually a EUR account, you will receive your funds according to the current exchange rate between Dollars and Euros.

The Global Currency setting is located at yoursite.com/wp-admin » IDC » IDC  (scroll down the page to Currency Settings found below the General Settings panel). This should be set the same as your payment gateway currency in IDC » Gateways.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/64b6ede5a9d61472afe08f50/file-vaabB3L6a3.png)
The Global Currency setting should match the currency for your payment gateway(s) in IDC » Gateways

NOTE: Changing your site’s Global Currency will not effect the amounts or currencies shown for past orders shown on the IDC > Orders screen or in the Member Dashboard’s Orders Tab.

## Using Custom Virtual Currencies/Credits as Your Site’s Global Currency

If you would like your site’s prices to be based primarily on a custom virtual currency (credits system), choose Virtual Currency from the Global Currency selector.  To learn how to configure your virtual currency, see the documentation page on Creating and Managing Credits in IDC.



---
**Source:** [https://docs.ignitiondeck.com/article/56-global-currency](https://docs.ignitiondeck.com/article/56-global-currency)
