---
<div align="center">
 
 # Starfall - AO3 Skin
 Custom AO3 site skins made by me!!
 
</div>

### Welcome!
This repository contains the CSS code for an AO3 skin I created.  
It's inspired by:
* 🌌🌌🌌 (as it appears on apple devices)
* "Constellations" by thevalkyrieflies on Tumblr
* "Neos" by ZerafinaCSS on AO3

---

<div align="center">

## Customization Notes

</div>

Below are a few elements you may want to tweak to better suit your preferences.  
(These are things I mostly couldn’t decide on!)

### ✦ Glow Intensity
The glow on this skin can be changed in a few places.

<b>Globally (Everywhere):</b>
```css
/* Lines 26-27 */
--glow: 0px 0px 7px #a8c7f7;             /* the last value represents intenisty. this can be changed to your liking. */
--glow-sm: 0px 0px 3px #a8c7f7;          /*  just make sure that --glow is a larger value than --glow-sm. */
```
<b>Specific Spots:</b>
Look for the line "text-shadow:" under the section you would like to change.
For example, If I don't like the glow on the Relationship Tags, I would change this line -->
```css
/* Line 373 */
text-shadow: 0px 0px 3px var(--accent)  /* I would change the 3 to a 0 for no glow, 
                                           or a 3 to a 5 if i want it to glow more! */
```
The Tags section can be found starting at Line 354, if you would like to change any others!


### ✦ Freeform Tag Colour
Currently, the freeform tags are slightly darker so they aren’t overwhelming. However, this can make them harder to read.
To increase contrast, you can edit their colour value in the TAGS section (Line 381):

```css
color: var(--accent-lite);   /* Replace "--accent-lite" with a HEX colour of your choice!
                                I recommend #97A3C2 to stay on theme! */
```
---
<div align="center">
  
## To Be Fixed 
As Of April 29th 2026 @ 11:38am
</div>
- Nothing! Yay!

<div align="center">

## To Impliment (Maybe??)
</div>
- TBD...


