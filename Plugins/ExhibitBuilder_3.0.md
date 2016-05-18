Plugins/ExhibitBuilder 3.0
==========================

[Plugins](../Plugins.1.html "Plugins")

The Exhibit Builder plugin allows you to develop online exhibits, or
special web pages, that combine items from your Omeka archive and may
include narrative text.

Exhibits are composed of pages, generally an initial page that
introduces your exhibit and subsequent pages composed of the items from
your Omeka database that you wish to highlight and/or relate to each
other. Exhibit Builder exhibits may be as short as one page or consist
of multiple pages. You can make the pages of an exhibit hierarchical.

The layout of exhibits in Exhibit Builder 3.0 is highly customizable,
with the pages composed of smaller units called blocks. There are three
content block types which come with Exhibit Builder 3.0: file with text,
gallery, and text block.

Other plugins may include their own Exhibit Builder block layouts, if
the developer has created them.

Upgrading from Exhibit Builder 2.0
-----------------------------------------------------------------------------------------------------------

Before you upgrade from Exhibit Builder 2.0 to 3.0, be sure to [back up](https://omeka.org/codex/Backing_up_an_Omeka_Database "Backing up an Omeka Database")
your Omeka installation, especially your Exhibit Builder tables.

The upgrade should transform the layouts of your exhibit pages from the
old format to the new, without any loss of information. The [section
below](ExhibitBuilder_3.0.html#Previous_Exhibit_Builder_Layouts)
describes how older exhibit layouts should transfer.

Configuring
--------------------------------------------------------------

This plugin is included in your Omeka installation and does not require
a separate download. Select Plugins in the top navigation of your admin.
Activate your plugin and select Configure to choose the sequence in
which your exhibits appear. Exhibits may be ordered by date added,
alphabetically by name, or most recent.

[![Eb3config.jpg](https://omeka.org/c/images/c/c8/Eb3config.jpg)](https://omeka.org/codex/File:Eb3config.jpg)

-   Choose the order of your Browse Page Exhibit display from the
    dropdown menu.
-   Don't forget to save your changes.

Getting Started
---------------------------------------------------------------------

Once you have activated and configured the Exhibit Builder plugin,
Exhibits should appear in the left navigation bar. Clicking on it will
take you to the Browse Exhibits page (admin/exhibits in your
installation).

[![Ebadd.jpg](https://omeka.org/c/images/9/94/Ebadd.jpg)](https://omeka.org/codex/File:Ebadd.jpg)

To create an exhibit, go to the Exhibits tab and click the green button
labeled "Add an Exhibit". This will take you to a new page where you can
enter the following metadata:

-   Title: the name of your exhibit, which will be displayed to users
-   Slug: the abbreviated exhibit name which appears in the url, for
    example <http://youromekasite/exhibits/show/slug>
-   Credits: acknowledgements which will be visible to the public
-   Description: an introduction or overview for the exhibit
-   Tags: keywords or themes that give users another option for
    finding exhibits.

Once you have entered the data, click Save Changes to create your
exhibit.

### Theme

By default, your exhibits will display using the same theme as the rest
of the site. Or, you may choose a different theme for each exhibit. To
do so, select a theme from the dropdown, which will default display
"Current Public Theme."

[![Ebtheme.jpg](https://omeka.org/c/images/2/21/Ebtheme.jpg)](https://omeka.org/codex/File:Ebtheme.jpg)

After selecting a specific theme for exhibit, you can configure that
theme by adding a logo, header image, footer text, and copyright
information which displays only for that exhibit. Note that if you
change the theme, you must click Save Changes before you configure the
theme. So if you have been using Berlin and you want to change to the
Winter version of Seasons, you will have to click Save Changes after
switching from Berlin to Seasons in the Theme dropdown before you can
configure the Seasons theme.

Pages
-------------------------------------------------

Once you have created an exhibit you can add pages to it by clicking the
Add Page button at the bottom of the Exhibit Metadata page.

[![Ebaddp.jpg](https://omeka.org/c/images/2/21/Ebaddp.jpg)](https://omeka.org/codex/File:Ebaddp.jpg)

Once on the Add Page screen, add the following:

-   Page Title: visible to users, used for navigating through
    the exhibit.
-   Page Slug: an abbreviated exhibit name that appears in the url, for
    example <http://youromekasite/exhibits/show/exhibit_slug/page_slug>

To save the page information and continue editing that page, click the
Save Changes button. To save the basic information for that page and add
another page, click the Save and Add Another Page button.

### Organizing Pages

An exhibit in Omeka can have multiple pages. You can reorder these pages
by dragging and dropping, and you can use drag and drop to set up an
exhibit page hierarchy. Note that these hierarchies cannot be more than
three levels deep.

You can also delete pages from the Exhibit Metadata page through a
two-step process. First, click the large black X on the display bar of
the page you wish to delete. Once you click the X, the bar will turn red
(see the bar for the page Edward in the image below). Clicking the arrow
will undo the delete action. To confirm deleting a page, you must click
the Save Changes button. Once pages have been deleted, they cannot be
restored.

[![Ebpage.jpg](https://omeka.org/c/images/1/19/Ebpage.jpg)](https://omeka.org/codex/File:Ebpage.jpg)

Content
-----------------------------------------------------

Layouts from earlier versions applied to an entire page, but in EB 3.0
pages combine smaller content units called 'blocks.' There are four
kinds of blocks: item(s) with text, an item gallery, text only, or a
geolocation map (if you have installed the Geolocation plugin). Each
page can have one or more content blocks.

The **File with Text** block allows you to pair fullsize or thumbnail
files of your items with a block of text. The item files will all be the
same size. Text will appear either to the right or left of the item(s).
You can use a single item file paired with text, or have multiple item
files to the right or left of a block of text.

The **Gallery** block creates a gallery of item files, generally large
square thumbnails. You can add text to the gallery, which will display
left or right of the gallery. In a gallery block, you can specify a
showcase file, which will appear fullsize either to the right or left of
the text. The other gallery images can be placed below the showcase
image or beside it, over the text.

The **Text** block allows you to create a section of text which spans
the width of the entire page.

[![Ebaddc.jpg](https://omeka.org/c/images/a/a8/Ebaddc.jpg)](https://omeka.org/codex/File:Ebaddc.jpg)

To add a content block, select the layout you want in the New Block
dialog box. Once you have selected the kind you want, click the "Add new
content block" button. You will have a new block on the page to
configure your content.

### Adding Items

If you have selected any block other than Text, choose an item by
clicking the large plus sign button appearing in the Items area. An
items browse dialog box pops up showing all of your items. You can
search in the items or browse. To select an item, click on its bar. The
right end of the bar will highlight a dark brown "Select Item" button.
Click Select Item to find options for creating a caption for the item.
If you have more than one file uploaded for an item, you will be able to
select which you want to use by clicking on it. When you have finished,
click the green "Apply" button in the bottom right-hand corner to add
the item.

Once you have added an item, you can change the caption or selected file
by clicking the edit button which sits across the bottom of the item
icon. To delete items, click the x in the upper right hand corner of the
item icon; this will gray out the icon, indicating that it will be
deleted the next time you save changes. If you decide not to delete the
item, you can click the arrow which replaced the x, but you must do so
before you save your changes.

[![Ebitma.jpg](https://omeka.org/c/images/a/a1/Ebitma.jpg)](https://omeka.org/codex/File:Ebitma.jpg)

Exhibit text can be formatted, either using the formatting toolbar at
the top of the text entry box or with html. To write your own html, or
paste from somewhere else, click the blue HTML button in the formatting
toolbar at the top of the text entry box. This will open up an HTML
Source Editor window in which you can work.

### Layout Options

Both the File with Text and Gallery blocks include layout options to
change the look of the exhibit page. To access these options, click the
black triangle button to the right of the Layout Options text at the
bottom of the block. This will reveal dropdown menus with options for
changing the layout.

For **File with Text** you can change the position of the file relative
to the text (file position) and the size of the file. File position is
either right or left. File size can be full size, thumbnail, or square
thumbnail. Whatever you select affects all of the files for that block
equally. The text in this block will stay fixed to the right or left of
the file, but will wrap below if the length of the text exceeds the
height of the file. Captions can be set to align to the left margin,
center, or right margin of the thumbnail file for which they are
entered.

\

[![Ebftlo.jpg](https://omeka.org/c/images/e/ee/Ebftlo.jpg)](https://omeka.org/codex/File:Ebftlo.jpg)

For **Gallery** you can determine the showcase file position, gallery
position, gallery file size, and captions alignment. A showcase file
will be fullsize, while the rest of the gallery files are large square
thumbnails. Exhibit Builder will use the first item in the block for the
showcase; note that you can change the order of the items by dragging
and dropping. If there is no showcase file or text, the gallery will use
the full width of the page. Gallery position is relative to the text in
that block. Your options for the thumbnail images in Gallery file size
are square or not. Captions can be set to align to the left margin,
center, or right margin of the thumbnail file for which they are
entered.

[![Ebglo.jpg](https://omeka.org/c/images/b/b9/Ebglo.jpg)](https://omeka.org/codex/File:Ebglo.jpg)

### Additional Layouts

Some plugins include their own Exhibit Builder content block layouts.

If you have installed the Geolocation plugin, you will have the
**Geolocation Map** block as an option in your exhibits. This block has
no text. Select items which already have been geolocated using the
plugin in their item edit page. This block displays as a map across the
full width of the page, with markers for the items you select. Any
captions you enter will appear in a pop-up inside the map when the item
marker is clicked, as will the item file and title.

[![Ebmap.jpg](https://omeka.org/c/images/9/9d/Ebmap.jpg)](https://omeka.org/codex/File:Ebmap.jpg)

### Previous Exhibit Builder Layouts

The following is a list of [layouts from previous versions](https://omeka.org/codex/Exhibit_Builder_Layouts "Exhibit Builder Layouts")
of Exhibit Builder showing how the old layouts can correspond to new
content blocks. These correlations are how pages built in previous
versions of Exhibit Builder will be imported when upgrading.

Although it is possible to reproduce previous layouts using Exhibit
Builder 3.0, the content blocks allow for a much wider variety of
layouts. For example, rather than having all the files on one side, as
in image list left or right, files could alternate sides. You can also
combine a Gallery block with File with Text Blocks, or stack multiple
Galleries with interpretive text for each set.

NB: You cannot change one kind content block (ex. Gallery) to a
different kind of content block (ex. File with Text). However, because
you can move content blocks around, adding a new block to replace an
existing one is less work than in previous versions of Exhibit Builder.

Layout options ([see above](ExhibitBuilder_3.0.html#Layout_Options)) are
in *italics* for Exhibit Builder 3.0 blocks.

  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
  Exhibit Builder 2.0                                                                                                                                                             Exhibit Builder 3.0
  ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- -----------------------------------------------------------------------------------------------------------------
  [![Gallery-full-left.gif](https://omeka.org/c/images/2/20/Gallery-full-left.gif)](https://omeka.org/codex/File:Gallery-full-left.gif)\                                          [![EBGallery.gif](https://omeka.org/c/images/1/19/EBGallery.gif)](https://omeka.org/codex/File:EBGallery.gif)\
  Gallery-full-left                                                                                                                                                               One gallery block. Showcase file position *left*, gallery position *right*.

  [![Gallery-full-right.gif](https://omeka.org/c/images/c/cc/Gallery-full-right.gif)](https://omeka.org/codex/File:Gallery-full-right.gif)\                                       [![EBGallery.gif](https://omeka.org/c/images/1/19/EBGallery.gif)](https://omeka.org/codex/File:EBGallery.gif)\
  Gallery-full-right                                                                                                                                                              One gallery block. Showcase file position *left*, gallery position *right*.

  [![Gallery-thumbnails.gif](https://omeka.org/c/images/5/5e/Gallery-thumbnails.gif)](https://omeka.org/codex/File:Gallery-thumbnails.gif)\                                       [![EBGallery.gif](https://omeka.org/c/images/1/19/EBGallery.gif)](https://omeka.org/codex/File:EBGallery.gif)\
  Gallery-thumbnails                                                                                                                                                              One gallery block

  [![Gallery-thumbnails-text-bottom.gif](https://omeka.org/c/images/e/e0/Gallery-thumbnails-text-bottom.gif)](https://omeka.org/codex/File:Gallery-thumbnails-text-bottom.gif)\   [![EBGallery.gif](https://omeka.org/c/images/1/19/EBGallery.gif)](https://omeka.org/codex/File:EBGallery.gif)\
  Gallery-thumbnails-text-bottom                                                                                                                                                  One gallery block with text added, or one gallery block with no text and one text block.

  [![Gallery-thumbnails-text-top.gif](https://omeka.org/c/images/2/2a/Gallery-thumbnails-text-top.gif)](https://omeka.org/codex/File:Gallery-thumbnails-text-top.gif)\            [![EbText.gif](https://omeka.org/c/images/a/ae/EbText.gif)](https://omeka.org/codex/File:EbText.gif)\
  Gallery-thumbnails-text-top                                                                                                                                                      [![EBGallery.gif](https://omeka.org/c/images/1/19/EBGallery.gif)](https://omeka.org/codex/File:EBGallery.gif)\
                                                                                                                                                                                   One text block above one gallery block with no text.

  [![Image-list-left.gif](https://omeka.org/c/images/e/e1/Image-list-left.gif)](https://omeka.org/codex/File:Image-list-left.gif)\                                                [![FileWText.gif](https://omeka.org/c/images/1/1f/FileWText.gif)](https://omeka.org/codex/File:FileWText.gif)\
  Image-list-left                                                                                                                                                                 Series of File with Text blocks, file position *left*, files *full size* .

  [![Image-list-left-thumbs.gif](https://omeka.org/c/images/b/bb/Image-list-left-thumbs.gif)](https://omeka.org/codex/File:Image-list-left-thumbs.gif)\                           [![FileWText.gif](https://omeka.org/c/images/1/1f/FileWText.gif)](https://omeka.org/codex/File:FileWText.gif)\
  Image-list-left-thumbnails                                                                                                                                                      Series of File with Text blocks, file position *left*, files *thumbnail* or *square thumbnail size*.

  [![Image-list-right.gif](https://omeka.org/c/images/f/fc/Image-list-right.gif)](https://omeka.org/codex/File:Image-list-right.gif)\                                             [![FileWText.gif](https://omeka.org/c/images/1/1f/FileWText.gif)](https://omeka.org/codex/File:FileWText.gif)\
  Image-list-right                                                                                                                                                                Series of File with Text blocks, file position *right*, files *full size*.

  [![Image-list-right-thumbs.gif](https://omeka.org/c/images/1/19/Image-list-right-thumbs.gif)](https://omeka.org/codex/File:Image-list-right-thumbs.gif)\                        [![FileWText.gif](https://omeka.org/c/images/1/1f/FileWText.gif)](https://omeka.org/codex/File:FileWText.gif)\
  Image-list-right-thumbnails                                                                                                                                                     Series of File with Text blocks, file position *right*, files *thumbnail* or *square thumbnail size*.

  [![Text.gif](https://omeka.org/c/images/d/df/Text.gif)](https://omeka.org/codex/File:Text.gif)\                                                                                 [![EbText.gif](https://omeka.org/c/images/a/ae/EbText.gif)](https://omeka.org/codex/File:EbText.gif)\
  Text                                                                                                                                                                            One text block

  [![Text-image-left.gif](https://omeka.org/c/images/c/c6/Text-image-left.gif)](https://omeka.org/codex/File:Text-image-left.gif)\                                                [![FileWText.gif](https://omeka.org/c/images/1/1f/FileWText.gif)](https://omeka.org/codex/File:FileWText.gif)\
  Text-image-left                                                                                                                                                                 One File with Text block, file position *left*.

  [![Text-image-right.gif](https://omeka.org/c/images/2/21/Text-image-right.gif)](https://omeka.org/codex/File:Text-image-right.gif)\                                             [![FileWText.gif](https://omeka.org/c/images/1/1f/FileWText.gif)](https://omeka.org/codex/File:FileWText.gif)\
  Text-image-right                                                                                                                                                                One File with Text block, file position *right*.
  -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------