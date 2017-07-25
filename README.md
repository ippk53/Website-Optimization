## Website Performance Optimization Project

This project was completed for Udacity's Front End Nanodegree Program. The goal of the project was to (index.html) achieves a PageSpeed score of at least 90 for Mobile and Desktop and optimize views/js/main.js make views/pizza.html render with a consistent frame-rate at 60fps when scrolling.
PageSpeed Results : 96/100 for Mobile and 97/100 for Desktop
### Getting started
Viewing project at https://ippk53.github.io/website-optimization/

#### Tools Used
ImageOptim
Chrome Dev Tool
PageSpeed Tools

#### List of Optimizations:
index.html:
- minify print.css and print css with media query "print"
- minify style.css and inline
- JS minified
- images optimized
- Remove Google fonts
- Async analytics

/views/pizza.html:
- images optimized

/views/css/style.css:
-minified css and
- added will-change property to class "mover"

views/js/main.js:
- use getElementByClass instead of querySelectorAll
- mover pizzas saved in "var items"
- Used requestAnimationFrame to call updatePositions on scroll
- Reduced number of pizzas being created to 40

Resources

Udacity
Google Developer's Rendering Performance:https://developers.google.com/web/fundamentals/performance/rendering/
Paul Lewis's Scrolling Performance: https://www.html5rocks.com/en/tutorials/speed/scrolling/