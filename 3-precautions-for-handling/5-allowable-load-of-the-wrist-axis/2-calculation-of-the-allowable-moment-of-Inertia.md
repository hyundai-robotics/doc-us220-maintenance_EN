# 3.5.2. Permitted inertia moment estimation

Loads must be kept below maximum conditions shown in [Table 3-3 ~ 3-5].

*	Step 1

    Calculate the inertia moment value of the load at each wrist axis center (J<sub>a4</sub>, J<sub>a5</sub>, J<sub>a6</sub>)

    J<sub>a4</sub> - Inertia moment from R2 axis rotation center

    J<sub>a5</sub> - Inertia moment from B axis rotation center

    J<sub>a6</sub> - Inertia moment from R1 axis rotation center

*	Step 2

    Check whether the inertia moment value is within the limit based on the allowed inertia moment table


![](../../_assets/작은주의표시.png) <b>Allowable Moment of Inertia</b>

Table 3-4 Allowable Moment of Inertia

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-zegx{background-color:#f8f8be;color:#000000; font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-zegx" rowspan="2">Robot model</th>
    <th class="tg-zegx" colspan="3">Allowable moment of inertia</th>
  </tr>
  <tr>
    <th class="tg-zegx">4 axis</th>
    <th class="tg-zegx">5 axis</th>
    <th class="tg-zegx">6 axis</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">US220</td>
    <td class="tg-nrix" colspan="2">152 kg·m² (15.5 kgf·m·s²)</td>
    <td class="tg-nrix">86 kg·m² (8.8 kgf·m·s²)</td>
  </tr>
</tbody>
</table>
