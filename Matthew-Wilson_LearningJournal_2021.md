# Learning Journal

### 16/02/2021

Created a 2D character controller. Encountered small issue where player would not move after I set up the inputs. This was quickly resolved when I realised I had never set up a player movement speed. Adding a variable to contain the movement speed fixed the issue.

### 23/02/2021

Inital plan was to create a 2D pathfinding module. Guides on how to do this on the scale I wanted were all based upon using the A* pathfinding package. As I didn't want my package to rely on an existing one, I decided to switch to a more basic enemy patrol script for this package.

Issue with making the object move correctly. The raycast that is being used to detect the ground keeps triggering for seemingly no reason.
