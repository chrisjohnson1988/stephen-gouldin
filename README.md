# Stephen Gouldin - A Yorkshire based artist

This is the software repository used for the personal website of [Stephen Gouldin](http://www.gouldin.online/). It is built using [Jekyll](https://jekyllrb.com/)

## Parts of the project to focus on

The project pages are defined in the `_posts` directory, and images are stored within `imgs`

## Creating Pages

To create a new project page, you have to add a new file in the `_posts` directory. The filename is important, and must conform to the following format: **{date}-{title}.markdown** (e.g. 2016-04-05-Clarisse.markdown). The contents of this file define the contents of the page along with some header information about the page (e.g. title, icon in the front page carousel. etc.). The structure of a file would look something like this:

    ---
    title:     "I am the title of a new page"
    permalink: Page_URL_in_Address-bar
    icon:      imgs/carousel_icon_from_imgs_directory.jpg
    layout:    default
    ---

    This is a page written in markdown.

    # The hash symbol defines a heading 

    You can add images from the images directory by adding something similar to the following:

    ![Some title for the image](imgs/filename_to_image.jpg)

# Copyright

© Stephen Gouldin - All rights reserved
