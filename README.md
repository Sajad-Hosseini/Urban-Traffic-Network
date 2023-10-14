The data required for the following traffic network is provided below.
  
![image](https://github.com/Sajad-Hosseini/Urban-Traffic-Network/assets/117570290/4411d877-2d23-462d-a3ad-268658d1f6d6)
  
The link capacity of the network is as follows.
        
$x_{max}$= 
     
    [47, 95, 142, 119, 119, 47, 47, 47, 47, 59, 83, 35, 35, 71, 71, 35, 35, 107, 47, 59, 59, 23, 23, 23, 23, 23, 23, 35, 35, 23, 23, 47, 47, 47, 71, 23, 23, 23, 23, 119, 47, 47, 47, 35, 35, 83, 83, 119, 59, 119, 178, 166, 83, 83, 23, 23, 23, 23, 47, 23, 47, 71, 47, 119, 47, 47, 47, 35, 35, 404, 404, 47, 47, 71, 47, 23, 23, 47, 47, 47, 47, 23, 23, 95, 119, 119, 119, 178, 59, 59, 59, 59, 166, 166, 47, 47, 47, 47, 71, 71, 35, 35, 107, 35, 35, 35, 35, 47, 47, 47, 47, 47, 47, 23, 23, 71, 23, 23, 23, 23, 47, 47, 47, 47, 119, 119, 59, 59, 178, 59, 59, 35, 35, 23, 23, 95, 119, 119, 47, 47, 47, 47, 47, 47, 47, 47, 95, 95].
  
The possible turning rates in the network are as follows,

${\theta}(t)$ = [ ${\tau}^t_{1,4}$ , ${\tau}^t_{1,13}$ , ${\tau}^t_{2,5}$ , ${\tau}^t_{2,6}$ , ${\tau}^t_{2,15}$ ,..., ${\tau}^t_{147,134}$ , ${\tau}^t_{147,146}$ , ${\tau}^t_{148,142}$ , ${\tau}^t_{148,143}$ ],

where their values at different times are as follows.

${\theta}(t\leq24)$=
  
    [0.5, 0.5, 0.2, 0.3, 0.5, 0.2, 0.2, 0.6, 0.2, 0.2, 0.6, 0.4, 0.6, 0.7, 0.3, 0.2, 0.2, 0.6, 0.2, 0.3, 0.5, 0.7, 0.3, 0.2, 0.25, 0.55, 0.1, 0.3, 0.6, 0.2, 0.8, 0.4, 0.6, 0.1, 0.1, 0.8, 0.2, 0.25, 0.55, 0.5, 0.5, 0.45, 0.55, 0.15, 0.2, 0.65, 0.35, 0.65, 0.6, 0.25, 0.15, 0.65, 0.35, 0.45, 0.55, 0.5, 0.3, 0.2, 0.5, 0.5, 0.3, 0.7, 0.2, 0.5, 0.3, 0.55, 0.45, 0.35, 0.65, 0.4, 0.3, 0.3, 0.75, 0.25, 0.35, 0.65, 0.7, 0.15, 0.15, 0.3, 0.7, 0.55, 0.3, 0.15, 0.2, 0.8, 0.45, 0.1, 0.45, 0.25, 0.75, 0.35, 0.65, 0.15, 0.85, 0.25, 0.5, 0.25, 0.25, 0.75, 0.65, 0.35, 0.1, 0.6, 0.3, 0.75, 0.25, 0.65, 0.35, 0.65, 0.35, 0.15, 0.3, 0.55, 0.75, 0.25, 0.5, 0.5, 0.65, 0.35, 0.2, 0.8, 0.35, 0.65, 0.7, 0.3, 0.2, 0.8, 0.2, 0.8, 0.8, 0.2, 1.0, 0.5, 0.5, 0.85, 0.15, 1.0, 0.65, 0.25, 0.1, 0.35, 0.65, 0.3, 0.4, 0.3, 0.4, 0.6, 0.35, 0.65, 0.55, 0.45, 0.75, 0.25, 0.5, 0.5, 1.0, 0.3, 0.3, 0.4, 0.3, 0.7, 0.7, 0.3, 0.75, 0.25, 0.2, 0.8, 0.35, 0.65, 0.85, 0.15, 0.2, 0.3, 0.5, 0.5, 0.5, 0.35, 0.65, 0.6, 0.4, 0.7, 0.3, 0.35, 0.1, 0.55, 0.7, 0.3, 0.3, 0.4, 0.3, 1.0, 1.0, 0.75, 0.25, 0.15, 0.85, 1.0, 0.2, 0.8, 0.35, 0.65, 0.5, 0.5, 0.3, 0.1, 0.6, 0.1, 0.9, 0.5, 0.5, 0.3, 0.4, 0.3, 0.5, 0.5, 0.1, 0.6, 0.3, 1.0, 0.25, 0.75, 0.8, 0.2, 0.1, 0.9, 0.2, 0.8, 0.1, 0.9, 0.25, 0.75, 0.8, 0.2, 1.0, 0.15, 0.6, 0.25, 0.55, 0.45, 0.1, 0.6, 0.3, 0.5, 0.5, 0.8, 0.2, 1.0, 0.8, 0.2, 0.25, 0.75, 0.15, 0.85, 0.5, 0.5, 0.2, 0.8, 1.0, 0.2, 0.8, 0.4, 0.6, 0.3, 0.3, 0.4, 0.3, 0.7, 0.15, 0.4, 0.45, 1.0, 0.4, 0.6, 0.8, 0.2, 0.4, 0.6, 0.2, 0.2, 0.6, 0.65, 0.35, 0.6, 0.4, 0.8, 0.2, 0.1, 0.9, 0.7, 0.3, 0.25, 0.75, 0.4, 0.6, 0.55, 0.45, 0.25, 0.75, 0.3, 0.7, 0.25, 0.75, 0.3, 0.7, 0.3, 0.7, 0.4, 0.6, 0.25, 0.75, 0.4, 0.6, 0.35, 0.65, 0.5, 0.5, 0.5, 0.5].

${\theta}(t>24)$=
  
    [0.4, 0.6, 0.3, 0.3, 0.4, 0.15, 0.15, 0.7, 0.25, 0.3, 0.45, 0.45, 0.55, 0.65, 0.35, 0.2, 0.3, 0.5, 0.25, 0.3, 0.45, 0.75, 0.25, 0.1, 0.4, 0.5, 0.3, 0.2, 0.5, 0.3, 0.7, 0.3, 0.7, 0.15, 0.15, 0.7, 0.3, 0.25, 0.45, 0.6, 0.4, 0.5, 0.5, 0.15, 0.25, 0.6, 0.45, 0.55, 0.45, 0.35, 0.2, 0.6, 0.4, 0.5, 0.5, 0.3, 0.3, 0.4, 0.45, 0.55, 0.45, 0.55, 0.25, 0.45, 0.3, 0.5, 0.5, 0.3, 0.7, 0.3, 0.25, 0.45, 0.7, 0.3, 0.3, 0.7, 0.65, 0.2, 0.15, 0.45, 0.55, 0.55, 0.3, 0.15, 0.25, 0.75, 0.3, 0.2, 0.5, 0.15, 0.85, 0.25, 0.75, 0.4, 0.6, 0.3, 0.3, 0.4, 0.4, 0.6, 0.55, 0.45, 0.3, 0.35, 0.35, 0.65, 0.35, 0.45, 0.55, 0.6, 0.4, 0.2, 0.3, 0.5, 0.7, 0.3, 0.45, 0.55, 0.75, 0.25, 0.15, 0.85, 0.25, 0.75, 0.65, 0.35, 0.4, 0.6, 0.3, 0.7, 0.9, 0.1, 1.0, 0.6, 0.4, 0.75, 0.25, 1.0, 0.7, 0.2, 0.1, 0.25, 0.75, 0.4, 0.3, 0.3, 0.45, 0.55, 0.45, 0.55, 0.6, 0.4, 0.55, 0.45, 0.45, 0.55, 1.0, 0.4, 0.2, 0.4, 0.4, 0.6, 0.75, 0.25, 0.7, 0.3, 0.25, 0.75, 0.25, 0.75, 0.7, 0.3, 0.25, 0.3, 0.45, 0.6, 0.4, 0.45, 0.55, 0.55, 0.45, 0.6, 0.4, 0.4, 0.1, 0.5, 0.6, 0.4, 0.35, 0.4, 0.25, 1.0, 1.0, 0.8, 0.2, 0.2, 0.8, 1.0, 0.3, 0.7, 0.35, 0.65, 0.45, 0.55, 0.35, 0.1, 0.55, 0.25, 0.75, 0.6, 0.4, 0.25, 0.45, 0.3, 0.55, 0.45, 0.1, 0.4, 0.5, 1.0, 0.3, 0.7, 0.7, 0.3, 0.1, 0.9, 0.3, 0.7, 0.25, 0.75, 0.15, 0.85, 0.85, 0.15, 1.0, 0.2, 0.5, 0.3, 0.55, 0.45, 0.1, 0.45, 0.45, 0.45, 0.55, 0.75, 0.25, 1.0, 0.85, 0.15, 0.3, 0.7, 0.1, 0.9, 0.3, 0.7, 0.2, 0.8, 1.0, 0.3, 0.7, 0.35, 0.65, 0.2, 0.35, 0.45, 0.45, 0.55, 0.2, 0.4, 0.4, 1.0, 0.6, 0.4, 0.75, 0.25, 0.5, 0.5, 0.15, 0.15, 0.7, 0.85, 0.15, 0.45, 0.55, 0.75, 0.25, 0.1, 0.9, 0.55, 0.45, 0.15, 0.85, 0.45, 0.55, 0.5, 0.5, 0.15, 0.85, 0.25, 0.75, 0.4, 0.6, 0.35, 0.65, 0.45, 0.55, 0.3, 0.7, 0.35, 0.65, 0.3, 0.7, 0.4, 0.6, 0.45, 0.55, 0.5, 0.5].

The saturation flow rates of the links are as follows.

$s$=

    [1200, 2520, 4020, 2520, 2460, 2760, 2520, 2520, 2700, 1200, 2520, 1260, 1200, 2520, 2460, 1200, 1200, 3960, 1260, 1200, 1200, 1200, 1200, 1260, 1260, 1200, 1200, 1200, 1200, 1260, 1200, 2460, 2700, 2460, 4200, 1200, 1260, 1200, 1260, 2460, 2700, 2700, 2460, 1200, 1200, 1260, 1200, 2700, 1200, 2700, 4200, 2700, 1200, 1260, 1200, 1200, 1200, 1200, 2760, 1200, 2460, 4200, 1260, 2700, 2700, 2760, 2700, 1200, 1200, 2460, 2520, 2760, 2700, 4200, 2600, 1200, 1200, 2400, 2700, 2600, 2700, 2460, 2700, 2460, 3000, 3000, 2700, 4200, 1200, 1260, 1200, 1260, 1200, 1200, 2460, 2460, 2600, 2460, 3000, 2700, 1200, 1200, 4200, 1200, 1200, 1200, 1500, 2460, 2760, 2460, 2460, 2760, 3000, 1260, 1260, 4200, 1260, 1260, 1500, 1260, 2460, 2460, 2600, 2460, 3000, 2460, 1200, 1200, 4020, 1200, 1200, 1200, 1200, 1260, 1200, 2700, 2700, 2820, 2700, 2820, 2820, 2760, 2700, 2700, 2700, 2760, 2760, 2520] veh⁄h.

The inflow rates of the traffic network are given below.

Inflow rates | ${Q_{in,1}}$ | ${Q_{in,2}}$ | ${Q_{in,3}}$ | ${Q_{in,4}}$ | ${Q_{in,5}}$ | ${Q_{in,6}}$| ${Q_{in,7}}$ | ${Q_{in,8}}$ | ${Q_{in,9}}$
--- | --- | --- | --- |--- |--- |--- |--- |--- |---
$t\leq24$ | 700 | 950 | 850 | 400 | 650 | 450 | 950 | 750 | 800
$t\>24$ | 500 | 650 | 1100 | 350 | 700 | 750 | 800 | 650 | 600
   
