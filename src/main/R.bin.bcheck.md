  
__Function CONS_NR__  
  [UP] unprotected variable car while calling allocating function GetNewPage [src/main/memory.c:2267](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2267)  
  [UP] unprotected variable cdr while calling allocating function GetNewPage [src/main/memory.c:2267](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2267)  
  
__Function DeleteListElements__  
  [UP] unprotected variable xnames while calling allocating function Rf_allocVector [src/main/subassign.c:462](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L462)  
  
__Function DeleteOneVectorListItem__  
  [UP] unprotected variable xnames while calling allocating function Rf_allocVector [src/main/subassign.c:1595](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L1595)  
  
__Function HashAdd__  
  [UP] unprotected variable val while calling allocating function Rf_cons [src/main/saveload.c:865](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/saveload.c/#L865)  
  
__Function KeywordLookup__  
  [PB] has possible protection stack imbalance [src/main/gram.c:4131](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L4131)  
  
__Function NumericValue__  
  [PB] has possible protection stack imbalance [src/main/gram.c:4533](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L4533)  
  
__Function R_DispatchOrEvalSP__  
  [UP] unprotected variable prom while calling allocating function Rf_DispatchOrEval [src/main/subassign.c:1463](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L1463)  
  
__Function R_DispatchOrEvalSP5373__  
  [UP] unprotected variable prom while calling allocating function Rf_DispatchOrEval [src/main/subset.c:636](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subset.c/#L636)  
  
__Function R_FinalizeSrcRefState__  
  [PB] has negative depth [src/main/gram.c:3539](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3539)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3573](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3573)  
  
__Function R_InitSrcRefState__  
  [PB] has possible protection stack imbalance [src/main/gram.c:3534](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3534)  
  
__Function R_ReplDLLdo1__  
  [PB] manipulates PPStackTop directly results will be incomplete [src/main/main.c:350](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/main.c/#L350)  
  [UP] manipulates PPStackTop directly, results will be incomplete [src/main/main.c:350](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/main.c/#L350)  
  
__Function R_restore_globals__  
  [PB] restores PPStackTop from uninitialized local variable [src/main/context.c:170](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/context.c/#L170)  
  [UP] manipulates PPStackTop directly, results will be incomplete [src/main/context.c:170](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/context.c/#L170)  
  
__Function R_subassign3_dflt__  
  [UP] unprotected variable names while calling allocating function Rf_xlength [src/main/subassign.c:2091](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2091)  
  [UP] unprotected variable names while calling allocating function Rf_NonNullStringMatch [src/main/subassign.c:2100](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2100)  
  [UP] unprotected variable names while calling allocating function Rf_allocVector [src/main/subassign.c:2107](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2107)  
  [UP] unprotected variable names while calling allocating function Rf_allocVector [src/main/subassign.c:2108](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2108)  
  [UP] unprotected variable names while calling allocating function Rf_NonNullStringMatch [src/main/subassign.c:2130](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2130)  
  [UP] unprotected variable names while calling allocating function Rf_allocVector [src/main/subassign.c:2146](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2146)  
  [UP] unprotected variable names while calling allocating function Rf_allocVector [src/main/subassign.c:2147](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subassign.c/#L2147)  
  
__Function R_tryEval__  
  [PB] has negative depth [src/main/context.c:762](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/context.c/#L762)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/context.c:762](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/context.c/#L762)  
  [PB] has possible protection stack imbalance [src/main/context.c:764](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/context.c/#L764)  
  
__Function Rf_DispatchGroup__  
  [UP] ignoring variable lgr as it has address taken, results will be incomplete   
  [UP] ignoring variable lmeth as it has address taken, results will be incomplete   
  [UP] ignoring variable lsxp as it has address taken, results will be incomplete   
  [UP] ignoring variable rgr as it has address taken, results will be incomplete   
  [UP] ignoring variable rmeth as it has address taken, results will be incomplete   
  [UP] ignoring variable rsxp as it has address taken, results will be incomplete   
  
__Function Rf_InitMemory__  
  [PB] manipulates PPStackTop directly results will be incomplete [src/main/memory.c:2010](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2010)  
  [UP] manipulates PPStackTop directly, results will be incomplete [src/main/memory.c:2010](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2010)  
  
__Function Rf_InitTypeTables__  
  [UP] unprotected variable rchar while calling allocating function Rf_install [src/main/util.c:273](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/util.c/#L273)  
  
__Function Rf_NewEnvironment__  
  [UP] unprotected variable namelist while calling allocating function GetNewPage [src/main/memory.c:2310](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2310)  
  [UP] unprotected variable rho while calling allocating function GetNewPage [src/main/memory.c:2310](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2310)  
  [UP] unprotected variable valuelist while calling allocating function GetNewPage [src/main/memory.c:2310](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2310)  
  
__Function Rf_ReplIteration__  
  [PB] manipulates PPStackTop directly results will be incomplete [src/main/main.c:223](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/main.c/#L223)  
  [UP] manipulates PPStackTop directly, results will be incomplete [src/main/main.c:223](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/main.c/#L223)  
  
__Function Rf_cons__  
  [UP] unprotected variable car while calling allocating function GetNewPage [src/main/memory.c:2245](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2245)  
  [UP] unprotected variable cdr while calling allocating function GetNewPage [src/main/memory.c:2245](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2245)  
  
__Function Rf_initStack__  
  [PB] manipulates PPStackTop directly results will be incomplete [src/main/memory.c:3178](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L3178)  
  [UP] manipulates PPStackTop directly, results will be incomplete [src/main/memory.c:3178](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L3178)  
  
__Function Rf_matchArgs__  
  [PB] has too high protection stack depth results will be incomplete  
  [UP] protect stack is too deep, unprotecting all variables, results will be incomplete  
  [PB] has possible protection stack imbalance [src/main/match.c:388](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/match.c/#L388)  
  
__Function Rf_mkPROMISE__  
  [UP] unprotected variable expr while calling allocating function GetNewPage [src/main/memory.c:2342](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2342)  
  [UP] unprotected variable rho while calling allocating function GetNewPage [src/main/memory.c:2342](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L2342)  
  
__Function Rf_vectorIndex__  
  [UP] allocating function Rf_xlength may destroy its unprotected argument (x <arg 1>), which is later used. [src/main/subscript.c:312](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/subscript.c/#L312)  
  
__Function Rf_yyparse__  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2174](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2174)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2179](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2179)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2184](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2184)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2189](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2189)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2194](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2194)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2199](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2199)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2204](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2204)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2209](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2209)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2214](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2214)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2219](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2219)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2224](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2224)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2229](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2229)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2234](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2234)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2239](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2239)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2244](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2244)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2249](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2249)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2254](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2254)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2259](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2259)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2264](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2264)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2269](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2269)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2274](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2274)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2279](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2279)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2284](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2284)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2289](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2289)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2294](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2294)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2299](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2299)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2304](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2304)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2309](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2309)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2314](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2314)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2319](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2319)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2324](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2324)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2329](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2329)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2334](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2334)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2339](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2339)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2344](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2344)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2349](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2349)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2354](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2354)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2359](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2359)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2364](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2364)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2369](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2369)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2374](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2374)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2379](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2379)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2384](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2384)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2389](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2389)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2394](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2394)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2399](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2399)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2404](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2404)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2409](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2409)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2414](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2414)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2419](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2419)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2424](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2424)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2439](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2439)  
  [UP] allocating function setId may destroy its unprotected argument (yyval), which is later used. [src/main/gram.c:2444](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2444)  
  
