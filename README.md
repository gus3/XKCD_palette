# XKCD_palette
Gimp palette for the XKCD color-naming project in 2010

Randall Munroe did a survey in 2010, asking people to name the colors they
saw. There were two great big take-aways from this survey:

1. Women usually have a lot more color discernment than men.

2. Nobody taking the survey knew how to spell "fuchsia".

Once the survey was finished, there was a lot of effort put into collating and
cataloging the responses. It involved sorting out spurious responses like
"IDK" or "baby giraffe poop", correcting occasional mis-spellings (like the
typical "fuschia"), and ignoring letter case. The collation then got its first
machine-readable representation, as a pallete expressed in C#.

This Gimp palette is based upon Rune Grimstad's C# source, but I took it one
step further: sort by HSV instead of RGB. HSV is the best way to view a
palette on-screen, because hue is our strongest general indicator of color.

If you would like to use this crazy palette, copy the file "XKCD_palette.gmp"
to ~/.config/GIMP/{VERSION}/palettes/. The palette name in Gimp will be
"XKCD", near the top of the palette list. In my current desktop setup
(Slackware-current), the {VERSION} is 2.10.
