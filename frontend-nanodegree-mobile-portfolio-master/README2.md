To successfully run this app. Open index.html in google chrome.
Once open, you should be able to navigate to the pizza app through the link at the bottom of the page
Once inside the pizza app you have the ability to select a size and pizza
Enjoy!



Optimization Outline:

Changes for index.html includ the following:
    Profile Img and Pizzera Img were compressed
    Google analytics and perfmatters.js were givin async
    css was inlined
    css print was given the media=print since it is only used when printing
    google fonts was removed since it wasn't necessary

CHanges for pizza.html include the following:
    bootstrap.css was minified

Changes for main.js include the following:
    function update position was simplified by removing query selectors and placing variable names into the equations instead of the calculation themselves
    resize pizzas had a lot of the calculations done outside of the loops which greatly reduced the time taken to calculate
    reduced the number of background pizzas

