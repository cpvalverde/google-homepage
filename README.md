Google Homepage

This is my first project trying to builD something in HTML.
For this project I'll be building the google.com homepage using HTML and CSS for styling.
The objective of the project is just for it to look as the google homepage and not to have the same functionality, that's why it has no href on any link.

I did refered to developers tools to check on color values and dimensions (such as padding or text size). Everything else was found by trial and error. Google helped a lot as well.

It did take more time that I thought it would, since I had to redo everything because I was not happy with the structure and it looked disorganized.
Takeaways:
    1. Using 'overflow: hidden' on the menu bar on the top allows for it to be separate from the rest of the content so the google logo does not gets inbetween the left and right menu bar.
    2. Using 'display:flex' in the search bar and the buttons makes it really easy to align them to the center independently of the screen size.
    3. I had a little issue with the navigation bar at the bottom of the page since it made the document wider than the screen size eventhough it had a 'width:100%' value. The structure was basically the same as the top navigation bar but to make it stay at the bottom of the screen I used 'position: absolute' together with 'bottom: 0px' Using this made the elements pile together so using 'width: 100%' was the way to go to spread them as they were before, only it made the nav bar some pixels wider than the screen size. It was fixed adding 'left: 0px' and 'right: 0px'