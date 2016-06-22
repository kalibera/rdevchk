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
  
__Possibly fixed errors between versions 69241 and 69444:__  
&nbsp;&nbsp;  [src/main/eval.c:1558 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1558)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_defineVar  
&nbsp;&nbsp;  [src/main/eval.c:1564 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1564)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_defineVar  
&nbsp;&nbsp;  [src/main/eval.c:1572 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1572)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/eval.c:1576 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1576)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/eval.c:1580 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1580)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/eval.c:1584 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1584)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/eval.c:1588 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1588)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/eval.c:1592 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1592)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_allocVector  
&nbsp;&nbsp;  [src/main/eval.c:1599 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1599)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_defineVar  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_defineVar(?,V,?)  
&nbsp;&nbsp;  [src/main/eval.c:1602 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1602)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_SrcrefPrompt  
&nbsp;&nbsp;  [src/main/eval.c:1603 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1603)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_PrintValue  
&nbsp;&nbsp;  [src/main/eval.c:1604 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1604)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function do_browser  
&nbsp;&nbsp;  [src/main/eval.c:1606 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L1606)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable cell while calling allocating function Rf_eval  
&nbsp;&nbsp;  [src/main/eval.c:5453 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L5453)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable h while calling allocating function Rf_eval  
&nbsp;&nbsp;  [src/main/eval.c:5454 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L5454)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable h while calling allocating function Rf_mkPROMISE  
&nbsp;&nbsp;  [src/main/eval.c:5455 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L5455)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable __cell__107 while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable h while calling allocating function CONS_NR  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable h while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;  [src/main/eval.c:5456 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/eval.c/#L5456)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable h while calling allocating function GETSTACK_PTR_TAG  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable h while calling allocating function Rf_CreateTag  
&nbsp;&nbsp;  [src/main/main.c:1550 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/main.c/#L1550)  
&nbsp;&nbsp;&nbsp;&nbsp;    [PB] has possible protection stack imbalance  
&nbsp;&nbsp;  [src/main/subset.c:1208 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1208)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] allocating function pstrmatch may destroy its unprotected argument (input <arg 2>), which is later used.  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function pstrmatch  
&nbsp;&nbsp;  [src/main/subset.c:1230 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1230)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable input while calling allocating function Rf_translateChar  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_translateChar  
&nbsp;&nbsp;  [src/main/subset.c:1233 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1233)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_warningcall  
&nbsp;&nbsp;  [src/main/subset.c:1234 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1234)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_translateChar  
&nbsp;&nbsp;  [src/main/subset.c:1247 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1247)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable input while calling allocating function Rf_xlength  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_xlength  
&nbsp;&nbsp;  [src/main/subset.c:1250 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1250)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] allocating function pstrmatch may destroy its unprotected argument (input <arg 2>), which is later used.  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function pstrmatch  
&nbsp;&nbsp;  [src/main/subset.c:1281 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1281)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable input while calling allocating function Rf_translateChar  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_translateChar  
&nbsp;&nbsp;  [src/main/subset.c:1284 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1284)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_warningcall  
&nbsp;&nbsp;  [src/main/subset.c:1285 (69241)](https://github.com/wch/r-source/blob/9fe55e21d6b4b953b066a8d4811d90651155a678/src/main/subset.c/#L1285)  
&nbsp;&nbsp;&nbsp;&nbsp;    [UP] unprotected variable x while calling allocating function Rf_translateChar  
  
  
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
  
  
