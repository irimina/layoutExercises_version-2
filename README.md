# layoutExercises

Task #1 
Navbar

Create a navigation bar similar to the images shown in widerScreensNav.png and mobile_navBar.png

- Launch Chrome DevTools. On the Elements tab, click on the Toggle Device Mode icon
to go to the device mode.

- Build this navigation bar from scratch using the mobile-first approach. Make the
browser small or use the device mode in DevTools to ensure the navigation bar has
the right look and feel on mobile devices.

- Use media queries to re-style the navigation bar for tablets and wider screen. You can
use 768px as the breakpoint. That’s a standard breakpoint for tablets.

========================

Task #2

Create a photo gallery similar to the images shown in mobilePhotos.png, tabletPhotos.png and widerPhotos.png Use the Device Mode in DevTools to view the layout on various screen sizes.

- Note that on mobile, we have a single column. On tablets, we have two columns. On
laptops and wider screens, we have three columns and the third image takes up the
space of four images.

- Build this gallery from scratch using the mobile-first approach.
-You can set your image source to https://source.unsplash.com/collection/
190727/800x600 to get a random image.

- Sometimes you may get duplicate images as a result of caching. To prevent this, append
a question mark and a sequence number to the URL of the image source: https://
source.unsplash.com/collection/190727/800x600?1

- You can represent the container for the images using a div or a ul element. It’s up to you.

- To make the images fit the containing cell, you should give them a width of 100% and set
their object-fit property to cover so they don’t get squashed.
