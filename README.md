### The Lisp Machine console font
This is a version of the monospace font used on the consoles of the MIT, Symbolics, and (I believe) Texas Instruments Lisp Machines. It is based on Juanjo Garcia's PCF bitmap conversion of the CPTFONT from the original MIT Lisp Machines. The fonts in this repository are vector fonts based on the 13-point PCF included in the src directory. The FontForge file for the conversion is also included as `src/LispM.sfd`.

#### Using this font
This font was originally intended for display at a 13-point size without any antialiasing; it should look most authentic with those settings. As a vector font, it looks good at bigger point sizes with or without antialiasing.

#### Todo
* Fix path intersection errors
* Fix the shade glyph
* More testing
* Check accuracy against a Symbolics Lisp Machine

