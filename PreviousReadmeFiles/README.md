EECS 285 : Preliminary Spec : v0.1 [Prototype]
=======


## Notes
Update Trello to keep the team updated on progress/challenges/questions.

[NL == Not Listed in original markup - these are features that have been added to the spec after the original creation]


## Abstract
The first prototype is going to be a proof of concept. This means that we don't have to worry about 90% of the project when we first start. The idea is to make sure that the base level of implementation works for us. There will be a limited feature set to implement on this first go round.

## GUI Description
There will be basic HTML template that we will be customizing and rendering. There will be two main panels. Customization of the HTML will be afforded through five main sections on the left side.

* Left Panel : This is where our element customization will go.
  * Header Content - The raw text inside the <h> html tag.
    * Content Options - User can select ONE of TWO fonts. Georgia or Arial.
  * Paragraph Content - The raw text inside the <\p> html tag.
    * Content Options - User can select from ONE of TWO font weights. 8 and 14.
  * Add Image Button - This will add an image to the project directory and update the html <img> tag's src attribute to reflect the location of the image. If no image is selected, use a default.
  *  Export Website - This button will allow the user to specify a location to export a folder containing the index.html file and the image selected by the user. If the user selects no image, a default should be used.
  *  Apply Changes (NL) - This button is will modify the HTML and reflect these changes in the page render window.

EX: (User selects home directory)
```
~/myWebsite/
~/myWebsite/index.html
~/myWebsite/myImage.jpg
```

The right panel will be some sort of preview of the page. It should be a genuine render of the HTML.

I think we should also include some rudimentary user login system, just to get familiar with the JDBC package.

There is an accompanying image that outlines the general structure of the program. Specific implementation is up to the individual working on that piece of code unless otherwise agreed upon. In other words, no one has the time or the patience to micromanage, so do what you think is best. However, if you think a certain GUI element or package might influence someone else's code, then obviously be sure to inform that person.

## Helpful Resources
https://docs.oracle.com/javafx/2/webview/jfxpub-webview.htm
https://docs.oracle.com/javase/tutorial/jdbc/overview/index.html

Very useful link to add html elements: http://www.javadocexamples.com/javax/swing/text/html/HTMLDocument/insertBeforeEnd(Element%20elem,String%20htmlText).html
