This is a fun animation done using HTML , CSS and javascript.
The JavaScript code in this example provides the functionality for the Start, Stop, and Reset buttons to control the animation. Here’s the logic behind it:

Selecting Elements: The document.querySelectorAll('.bar') line selects all elements with the class name ‘bar’. These elements are stored in the bars variable as a NodeList.

Start Function: The start function sets the animationPlayState property of each bar to “running”. This starts or resumes the animation.

Stop Function: The stop function sets the animationPlayState property of each bar to “paused”. This pauses the animation.

Reset Function: The reset function sets the height of each bar to “200px” and clears the animation by setting it to an empty string. This resets the animation to its full size.
