Launching the Project:
1) User can either clone the repository or download the zip file and then navigate to their local copy of the index.html file.

2) Another option would be to use the live version hosted here : http://farazpatankar.github.io/Udacity-Project-4/

I decided to do the project from scratch all over again. I have listed the changes I have made to the original files below, the changes are also present in the form of comments in the actual files.
The pagespeed scores for index.html are above 90 for both Mobile and Desktop.
The time to resize pizzas is less than 5ms and the page scrolls at 60fps.
I have also provided comments in the main.js file that explain the changes I have made.

Submission 2:
1) Updated readme with launch instructions.
2) Added a separate pizzeria image file to improve user experience on pizza.html
3) I included the fonts because an instructor on the forums encouraged us to try and include them. Although my initial idea was what you suggested, which was getting rid of them :P

Submission 1:

Optimizations in index.html :
1) Inlined the style.css file and added media="print" to the print stylesheet.
2) Added the async tag to the analytics script.
3) Optimized font delivery by inlining the request.
4) Ran the code and the images through a minifier and provided a separate commentedindex.html file for readability.

Optimizations in pizza.html :
1) Defined viewport.
2) Minified original file and provided a separate commentedpizza.html file for readability.

Optimizations in main.js :
1) Changed the way pizza size and pizza containers were being handled.
2) Changed the number of pizzas being created from 200 to 32.
3) Minified original file and provided a separated commentedmain.js file for readability.

Other optimizations :
1) Minfied print.css, perfmatter.js, bootstrap-grid.css and both style.css files.
2) Ran all images through image optimizers.