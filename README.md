# Canvas Particle System

This is a fun side project that I whipped up in my spare time.  I wanted to try out the HTML5 Canvas, and I also wanted to make a semidecent particle system.  So far, this is the result!  The HTML page has instructions, but here they are as well:

## Usage:
*   It currently only works on chrome.
*   Just open the particles.html file in your browser.
*   Hold left click to create a graviton at the mouse.
*   Hold right click to emit new particles.
*   Press 1 to create an obstacle.
*   Press 2 to create a permanent graviton at the mouse.  Note:  Your graviton will turn off all others.
*   Press r to reset the simulation.

### Random info:
I've done a lot of optimizing in order for it to run at decent speeds.  For now, it's only functional on chrome.  The FPS is pretty abysmal in the other browsers.  

There's still more optimization that I could squeeze out of the system, but for right now, it isn't worth it.  Sadly, javascript drawing is extremely slow.  Profiles in Chrome and Firefox show that the particle drawing function takes up 95% of the program execution time.  I may add a 'fast mode' that draws small rectangles instead of an image for the particles.  That was how the system originally worked, and it could handle way more particles.



###Help me learn!
Last note:  If there are any mistakes or inefficiencies in the code, please feel free to make an issue to point them out!  I'd love to learn what could be better :)
