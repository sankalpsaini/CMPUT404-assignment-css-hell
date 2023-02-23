Assignment: CSS Hell
====================

You will skin 3 project gutenberg stories with custom CSS.

You will skin 2 versions of a possible professional homepage for your
self with 2 versions of CSS.

Read requirements.org

Read this comic http://theoatmeal.com/comics/design_hell

git clone https://github.com/abramhindle/CMPUT404-assignment-css-hell.git

License/Copyright
=================

Textual content is copyright Abram Hindle (C) 2013 under the CC-BY-SA
4.0 unported license. Attribution should be a hyperlink to the
repository and (C) 2013 Abram Hindle visibile in the text.

Content is copyright Sankalp Saini (C) 2023 under the CC-BY-ND 4.0 unported license. Attribution should be a hyperlink to the repository and (C) 2023 Sankalp Saini visibile in the text.

Code is licensed under the Apache 2.0 license.

Additional Information:
=================

Part 1 HTML File Changes:

    - I created an additional stylesheet that is linked after the already-provided styling in the html file so it overwrites the specified sections. The specific overwrites were:
    
        - body background-color: #e6e0b8;
        - h1,h2,h3,h4 font-family: "Snell Roundhand";
        - div font-family: papyrus;
        - p color: black;
        - p font-family: florence, cursive;
        - img filter:saturate(0%) sepia(100%) contrast(150%) saturate(150%);
        - img opacity: 0.6;


    - Added "<link rel="stylesheet" href="part1.css" >" in all of the files underneath the pre-existing CSS code. This is so that the newly created stylesheet overwrites the specified elements.

    - Also changed all of the href links to the newly named images found in the /images folder


Collaboration/Links:

    - https://websitesetup.org/website-color-schemes/
    - https://www.w3schools.com/howto/howto_css_blurred_background.asp
    - https://www.w3schools.com/css/css_inline-block.asp