__Function RunFinalizers__  
  [UP] unprotected variable next while calling allocating function Rf_endcontext [src/main/memory.c:1416](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/memory.c/#L1416)  
  
__Function StringValue__  
  [PB] has possible protection stack imbalance [src/main/gram.c:4894](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L4894)  
  
__Function SymbolValue__  
  [PB] has possible protection stack imbalance [src/main/gram.c:4990](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L4990)  
  
__Function applydefine__  
  [UP] unprotected variable saverhs while calling allocating function Rf_endcontext [src/main/eval.c:2126](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L2126)  
  
__Function bcEval__  
  [UP] ignoring variable sa as it has address taken, results will be incomplete   
  [UP] ignoring variable sa152 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa162 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa181 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa204 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa227 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa249 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa270 as it has address taken, results will be incomplete   
  [UP] ignoring variable sa280 as it has address taken, results will be incomplete   
  [UP] ignoring variable sb as it has address taken, results will be incomplete   
  [UP] ignoring variable sb182 as it has address taken, results will be incomplete   
  [UP] ignoring variable sb205 as it has address taken, results will be incomplete   
  [UP] ignoring variable sb228 as it has address taken, results will be incomplete   
  [UP] ignoring variable sb250 as it has address taken, results will be incomplete   
  [UP] unprotected variable __cell__ while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5485](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5485)  
  [UP] unprotected variable __cell__100 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5493](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5493)  
  [UP] unprotected variable __cell__107 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5517](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5517)  
  [UP] unprotected variable __cell__112 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5527](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5527)  
  [UP] unprotected variable __cell__115 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5533](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5533)  
  [UP] unprotected variable __cell__118 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5535](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5535)  
  [UP] unprotected variable __cell__121 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5536](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5536)  
  [UP] unprotected variable __cell__124 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5537](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5537)  
  [UP] unprotected variable __cell__397 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5688](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5688)  
  [UP] unprotected variable __cell__418 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5690](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5690)  
  [UP] unprotected variable __cell__426 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5692](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5692)  
  [UP] unprotected variable __cell__442 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5693](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5693)  
  [UP] unprotected variable __cell__462 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5695](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5695)  
  [UP] unprotected variable __cell__485 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5697](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5697)  
  [UP] unprotected variable __cell__493 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5699](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5699)  
  [UP] unprotected variable __cell__579 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5868](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5868)  
  [UP] unprotected variable __cell__583 while calling allocating function GETSTACK_PTR_TAG [src/main/eval.c:5897](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/eval.c/#L5897)  
  
__Function do_Math2__  
  [UP] ignoring variable res as it has address taken, results will be incomplete   
  
__Function do_anyNA__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_asatomic__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_asvector__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_attributesgets__  
  [UP] unprotected variable names while calling allocating function Rf_allocVector [src/main/attrib.c:1302](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1302)  
  [UP] unprotected variable names while calling allocating function Rf_shallow_duplicate [src/main/attrib.c:1309](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1309)  
  [UP] unprotected variable names while calling allocating function Rf_setAttrib(?,S:names,?) [src/main/attrib.c:1323](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1323)  
  [UP] unprotected variable names while calling allocating function Rf_setAttrib(?,S:dim,?) [src/main/attrib.c:1340](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1340)  
  [UP] unprotected variable names while calling allocating function Rf_setAttrib(V,S:dim,?) [src/main/attrib.c:1340](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1340)  
  [UP] unprotected variable names while calling allocating function Rf_installTrChar [src/main/attrib.c:1346](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1346)  
  [UP] unprotected variable names while calling allocating function Rf_setAttrib [src/main/attrib.c:1346](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1346)  
  [UP] unprotected variable names while calling allocating function Rf_setAttrib(V,?,?) [src/main/attrib.c:1346](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/attrib.c/#L1346)  
  
__Function do_cum__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_dput__  
  [PB] has negative depth [src/main/deparse.c:345](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L345)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/deparse.c:345](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L345)  
  [PB] has possible protection stack imbalance [src/main/deparse.c:381](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L381)  
  
__Function do_grepraw__  
  [PB] has negative depth [src/main/grep.c:1181](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L1181)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/grep.c:1181](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L1181)  
  [PB] has possible protection stack imbalance [src/main/grep.c:1343](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L1343)  
  
