# Bug List

> Make a list of the things that don't work as expected. Keep a list of things that you have fixed and try to document how you solved them.

1. Problem: Tried to set at with and hight to the bottons in the menu, noting happened. I added a justify property to my nav element. I first set the value to center, but then there was no space between the items. I changed the value to space-between, but according to (https://css-tricks.com/snippets/css/a-guide-to-flexbox/#aa-css-flexbox-background) it might not work properly in Edge, so it's recommended to use center instead. Added a gap prpperty.
   Solved: Used flexbox
2. Problem: Thought I solved the first problem, then I noticed then the closing tag of the ul element was'nt on the right place... I used the instructions on vuxcode to make the new menu. Worked fine but there is two links on the screen that I don't know where they came from.
   Solved: I had missed a closingtag to one of the links.
4. Problem: The LillyNailspicture were placed over my menu, I wanted it to lay beside the links.
   Solved: Discovered that I had made the nav element to a class in the CSS with a dot before the name (.nav) instead of (nav) that was the purpose.
5. Problem: The LillyNails logo is to big.
   Solved: Tried to make the picture smaller by setting a max. hight to the nav. element. Didn't work.Read how to fix it on the flex-website that Colin recomended. Made a class, didn't work at fort but then I realised that one letter was in lowercase letter... Read more about flex and slept on it and reset my classes. Tried again and moved my classes to different elements. It worked but the pic is in a weird shape and it will probably not work on every screen but I will look on that later.
6. Problem: Weird size on LillyNailspic
7. Problem: Nav will probably not work on every screen size.
8. Problem: The content in one article is not in the middle anymore. Solved: I took away the size of the div-elements with the headers and changed it to 100% and made the div a flex-container and put wrap on it. '
9. Problem: The text in the article is in the middle but not the botton.
Solved: Tried to set the .botton to flex and justifycontent to center. Didn't work.
10. Problem: I wanted the text on page 2 to be in a column but then the text under my "Eftervård" also came in a column and I wanted them to be in a row. Solved: Tried different comination to make boxes and put flex on them. I separated the articles into smaller boxes but it didn't work. Then I realised I needed a bigger box around the articles and made the whole box a container and changed the direction to row. 


