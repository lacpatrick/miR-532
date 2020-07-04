---
title: "CBC_total"
author: "Patrick Lac"
date: "May 13, 2020"
output: 
  html_document: 
    keep_md: yes
---





Let's begin by importing our data:



Next lets attach the different peripheral blood data together:

```
##   ï..Sample          Original.label Treatment Weeks.post.transplant WBC  RBC
## 1     MIG.1 BMT1.MIG (NEP cage 1/2)   control                     5 5.2 9.57
## 2     MIG.2 BMT1.MIG (REP cage 1/2)   control                     5 3.6 9.37
## 3     MIG.3 BMT1.MIG (BEP cage 2/2)   control                     5 6.5 9.58
## 4     MIG.4 BMT1.MIG (REP cage 2/2)   control                     5 6.2 9.74
## 5     MIG.5 BMT2.MIG (cage 2/2 BEP)   control                     5 4.5 9.84
## 6     MIG.6 BMT2.MIG (cage 2/2 LEP)   control                     5 3.0 9.83
##    HGB  HCT MCV  MCH MCHC PLT MPV  RDW Percent.Lym Percent.Mon Percent.Gra
## 1 14.7 45.7  48 15.4 32.2 473 6.8 15.7          NA          NA          NA
## 2 14.3 43.0  46 15.3 33.3 605 6.5 15.5          NA          NA          NA
## 3 14.6 44.4  46 15.3 32.9 453 6.7 15.3          NA          NA          NA
## 4 15.1 45.7  47 15.5 33.1 540 7.3 15.3          NA          NA          NA
## 5 14.6 45.8  46 14.9 32.0 631 6.5 16.0          NA          NA          NA
## 6 14.4 44.8  46 14.6 32.2 900 6.0 15.8          NA          NA          NA
##   Number.Lym Number.Mon Number.Gra  GFP
## 1        2.3        0.3        2.6 85.2
## 2        2.1        0.3        1.2 86.8
## 3        3.0        0.5        3.0 88.7
## 4        3.6        0.5        2.1 87.8
## 5        2.6        0.4        1.5 82.3
## 6        1.4        0.2        1.4 82.2
```





![](CBC_total_files/figure-html/WBC.wk5-1.png)<!-- -->



![](CBC_total_files/figure-html/RBC.wk5-1.png)<!-- -->



![](CBC_total_files/figure-html/HGB.wk5-1.png)<!-- -->



![](CBC_total_files/figure-html/HCT.wk5-1.png)<!-- -->


![](CBC_total_files/figure-html/MCV.wk5-1.png)<!-- -->



![](CBC_total_files/figure-html/MCH.wk5-1.png)<!-- -->


![](CBC_total_files/figure-html/MCHC.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/PLT.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/MPV.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/RDW.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Lym.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Mon.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Gra.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Lym.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Mon.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Gra.wk5-1.png)<!-- -->

![](CBC_total_files/figure-html/GFP.wk5-1.png)<!-- -->



![](CBC_total_files/figure-html/WBC.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/RBC.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/HGB.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/HCT.wk11-1.png)<!-- -->


![](CBC_total_files/figure-html/MCV.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/MCH.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/MCHC.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/PLT.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/MPV.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/RDW.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Lym.wk11-1.png)<!-- -->



![](CBC_total_files/figure-html/Percent.Mon.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Gra.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Lym.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Mon.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Gra.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/GFP.wk11-1.png)<!-- -->

![](CBC_total_files/figure-html/WBC.wk17-1.png)<!-- -->



![](CBC_total_files/figure-html/RBC.wk17-1.png)<!-- -->



![](CBC_total_files/figure-html/HGB.wk17-1.png)<!-- -->



![](CBC_total_files/figure-html/HCT.wk17-1.png)<!-- -->


![](CBC_total_files/figure-html/MCV.wk17-1.png)<!-- -->



![](CBC_total_files/figure-html/MCH.wk17-1.png)<!-- -->


![](CBC_total_files/figure-html/MCHC.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/PLT.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/MPV.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/RDW.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Lym.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Mon.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Gra.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Lym.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Mon.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Gra.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/GFP.wk17-1.png)<!-- -->

![](CBC_total_files/figure-html/WBC.wk21-1.png)<!-- -->



![](CBC_total_files/figure-html/RBC.wk21-1.png)<!-- -->



![](CBC_total_files/figure-html/HGB.wk21-1.png)<!-- -->



![](CBC_total_files/figure-html/HCT.wk21-1.png)<!-- -->


![](CBC_total_files/figure-html/MCV.wk21-1.png)<!-- -->



![](CBC_total_files/figure-html/MCH.wk21-1.png)<!-- -->


![](CBC_total_files/figure-html/MCHC.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/PLT.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/MPV.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/RDW.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Lym.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Mon.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/Percent.Gra.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Lym.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Mon.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/Number.Gra.wk21-1.png)<!-- -->

![](CBC_total_files/figure-html/GFP.wk21-1.png)<!-- -->




![](CBC_total_files/figure-html/graphs.WBC-1.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-2.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-3.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-4.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-5.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-6.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-7.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-8.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-9.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-10.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-11.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-12.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-13.png)<!-- -->![](CBC_total_files/figure-html/graphs.WBC-14.png)<!-- -->
