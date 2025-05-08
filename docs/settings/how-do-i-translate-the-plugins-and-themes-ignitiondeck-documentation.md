# How do I translate the plugins and themes? - IgnitionDeck Documentation

# How do I translate the plugins and themes?

[](javascript:window.print())
IgnitionDeck products come in American English by default, but can easily be modified to appear in other languages. Using this tutorial, you’ll be able to download the necessary translation files, modify them as desired, and add them to your IgnitionDeck installation.

You can also use this method to change words and phrases without a language translation—just use the English language code (en_US) where appropriate.

If you’re new to translation in WordPress, please see WordPress.org’s own documentation page called Translating WordPress.

## Step 1: Download the Translation Files

Using your favorite FTP client (we recommend Filezilla), download the translation files from /theme-or-plugin-directory/languages_default/.

You can also open your web hosting account and navigate to the plugins or theme via the File Manager to download the files.

They will have the file extensions “.po”

### Step 2: Translate IgnitionDeck

Download a free copy of POEdit for Mac, Windows, or Linux and install using system prompts.

Open the ignitiondeck.po file (this will be the default en_US version) within POEdit.  Click on the Catalog » Update from Sources button to ensure that you have the most up to date list of translatable text. Save the file.

Copy and paste the updated ignitiondeck.po file to your computer to work with the file.

Before you start the translation, open the catalog settings menu and ensure that the catalog is set to the language in which the file will be translated.

You should now see two columns. The left column contains the English source version, the right will eventually display your translated version. Do not alter the source text. Clicking on a row enables an editor in the bottom of the screen, that will allow you to type the translated values.

Translate all or some of the text strings. Save your changes. This will generate both the .po and compiled .mo files.

Rename the files using the language structures found in the WordPress codex (for example, if you are translating the IgnitionDeck Framework to Spanish, the files should now be called idf-es_ES.po and idf-es_ES.mo). See Text Domains for IgnitionDeck Products.

### Step 3: Install Translation Files

Upload both the .po and .mo files to the WordPress site containing your IgnitionDeck installation.

Using FTP, upload the .po and .mo files (do not upload the folder containing the files, just the two files themselves) to the /theme-or-plugin-directory/languages/ directory. You may need to create the /languages/ directory if there isn't one already present.

If the translation files already exist from prior version of IgnitionDeck, you are free to overwrite them.

### Step 4: Activate Language Files

If your WordPress installation is already activated in your language, then you can skip this step. If your site is still in English, you’ll need to configure your site in order to activate your language of choice.  Go to Settings > General and select the Language of Site to your language of choice.  Save the changes.

Your WordPress blog and IgnitionDeck installation should now be translated!

### Step 5: Repeat steps 2-3 for other ID themes/plugins

You will need to translate IgnitionDeck Crowdfunding as well as IgnitionDeck Commerce or one of our 500 themes, if you are using these on your site.

You can find the template language files inside of /plugins/ignitiondeck-crowdfunding/languages_default/, /plugins/idcommerce/languages_default/ and /themes/fivehundred/languages_default/, respectively. Copy these and name them in the following formats:

### Text Domains for IgnitionDeck Products

 Product
 Text Domain

IgnitionDeck Framework
idf

IgnitionDeck Commerce
memberdeck

IgnitionDeck Crowdfunding
ignitiondeck

Theme 500 Framework*
n/a

*Unlike plugin language files, a name like my_theme-en_US.mo will NOT work for a theme. Although plugin language files allow you to specify the text-domain in the filename, this will NOT work with themes. Language files for themes should include the language shortcut ONLY like en_US.po and en_US.mo.

## Troubleshooting

If your translation doesn't appear, check for the most common errors:



---
**Source:** [https://docs.ignitiondeck.com/article/49-how-do-i-translate-the-plugins-and-themes](https://docs.ignitiondeck.com/article/49-how-do-i-translate-the-plugins-and-themes)
