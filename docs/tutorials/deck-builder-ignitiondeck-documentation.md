# Deck Builder - IgnitionDeck Documentation

# Deck Builder

[](javascript:window.print())
Important note: the Deck Builder is of use only to sites with non-IgnitionDeck themes. This is a alternative method to styling IgnitionDeck content such as the project grid. If the site is using the WP Blocks Editor, please see our documentation on using the IgnitionDeck Blocks for featured projects and a project grid.

With the IgnitionDeck Deck Builder, you can control what is shown and what is hidden within the project’s data display. You can build and customize any number of decks in any format you want. This works with widgets and shortcodes only, and does not work with theme templates.

To use the Deck Builder, give your Deck a name, and then select the components you wish to display. Once you click save, your deck will be assigned a custom Deck id, which you can call via shortcodes.

This currently works on project_widget, project_mini_widget, project_grid, and project_page_complete. Simply add deck=”id” within the shortcode.

For example:

```
[project_mini_widget product="1" deck="1"]
[project_page_widget product="1" deck="1"]
```

Some examples below using the project_grid shortcode, please remember to type them in using Text (HTML) mode and without the start or ending spaces.

```
[project_grid columns="4" max="12"]

[project_grid columns="4" max="12" deck="1"]
```



---
**Source:** [https://docs.ignitiondeck.com/article/128-ignitiondeck-deck-builder](https://docs.ignitiondeck.com/article/128-ignitiondeck-deck-builder)
