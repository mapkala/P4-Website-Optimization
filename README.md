### P4-Website Performance Optimisation Portfolio Project

You will find 2 folders: `src` and`dist`. The first one contain all the original files. The second one all the files with my modifications. 
For index.html the goal was to score over 90 in [Google PageSpeed Insight](https://developers.google.com/speed/pagespeed/insights/) and for pizza.html achieve a frame rate at 60fps when scrolling the page and resize the pizzas in less than 5ms.

You can see the result [here](https://github.com/mapkala/P4-Website-Optimization)  

1.CHANGES IN INDEX.HTML

- Add media="print" to print.css
- Minify print.css
- Inline style.css
- Put script for perfmatters.js and Google analytics just before </body> with async attribute
- Load Google Font asynchchronously
- Optimize all images with ImageOptim
- Create a new image for Cam´s Pizzeria it was too big

2. CHANGES IN VIEW/JS/MAIN.JS

- Change all the querySelector for getElementById or getElementsByClassName
- In function updatePosition(), changePizzaSizes() remove and create variables out of the loop
- Calculate size of the window so the browser paint only the pizzas that are needed.
