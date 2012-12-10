Parallax-Scrolling-in-Two-Lines
===============================

Simple parallax scrolling effect in two lines of javascript
The critical lines
biggerdiv.style.backgroundPosition = '0' +'px ' +(windowScroll/2)+"px";
and
smallerdiv.style.top = 0-(windowScroll/2) + 'px'; 