# 3.5.3. Example of permitted torque and inertia moment calculation (HS180 Case)

(1)	Case #1 Simple 2-D model

![](../../_assets/그림_3.14_2차원_부하_모델.png)

Figure 3.14 2D Load Model



M - Load weight

J<sub>xx</sub> - Inertia moment in X direction from weight center of load

J<sub>yy</sub> - Inertia moment in Y direction from weight center of load

J<sub>zz</sub> - Inertia moment in Z direction from weight center of load

J<sub>a4</sub> - Inertia moment from R2 axis rotation center

J<sub>a5</sub> - Inertia moment from B axis rotation center

J<sub>a6</sub> - Inertia moment from R1 axis rotation center


 
<br></br>
☞ Load condition: Stainless steel with length and width of 260mm and thickness of 260mm (Mass 138.15kg)

① Weight limitation

Load weight: 138.15 ≤180 kg

   <br>

②	Permitted torque limit

Location of B axis weight center   L<sub>X</sub> = 350mm, L<sub>Y</sub> = 0mm, L<sub>Z</sub> = -60mm

The distance from the axis B and R1 to the center of gravity can be calculated as follows.

![](../../_assets/3.6.3_수식1.png)


<br>

③	Permitted inertia moment limit

Inertia moment of load from the weight   J<sub>xx</sub>= 1.56kgm², J<sub>yy</sub>= 1.56 kgm², J<sub>zz</sub>= 1.56 kgm²


![](../../_assets/3.6.3_수식2.png)


<br>
  
④	Conclusion

It is safe because the weight, torque and inertia moment all satisfy the limited condition.

<br></br>

(2)	Case #2 Complicated 3-D model

![](../../_assets/그림_3.15_3차원_부하_모델_2D_형상.png)

Figure 3.15 2D Shape of the 3D Load Model

<br></br>

Aluminum block shape combination
(σ=0.0027 g/mm<sup>3</sup> : 176.3 kg)

m1 (60×300×300)	 14.6kg

m2 (480×440×220)	125.4kg

m3 (280×300×160)	 36.3kg

<br>

mi  - i 블록 부하 중량

L<sub>xi</sub> - Weight center location in X axis direction of I block

L<sub>yi</sub> - Weight center location in Y axis direction of I block

L<sub>zi</sub> - Weight center location in Z axis direction of I block

<br>

①	Weight limitation

Load weight : 176.3 ≤180 kg

<br>

②	Permitted torque limit

You can calculate the weight center location for the total load from the B axis rotation center as follows.

![](../../_assets/3.6.3_수식3.png)


<br>

The weight center location for the total load from the B axis rotation center L<sub>x</sub> = 520.85mm, L<sub>y</sub> = 0mm, L<sub>z</sub>= -238.47mm

<br>

![](../../_assets/3.6.3_수식4.png)

<br>

x1 y1 z1 – x, y and z direction length of block m1

x2 y2 z2 – x, y and z direction length of block m2

x3 y3 z3 – x, y and z direction length of block m3

<br>

L<sub>X1</sub>, L<sub>Y1</sub>, L<sub>Z1</sub> - Weight center location of block m1 from B axis rotation center

L<sub>X2</sub>, L<sub>Y2</sub>, L<sub>Z2</sub> - Weight center location of block m2 from B axis rotation center

L<sub>X3</sub>, L<sub>Y3</sub>, L<sub>Z3</sub> - Weight center location of block m3 from B axis rotation center

<br>

J<sub>xx1</sub>, J<sub>yy1</sub>, J<sub>zz1</sub> – Inertia moment by x, y and z axis from the weight center of block m1

J<sub>xx2</sub>, J<sub>yy2</sub>, J<sub>zz2</sub> – Inertia moment by x, y and z axis from the weight center of block m2

J<sub>xx3</sub>, J<sub>yy3</sub>, J<sub>zz3</sub> – Inertia moment by x, y and z axis from the weight center of block m3


![](../../_assets/그림_3.16_3차원_부하_모델_3D_형상.png)

Figure 3.16 3D Shape of the 3D Load Model

<br>

③	Permitted inertia moment limit

Table 3-5 Inertia moment from weight center by block
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1e26{background-color:#f8f8be;color:#000000; font-weight:bold;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-1e26">Block weight (kg)</th>
    <th class="tg-1e26">Weight center(L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>)</th>
    <th class="tg-1e26">J<sub>xx</sub></th>
    <th class="tg-1e26">J<sub>yy</sub></th>
    <th class="tg-1e26">J<sub>zz</sub></th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-amwm">m<sub>1</sub>(14.6)</td>
    <td class="tg-baqh">(0.25, 0, 0)</td>
    <td class="tg-baqh">0.219 kgm²</td>
    <td class="tg-baqh">0.114 kgm²</td>
    <td class="tg-baqh">0.114 kgm²</td>
  </tr>
  <tr>
    <td class="tg-amwm">m<sub>2</sub>(125.4)</td>
    <td class="tg-baqh">(0.48, 0, -0.26)</td>
    <td class="tg-baqh">2.530 kgm²</td>
    <td class="tg-baqh">2.915 kgm²</td>
    <td class="tg-baqh">4.433 kgm²</td>
  </tr>
  <tr>
    <td class="tg-amwm">m<sub>3</sub>(36.3)</td>
    <td class="tg-baqh">(0.89, 0, -0.26)</td>
    <td class="tg-baqh">0.350 kgm²</td>
    <td class="tg-baqh">0.314 kgm²</td>
    <td class="tg-baqh">0.509 kgm²</td>
  </tr>
</tbody>
</table>

<br>

![](../../_assets/3.6.3_수식5.png)

<br>

④	Conclusion

It is safe because the weight, torque and inertia moment all satisfy the limited condition.
