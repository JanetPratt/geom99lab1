# My personal directions request

First, explore the various options through the Directions API https://developers.google.com/maps/documentation/directions/get-directions. 

Be creative and use multiple parameters from the API documentation to earn a top grade. The rubric is listed in the bottom of the MarkDown document. 

> Tip: Can't make changes? GitHub previews MD documents by default (read-only). Start editing to make the changes for your URL and JSON response below

## Directions URL

```
https://YourDirectionsApiURLGoesHere](https://maps.googleapis.com/maps/api/directions/json?origin=Englehart,ON&destination=Timmins,ON&waypoints=optimize:true|Kirkland+Lake,ON|Matheson,ON&via=South+Porcupine,ON&avoid=highways&mode=driving&arrival_time=1676311375&language=english&units=metric&key=AIzaSyCM-WWHYHIKY-do4kquMy9Z4wQaQx51AuE)
```

## Next paste the full JSON response to this query here:

```JSON
{
   "geocoded_waypoints" : [
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJ7dzdM6clJE0RMPOQylnsEq8",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJqwQrKupyJE0RwR1YKgnXfTg",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJB4HVlcVxI00RrwPyJx3szu4",
         "types" : [ "locality", "political" ]
      },
      {
         "geocoder_status" : "OK",
         "place_id" : "ChIJzT_NUd2lPE0Rdpzq_mrp-Hc",
         "types" : [ "locality", "political" ]
      }
   ],
   "routes" : [
      {
         "bounds" : {
            "northeast" : {
               "lat" : 48.5522638,
               "lng" : -79.8738261
            },
            "southwest" : {
               "lat" : 47.824585,
               "lng" : -81.3308316
            }
         },
         "copyrights" : "Map data ©2023 Google",
         "legs" : [
            {
               "distance" : {
                  "text" : "45.3 km",
                  "value" : 45322
               },
               "duration" : {
                  "text" : "34 mins",
                  "value" : 2027
               },
               "end_address" : "Kirkland Lake, ON P2N 2E1, Canada",
               "end_location" : {
                  "lat" : 48.151018,
                  "lng" : -80.0330785
               },
               "start_address" : "Englehart, ON P0J 1H0, Canada",
               "start_location" : {
                  "lat" : 47.8245977,
                  "lng" : -79.8738261
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "0.2 km",
                        "value" : 151
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 19
                     },
                     "end_location" : {
                        "lat" : 47.824585,
                        "lng" : -79.8758521
                     },
                     "html_instructions" : "Head \u003cb\u003ewest\u003c/b\u003e on \u003cb\u003e5th Ave\u003c/b\u003e toward \u003cb\u003e4th St\u003c/b\u003e",
                     "polyline" : {
                        "points" : "wv{bHljofN?R?fA?|@?bA?rB@f@?J@L"
                     },
                     "start_location" : {
                        "lat" : 47.8245977,
                        "lng" : -79.8738261
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 104
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 30
                     },
                     "end_location" : {
                        "lat" : 47.8255201,
                        "lng" : -79.87585729999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e4th St\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "sv{bH`wofN{D@"
                     },
                     "start_location" : {
                        "lat" : 47.824585,
                        "lng" : -79.8758521
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.7 km",
                        "value" : 727
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 80
                     },
                     "end_location" : {
                        "lat" : 47.8252929,
                        "lng" : -79.88544929999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e at the 1st cross street onto \u003cb\u003e4th Ave\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "o|{bHbwofN?~H?tEAzOA`@AtI?~@?n@Al@BL?NAn@?hA@|@BPDVJVZ\\"
                     },
                     "start_location" : {
                        "lat" : 47.8255201,
                        "lng" : -79.87585729999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "19.1 km",
                        "value" : 19149
                     },
                     "duration" : {
                        "text" : "12 mins",
                        "value" : 722
                     },
                     "end_location" : {
                        "lat" : 47.9701676,
                        "lng" : -80.0174222
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-11 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "a{{bH`sqfNy@tAYd@q@lAoAxBgAjBGLOV}B`E_C`EyAlCc@r@}AlCo@nAaA|A]n@EHWd@QZm@dAy@vA[l@Wb@A@Wd@a@p@y@tAIPEHU`@o@fAi@bAg@z@u@pAe@x@Wd@GHKRi@`A_A~A_@l@a@t@c@r@EHINOVQZi@|@g@v@i@|@}AzBkA|A[\\EFUVCDC@[^k@n@aBbBaBxAA@uAjAUPs@f@WTg@^c@V}AbA_BfA_BfA_@VaAl@_An@yA`Ai@VYRa@VYPYRa@XEBa@VgBjAaAn@eAr@q@b@YPEB}@l@s@f@mAv@A?_@VkHvEqBnA]V_@V_@T}A`AsBrAkCdBg@ZkDzBUN_An@WNoBpAu@f@y@f@e@^c@Xa@V{DfCq@b@wFpDgAt@w@d@eCdBe@ZyGhE]T_Al@qCjBkBlAeAr@C@}@l@}@l@KFSL[ReAp@KHSLu@b@w@f@kAx@yA~@OJ_@Tm@`@SL_@Va@VcAp@gDzBuBtAeAr@yA`A_@T}@j@cC~AA@_@T_@V_@VcIhFcC`BgAp@mHxEkAv@_An@[RCB_@Va@V_Al@_@TIFkAx@IF_@TyEzCiAv@_@T_An@mAx@SL_@TaC|AaFbD_@VC@_GvDOJOJ_BdAaAn@_Al@[ReBhA]Ra@Z_@T_@V]TcAp@_@TiBlAWNuBrAkBnAqIvF{DfCo@`@_DtBsBrA_@Vw@f@i@\\sDbCmBnAuA~@oChB{@h@kErCwClBaAn@_An@GDwBvAcElCcDrBeBfA_BhAkEtCiBlA}HfFaDrBaCzAa@VeC~AgDzBwH`FuClBKFaAp@aBfA{@l@q@b@g@\\iA~@y@p@SPg@d@EDm@j@k@j@g@f@u@z@k@r@y@`Am@x@{ArBGHSVs@dA]b@Yb@IHa@l@w@hAmA~AQToD`FkA~Aa@j@a@l@o@x@Y`@gAxA_ApAsAjBA@_ArAMR[`@Y`@gCjDqAhBkA|Ac@l@[`@[b@qAfBc@n@aCdDiBfCw@bAGJm@z@y@hAcAtAqAfBeA|AUXi@r@uAnB{@jA}EzG[`@gClDwBvC}BbD_BvBY`@eBbC_KhNuFvHaJdM[b@u@dAcDnEmBjCmBjCu@dAw@dAY`@oAdBuAjBYb@w@bA[b@GHiA|AcDpEY`@W^CB[`@Yb@[`@[`@CFq@|@qAfBqAhB[`@UZgDxEQVsBrC]d@_ApAm@x@[`@Y`@W\\CBUX_@d@ABKPMPa@l@_@j@OPW^A@qAhB[`@CFmA~A[b@OPiBjC_BxBk@t@e@p@[`@k@x@IJ[`@ORg@p@UZCDw@dAOTIJ[b@}@nAiA~Ai@v@q@z@QVY`@}@lAUXOTi@t@q@~@i@t@w@dAg@p@aAvAg@p@OTm@x@[b@o@|@ILQRABY\\QTe@l@A@[Zk@j@ONu@n@mA|@wA|@A@a@RKHYLs@ZoAb@mA\\WDwF|@_IlAsEt@qDh@c@FmAPuEp@{B\\}B`@g@Fy@JuC`@i@HeAPQDk@H}@Ly@LyB`@{@PaAX}@Zs@X_@Ts@ZKF{@h@"
                     },
                     "start_location" : {
                        "lat" : 47.8252929,
                        "lng" : -79.88544929999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "19.6 km",
                        "value" : 19619
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 791
                     },
                     "end_location" : {
                        "lat" : 48.1197972,
                        "lng" : -80.0851069
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eON-112 N\u003c/b\u003e (signs for \u003cb\u003eKirkland Lake\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "qdxcHzkkgN}@PSDQDQ@qASGGICECOIICKAKCM?M?m@@y@HS@aAHi@BS@c@@e@B]?Y?O?_@?E?u@?k@?C?o@Bq@?m@?s@?w@?S?O?u@?u@?iA?a@?e@?a@?U?uA?A?a@?g@?gA?gB?U?}A?qD?G?c@?aB?uB?G?aB?k@?c@?mA?yA@C?c@?c@?O?iC?qB?iA?}B@mA?eFCeC@_B@gB?yCAc@?K?cC?c@?c@?A?a@@y@@q@DY@I?c@D[@i@Fc@Bc@Fc@DQBQBeAPqAPqAVmATc@H_@HA@c@Fc@Hc@HG@oATQBa@HSDo@He@Jy@@O?s@@m@AIAe@Ee@Im@Ma@Is@USIUIECMESKa@Qa@Ua@YWQYSIIKIOO][_@_@u@u@gBgBaAgAiHmH{C}C}A}Aq@q@]]UU_B_BMOOMeBgB{B{BKM]]wAwAyB{BwAwA]]]]IIs@s@UWOOSQ{CqCYUg@[{@i@YQ]Sk@Ws@Yq@WWKIC_A]iAc@sAg@wAg@u@YMEOGQGo@Ww@Ws@UkAYm@Mc@GICYCa@E]CE?q@CUASAiA?cBA}AHiKh@_HZuETc@BoCNgAD{FXkH^yAFgAFa@BwADwAJg@BYBI@e@Da@FC@]Ha@NWJWNe@XMHKJUPa@^UXm@x@_@j@AB_@l@S\\_@j@CDuAxB_AxAs@hAe@v@}@xAMPKRo@`A]j@SXs@lA_@p@{@nA}@xAYd@Yd@aCxDqD`GqAnBGFSXORKLONMLOJe@\\ID_@VA@u@XMDa@LG@u@HI?c@?c@Ac@?A?y@I{Aa@y@WcA]c@Oa@MkMgE}Bw@c@OICWGkBi@_AKy@Ag@@a@Bq@JA?m@Rk@Rm@ZC@}DfCa@T_BdAa@T_BdAaAl@_@VaCzA_@Ta@V_@T_@V_@Ta@V_@VaEhCaCzAaCzAeIdFaCzA_An@a@T_@V_@T_@VcDpB_@VaBdA_@TcF`DaCzA_BdAcEhC_Al@a@T_@V_Al@aAl@_Al@aAl@_@VcEhC_Al@_@VgOnJa@VaCzAoCfBoA~@c@\\YV_@ZUReA~@]ZQLgAjAa@d@WXq@z@e@j@m@x@q@~@e@p@[`@u@dAw@bA[^MP{@fAy@fAu@~@sAdBsAbBq@x@k@n@sBdBg@ZwA|@sCpA}@Zs@TWHKBgBh@a@Lc@NkDdAc@LiCv@eAZa@Lc@LoCx@[L{@ZqAp@YPm@^SLc@XcAx@qAnAm@n@q@v@w@bAu@hAg@|@Yh@Wd@iLjTuEvIWf@qClF{AtCu@tAcKlRu@vAWf@Wf@S^CFWf@eA~BUd@Uj@Qb@CDS^Yf@_@d@AB]\\[XQL]TOHQFi@Pw@Nq@Da@?g@A_@Ci@Mq@Wu@a@e@]e@e@OUQSIMS[[s@MWo@}A]cA]cAmAsDEKM_@c@eA]y@EGS[U[a@g@k@k@QMYUEC}@a@CAc@IICYEQEO?c@AGA_AFQ@w@R_@LYJGD_Al@y@~@_A`AiC`DsAbB[^Y\\CBkD~D[`@y@~@]^e@h@QVmCbD]^w@`A[`@]^sAbB[^iBxBoB~BaApA[`@ABm@jAWf@Wf@KPKVgB~DGPm@rAUh@Uh@Uh@Wh@Uh@yAfDUh@qAvCu@bBUh@m@rAUh@Uh@cA|BUh@gCzFUh@cA|BWf@wGfOo@xAIR_@bAa@rAWnAAJIf@Kp@EXSzBWbDW|CGr@YpDOdCIx@Gr@Gl@Kx@AJGd@Kn@AFI`@Od@ITGPQ^[n@m@z@c@f@"
                     },
                     "start_location" : {
                        "lat" : 47.9701676,
                        "lng" : -80.0174222
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "5.6 km",
                        "value" : 5572
                     },
                     "duration" : {
                        "text" : "6 mins",
                        "value" : 385
                     },
                     "end_location" : {
                        "lat" : 48.151018,
                        "lng" : -80.0330785
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-66 E\u003c/b\u003e (signs for \u003cb\u003eKirkland lake\u003c/b\u003e)",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "wkudH|rxgNaAh@KBE@G@K?KCICIE[Qu@c@uBcD_@m@[e@GKmByCUa@Ui@O]i@uAUk@Ui@AACIe@sAOe@Us@Sm@g@aBk@cBy@oBWg@o@qAEM}@}AEGS[EI_BoCEGQYGKOWIKs@kA}Rm[sB_DyBoD_BgCg@u@a@i@e@k@KKwAyA{@g@EAa@QyAs@yAi@mDcAy@U_Bg@eA[GAa@Ma@M}@Ya@MME]KYKa@MSIy@Yg@SyB_AGCa@OYMkAg@WMMG_Bs@YKKEw@]a@Qi@U{Ao@eAc@[MIGm@[s@e@_@YeAaAgAoBm@wAc@_Am@wAm@wA_AyBO]IOQc@GK]}@O[IUGQOe@K_@K_@Ke@Ki@UgAk@kCWkAa@uBWgBOsAEm@Ew@AYO_DEkACg@Ec@Ac@I{@a@yBi@gCc@mBGa@YuA_@uBKm@Kq@K_AI_AY_EQeEAK?MI{AAi@?MCu@KgBMkBQ}Ak@sCMq@WgAe@iCI_@OcAOaBIiBEu@Cu@Oo@IWEWAEGUGSCIGOUi@We@IQQYWg@Q[g@cAWg@o@oASs@Om@CGKg@CKKe@COEc@?EIeAC[Eg@AMCUAOGc@[cAAAUk@KUACUg@AAQU"
                     },
                     "start_location" : {
                        "lat" : 48.1197972,
                        "lng" : -80.0851069
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "71.4 km",
                  "value" : 71386
               },
               "duration" : {
                  "text" : "48 mins",
                  "value" : 2883
               },
               "end_address" : "Matheson, ON P0K 1N0, Canada",
               "end_location" : {
                  "lat" : 48.5338059,
                  "lng" : -80.4640886
               },
               "start_address" : "Kirkland Lake, ON P2N 2E1, Canada",
               "start_location" : {
                  "lat" : 48.151018,
                  "lng" : -80.0330785
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "14.4 km",
                        "value" : 14383
                     },
                     "duration" : {
                        "text" : "13 mins",
                        "value" : 769
                     },
                     "end_location" : {
                        "lat" : 48.0942053,
                        "lng" : -80.18791399999999
                     },
                     "html_instructions" : "Head \u003cb\u003esouthwest\u003c/b\u003e on \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-66 W\u003c/b\u003e toward \u003cb\u003eProspect Ave\u003c/b\u003e",
                     "polyline" : {
                        "points" : "{n{dHvmngNPT@@Tf@@BJTTj@@@ZbAFb@@NBT@LDf@BZHdA?DDb@BNJd@BJJf@BFNl@Rr@n@nAVf@f@bAPZVf@PXHPVd@Th@FNBHFRFT@DDVHVNn@Bt@Dt@HhBN`BNbAH^d@hCVfALp@j@rCP|ALjBJfBBt@?L@h@HzA?L@JPdEX~DH~@J~@Jp@Jl@^tBXtAF`@b@lBh@fC`@xBHz@@b@Db@Bf@DjAN~C@XDv@Dl@NrAVfB`@tBVjAj@jCTfAJh@Jd@J^J^Nd@FPHTNZ\\|@FJPb@HNN\\~@xBl@vAl@vAb@~@l@vAfAnBdA`A^Xr@d@l@ZHFZLdAb@zAn@h@T`@Pv@\\JDXJ~Ar@LFVLjAf@XL`@NFBxB~@f@Rx@XRH`@LXJ\\JLD`@L|@X`@L`@LF@dAZ~Af@x@TlDbAxAh@xAr@`@PD@z@f@vAxAJJd@j@`@h@f@t@~AfCxBnDrB~C|Rl[r@jAHJNVFJPXDF~AnCDHRZDF|@|ADLn@pAVf@x@nBj@bBf@`BRl@Tr@Nd@d@rABH@@Th@Tj@h@tAN\\Th@T`@lBxCFJZd@^l@tBbDl@dAr@vAh@vATp@DJf@xARl@DP^fAf@zAd@xARl@l@hBXt@Pb@NZZp@BDv@pAP\\NRr@~@j@n@XVBB\\Zr@l@hBtAb@\\z@j@b@ZXTxAdAxDpCx@n@l@h@FFr@r@DBNPb@h@f@r@NTZf@T`@?Bl@lAJVHVHNL\\Rl@ZdANr@VhARfANbAF`@VdBT~ALp@Lr@Nr@Pn@HZf@tATj@Rj@Rj@Tl@Zr@PTLPTVTPLDFDLDXF\\Hf@J~@Rb@HB@HBFDHDBBDBFFJJBD\\^Z\\d@f@^^PLNF@@RHH@FBVBD@^@B?^?b@?B?bAAL?b@@b@?b@?jA?nCBL?j@F\\FTHPJHDTNDDVTX^NTJP?@FLN^Lb@@DFXDVBHD`@Db@@`@DbABx@?X?b@@t@?~A@t@?hB?t@@t@?jB@jB?t@@vE@X?Z@bCBbBFpCFfB@\\@VDz@HbB@JDf@NxBr@~IB`@@RV|Ct@nJ?Bf@vG@^HzALpCHfCPtEBt@L~CBt@DxANlGDbI?F?l@C~CAt@At@?Z?XAt@AjBA`DC~C?^ATC`DGbIAt@EjGAt@At@AjBIdJ?PAbE?R@t@?t@@l@?FBr@FdBLnBLhB?@Dp@HjBBl@?DDt@ZrE?DJbBLpBd@xGTrCHp@Db@Hj@Hl@\\jB?BNx@b@nBZfANn@J^V|@Pl@Pn@Pl@Pl@HZDRNn@Nn@FVDXLp@Hb@@LLr@Jp@?@TtBN`BN|A@FBl@Dr@Ft@?DBl@Bl@DfB?JBx@@vAAbA?p@CnBAZ?XEtCKvGCbA?f@CnB?n@?t@?\\BlA@f@@LFjBBf@V~EDt@Dt@VnEV|EDn@Dn@@BRjCJdAFr@?@Fp@RfBFr@Fn@@BX|Cp@hHHdAHn@`@pEHr@NfBHr@h@dGPfBHr@Fr@PfBFt@D\\N`A@DLn@@HXjAVv@FP^dANb@t@xBd@vABDnA|D"
                     },
                     "start_location" : {
                        "lat" : 48.151018,
                        "lng" : -80.0330785
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "56.9 km",
                        "value" : 56869
                     },
                     "duration" : {
                        "text" : "35 mins",
                        "value" : 2096
                     },
                     "end_location" : {
                        "lat" : 48.5328172,
                        "lng" : -80.4634112
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-11 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "ykpdHlulhNJp@BPBR@J@V?LABANAFCLCJ?@OXGHe@n@ADABERy@x@]\\[\\]^qAnAc@d@oBnBWVc@d@{@z@[\\wAzAq@p@e@h@A@STeBnB{@bAQT[`@[b@o@z@SZYb@S^]h@mAjBwAhCmB`DmAnBiB|C}AhCMN_AzA[h@MT_@t@}@fBc@dASb@wA~Dg@tAo@jBGNg@vAmAjDo@dBM^_@hAcArC]dAYv@Un@k@zAQb@Sj@IP[r@e@hAe@`As@xAu@tAm@fAA@w@nASZ?@[d@OVy@hA}@lAy@dAq@v@C@CB{AbBcAdAKJcA|@IHq@l@}@p@o@f@mAx@i@\\uAz@aAj@IDw@b@cB`Ak@ZSLi@Xc@VwAv@wBnAwC`Bg@XuDtBsAt@eCtAMHs@`@A?gHbEwHjEQJ{BpAgDjBkAp@kCvAeAj@w@^E@[LsAh@cAZOFiF~AgDbAa@LeAZcAZsFbBuGnBa@LgBh@sFbBa@LmDdAa@LeAZoEtAwH|Bc@La@LqNfEcBf@wH|BgMvD_EnAk@RKDSHSHUHc@Ne@P_Bt@KFGBC@ID_@T{@f@QJeAl@WNc@Xu@f@qAbAiB`BoE`E]ZCBsG~FcCzBA?QP_@Z]Zy@t@g@d@SPCB]Z[XCBYV}@x@{@v@eBtAoCdCc@^eCzBoJrI]ZyBpBoKnJ{@v@]Z{AtA}@v@]ZuF`F]Z]\\}@v@{ArAg@f@yCjC]\\qHxG}@v@]\\]Z_@Z{@v@_@Z]\\]Z}@v@]Z{AtA]ZqIvH{@v@_@Z]Z]Z_@\\{ArA]Z{@x@_@Z]Z]Z_@Z]Z]Z}@x@wClC_@Z{@v@WRGF{@v@_@ZcA~@sBlAkAn@k@V}@ZcCt@wFbAoATmCb@C@_ALe@JkAR}B`@oDl@c@FiDj@G@c@F_BTm@FWDK?y@Fq@@a@BaABcA@_A?u@AcCEc@AgACc@AkBGuBEc@A_@AC?kBCsDIc@AwEKuEKw@AiDIi@CgAAC?cAC_CEc@A}@CI?c@CgAIc@Cc@Ck@EiDWwB]e@KIAeDy@mBe@cG{Ac@KqA]qJmCA?a@Iq@OaDs@kD}@u@S[Ku@SeCm@eAWiBe@gBc@eAY{HoBeAWa@Kc@KeAYmD}@c@KeFqAaCo@gBe@uPgEgAWa@KgCo@uA[_BUcBSIAyAMqBGc@Ac@A[?G?}DBaBLc@B}@FyFp@iIbAeTjCyBPS@y@D}@?_@Ai@CUAIAi@Ii@I}@O_B[iB_@oDs@}Co@wBc@oDs@kAUgGkAk@KeAQcAM_@Ea@EA?eAIgAISAOA_BEu@?]?QAq@@C?w@BgAFwCRo@F]DA?g@J[Fe@Ha@Ja@Hg@LeE`AGBc@JeAVsFtAiBd@a@J_FnAmD|@kCr@[HsCt@A?gB`@I@ODc@Ji@LeAT_C`@yB\\YFG@C?gHv@oEXg@DW@[?G@_CDaA?mCBgBCcBCcBGGAA?_BGiAGAAgBMi@Ee@EWAKAeBSw@IKCc@GGAG?m@KQCeAQOCSE}@QqB_@y@OwBa@a@IGA_AOkCg@k@Ka@IUCsCi@aHoAqFaAyE}@_AOGA_LsBk@K[Gc@Ii@I_AQyE{@yDs@kEy@c@I}AYCAi@KQEIAcAO_AOaAMc@E]EcBKEAUAKAc@AYAi@?[?G?[?kK?G?gJ?yX?sI?gD?c@?gA?gAAaI?wE?wE?}F?yFAc@?iA?eA@c@?aE?mF?sD?sD?sC?kC?mC?c@?gI?oD?oC?c@?sD?oC@c@?_A?_E?gB?kFAwEAwH?sF@c@?g@?mD?iB?eI?sD?kB?c@?oC?kB@c@?c@?qB?uD?oHCqA?uI?c@?kB?wE?}G?c@?kB?kB?sD@aG?kDAmB?iB?eIBmC?uE?e@?uDAeA?c@?y@AmH?c@?wE?c@?cI?gA?kB?_A?eF?[?c@?oC?c@?c@?oA?sB?w@?mDAuC@U?M?qB?aA?yAAoABoA@sBH[B}D\\{@Jc@FK@y@J[DG@c@HuARw@PQDOBcATcATiA\\c@LWHk@Rc@Na@Na@Nw@VKFa@N]NgAb@eCjASJoAn@a@RSLmAr@{@d@mAv@s@f@g@\\WPg@^k@d@i@d@s@h@]ZMJo@j@]\\]ZGFUT]\\m@l@ML]^q@t@e@f@s@v@EF[`@g@n@{AjBaArAW`@[b@Yb@Yb@k@~@c@n@e@v@MPYd@Yb@Yd@s@jAuAzBeAbBGJcAdBCB}BvDsDfGYd@Yd@uAzBcAdBkAlBaAbBsBfDYd@aCzDYd@gBtC]j@eC`Ei@|@Yd@s@jAYd@ABiChEw@rAc@x@w@pAcBfDcAxBc@bAUh@GJy@nBk@xAIPKXkBxEIViAtCUj@_A`CiAvCKVuApDmA|Co@bBSj@m@~As@hBs@lBm@zAg@lAs@nBYx@IRUn@u@pBy@tBcBrE_@bAi@tA{A|DcAhCWp@sAhDaAlCg@rAg@tAk@xA[z@cAlCs@hBSj@}BdGk@vASj@A@g@tASj@i@xAeBtEWp@Uj@i@tAUj@Sj@i@vAA@Sh@iAxCu@jBs@jB{@~B}BdGsApD_@~@Wn@Sf@}DtKk@tAeAxBQZs@lAi@z@q@~@AB{@dAw@z@{@z@u@l@GDk@b@kAv@aAh@k@Xa@RaAf@WLGDa@T_@Ra@Ra@ROHQH_@Ty@b@GBuCxAiCrAwCxAcErBC@cD`ByBlA_@Ta@T]PmFlC_@Ra@ReCnA}BhAeCnAoB`AgB`AGBsAr@cB|@e@T[Pa@ReCnAa@R_@RcAf@a@R_@RcAf@_@Ra@Ra@ReCnAaAf@k@Zw@`@cAf@_@RUJqDlB[NCB}At@cEvBa@RyDnBwC|A_Bx@_@RMFSN_@VA?]XQLKHa@Zo@j@gAfAqAbBe@l@aA|A{@zA_@p@}@rBsA|CiBhEiAlCeB`EcAbCcBzDeBbEEJ{@pBk@tAeC~Fy@nBu@bBcA~BO^q@|AcAbC[r@wAjDy@pB{AhDw@jBIPeC|Fm@tAuDxI}@xBk@tAUh@Wj@Uh@aA~BIPmAvCk@nAADk@rA_AxBWp@e@fAkCdGm@xAi@nASb@Wl@Uh@o@|AGLq@|Au@jBu@fB}CfHaA~Bm@rAqDrIWh@aA~BWh@qDpIWh@q@~AiBhEUj@Uh@cA~BSh@Wh@gBfEiAlCUh@oBvEgBbEyAhDoBrEUh@eC~FaAxBs@bB}@rBABsBfE_AbBIPYd@QZgB|CEDORGJWb@CDs@jAKP}@|Aq@nAo@hAoAxBq@nAo@hAuCfFQXWf@s@jAWd@s@lAaBxCA@kApB_@n@_BnCINcCfEeAhBg@~@Yd@OX{@xAWf@Yd@q@lAaAfBsA`CCDsA~BKR_C`EaBvCgBzCW`@Yh@gAjBu@tAWb@A@qC|EkArBy@tAQXYf@_@n@_@p@a@p@w@xA}@~AeAfBUb@Yd@S^qAvBYf@oBdDU`@Q\\Wb@_A|AeApBMTuA`Cq@lAy@zAeAhBeBbDm@bAYf@KPqAzBeAhB{@xAgAlBy@xAQXGJYd@a@r@iApBk@~@GJQXe@r@U^]d@_AlAIJg@p@g@j@yA|Ao@l@eAdAmC~B_CjB}AlAg@`@w@l@]X}BfBgCpB{@n@YR}BfB_CdBUPGF_@XeDlCmB~A}C`C_@X_@X}AlAKHSN_Ar@q@f@k@d@c@\\YT_@XmFdEcBpAIF_@V_@XA@]Tk@`@s@f@o@f@m@b@_BhAe@\\g@\\}@n@gDdCwB|AgBnA_HzE_An@_@VA@_@V_An@_BfA_@V_@XaDxBwAbAkKfHgCdBwA`AqClBqA|@oAz@kGjEkFpDuDhC_@X_@V_HzEaC`B_@VqI`GoAz@KFSLqAx@u@h@w@l@_Ap@WPuAz@SNYR_@V]VgAx@_An@eAv@cAv@u@f@_@X_An@_@V_BhA_C`Bg@\\yAbA{AdAaAn@A@_@T_@TeAv@iA`AeAdAw@z@_@f@[d@CBW^MRYd@KNOVILMTYj@OXWd@?BWh@ABWn@CJc@hAWt@[bAGPUz@U~@YlAWxAIb@WzAM`AMjAGh@Gp@Ed@Cb@?BGt@"
                     },
                     "start_location" : {
                        "lat" : 48.0942053,
                        "lng" : -80.18791399999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "0.1 km",
                        "value" : 134
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 18
                     },
                     "end_location" : {
                        "lat" : 48.5338059,
                        "lng" : -80.4640886
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003e4th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-101 E\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "cafgHhobjNMp@ABCHAFEFCDCDA?EDCBCBEBGBi@^WAaAG"
                     },
                     "start_location" : {
                        "lat" : 48.5328172,
                        "lng" : -80.4634112
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            },
            {
               "distance" : {
                  "text" : "68.6 km",
                  "value" : 68574
               },
               "duration" : {
                  "text" : "50 mins",
                  "value" : 2994
               },
               "end_address" : "Timmins, ON, Canada",
               "end_location" : {
                  "lat" : 48.4758161,
                  "lng" : -81.3308203
               },
               "start_address" : "Matheson, ON P0K 1N0, Canada",
               "start_location" : {
                  "lat" : 48.5338059,
                  "lng" : -80.4640886
               },
               "steps" : [
                  {
                     "distance" : {
                        "text" : "49 m",
                        "value" : 49
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 48.5333633,
                        "lng" : -80.4641446
                     },
                     "html_instructions" : "Head \u003cb\u003esouth\u003c/b\u003e on \u003cb\u003e4th Ave\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-101 W\u003c/b\u003e",
                     "polyline" : {
                        "points" : "igfgHpsbjN`AFV@"
                     },
                     "start_location" : {
                        "lat" : 48.5338059,
                        "lng" : -80.4640886
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "6.5 km",
                        "value" : 6467
                     },
                     "duration" : {
                        "text" : "5 mins",
                        "value" : 275
                     },
                     "end_location" : {
                        "lat" : 48.538481,
                        "lng" : -80.55081009999999
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e onto \u003cb\u003eTrans-Canada Hwy\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-101 W\u003c/b\u003e/\u003cwbr/\u003e\u003cb\u003eON-11 N\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "odfgHzsbjNNLLFHHJNBL@BBRDZ?DB`@B\\Fj@?`@?nAApCApB?bDCdGAnFAvF?TA^?bCCzJ?^?TCxF?TAxE?\\?lAA`DAlAAvF?\\?X?\\AfE?fAAxA?bB?fC?T?^?^AbB?l@A|@AdBCrBAbAEtBEtAK~DMdEItBCt@ALMpCEt@MhBEt@Et@CVq@pJC^mAjOOnBe@hGEr@QxBEd@Gr@MjBGr@WbDMxA]zDi@fG]xDW|CUdCGt@Eh@AHOhBGr@Y|COhBO~AYfDQhBW|CQhBGt@E\\}@rKi@zFUhCIhAGr@APEb@GbACd@Er@?@K~BE~ACfBAzC?zE?vE?V?\\AjS?xE?xE?fD?fS@dF@t@?t@@xE?zD?nG?t@?t@?t@?lB?t@?`D@bD?nG?t@?jB?bD?n@?N?nEClBC|@Al@?DK|AE|@Gt@Gp@CVE^Gp@Kz@[vBe@vC"
                     },
                     "start_location" : {
                        "lat" : 48.5333633,
                        "lng" : -80.4641446
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "29 m",
                        "value" : 29
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 5
                     },
                     "end_location" : {
                        "lat" : 48.5382376,
                        "lng" : -80.55095450000002
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eON-101 W\u003c/b\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "odggHpqsjNn@Z"
                     },
                     "start_location" : {
                        "lat" : 48.538481,
                        "lng" : -80.55081009999999
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "62.0 km",
                        "value" : 61991
                     },
                     "duration" : {
                        "text" : "45 mins",
                        "value" : 2692
                     },
                     "end_location" : {
                        "lat" : 48.4761603,
                        "lng" : -81.3308316
                     },
                     "html_instructions" : "Turn \u003cb\u003eright\u003c/b\u003e to stay on \u003cb\u003eON-101 W\u003c/b\u003e",
                     "maneuver" : "turn-right",
                     "polyline" : {
                        "points" : "_cggHlrsjN^XDDFDDFDF?@DF@DBDBJBLBN@L@N?NF~A?hD?p@?`@AdD@`A?v@?rE?B?t@?lB?t@A|F?rD?lE?lD?fB?z@?t@@t@?t@?h@?bA?t@?t@?nGA`U?t@?t@AdI?t@?bD?bE?t@@zC?hD?t@?xE?B?fB?rG?hB?jB?t@?jBAnG?jB?lB?jB?j@?H?xF@nF?|A?xB@nG?lB?t@?RAlC?t@AlB?f@?L?t@?t@?t@?v@?t@?t@?t@?t@?bD?bC?vE?t@@bD?t@?t@?zA?hF?nG?bD?lGAt@?rB?~H?zJ?t@?t@?t@?xE?t@?pB?lA?tB?N?zJ?lB?t@?zC?|@?t@AdE?xI@vE@fE?bA?f@?L?jB?~A?J?jE@d@?fA?J?v@?~G?zA?|A?LAh@?|@?x@?bC?tA?h@?xB?r@ArL?t@?t@?v@?t@?pA?~I?t@?bD?tD?`@?bD?xB?lC?xE?bD@|O?t@?hA?nC?t@?t@?pB?hG?v@?t@?pB?n@@bE?vD?v@?jB?xB?tC?t@?tDAxA?fG?F?t@?t@?lAA`E?t@?~E@n@?t@?t@?d@?xI?~C?t@?bK?xE?dI?t@?~O?t@?fA?vH?p@?t@?v@?t@?t@?t@?`P?~D?|D?vE?hD?pE?|@?rA?fC?|I?t@?jB?xEAvI?dG?t@?t@?xE?|@?nE?vPA|J?t@?vE?v@?|O?t@?v@?vE@hFAvV?nX?zJ?vE?hNAdI?jX?~J?hu@@~O?lX?`EApA@nA?hF?dE?B?t@?dI?dZ?vE?~O?fE?vM?pL?z[?zJ?bD?tC?bD?zJ?jB?dI?pL?dI?|J?x[?v@?jB?fN?v@?`U?vE?t@?lJ?nD?xE?z[?`D?t@?lB?pL?tQ?t@?jB?lB?zJ?t@?`D?v@?t@?|A?L@t@@xE?jB@t@?XAhA?HAxA?PA`@Ar@EbACh@GhAKbBI~@MvAIv@OnAAHY|B]zBKp@Kr@Kp@Kr@eArHKp@cAdHgCjQa@nCuBpNSrAE^Il@ADMhAIx@AXGl@?FGx@GnAI|AK~CAd@Ct@SbIWpLg@`UuAbi@SrIWnLEjBCt@GjBCdAUjJKlEG|BIhB?DCt@IzAGbACb@APEt@Gn@MzAKdAAPc@~DWbCU`CaAnJSfBQfBcAdJQfBI~@Gr@CVMlAMdBIdACj@A\\E~@Cz@Az@C|A?P?t@GtQ?t@A`D?lBAvDClG?X?\\?VCzJArA?X?ZAzD?hCAdC?\\AnA?t@?jBA\\?t@A`DAxE?`BCrF?ZAtH@dAAnA?nDAzC?L?f@AhCAlEC~JAzICdKA|HAjD?t@?t@CvGCfG?HCtH?z@AxEA`DAxCA|GAzAAfFC~H?j@EpIAvCC`D?t@CxEAhAAnEAj@AdCC~D?TA^AxDAtAAjB?TCrEApFAbAAt@?t@At@?HCpFAnEA\\?t@A|BCnDC|HC`EAx@EdJCtDAfCEfK?b@CzH?DAn@CnE?~@AtAA`C?P?d@At@?TA^C`EAfGCjCAzBApCAv@AfC?XAt@AbD?t@AdB?DCzHCbFAz@CvECzEAnA?dA?jAAfA?t@AfBAz@A`DAxAAxB?DAZAdC?V?V?DAn@?@?z@AP?rBApAAp@?D?PAjAAd@Cv@ARAf@Cd@A^Cb@CXAZGz@Gh@?@Gd@AJCXGb@Ed@ABE`@]pCi@xDo@|ES|AWfBUdBa@|CUbBa@|CObAy@jGOjAUfB[xBGb@a@tCg@zDq@zEIl@Kp@[|BE\\m@lEKv@WlBIf@a@xCS`Bg@rD_@pCOhAYjBWlBWlBKp@CVEZIl@YlBOhAWlBOhAEd@Gb@C\\AFEd@ADC^Ix@Ez@Et@APAf@?DA^Ad@Ad@Ab@AtBArB?pA?`IA|E?T?^AjF@xC@pJ?R@b@@nJ@`@?nA@~C?~C@x@?t@?F?zC@pA?nA?f@?L@vD?`@@zB@jF@bE?~A@jB?\\?nA@d@?N@xB?tC@jB@xE?F?xC@t@?|B@fE?bA@jE?t@@bB?~@?t@@t@?t@?v@?lA?\\@fD?|C?f@BnF?fEB`F?L@fE@zG?bB@nC@xB?D?t@?t@@dD@vG@rFBrD?n@@pB?l@?tB@nA@nABnADnADlAHlAHlADd@Db@Dd@NhAFb@PfA@@PdAF^Lp@FTDZLh@PbAZvALp@R`A|@hEfApFf@lC@FFXh@nCf@fCJf@j@fCh@`CXnAb@fBBFH^T~@ZjATx@f@bBV`AL`@f@`BbA`Dt@~Bf@xA|@fCj@|A|@~Bl@|AjAzC@B~@bCTj@Pd@j@zAN^DJf@pA`AhCTj@|@`C@@vBvFDLTj@dBrE`BfEt@rBTj@Rj@fAnCb@hAhBxE~@bCTj@b@hAv@pBv@nBf@fAR`@Vf@^r@PVb@p@BDLPPVPTRTPTRTf@h@RRRPNLBDTPBBNLTPRPTNTNTNTLVLTLTJVJTJVJTHVHVHTHXFTFJBLBTDXDb@ChAJpBBjBAH?n@?~@?T?v@?dA?P?b@?V?t@?z@?lA?r@?n@?P?n@?fA@D?n@An@@D?f@?`AAlA?p@?l@?n@@~@?B?b@?T?p@?z@?n@?n@?p@Al@?`@@@?z@AR@l@An@@n@?Z?P?P?N?z@?b@?^AJ?V?R@h@?Z?\\Ap@@d@Av@@`@?lACN@h@?^?n@?^?n@@X?`@@\\@F?ZBb@Dd@Dj@J`@Hh@Lj@Lz@Zr@XNFPH`@RFDVNFBVPXPl@b@ZVp@l@VVLLXXd@h@VX\\d@TV^d@NR\\b@HLV\\f@l@b@j@h@r@X^NRb@h@b@j@b@j@NTTX`@j@JLRXPVBFLRR\\NXPZR`@^v@JVR`@Tl@L\\N`@BHNd@L`@JZNl@Nh@Nn@FVLl@F\\H`@DZHb@@BTbB@FVpBTdBRrAHr@@HXpBRzAZhCLz@J`AJx@JfAFt@@JB\\Dj@Dx@Bn@D~@DfA@z@@dA?t@?|@?l@Az@CzBG~CCjBARClBA\\?VErBCbBAt@?HGhDGxDGnDEjBAt@EjBAt@GxDIvFMrHGrDIzFAPAb@?R?RA`@GrCAbA?@?j@?h@?@?P@t@BdABp@@\\B`@Hz@H~@Jx@Lv@N~@Nr@Rv@Rt@HZPb@Vr@Tn@Rb@h@jAVj@Vh@JV@Bv@dBRd@NZDHN^@@Tf@DHN\\@BBFLVBDDJ@DbAfCL^p@hBDNTj@Rj@DJ^dAHPh@xAb@jARj@DJN^l@bBN^Rl@DJN^d@pA\\|@Xx@b@jAZ|@t@rBHPz@`CFPf@vADHLb@N`@BHL`@Vz@Jh@Lj@\\bB@FLj@DR\\`BH\\DRLp@BFDRDRLp@HZDTj@rCNn@^lBRdAj@lCF^FXJp@XnBf@nDz@bGx@bGl@rEHh@`@xC`@rCTdBLx@Lx@Pz@Nv@Rr@Rn@Rj@Pd@Zn@BH\\n@Xf@d@r@rCfE~AbCZd@dCvDt@rAXh@P`@N^L\\Tn@Nf@Ll@Lh@H`@PdAF`@Fn@LpADn@Bt@?DBv@@hB?xA@`A@z@BxDDjKJbMFnLB`DDhG@t@?NFrJ@\\CrBCl@?BE\\APCPKl@Kf@I^IZQh@Wn@OZINg@|@eAjBEFWd@qAzBaAjBc@`AO`@Sj@Y`AOv@Ox@QdAE^Gf@It@Ej@G|@Cx@AjA@rADjABr@Dh@Fl@Jp@@HFf@?@`@vBV~@L^~ApEj@tAtAnD\\|@t@tB`AdC~@dCN`@|@~BBF`@fA^dAn@`BXt@HPlFnNpDnJTj@fF`NtAnDv@tBpAnDVr@tBpFzAzDFLN`@JVvAtD`@fAZ|@h@vArAnD@DZ|@Rr@Nj@Ll@RhALt@DXJfAJlABjA@|@?hABhDAnE?lACfG@nK@fC@v@@h@@Z@H@LB^Fv@Jt@Hj@N~@DTFTNp@H\\DNBHJ\\L^N`@N\\HNTf@f@z@jAvBdCjEtBtDJNf@z@Vd@zBxDb@x@PXHPVd@j@hABFXp@DJN\\N`@L^DJDLJXPl@b@dBNp@Nt@Hd@Fb@Jx@NhALrBB|@BfA@r@?bAAhD?rAAnHAzIAt@?t@?bD?t@?t@AjEAvD?jB?PA~EArA?t@?t@?t@?V?\\?vEAnG?t@?b@AhA?`D?D?n@AbD?t@CpL?dEA~B?`D?t@?XAjHChD?L?f@?tC?LAlD?h@AP?F?Z?nDArBAzFAnAA|D?L?B?lB?xA?t@AJ?D?nA?pAAt@?d@?J?z@A~@?nA?rDAfB?h@AP?t@CrH?JAz@?d@AlD?B?zA?fA?t@?fBAnB?d@?vBAz@?n@?bDAL?d@?F?t@An@?DAbB?v@?F?lA@T?l@Bz@@v@B^?TDt@NbFBh@LvDDhA@JDt@?D@L@^@F@ZHfADr@Dv@Hr@Dd@@NFl@Fl@VdCd@tDLr@b@tCPfARhANz@Nz@ZxAj@dCn@~Cn@zCBDZ|ALv@F\\BRD\\LdAJvADr@@d@Bt@@bAAZCfDEnGAn@?j@?HAz@E~CCtAGnGGtMAvB?jBAt@?t@?lB?D?dBAt@?R@`@?t@?D?R@^?VBb@?PDr@Bt@@ZDt@Dt@D~@@h@@j@@t@?x@AjAElBCt@CjBCt@EjBAt@EjB?@Ar@?@?z@?l@?L@f@@\\P`ELpD@l@Bv@?T?^@~@@tC?nBAdEA|AA`C?d@At@AxB?l@A^?hA?|@?v@@bABt@@PFbBFtADf@?HHr@@FB\\Jv@Dd@TjBDb@PrAJhADl@HhA@LBd@@L?\\@V?v@?|@AbG?tF?t@?lE"
                     },
                     "start_location" : {
                        "lat" : 48.5382376,
                        "lng" : -80.55095450000002
                     },
                     "travel_mode" : "DRIVING"
                  },
                  {
                     "distance" : {
                        "text" : "38 m",
                        "value" : 38
                     },
                     "duration" : {
                        "text" : "1 min",
                        "value" : 17
                     },
                     "end_location" : {
                        "lat" : 48.4758161,
                        "lng" : -81.3308203
                     },
                     "html_instructions" : "Turn \u003cb\u003eleft\u003c/b\u003e onto \u003cb\u003eBalsam St S\u003c/b\u003e\u003cdiv style=\"font-size:0.9em\"\u003eDestination will be on the left\u003c/div\u003e",
                     "maneuver" : "turn-left",
                     "polyline" : {
                        "points" : "__{fHt|koNbAA"
                     },
                     "start_location" : {
                        "lat" : 48.4761603,
                        "lng" : -81.3308316
                     },
                     "travel_mode" : "DRIVING"
                  }
               ],
               "traffic_speed_entry" : [],
               "via_waypoint" : []
            }
         ],
         "overview_polyline" : {
            "points" : "wv{bHljofNBrK{D@?~HApVCfNJlHk@pDqE`I{Qx[iFjJoMfUuPpWwX~Te{@lj@osC|jB{{DhhCih@d^sSpWmz@tjAchCdnDkd@rn@qObTuGjGsJhEq{@tM_XlH_L[uNJ{t@@kn@?eQxAaSbDaNqCez@az@uJuHqKcEaR_FmdA~DeJl@sDfBqPtVaXrb@kCtBuFv@_K_CuZsIiGvAeT`Nsg@x[oxAb`A_UlYeGrHgKpGoNlEaP`FuKdI_t@nrAqJxO_Hr@iGcE_LuWmEeCqFLyYb[wXp^ok@~sAmEte@iCbGaDpAcKyMwCaHyNu\\_Zke@iNqQ{YsJgT{IsJ{EkKqS_HmWoAoQcDkRwDqf@_Fo\\_HsO}BgNe@cAVh@nAtEj@vFfDxItD~KbF|c@xAlTfEfUn@zMzD`ThKfW`FpFxCtArJbE`SpHjRjGvHlH|f@lx@`L`Z`KnPzEnMfFtNzEtGjYhUlDtGrCjL|BlMvDbJ|HpC~GnEdRh@rDpHZhc@|Bph@|EtiAg@pt@X~h@lE`k@bGdVfCnVQhg@hCti@fF|i@hFn^rEpOIfB{NlP{RtUuQhZwIbRaPdd@}QzZsVtR}j@r[c]jR}RnGikA|]ej@pQ_c@~]iXdV}_BtxA_VfT{LdJgWvF{_@bFsg@{@}`@iAm[kG}[kI}r@oQid@gK_OW{p@nHuHWqo@kLoUXgl@tNaKbC}YpDa_@]acAuPen@aLk[_AqqD?_sCAi{BAw^bBwTdGoYrPsNlNyu@tlAc\\rk@yUdm@en@haBsUbn@aNj]wJxLyPpJun@x[ocAhh@uP~IiHdHqb@|_Asv@diBk}@puBgUbe@uXnf@cv@`sA{p@hkAqQzVge@h_@yaAdu@mqBruAaY`SaNfJeJlJoG~MaFfZe@zA_Dj@rCjAXrGWhgAKzk@gB|n@cIfeA{NxjBCjcDm@nJuA|J|A`A^~@NzK?nw@AllAA~iB?hrFA`e[BlsFuA`\\cQjmAiKrpDmIrz@iAtq@c@~uBgAtsDcC|uFgA`h@cWhmBaHdh@u@bRRhyB\\fgBRv~@jCx[lL~k@rOti@jm@n~AhJfNpHxEbQ`B~V@lf@?xPAfPbBrLpIfMdPjHlMtD~NjFnb@Nv`@yBb|Az@dLpCdK|GhOzVlq@lNnn@bMpx@zTb`@dBjKRdN^dpAcMzXwBbLAlNdBjJfMx\\bf@hpAdOxc@l@rv@~CzO~Uvb@hFzSJz~@WnoBYnkAXb_ArAfVrKtn@h@v`@]lt@f@dUKj_@J|i@tAzYz@dh@bAA"
         },
         "summary" : "Trans-Canada Hwy/ON-11 N and ON-112 N",
         "warnings" : [],
         "waypoint_order" : [ 0, 1 ]
      }
   ],
   "status" : "OK"
}
```
____
## Rubric

This is part of your first practical lab in Week 3 

1. A working URL properly documented in the MarkDown with a unique origin and destination earns 50%
2. Including one to four additional functioning unique parameters from the API earns 50-70%
3. Having 3 or more functioning unique/novel and well-thought out parameters from the API earns 70-90%
4. Including more than 2 "stops", including links to display PlaceIDs on Google Maps, or other innovative presentations earns 80%-100%. 
