# nittany-beamer

Nittany Beamer Theme
Colors are PSU Brand Colors

## Version 0.8

Two distinct title pages:
- Fancy title page with 3 logos
- Simple Text title page
  
Title page set by parameters on title frame entry.  "nittanytitle" for fancy, "nittany" for simple.  "nittanytitle" also needs the b parameter.

\frame[b,nittanytitle]{\titlepage}

\frame[nittany]{\titlepage}

Current version fancy title only works on 4:3, changing to flexible next version.

## Version 0.9

Now (should) work in all aspect rations for fancy title page.  Tested 4:3, 16:9, 16:10.
Rejiggered load order to fix weirdness with subsequent headers. 
