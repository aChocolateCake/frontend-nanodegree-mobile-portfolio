To run, open index.html. From here you can click on Cam's Pizzeria to get to the pizza.html page.

Changes made:


index.html
    changes made to index.html to increase pagespeed to 90 or above. These comments are also noted in index.html:
    
      loading font using an inline js instead of a direct link to the googlfont
      added media tag "print" to print.css link
      inlined all css
      shrunk img sizes of pizzeria.jpg and profilepic.jpg
      moved links to analytics.js and perfmatters.js to bottom of page and set both to sync
    
pizza page
    changes made to main.js to increase fps to 60 or higher. These comments are also noted in main.js:
    
      to increase speed I pulled this method calls out of their loops or function and assigned them to a var instead:
    
      function determineDx
      function changePizzaSizes
      function updatePositions
