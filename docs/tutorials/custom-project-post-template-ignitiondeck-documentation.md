# Custom Project Post Template - IgnitionDeck Documentation

# Custom Project Post Template

[](javascript:window.print())
NOTE: The following is recommended for those familiar with working with WordPress themes, and is not required to use IgnitionDeck.

If you’re using a theme that doesn’t have IgnitionDeck functionality built in, you can do a quick trick to make your project posting life a little easier. With this, you won’t have to paste a shortcode for each project you make.

Simply create a new post template in your theme, and name it single-ignition_product.php. The easiest way to get started, is to duplicate your theme's single.php file, and then make the modifications you need to that duplicate file.

There’s a way to call shortcodes, straight from a php/template file—and it’s called do_shortcode. Using this, you can easily control the layout of your Project posts, and have them show the information you need them to show.

Here’s a simple example of a possible single-ignition_product.php file:

```
<?php
  global $post;
  $id = $post->ID;
  $project_id = get_post_meta($id, 'ign_project_id', true);
?>
<?php get_header(); ?>
<div id="primary">
  <div id="content">
    <?php /* The loop */ ?>
    <?php while ( have_posts() ) : the_post(); ?>
    <div style="width: 60%; margin-right: 5%; display: inline-block; vertical-align: top;">
      <?php echo do_shortcode( '[project_page_content product="'.$project_id.'"]') ?>
    </div>
    <div style="width: 33%; display: inline-block;">
      <?php echo do_shortcode( '[project_page_widget product="'.$project_id.'"]') ?>
    </div>
    <?php endwhile; ?>
  </div><!-- #content -->
</div><!-- #primary -->
<?php get_footer(); ?>
```

As you can see, we’ve called 2 IgnitionDeck shortcodes into the page.  Something else required to make this dynamic, is to make sure you’re able to define what the Project ID is, of the project post you are viewing.  Make sure you’ve got the first 5 lines of the above example, in your own file.  As well, you’ll need to dynamically get the Project ID for each shortcode, by doing it like it’s done in the above example.

Experiment with other IgnitionDeck shortcodes, and create a layout that fits your site perfectly!



---
**Source:** [https://docs.ignitiondeck.com/article/139-custom-project-post-template](https://docs.ignitiondeck.com/article/139-custom-project-post-template)
