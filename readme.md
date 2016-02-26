# HTML Jeopardy

This is a Jeopardy-like app meant to be run locally. The following four files
need to be in the same folder to run it:

* jeopardy.html
* jeopardy.css
* jeopardy.js
* jquery-2.1.0.min.js

No internet connection is needed. Just open `jeopardy.html` and it'll run out
of the box (missing media files notwithstanding).

## Known Issues

* Sometimes the Final Jeopardy button disappears when clues are opened and closed
  too quickly.
* Chrome doesn't render this character
    
    &#9646;
  
  with the right dimensions, so the characters appear off screen when the answer timer
  starts. They eventually tick down, but it takes a moment. Does not occur in Firefox
  and IE.
* Overlapping depth isn't sorted right on Chrome when hovering over the clues on the
  board. Works correctly in Firefox and IE.
* Chrome and Safari use weird colored symbols for some Unicode values. Does not occur
  in Firefox and IE.
* Only tested on desktop Chrome, IE, and Firefox. Use in other browsers at your own risk.
