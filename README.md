# Lua-Pogo-stick-scripts

This pogo system uses conventional player events to work as a pogo stick

The player is set to infintley jump and holding down spacebar increases the jump power increasing the height of each bounce the longer it is held down until it reaches a set limit
Over time the jump power will decay until it reaches a set minimum value

Instead of using values and numbers of decrease I instead used rate of increase/decrease to dictate bounce and bounce decay because having weird values 
such as -3 for example has the potential to decrease or increase a player's jump power above or below the min/max. There's probably a better way of doing this but this
fix seems pretty good so far the only downside is that I have less control of the rates of pogo increase and decrease because I basically need to eyeball the
measurements for rates.

Mobile support isn't taken into consideration for this script but maybe sometimes in the near future it will be added.

Instead of having animations and stuff like that I instead chose to weld a pogo stick onto the player with no collisions and manually change the rotation of the limbs to make it look like the player
is actually holding on to a pogo stick. I don't know if this method is better or worse but I'm sticking with it for now because I really don't know how to work with animations and complex welds.


