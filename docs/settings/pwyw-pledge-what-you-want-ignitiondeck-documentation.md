# PWYW (Pledge What You Want) - IgnitionDeck Documentation

# PWYW (Pledge What You Want)

[](javascript:window.print())
IgnitionDeck’s Pledge What You Want (PWYW) functionality allows supporters of a project to pay any amount they want at checkout. Levels of project support are set by the project’s creator, and when supporters choose a level of support and continue to the payment screen, they can change the default value to anything they want, as long as it at least meets the level’s set value.

#### PWYW in IgnitionDeck Commerce (IDC)

In IgnitionDeck Commerce, PWYW is enabled for all Project Levels by default.

Before finalizing their contribution, supporters can change the default payment amount for the level of  support they have selected to any larger value they wish. This is why when using IDC as your commerce platform, in the project settings screen, there is no PWYW option.

STRIPE USERS: PWYW with Recurring Payments turned on is not possible with Stripe.

If a customer changes their payment amount, Stripe will no longer be available as a payment gateway, so you will want to have at least one additional payment gateway activated. This is due to the fact that Stripe handles recurring payments based on a unique “Stripe Plan Name,” which has a set price assigned to it.

PWYW is automatically enabled for projects when using IDC and all projects are level-based.

#### PWYW-Only with “no levels”

If you wish to have a PWYW-only campaign, without apparent support levels, the way to do this is to only have one level. Create a single Project Reward Level for your project and leave the Level Price field empty or set a minimum donation amount (i.e. 1).



---
**Source:** [https://docs.ignitiondeck.com/article/143-pwyw-pledge-what-you-want](https://docs.ignitiondeck.com/article/143-pwyw-pledge-what-you-want)
