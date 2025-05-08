# How to use IgnitionDeck Project & Grid Blocks - IgnitionDeck Documentation

# How to use IgnitionDeck Project & Grid Blocks

[](javascript:window.print())

The IgnitionDeck plugin comes with 2 blocks for the WordPress Gutenberg editor: a Featured Project block and a Project Grid block. Both of these blocks can be found by searching for "IgnitionDeck" in the blocks editor.

The blocks can be used on Pages, Posts, and other areas that are block enabled. Multiple blocks can also be used on the same page or post.

## 

## Featured Project Block

This is a great way to showcase a single project on the homepage or highlight a project in each project category. The block will display the project title, featured image, short description, meta data (project goal, progress, etc.), a button to the project, as well as social media links.

The image can be set to appear on the right or left side of the block with the text appearing on the opposite side. The text and buttons can be custom coloured.

### To use the block:

## Project Grid Block

The Project Grid block can be used to create a custom home page sorting projects into specialized sections, creating filtered project category pages, creating a page to showcase successful or ongoing projects.

The grid will display the project title, featured image, short description, meta data (project goal, progress, etc.), project owner, a button to the project, project category, days remaining, as well as success/failure flags. The grid can be customized to show from 1 to 6 columns and can be set to a fixed number of projects or to display all of your projects at once. The grid supports custom color options, as well as the ability to toggle on/off various elements.

### To use the block:

Additionally, all elements are assigned a class that can be targeted with CSS to hide individual elements on a project by project basis. For example, if all active, open-ended projects were being displayed but you didn't wish to show the number of days remaining (0 days on on-going projects), you could hide that meta element with the following CSS:

```
/* HIDE DAYS REMAINING */
.idcf-grid-projects-block-single-info-days {
    display: none;
}
```

This can be further targeted by identifying individual projects:

```
/* HIDE DAYS REMAINING ON PROJECT 5 */
.idcf-grid-projects-block-single-5 .idcf-grid-projects-block-single-info-days {
     display: none; 
}
```



---
**Source:** [https://docs.ignitiondeck.com/article/129-how-to-use-ignitiondeck-project-grid-blocks](https://docs.ignitiondeck.com/article/129-how-to-use-ignitiondeck-project-grid-blocks)
