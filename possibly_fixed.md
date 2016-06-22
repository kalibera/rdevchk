__Many changes between versions 68783 and 69241, the last one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r69241 | pd | 2015-08-31 23:29:06 +0000 (Mon, 31 Aug 2015) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  maintainer-mode changes  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
__and the first one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r68783 | hornik | 2015-08-01 05:12:25 +0000 (Sat, 01 Aug 2015) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  Remove re-saved other data files at the end of re-saving.  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
  
__Possibly fixed errors between versions 68783 and 69241:__  
&nbsp;&nbsp;  [src/main/util.c:273 (68783)](https://github.com/wch/r-source/blob/94d2f8a4f59b5bc6ce1ddef671fe195a48e3ba0d/src/main/util.c/#L273)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable rchar while calling allocating function Rf_install  
&nbsp;&nbsp;  [src/main/summary.c:879 (68783)](https://github.com/wch/r-source/blob/94d2f8a4f59b5bc6ce1ddef671fe195a48e3ba0d/src/main/summary.c/#L879)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable v_nms while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/grep.c:372 (68783)](https://github.com/wch/r-source/blob/94d2f8a4f59b5bc6ce1ddef671fe195a48e3ba0d/src/main/grep.c/#L372)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_mkCharCE  
&nbsp;&nbsp;  [src/main/grep.c:374 (68783)](https://github.com/wch/r-source/blob/94d2f8a4f59b5bc6ce1ddef671fe195a48e3ba0d/src/main/grep.c/#L374)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_markKnown  
&nbsp;&nbsp;  [src/main/grep.c:479 (68783)](https://github.com/wch/r-source/blob/94d2f8a4f59b5bc6ce1ddef671fe195a48e3ba0d/src/main/grep.c/#L479)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_mkCharCE  
&nbsp;&nbsp;  [src/main/grep.c:481 (68783)](https://github.com/wch/r-source/blob/94d2f8a4f59b5bc6ce1ddef671fe195a48e3ba0d/src/main/grep.c/#L481)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_markKnown  
  
  
