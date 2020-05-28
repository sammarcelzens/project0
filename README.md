# Project 0

Web Programming with Python and JavaScript

A website by Marcel Zens

This website contains 4 pages about the headwear of the english Royal Family. As a German living in the United Kingdom I thought it be be amusing to show you some of the slightly bizare head gear the Royals are waring over here.

  The Pages are index.html, theduke.html, theprince.html & thehats.html

There are a couple of unordered lists, for example in the NAV section and in the bottom footer navigation

There are also a couple or ordered lists used in the slider carousels on theprince.html and on thehats.html

The stylesheet file is called mystylesheet.css & mystylesheet.scss for the SASS file.

I have not included many @media queries, as I felt it was not entirely neccessary due to the use of bootstrap. However I included one for screen and (max-width: 600px) which changes the body background and the jumbotron background.

  I added another @media query to not have any output of the page for print media. Instead it will display a message not to waste paper. This is a homage to my current boss who on a daily basis comes into my office with an email he just printed out...

As you can see there are plenty of images on each page. I only used one table. The table is on the theduke.html page. It is actually used for holding 5 images and a caption for each in the table header. I know that this is not entirely the right use for a table and I certainly could have done the 5 images in a row with divs which would have been more elegant. Unfortunately the requirements for this projects you asked for at least one table and here it is... Sorry the actual content of my page is so silly I really could not think of a real reason for a table to present you some Royal headwear...

Anyway, moving on.

I have used a lot of bootstrap elements on each page so hopefully that fulfils that criteria.

The the mystylesheet.scss I used a couple of variables for the colour of the links ($highlight-col) and for the footer ($pink-accent). Both variables represent a hex color.

SCSS nesting can be seen on line 30 of the mystylesheet.SCSS
SCSS inheritance can be seen on line 20 which is inheriting the style from the a tag. The behaviour can be seen on the normal hyperlinks inside the main content. There is one on index.html and at the bottom of each page in the footer.

just to sum up, I "borrowed" all the images from the Internet and don't own the rights on any of them. Most of the actual content text is taken from wikipedia and it should be fairly obvious what was not taken from Wikipedia.

Hope you guys enjoy this little website.
