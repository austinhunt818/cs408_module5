# Lab 3
### Austin Hunt

## Overview

This project contains a fake page about bears, which include a variety of features, and ways to make those features accessible.

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

To make the audio player more accessible, I transcribed the audio for those who are hearing impaired and added a button to show and hide the transcript. I also added a link to download the audio file if the browser is older.

### Forms 

To make the search bar more accessible to screen readers, I added an aria-label property to the input element. I also added label elements to the comment inputs to make them more accessible to screen readers.

### Comment Control Button
To make the show comments button more accessible with the keyboard, I made it an actual button instead of just a div, so that you can focus it with tab and activate it with return or space.

### Table

To make the table more accessible to screen readers, I changed the headers of the rows and columns to th elements with the proper scope, and added a caption. I also added a paragraph explaining the table data more directly in case screen reader users wanted a more in-depth summary of the table's data.

### Other considerations

I added a link to return to the top of the page at the bottom. I also set the lang attribute of the html element to be "en" as it didn't have language before. This tells screen readers what language the page is in, so they don't set to the default language already. This increases accessibility to users in other regions who speak multiple languages.

## Sources and Credits

* https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Multimedia
* https://developer.mozilla.org/en-US/docs/Learn/Accessibility/HTML
* https://developer.mozilla.org/en-US/docs/Learn/Accessibility/CSS_and_JavaScript
* https://developer.mozilla.org/en-US/docs/Learn/Accessibility/WAI-ARIA_basics
