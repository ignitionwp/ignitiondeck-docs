# IgnitionDeck Shortcodes - IgnitionDeck Documentation

# IgnitionDeck Shortcodes

[](javascript:window.print())
Product=”#’ is the project number, which is determined by the order in which you added to projects. You can find this number in the IgnitionDeck Shortcodes sidebar in your Posts, Pages and Projects admin sections.

Project Content Template: [project_page_content product="1"]

Full Project Template: [project_page_complete product="1" deck="#"]—optional: deck="#" enter the number of the custom ID deck you wish to use for display

Display Templates Separately [project_page_content_left product="1"]  [project_page_widget product="1" deck="#"] [project_mini_widget product="1" deck="#"]—optional: deck="#" enter the number of the custom ID deck you wish to use for display

Display Project Grid: [project_grid columns="#" max="#" category="#" deck="#" orderby="days_left" order="ASC" author="admin"] Required Attributes – columns: How many projects wide.  – max: The number of projects you want to show in the grid. Using -1 will show all filtered projects (good to set this to a multiple of the columns).  Optional Attributes – category: Enter the category ID of the ‘Project Category’ taxonomy if you only want to show projects from certain categories.  – deck: Enter the ID number of the custom deck you wish to use for display.  – orderby: You can set what you want the projects to order by. Possible values are ‘days_left’, ‘percent_raised’, ‘funds_raised’, ‘rand’ (random), ‘title’, ‘date’ (default).  – order: You can set the orderby to order ascending or descending using these values: ‘ASC’ or ‘DESC’.  – author: Enter the username of the author’s post you wish to display. Only one author is allowed.

Display Project Name [project_name product="1"]

Display Project Thumbnail: [project_image product="1" image="1"]

Display Project Long Description: [project_long_desc product="1"]

Display Project Video [project_video product="1"]

Display Percentage Bar: [project_percentage_bar product="1"]

Display Short Description: [project_short_desc product="1"]

Display Goal Amount: [project_goal product="1"]

Display Total Number of Pledges: [project_users product="1"]

Display Fundraising Total: [project_pledged product="1"]

Display Days Left: [project_daystogo product="1"]

Display Project End Date: [project_end product="1"]

Display Project FAQ: [project_faq product="1"]

Display Project Updates: [project_updates product="1"]

Display Product Button (Crowdfunding is not supported): [idc_button product="1" text="Sample button text"]

Note: You can build these shortcodes directly into a WordPress Theme page template, by using the WordPress function do_shortcode(). Get creative!

Learn more about it here: http://codex.wordpress.org/Function_Reference/do_shortcode



---
**Source:** [https://docs.ignitiondeck.com/article/85-ignitiondeck-shortcodes](https://docs.ignitiondeck.com/article/85-ignitiondeck-shortcodes)
