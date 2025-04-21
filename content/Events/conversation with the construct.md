appears, slams doors shut with telepathy (and locks them)
says something in mysric and repeats it when i spoke in king's common
hum an old song and it sings the lyrics
sing a newer song and it sings along and appears to understand now
"invaders..."
"this place has been brought low by your masters; they killed others, only i remain"
"home no longer, now it is a trap"
(causes ceiling to collapse)
"you know not the masters you serve"
"you are puppets, let me cut your strings"
"you must not reach the heart"
"other... above? how long... (gets crushed by rubble)"

has magic:
- can control things telekenetically by moving its claws (closing door, causing ceiling to collapse)
- can damage/destroy things by conjuring a ring around them
	- it's thin, like a thread (almost 2d), and light blue (faintly glowing) similar to sunlight water
	- doesn't do anything until the ring is complete
	- doesn't appear to instantly destroy it - the pillars started to crumble over time

is not myrsc (a nimiri), even though it has striking similarities:
- core with a crafted exoskeleton
- speaks myrsc
- extremely old
- BUT
- doesn't do any mind control
- much more actively powerful, rather than relying on others
- has telekinesis
- missing the classic mind stone




1. make story ticket
2. write 6 steps as subtasks + comments

1. make sure initialisation + shutdown hooks work + can be used with `python -m vcmodule`
2. extract pystats stuff using c module during shutdown
3. add macros in relevant places (time consuming + hard)
4. add routine for extracting hardware stats from csrs
5. add enter region/leave region macros around "areas of interest" (to be defined)
6. put it all together - format using depyct and output to files

for EVERY macro which increments a counter, add a doc comment explaining what it was counting and why (using a standard prefix so it's easy to grep for)
