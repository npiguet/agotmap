agotmap
=======

A PBF JavaScript map for "A game of thrones"

###The Map:

- [2nd Edition setup with house cards.](http://tinyurl.com/9TNrD9ikL2WTjf4X9C0V)
- [2nd Edition + Dance with Dragons Expansion setup with house cards.](http://tinyurl.com/mOwkgPPeJfoCtokpimYU)
- [2nd Edition + A Feast for Crows Expansion setup (maybe with mistakes, please say if you see one).](http://tinyurl.com/zUmA6i5xQfMETKZSIxHU)

###Usage:

On top of the screen is a semi transparent black bar; when you move your mouse cursor over it a menu should slide down.
Here you can set all things I could think of. The fields with default values should be self-explanatory.

###Order Tokens:

To place an order token, go to the menu for the appropiate side. Enter the area, then a colon and a space and the order you want. To place an order in a port, just write the area name and append "- Port". The orders are case-insensitive and named as follows:

- *Support*: Support-1, s, support
- *Support**: Support-2, s+1, s\*, s+1\*, support+1, support\*, support+1\*
- *Defend*: Defend-1, d, d+1, defend, defend+1
- *Defend**: Defend-2, d+2, d\*, d+2\*, defend+2, defend\*, defend+2\*
- *Raid*: Raid-1, r, raid
- *Raid**: Raid-2, r\*, raid\*
- *Consolidate Power*: Power-1, cp
- *Consolidate Power**: Power-2, cp\*
- *March-1*: March-0, m-1
- *March+0*: March-1, m+0
- *March+1**: March-2, m+1, m\*, m+1\*

For example, a March+1 in Winterfell, a March-1 in White Harbor's Port, and a Raid* in the Shivering Sea would be written as:

- Winterfell: March-2
- White Harbor - Port: March-0
- The Shivering Sea: Raid-2

###Power Tokens:
To place a power token in an area, just add the area's name in the appropriate textfield. One area per line.

###Placing Units:
Units work like orders. The names are:

- *Footman*: Footman, FM
- *Knight*: Knight, KN
- *Siege Engine*: Siege, SE
- *Ship*: Ship, SH

To place a routed unit, add the prefix "routed-" to the unit's name. e.g. "routed-Footman" or "routed-FM".

###VSB and Raven tokens:
Click on the icon below the influence tracks to toggle whether the token has been used.

###House Cards:
Images or text representing the cards can be entered in the Influence Tracks/Supply tab, one line per card. The cards will appear on the side tabs, and can be clicked to toggle whether they've been used.

###How to Share Your Board:
After every change, a tinyurl.com link appears in the settings panel. This link will point to the updated board. Occasionally, tinyurl will not create a valid link; checking to make sure it works is advised.

###Attention:
Empty lines in one of the text areas will cause the map to silently fail. Don't use empty lines.

###Browser Support:
It has been tested in Chrome and Firefox. It should work in IE 10, but old browsers are not supported.

###Hint:
Feel free to play around. You can't really break anything as long as someone has the link to the version before you destroyed it ;-)
