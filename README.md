# AO3 Skins
Custom AO3 site skins made by me!!

## Hello!

This repository contains the CSS code for an AO3 skin I created.  
It is heavily inspired by *Constellations* by thevalkyrieflies on Tumblr.

To make customization easier, I’ve added comments throughout the code.  
AO3 automatically removes these comments when applied (lucky us!!) so don't worry about removing them.


## Customization Notes
Below are a few elements you may want to tweak to better suit your preferences.  
(These are things I mostly couldn't decide on!)

### ✦ Relationship Tag Glow
You can adjust the glow effect by changing the last value here (line 348):

```css
text-shadow: 0px 0px 3px var(--accent);
```
Increasing the last number will increase the glow, while decreasing the value softens the effect

### ✦ Overall Glow Intensity
You can also customize the glow used throughout the skin! This can be changed in lines 39-40 by increasing/reducing the last value in the line.

```css
--glow:    0px 0px 7px #a8c7f7;
--glow-sm: 0px 0px 3px #a8c7f7;
```
Just make sure that --glow stays smaller than --glow-sm

### ✦ Freeform Tag Colour
Currently, the freform tags are slightly dark so they aren't overwhelming, however I cunderstand that this makes it harder to read! To increase the contrast between the tags and the background, edit their colour value in the tags section (line ---)

```css
color: var(--accent-lite);
```

## TO BE FIXED
* Filter Background Colour on Mobile
