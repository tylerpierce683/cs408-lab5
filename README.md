# Web Dev Starter Code

## Overview

In this project, we were given a website with poor accessibility and had to make 
adjustments to make the website more accessible.

## How to run
1. Clone or fork my github repository into a local directory.
2. Open this directory in VSCode.
3. Open the VSCode Command Palette.
4. Launch the command "Live Preview: Start Server"
5. Browse the website!

## Accessibility Lab Answers
### Semantic HTML
1. When I try to navigate the content using a keyboard, it doesn't select everything. For example,
the show comment button would not get highlighted.
2. I made the the article text easier for screen readers to navigate by switching the top level
font objects into headings and the empty text into paragraphs to give it more structure.
3. I fixed this issue by changing the \<div> to a \<nav>.

### The Images
I fixed this issue with the images on the site by adding alt tags that gave descriptions of the
pictures.

### The Audio Player
1. To help people who are hard of hearing or deaf, I added a transcript to tell what the audio
clip is discussing.
2. To help those using older browsers that don't support HTML audio, I assume we could add a 
link to the audio that way they can play it externally.

### The Forms
1. I struggled with this for a while and ended up having to go to StackOverflow to find the
solution which was to add a label that applied to the search box, but was out of the boundaries 
of the screen so as to not be visually present, but help those with screen-readers.
2. In order to fix this issue with the labels, I changed the \<p> tags to \<label> tags to associate
the text with their given fields.

### The Show/Hide Comment Control
I made the show/hide comment control button accessible by actually turning it into a button. It was
originally something else that doesn't take input. Once I did this, the problem was solved.

### The Table
I fixed the association of data in the table by changing the top row in the table to table headers 
so as to associate the data with its given heading.

### Other Considerations
1. I think one thing that would also improve the website's accessibility is making the text bigger.
I think with the way it's currently set, the text just gets lost in the site.
2. My other recommendation would be to use a heading font that's a little easier to read, as the 
current one can be hard for even people with decent vision to figure out.

## Sources and Credits

- W3.org (Table accessibility): [https://www.w3.org/WAI/tutorials/tables/one-header/](https://www.w3.org/WAI/tutorials/tables/one-header/)
- blog.pope.tech (Navigation accessibility): [https://blog.pope.tech/2024/01/30/how-to-create-accessible-navigations-and-sub-menus/](https://blog.pope.tech/2024/01/30/how-to-create-accessible-navigations-and-sub-menus/)
- StackOverflow.com (Label for search bar that's only accessible by screen-readers): [https://stackoverflow.com/questions/13551899/how-to-show-a-label-only-to-screen-readers-web-accessiblity](https://stackoverflow.com/questions/13551899/how-to-show-a-label-only-to-screen-readers-web-accessiblity)

