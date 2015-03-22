Changes made:


index.html
    changes made to index.html to increase pagespeed to 90 or above. These comments are also noted in index.html:
    
      loading font using an inline js instead of a direct link to the googlfont
      added media tag "print" to print.css link
      inlined all css
      shrunk img sizes of pizzeria.jpg and profilepic.jpg
      moved links to analytics.js and perfmatters.js to bottom of page and set both to sync
    
pizza.html
    changes made to pizza.html to increase fps to 60 or higher. These comments are also noted in pizza.html:
    
      to increase speed I pulled this method calls out of their loops or function and assigned them to a var instead:
    
      function determineDx
      function changePizzaSizes
      function updatePositions
