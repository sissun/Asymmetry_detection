This software is developed using Microsoft visual studio 2015.
The input include: the 3D model file(.sca), the sampling point file （-sampling.txt） and the WKS value file （-wks.txt）

1. Format of 3D meshes 
the number of vertices (n)
x1   y1   z1
x2   y2   z2
.      .      .
xn   yn   zn
the number of triangle meshes (m)
a1   b1   c1
a2   b2   c2
.      .      .
am  bm  cm

2. Format of sampling.txt
x1   y1   z1
x2   y2   z2
.      .      .
xd   yd   zd

3. Format of wks.txt
number of vertices (n)   number of frenquncies (k)
wks11   wks12   .....   wks1k
wks21   wks22   .....   wks2k
.            .                   .
wksn1   wksn2   .....   wksnk