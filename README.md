---
<div align="center">
 
 # AO3 Skins
</div>
<div align="center" style="font-size: 1.5em; margin-top: 0.2em;">
  Custom AO3 site skins made by me!!
</div>

### Welcome!
This repository contains the CSS code for an AO3 skin I created.  
It is heavily inspired by *Constellations* by thevalkyrieflies on Tumblr.

To make customization easier, I’ve added comments throughout the code.  
AO3 automatically removes these comments when applied (lucky us!!), so don't worry about removing them.

**NOTE:** When mentioning line numbers, these are as they appear in GitHub before AO3 removes comments.  
Keep in mind that the numbers will significantly decrease when added to AO3.

---

<div align="center">

## Customization Notes

</div>

Below are a few elements you may want to tweak to better suit your preferences.  
(These are things I mostly couldn’t decide on!)

### ✦ Relationship Tag Glow
You can adjust the glow effect by changing the last value here (line 348):

```css
text-shadow: 0px 0px 3px var(--accent);   /* last number changes intensity (higher # = higher glow, lower # = less glow) */
```

### ✦ Overall Glow Intensity
You can also customize the glow used throughout the skin! This can be changed in lines 39-40 by increasing/reducing the last value in the line.

```css
--glow:    0px 0px 7px #a8c7f7;     /* Just make sure that --glow is a larger value than --glow-sm */
--glow-sm: 0px 0px 3px #a8c7f7;       
```

### ✦ Freeform Tag Colour
Currently, the freeform tags are slightly darker so they aren’t overwhelming. However, this can make them harder to read.
To increase contrast, you can edit their colour value in the TAGS section (line 357):

```css
color: var(--accent-lite);   /* Replace "--accent-lite" with a HEX colour of your choice!
                                I recommend #97A3C2 to stay on theme! */
```
---
<div align="center">
  
## ⚠️ To Be Fixed ⚠️

</div>

* Filter Background Colour on Mobile (Doesn't match theme/desktop version)
