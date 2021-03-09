# Learning Journal

### 16/02/2021

Created a 2D character controller. Encountered small issue where player would not move after I set up the inputs. This was quickly resolved when I realised I had never set up a player movement speed. Adding a variable to contain the movement speed fixed the issue.

### 23/02/2021

Inital plan was to create a 2D pathfinding module. Guides on how to do this on the scale I wanted were all based upon using the A* pathfinding package. As I didn't want my package to rely on an existing one, I decided to switch to a more basic enemy patrol script for this package.

Issue with making the object move correctly. The raycast that is being used to detect the ground keeps failing to trigger for seemingly no reason. After triple checking everything I noticed that I had left the basic box I was using as a place holder with a 3D box collider instead of a 2D one. As the raycast was looking for 2D, it was not detecting the box. I swapped the 3D collider for a 2D one and this fixed the issue.

### 02/03/2021

Created a cel shader. Had a small issue where there were not as many tones showing up as expected. This turned out to caused by the test material being too bright for the tones to show up correctly. Adding customisation options to the shader allowed this to be corrected.
