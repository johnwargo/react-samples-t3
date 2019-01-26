# React Samples

The files in this repository demonstrate multiple ways to build a simple HTML page that renders React content without doing the whole react project thing. This approach is necessary so your React page can integrate seamlessly with the other pages made by your teammates.

Most of this content was **stolen** from [Kirupa's Learn React](https://www.kirupa.com/react/) web site, and tweaked.

The repository contains the following files:

+ `base.html`: A simple, base Hello World kinda React page.
+ `sample-1.html`: A react page that displays two paragraphs and a button, creating a separate component for each.
+ `sample-2.html`: Added some styling to the page (not any of the components).
+ `sample-3.html`: Added styling to the button (through React).
+ `sample-4.html`: Removed the separate paragraph components and replace with a single Paragraph component that gets its content through `props`.
+ `sample-5.html`: Separates the paragraph content into variables passed to the Paragraph component via `props`.
+ `sample-6.html`: Stores the paragraph content in a separate `paragraphs.js` file (below).
+ `paragraphs.js`: External JavaScript file containing the paragraph content for the page.
+ `sample-7.html`: Implements a clunky approach to changing the behavior of buttons through `props`.
+ `sample-8.html`: A cleaner implementation of dynamic button action.