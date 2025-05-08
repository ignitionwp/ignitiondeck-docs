# Create Your Own 500 Child Theme - IgnitionDeck Documentation

# Create Your Own 500 Child Theme

[](javascript:window.print())
Building child themes for the Theme 500 crowdfunding framework is very straight forward. Use the following steps to get started, and if you have any questions, use the forums to get in touch. We’ll be happy to help.

Initial Requirements

Getting Started

Congratulations, you’ve created a Theme 500 child theme!

Advanced

The Theme 500 Framework uses the WordPress function get_template_part() to retrieve template files. For example, the get_template_part(‘project-featured’) function retrieves the template for the featured area in the Classic child theme.

To remove this portion, simply delete that line, or better yet, replace it with your own function.

To create your own version of the modified section, simply create a file called project-featured.php and save it in your child theme directory. Now, this will automatically overwrite the original template. Alternatively, you can rename the function and create a new file matching said name (e.g. get_template_part(‘my-template’) with a file named my-template.php ).

If you wish to add functions to the Theme 500 framework, create your own functions.php and include those functions. These will automatically extend the framework functions.



---
**Source:** [https://docs.ignitiondeck.com/article/48-create-your-own-500-child-theme](https://docs.ignitiondeck.com/article/48-create-your-own-500-child-theme)
