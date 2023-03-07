# CS260Simon
The tag in meta data in about.html is new. I never realized you could use viewpoint to adjust how the images showed up relative to the size of the page. 

For the index.html, it asks for a login to play. But what database is it going to reference to actually verify someone?

It is impressive that we are able to make the entire Simon wheel using only HTML. There is a lot more capability to HTML than I realized, it just never gets used because of CSS and JavaScript. 

This excersise really opened my eyes to the potential of HTML, even though it doesn't every get used. I was able to replicate somethings that could actually pass for a really low level website with a few graphics and things. I didn't really think that possible with HTML. 

# CSS NOTES
Using the border-radius tag rounds the corner of the square. Thus, if you set it to 50%, you get a circle. 

To create the wheel for the simon game, you first created a div and then rounded the corners using the border-radius tag. After that another div element was created in the first and this time was laid out using a grid. Then on that grid was put four buttons each formatted to make a quarter circle. Then finally within the grid div another div was made in a simiilar fashion to the first to hold the control center and the score. 

On another note, I have no idea what the center class does. I changed every variable in it and nothing changed. 

When declaring CSS classes you can use something like "footer a" which will apply the css to all a tags only found in footer tags. 

It is amazing everything you can do with bootstrap. A ton of the formatting used wasn't declared in the main.css and was all just imported in from bootstrap. That can save a ton of time if I can figure out how to really use it. 

# Javascript notes
I like how the scores.js gives a really good example of how to make new, complex elements to add to the DOM. A lot of the elements I want in my startup are kind of complex, so this will be really helpful.

The login.js gives a good example of how to get information from a form and then add that to your display using javascript. That will be really helpful. 

Scores makes sense to me, but not super well. It is really useful to look at as examples for a lot of things, from accessing info from local storage and using async functions. 
