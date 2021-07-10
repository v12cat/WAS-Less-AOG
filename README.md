# WAS-Less-AOG

A rudimentary attempt at WAS less steer.
It uses rotational velocity from the BNO085 and factors in GPS speed to give an approximation of steer angle.

I found halving proportional steer value and using a decent lookahead helped it to function smoothly. 
IIRC counts per degree needs to be around 120.

It is in very early development and my focus has been on rogue value rejection.
Fancy maths to get a better steer angle curve is way less important than this.

Faster reacting GPS speed woud help.

Select DIFFERENTIAL MODE for ADS to enable it.
Disabled (Single mode) DOESN'T WORK as I need to read the BNO085 in this mode lust to keep the BNO085 happy.

I think this is the version I used maize drilling. It may have variables specific to my installation and there are variables defined that are not used in this version.

I've had LOTS of versions!!

My codding ability does not match my conceptual unserstanding ability either!!