__Function do_isfinite__  
  [PB] has negative depth [src/main/coerce.c:2334](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2334)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/coerce.c:2334](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2334)  
  [PB] has possible protection stack imbalance [src/main/coerce.c:2336](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2336)  
  
__Function do_isinfinite__  
  [PB] has negative depth [src/main/coerce.c:2406](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2406)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/coerce.c:2406](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2406)  
  [PB] has possible protection stack imbalance [src/main/coerce.c:2408](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2408)  
  
__Function do_isna__  
  [PB] has negative depth [src/main/coerce.c:2075](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2075)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/coerce.c:2075](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2075)  
  [PB] has possible protection stack imbalance [src/main/coerce.c:2078](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2078)  
  
__Function do_isnan__  
  [PB] has negative depth [src/main/coerce.c:2270](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2270)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/coerce.c:2270](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2270)  
  [PB] has possible protection stack imbalance [src/main/coerce.c:2273](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/coerce.c/#L2273)  
  
__Function do_log1arg__  
  [UP] ignoring variable res as it has address taken, results will be incomplete   
  [UP] unprotected variable tmp while calling allocating function Rf_DispatchGroup [src/main/arithmetic.c:1550](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/arithmetic.c/#L1550)  
  
__Function do_log_builtin__  
  [UP] ignoring variable res as it has address taken, results will be incomplete   
  
__Function do_logic3__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_nextmethod__  
  [UP] ignoring variable callenv as it has address taken, results will be incomplete   
  [UP] ignoring variable defenv as it has address taken, results will be incomplete   
  [UP] ignoring variable generic as it has address taken, results will be incomplete   
  [UP] ignoring variable group as it has address taken, results will be incomplete   
  [UP] ignoring variable klass as it has address taken, results will be incomplete   
  [UP] ignoring variable method as it has address taken, results will be incomplete   
  
__Function do_range__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_readDCF__  
  [UP] protect stack is too deep, unprotecting all variables, results will be incomplete  
  
__Function do_seq_along__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_sprintf__  
  [UP] protect stack is too deep, unprotecting all variables, results will be incomplete  
  [UP] unsupported form of unprotect, unprotecting all variables, results will be incomplete [src/main/sprintf.c:454](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/sprintf.c/#L454)  
  
__Function do_strsplit__  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:202](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L202)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:209](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L209)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:216](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L216)  
  [UP] unprotected variable tok while calling allocating function Rf_translateCharUTF8 [src/main/grep.c:222](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L222)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:225](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L225)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:226](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L226)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:230](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L230)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:233](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L233)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:234](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L234)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:250](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L250)  
  [UP] unprotected variable tok while calling allocating function Rf_mkCharCE [src/main/grep.c:254](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L254)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:257](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L257)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:261](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L261)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:266](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L266)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:274](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L274)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:278](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L278)  
  [UP] unprotected variable tok while calling allocating function Rf_translateCharUTF8 [src/main/grep.c:290](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L290)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:294](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L294)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:305](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L305)  
  [UP] unprotected variable tok while calling allocating function Rf_translateCharUTF8 [src/main/grep.c:312](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L312)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:315](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L315)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:316](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L316)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:320](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L320)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:323](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L323)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:324](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L324)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:342](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L342)  
  [UP] unprotected variable tok while calling allocating function Rf_mkCharCE [src/main/grep.c:363](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L363)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:365](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L365)  
  [UP] unprotected variable tok while calling allocating function Rf_mkCharCE [src/main/grep.c:372](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L372)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:374](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L374)  
  [UP] unprotected variable tok while calling allocating function Rf_translateCharUTF8 [src/main/grep.c:389](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L389)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:393](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L393)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:410](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L410)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:416](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L416)  
  [UP] unprotected variable tok while calling allocating function Rf_translateCharUTF8 [src/main/grep.c:423](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L423)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:426](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L426)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:427](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L427)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:431](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L431)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:434](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L434)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:435](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L435)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:453](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L453)  
  [UP] unprotected variable tok while calling allocating function Rf_mkCharCE [src/main/grep.c:473](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L473)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:475](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L475)  
  [UP] unprotected variable tok while calling allocating function Rf_mkCharCE [src/main/grep.c:479](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L479)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:481](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L481)  
  [UP] unprotected variable tok while calling allocating function Rf_wtransChar [src/main/grep.c:501](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L501)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:509](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L509)  
  [UP] unprotected variable tok while calling allocating function Rf_wtransChar [src/main/grep.c:512](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L512)  
  [UP] unprotected variable tok while calling allocating function tre_regwexec [src/main/grep.c:518](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L518)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:526](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L526)  
  [UP] unprotected variable tok while calling allocating function tre_regwexec [src/main/grep.c:531](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L531)  
  [UP] unprotected variable tok while calling allocating function mkCharWLen [src/main/grep.c:545](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L545)  
  [UP] unprotected variable tok while calling allocating function mkCharWLen [src/main/grep.c:549](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L549)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:569](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L569)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:580](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L580)  
  [UP] unprotected variable tok while calling allocating function Rf_translateChar [src/main/grep.c:587](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L587)  
  [UP] unprotected variable tok while calling allocating function Rf_warning [src/main/grep.c:590](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L590)  
  [UP] unprotected variable tok while calling allocating function Rf_ScalarString [src/main/grep.c:591](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L591)  
  [UP] unprotected variable tok while calling allocating function tre_regexec [src/main/grep.c:600](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L600)  
  [UP] unprotected variable tok while calling allocating function Rf_allocVector [src/main/grep.c:608](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L608)  
  [UP] unprotected variable tok while calling allocating function tre_regexec [src/main/grep.c:613](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L613)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:626](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L626)  
  [UP] unprotected variable tok while calling allocating function Rf_markKnown [src/main/grep.c:629](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/grep.c/#L629)  
  
__Function do_subassign2_dflt__  
  [UP] ignoring variable subs as it has address taken, results will be incomplete   
  [UP] ignoring variable x as it has address taken, results will be incomplete   
  [UP] ignoring variable y as it has address taken, results will be incomplete   
  
__Function do_subassign_dflt__  
  [UP] ignoring variable x as it has address taken, results will be incomplete   
  
__Function do_summary__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_unlist__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function do_vapply__  
  [PB] has an unsupported form of unprotect (not constant, not variable), results will be incomplete [src/main/apply.c:265](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/apply.c/#L265)  
  [UP] unsupported form of unprotect, unprotecting all variables, results will be incomplete [src/main/apply.c:265](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/apply.c/#L265)  
  
__Function do_which__  
  [UP] unprotected variable v_nms while calling allocating function Rf_allocVector [src/main/summary.c:929](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/summary.c/#L929)  
  
__Function do_xtfrm__  
  [UP] ignoring variable ans as it has address taken, results will be incomplete   
  
__Function protectedEval__  
  [PB] has possible protection stack imbalance [src/main/context.c:743](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/context.c/#L743)  
  
__Function setParseFilename__  
  [PB] has negative depth [src/main/gram.c:5012](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L5012)  
  [PB] has possible protection stack imbalance [src/main/gram.c:5013](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L5013)  
  
__Function vec2buff__  
  [UP] unprotected variable nv while calling allocating function linebreak [src/main/deparse.c:1545](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1545)  
  [UP] unprotected variable nv while calling allocating function Rf_isValidName [src/main/deparse.c:1549](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1549)  
  [UP] unprotected variable nv while calling allocating function Rf_translateChar [src/main/deparse.c:1549](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1549)  
  [UP] unprotected variable nv while calling allocating function deparse2buff [src/main/deparse.c:1550](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1550)  
  [UP] unprotected variable nv while calling allocating function deparse2buff [src/main/deparse.c:1553](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1553)  
  [UP] unprotected variable nv while calling allocating function deparse2buff [src/main/deparse.c:1557](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1557)  
  [UP] unprotected variable nv while calling allocating function src2buff [src/main/deparse.c:1563](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1563)  
  [UP] unprotected variable nv while calling allocating function deparse2buff [src/main/deparse.c:1564](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/deparse.c/#L1564)  
  
__Function xxaddformal0__  
  [PB] has negative depth [src/main/gram.c:2992](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2992)  
  [PB] has possible protection stack imbalance [src/main/gram.c:2993](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2993)  
  
__Function xxaddformal1__  
  [PB] has negative depth [src/main/gram.c:3006](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3006)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3008](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3008)  
  
__Function xxbinary__  
  [PB] has negative depth [src/main/gram.c:3318](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3318)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3319](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3319)  
  
__Function xxdefun__  
  [PB] has negative depth [src/main/gram.c:3295](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3295)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3296](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3296)  
  
__Function xxexprlist0__  
  [PB] has possible protection stack imbalance [src/main/gram.c:3023](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3023)  
  
__Function xxexprlist2__  
  [PB] has negative depth [src/main/gram.c:3055](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3055)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3056](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3056)  
  
__Function xxfirstformal0__  
  [PB] has negative depth [src/main/gram.c:2962](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2962)  
  [PB] has possible protection stack imbalance [src/main/gram.c:2967](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2967)  
  
__Function xxfirstformal1__  
  [PB] has negative depth [src/main/gram.c:2978](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2978)  
  [PB] has possible protection stack imbalance [src/main/gram.c:2979](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2979)  
  
__Function xxfor__  
  [PB] has negative depth [src/main/gram.c:3208](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3208)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3209](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3209)  
  
__Function xxforcond__  
  [PB] has negative depth [src/main/gram.c:3196](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3196)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3197](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3197)  
  
