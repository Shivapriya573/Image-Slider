Javascript Code
The JavaScript code adds the interactive functionality to the Image Slider.
First, the code selects the slides, images, navigation buttons, and dots container from the HTML. 
The index variable keeps track of the currently displayed image.

The code creates navigation dots dynamically based on the number of images and adds click events to them. 
The showSlide() function changes the current slide by using translateX() and also updates the active dot. 
The previous and next buttons call this function to move through the images.
Finally, setInterval() automatically changes the slide every three seconds, creating a continuous image carousel.
