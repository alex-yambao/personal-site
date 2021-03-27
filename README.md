# personal-site

This is a website I created from scratch during the first week of Fullstack Academy's Coding Bootcamp. 

Here were the parameters for the website: 

Day 1 Project Goals
Today we should be working on semantically laying out the personal site. We want to create the skeleton that will become beautiful as we add styling to it.

FIRST STEPS
Open or navigate to your folder called personal_site, inside of project_01
Inside that folder, create files: index.html, about.html, and portfolio.html
For now, we can do basic styling in a <style></style> tag inside the <head> tag, tomorrow we'll move our styling to organized external sheets
Start by working in index.html, this will be your landing page:
Add a header, main, and footer tag to the body element
You will copy the header and footer, once completed, to all of your other pages to maintain visual consistency
GOALS
Get your content into the three pages.
Add biographical information, pictures, keep your HTML semantic using the named tags.
Add some basic styling if you like, change the fonts, add a background color, and size your images. (The rest of the styling will come over the next two days.)

FIRST STEPS
Inside the personal_site folder, create files index.css, about.css, portfolio.css, and finally site.css.
Then, move any styling that you intend to keep into the respective files.
Finally, add the appropriate links in the header (e.g. <link rel="stylesheet" href="site.css" /> should be in all HTML documents, and <link rel="stylesheet" href="index.css" /> should be in index.html, etc.)
GOALS
Today's reps are all about fonts, colors, and sizing, so let's replicate that in what we do with our project.

Go fetch a few web fonts from Google Fonts. When you've selected them, there's two ways to add them: a link for the header of each page that needs them, or an import tag (under @import) that you can use in your stylesheets. If you chose the latter, you can add it (e.g. @import url('https://fonts.googleapis.com/css?family=Gelasio|Open+Sans&display=swap');) to the top of your site-wide style sheet, site.css.
For the footer, go grab a few social media icons, find PNG or SVG files, add them to your folder. If you wrap the img tag in an anchor tag, then the image becomes clickable. It also means that if you set text-align: center to the footer, the icons will be centered.
For the rest, start sizing your images, give your main content a size and a margin of 0 auto, give the project cards a size and margin of XXX auto so that they don't bump up against on each other and also center within your main content tag.
The Adobe Color web app allows you to pick out pleasant color themes. The colors are usable via hex codes (e.g. #eaf32b), and can be copied into your CSS files with ease.

Day 3 Project Goals
FIRST STEPS
There are no additional steps necessary. You've created all the files you need at this point.

GOALS
There is no additional initialization needed. Today we are adding positioning, floats, and deploying our site.

Make your header and footer fixed, for the header set top to 0, and footer set the bottom to 0.
Give your main content some padding on the top and bottom, so that it doesn't disappear behind the header and footer when scrolling.
To get the header of your page to separate your name & links, you can have the name element float left, and the navigation element float right. Don't forget to give the header { overflow: auto; } to help clear the floats.
The photos in the preview float.
Make sure to float them, by setting float: XXXXX;
Set the overflow property of anything with a float inside (the parent) to auto.
For the links in the header, make sure to have the active one underlined. You can do this with adding a bottom border to the one for the current page.
