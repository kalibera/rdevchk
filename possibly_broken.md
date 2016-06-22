__Many changes between versions 69241 and 69444, the last one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r69444 | ripley | 2015-10-01 09:12:05 +0000 (Thu, 01 Oct 2015) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  correct error message  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
__and the first one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r69241 | pd | 2015-08-31 23:29:06 +0000 (Mon, 31 Aug 2015) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  maintainer-mode changes  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
  
__Possibly introduced errors between versions 69241 and 69444:__  
&nbsp;&nbsp;  [src/main/eval.c:5456 (69444)](https://github.com/wch/r-source/blob/eeac7b453fff991ec36509b87397d5a94897417e/src/main/eval.c/#L5456)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__107 while calling allocating function GETSTACK_PTR_TAG  
  
  
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
  
__Possibly introduced errors between versions 68783 and 69241:__  
&nbsp;&nbsp;  [src/main/util.c:273 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/util.c/#L273)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable rchar while calling allocating function Rf_install  
&nbsp;&nbsp;  [src/main/summary.c:879 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/summary.c/#L879)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable v_nms while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/grep.c:372 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/grep.c/#L372)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_mkCharCE  
&nbsp;&nbsp;  [src/main/grep.c:374 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/grep.c/#L374)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_markKnown  
&nbsp;&nbsp;  [src/main/grep.c:479 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/grep.c/#L479)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_mkCharCE  
&nbsp;&nbsp;  [src/main/grep.c:481 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/grep.c/#L481)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable tok while calling allocating function Rf_markKnown  
  
  
__Many changes between versions 68486 and 68608, the last one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r68608 | pd | 2015-06-30 23:32:35 +0000 (Tue, 30 Jun 2015) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  maintainer-mode changes  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
__and the first one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r68486 | hornik | 2015-06-08 06:44:45 +0000 (Mon, 08 Jun 2015) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  Update for R 3.2.0 release on 2015-06-18.  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
  
__Possibly introduced errors between versions 68486 and 68608:__  
&nbsp;&nbsp;  [src/main/subscript.c:319 (68608)](https://github.com/wch/r-source/blob/ebb4b8e50d6a05d9caaf64441e09afe8206eeb3c/src/main/subscript.c/#L319)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] allocating function Rf_xlength may destroy its unprotected argument (x <arg 1>), which is later used.  
&nbsp;&nbsp;  [src/main/subset.c:1247 (68608)](https://github.com/wch/r-source/blob/ebb4b8e50d6a05d9caaf64441e09afe8206eeb3c/src/main/subset.c/#L1247)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable input while calling allocating function Rf_xlength  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_xlength  
&nbsp;&nbsp;  [src/main/subassign.c:2033 (68608)](https://github.com/wch/r-source/blob/ebb4b8e50d6a05d9caaf64441e09afe8206eeb3c/src/main/subassign.c/#L2033)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable names while calling allocating function Rf_xlength  
  
  
