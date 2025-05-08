# Projects | Organizing Projects with Categories - IgnitionDeck Documentation

# Projects | Organizing Projects with Categories

[](javascript:window.print())
Project Categories provide a convenient means for you to organize multiple projects hosted on your site. When one or more projects are assigned to a project category, you can then display groups of projects on a page via shortcode.

If you’re using one of our IgnitionDeck themes, the ability to sort available projects by category is already built into your site.

Please note: "Project Categories" and "Project Types" are distinct and separate from general WordPress "Categories" and "Tags" which are available for every post type. The WP "Categories" and "Tags" are not used with Projects.

🆕 As of IgnitionDeck Crowdfunding v. 2.2.1, the "Categories" and "Tags" will no longer be present in the menu. Only the applicable "Project Categories" and "Project Types" will be available.

![](https://d33v4339jhl8k0.cloudfront.net/docs/assets/5c47e765042863543ccc1e58/images/64ca8738eb931e0627da6f93/file-TtJIDjnXQE.png)

  Project Categories location
 

Let’s take a look at how to get project categories working.

## Step 1: Create a new project category

Underneath your Projects menu, select “Project Categories”. This will take you to the following screen:

Here, you can add a name and optional description for your new project category. Click “Add New Tag” and you should see your new category appear in the list to the right. You will be able to see how many projects are currently assigned to that category, and be able to edit the project category details any time you wish to make changes.

Tip: If you’re also an ID Commerce user, you can restrict access to categories based on IDC product ownership. When editing an existing project category, you’ll see an additional option called “Protect Category”. If you select “Yes”, you’ll then be able to assign permissions to specific IDC products, allowing or disallowing access to entire project categories based on membership level.

## Step 2: Assign a project to the new project category

From the Projects view, you can edit a specific project and look for the Project Categories box in the right-hand column. Type in the name of your project category and click Add.

If you wish to assign multiple projects to the same category at once, you can do a bulk edit action from the Project view and type the name of your project category into the box near the top right:

## Step 3: Display your project

There are three current methods to display projects by the category they’re in.

Automatically via Theme

Our themes have built-in functionality to take advantage of project categories and allows sorting of all projects based on their category.

Manually via Shortcode

We use the project grid shortcode to display a category at once. Here’s the syntax, as indicated on our shortcode documentation page:

[ project_grid columns="#" max="#" category="#" ]

– columns = how many projects wide– max = total number of projects to display (good to set this to a multiple of the columns)– category = enter the category ID of the ‘Project Category’ taxonomy that you wish to display– can also add in a custom deck with deck=”id”

To find the ID of a project category, look in the link in your address bar while you’re editing a project category. Within this link you should see a part that reads “tag_ID=X”, where X equals the ID for that particular project category. Use this number in your shortcodes to ensure proper display.

Link to Project Category Archive

You can also directly link to a specific category archive page to view all the contained projects sequentially. Usage is dependent upon your permalink format, but you can find the project category URL by visiting the project category admin and clicking ‘view’ under any listed category.

An example using /%postname%/ format would be: https://yoursite.com/project-category/your-category-name



---
**Source:** [https://docs.ignitiondeck.com/article/91-projects-project-categories](https://docs.ignitiondeck.com/article/91-projects-project-categories)
