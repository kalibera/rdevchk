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
  
  
