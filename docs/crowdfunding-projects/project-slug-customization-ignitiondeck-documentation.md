# Project slug customization - IgnitionDeck Documentation

# Project slug customization

[](javascript:window.print())
There are limitations on what can be filtered to customize the slugs within the URL. We have filters for most which needs to be done with PHP, not the htaccess file.

For example, this will allow you to filter the "project" slug:

```
add_filter('idcf_archive_slug', 'customid_filter_archive_slug');   
function customid_filter_archive_slug($slug) {
      return __('new_slug', 'ignitiondeck'); 
}
```

We also offer:

The rest are not currently filterable and would require further customization.



---
**Source:** [https://docs.ignitiondeck.com/article/182-project-slug-customization](https://docs.ignitiondeck.com/article/182-project-slug-customization)
