# IgnitionDeck Module API - IgnitionDeck Documentation

# IgnitionDeck Module API

[](javascript:window.print())
## Introduction to the IgnitionDeck Module API

IgnitionDeck Modules are drop-in code libraries that integrate with the IgnitionDeck Framework (IDF) and allow you to easily enable or disable additional functionality for your website. In most situations, these modules modify or enhance functionality that is bundled with one of the three major IgnitionDeck plugins (Framework, Commerce, Crowdfunding).

The IgnitionDeck Module API enables the addition of 3rd party libraries that can be managed via the IgnitionDeck->Modules menu, giving users complete control over the features they enable or disable, and is the only supported method for adding/modifying IgnitionDeck features.

The IgnitionDeck Module API is new, and therefore parameters are limited.  However, our development team is actively working to improve base functionality, including the addition of a 3rd party module library, and the ability to charge fees for module activation.

## IgnitionDeck Module Structure

Custom modules should be placed in the /classes/custom-modules folder inside the IDF and IgnitionDeck Commerce (IDC) plugins. It is recommended that commerce related modules be installed in IDC, and general modules installed in IDF. You may create this folder if it does not exist.

When installed, a module should have the following structure:

/classes/custom-modules/custom_module/[files_here]

Module parameters are defined via a module_info.json file located in the module’s root directory:

/classes/custom-modules/custom_module/module_info.json

Module logos are located in the same directory:

/classes/custom-modules/custom_module/thumbnail.png

Modules must also include a primary class file that uses the same name format as the root directory:

/classes/custom-modules/custom_module/class-custom_module.php

As long as these three files are properly placed, you may use any folder structure you wish inside the module’s root directory.

## Building module_info.json

This file currently accepts the following parameters:

title (required): The name of the module as listed in the module directory.

short_desc (required): A short description of the module’s feature set displayed in the module directory under logo and title.

doclink (optional): A link to the module’s documentation page.

status (required): Set to “live” when module is ready to be published.

type (required): “module” is the only allowed argument.

requires (optional):  Leave empty if the module does not require an IgnitionDeck license. Set to idc if Echelon is required. Set to ide if Enterprise is required.

Using the IgnitionDeck Helix module as an example, a final module_info.json file might look like:

{

"title":"Helix",

"short_desc":"Helix is a sleek and sexy navigation module for WordPress that integrates with IgnitionDeck and WooCommerce.",

"doclink":"https://ignitiondeck.com/id/documentation/ignitiondeck-modules/helix-documentation/",

"status":"live",

"type":"module",

"requires": "",

"priority": "high",

"category": "",

"tag": "spotlight"

}

[view raw](https://gist.github.com/nhangen/fcc5f0bc6321a7682839189acf02a6f3/raw/e0505db3f8ca1c7d568d8b7e11a2b84db7b042a9/module_info.json)[module_info.json](https://gist.github.com/nhangen/fcc5f0bc6321a7682839189acf02a6f3#file-module_info-json) hosted with ❤ by [GitHub](https://github.com/)

## Module Activation & Autoload

Modules will display in the IgnitionDeck->Modules menu as soon as this file is built and the module->status is set to live. Once listed, modules will automatically receive a button to enable activation/deactivation. Once activated, modules are detected and their class file is loaded automatically. Use this file to load any additional files your module might require.

## Module Updates

The IgnitionDeck Module API does not yet support versions or automatic updates. Therefore, it is recommended that modules are updated manually via FTP.



---
**Source:** [https://docs.ignitiondeck.com/article/102-ignitiondeck-module-api](https://docs.ignitiondeck.com/article/102-ignitiondeck-module-api)
