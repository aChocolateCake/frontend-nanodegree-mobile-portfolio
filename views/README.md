improvements made to main.js to increase FPS(these are noted in the main.js file):

in the function updatedPostions, pulled document.body.scrollTop out of the loop and assigned to var theTop.
I did the same thing with changePizzaSizes and determineDx - created variables allContainers and theWidth to hold these calls.