__Function xxfuncall__  
  [PB] has negative depth [src/main/gram.c:3262](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3262)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3263](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3263)  
  
__Function xxif__  
  [PB] has negative depth [src/main/gram.c:3170](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3170)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3171](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3171)  
  
__Function xxifelse__  
  [PB] has negative depth [src/main/gram.c:3182](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3182)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3184](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3184)  
  
__Function xxnullformal__  
  [PB] has possible protection stack imbalance [src/main/gram.c:2956](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2956)  
  
__Function xxnullsub0__  
  [PB] has negative depth [src/main/gram.c:3106](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3106)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3111](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3111)  
  
__Function xxnullsub1__  
  [PB] has negative depth [src/main/gram.c:3117](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3117)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3123](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3123)  
  
__Function xxnxtbrk__  
  [PB] has possible protection stack imbalance [src/main/gram.c:3241](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3241)  
  
__Function xxsub0__  
  [PB] has possible protection stack imbalance [src/main/gram.c:3066](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3066)  
  
__Function xxsublist2__  
  [PB] has negative depth [src/main/gram.c:3146](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3146)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3147](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3147)  
  
__Function xxsubscript__  
  [PB] has negative depth [src/main/gram.c:3346](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3346)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3347](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3347)  
  
__Function xxsymsub1__  
  [PB] has negative depth [src/main/gram.c:3099](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3099)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3100](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3100)  
  
__Function xxvalue__  
  [PB] has negative depth [src/main/gram.c:2946](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2946)  
  [PB] has possible protection stack imbalance [src/main/gram.c:2949](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L2949)  
  
__Function xxwhile__  
  [PB] has negative depth [src/main/gram.c:3220](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3220)  
  [PB] has possible protection stack imbalance [src/main/gram.c:3221](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/gram.c/#L3221)  
  
__Function zipunzip__  
  [PB] has negative depth [src/main/dounzip.c:219](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/dounzip.c/#L219)  
  [UP] attempt to unprotect more items (1) than protected (0), results will be incomplete [src/main/dounzip.c:219](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/dounzip.c/#L219)  
  [PB] has possible protection stack imbalance [src/main/dounzip.c:246](https://github.com/wch/r-source/blob/875c595bd8ca9750a6ecebc6c65e137411aef53e/src/main/dounzip.c/#L246)  
