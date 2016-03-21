# P4-Website-Optimization

1.CHANGES IN INDEX.HTML
- Add media="print" to print.css
- Minify print.css
- Inline style.css
- Put script for perfmatters.js and Google analytics just before </body> with async attribute
- Load Google Font asynchchronously
- Optimize all images with ImageOptim
- Create a new image for Cam´s Pizzeria it was too big
- 
2. CHANGES IN VIEW/JS/MAIN.JS
- Change all the querySelector for getElementById or getElementsByClassName
- In updatePosition() remove and create variables out of the loop
- Calculate size of the window so the browser paint only the pizzas that are needed
