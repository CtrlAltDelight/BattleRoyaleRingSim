# BattleRoyaleRingSim
Simulates the ring closing in a battle royale game such as Apex Legends.

## Quick Start
#### Make sure sdl2 and sdl2_image are installed
Arch Linux
~~~
sudo pacman -S sdl2 sdl2_image
~~~

Use the makefile to make the executable
~~~
TODO Have not created the makefile at the time of writing this.
~~~

## Background
### SLD2
This is my first time using a graphics library in C. 

I have chosen to use SDL2 for a few reasons:
+ I am also interested in making games, so I could potentially use it in other projects for that purpose.
+ It seems prevalent, as in a lot of people use it. This could be a sign that it works well for a lot of people and there is probably a good support structure around it.

### Thoughts going into this
As I was playing Apex Legends, I wondered how the next circle was able to appear anywhere and not just the center of the previous circle. 

How do the edges of the previous circle seem to collapse inwards at the same rate from all sides, but end up becoming a circle at a non-centered location?

It's something that I don't quite understand right away, though I have some hypothesis on how it might work, so I decided this might be a fun project.

