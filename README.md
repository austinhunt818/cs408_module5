# Lab 3
### Austin Hunt

## Overview

This project contains a fake birdwatching page that I styled according to the specifications.

## Running

To run this website, you can right click on the index.html file and click the 'show preview' option. While this web server is running, the url shown in the preview can be used in a web browser as well.

## Accessibility Lab Answers

### Color

I ran an accessibility test using lighthouse on the page. It gave a score of 75. The color section said that the background and foreground colors had an insufficient contrast ratio. I changed the background of the content sections to be a lighter color, and the html background to be darker. After running the test again, it did not flag color as an issue.

### Semantic HTML

When trying to navigate the page with just a keyboard, it is difficult, as I can only really tab through the selectable elements of the page. I updated the article text to be contained in p elements rather than just the article element. I then updated the nav section to properly enclosed in a nav element rather than just a div.

### Images

To make the images more accessible to screen readers, I added alt text to the img elements.

### Audio Player



## Sources and Credits

* https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Multimedia
* https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML
