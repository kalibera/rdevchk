__Many changes between versions 69895 and 70052, the last one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r70052 | maechler | 2016-01-30 16:46:26 +0000 (Sat, 30 Jan 2016) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  rhyper() works for more large parameters  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
__and the first one is:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r69895 | maechler | 2016-01-09 17:40:22 +0000 (Sat, 09 Jan 2016) | 2 lines  
&nbsp;&nbsp;    
&nbsp;&nbsp;  "Links" to "real" change logs  
&nbsp;&nbsp;    
&nbsp;&nbsp;  ------------------------------------------------------------------------  
  
__Possibly introduced errors between versions 69895 and 70052:__  
&nbsp;&nbsp;  [src/main/eval.c:5751 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5751)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__401 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5753 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5753)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__422 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5755 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5755)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__430 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5756 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5756)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__446 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5758 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5758)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__466 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5760 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5760)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__489 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5762 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5762)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__497 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5931 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5931)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__583 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5960 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/eval.c/#L5960)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__587 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/subassign.c:1996 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/subassign.c/#L1996)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable nlist while calling allocating function R_DispatchOrEvalSP  
&nbsp;&nbsp;  [src/main/radixsort.c:1888 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/radixsort.c/#L1888)  
&nbsp;&nbsp;&nbsp;&nbsp;    WARNING Suspicious call (two or more unprotected arguments) to Rf_setAttrib at do_radixsort  
&nbsp;&nbsp;  [src/main/radixsort.c:1895 (70052)](https://github.com/wch/r-source/blob/157e929e9a4534a6f273ae4a496c080a2088ca39/src/main/radixsort.c/#L1895)  
&nbsp;&nbsp;&nbsp;&nbsp;    WARNING Suspicious call (two or more unprotected arguments) to Rf_setAttrib at do_radixsort  
  
  
__Changes between versions 69893 and 69894:__  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r69893 | ripley | 2016-01-09 09:52:07 +0000 (Sat, 09 Jan 2016) | 1 line  
&nbsp;&nbsp;    
&nbsp;&nbsp;  use conistent capitalization for ASCII  
&nbsp;&nbsp;  ------------------------------------------------------------------------  
&nbsp;&nbsp;  r69894 | lawrence | 2016-01-09 14:09:58 +0000 (Sat, 09 Jan 2016) | 3 lines  
&nbsp;&nbsp;    
&nbsp;&nbsp;  experimental new radix sort from Matt Dowle; currently undocumented  
&nbsp;&nbsp;  and unsupported; review pending  
&nbsp;&nbsp;    
&nbsp;&nbsp;  ------------------------------------------------------------------------  
  
__Possibly introduced errors between versions 69893 and 69894:__  
&nbsp;&nbsp;  [src/main/radixsort.c:1824 (69894)](https://github.com/wch/r-source/blob/5fa5966956ce0f9334c8de786b97129adfea3b97/src/main/radixsort.c/#L1824)  
&nbsp;&nbsp;&nbsp;&nbsp;    WARNING Suspicious call (two or more unprotected arguments) to Rf_setAttrib at do_radixsort2  
&nbsp;&nbsp;  [src/main/radixsort.c:1827 (69894)](https://github.com/wch/r-source/blob/5fa5966956ce0f9334c8de786b97129adfea3b97/src/main/radixsort.c/#L1827)  
&nbsp;&nbsp;&nbsp;&nbsp;    WARNING Suspicious call (two or more unprotected arguments) to Rf_setAttrib at do_radixsort2  
  
  
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
  
  
