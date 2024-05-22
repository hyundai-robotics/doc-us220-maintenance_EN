# 6.5.3. Encoder Compensation and Selection



*	It is necessary to compensate the encoder data at the reference position of each axis of the robot.

*	Compensate the encoder by referring to “Encoder Compensation” in the controller operation manual.

[Encoder Compensation Screen]



![](../../_assets/그림_6.5_엔코더_보정.png)

Figure 6.5 Encoder Compensation

(1)	Select an axis, move the axis to the reference position using the [Axis Operation] key, and press the “[F1]: Single Initialization” key.

(2)	When you move all axes to their reference positions using the [Axis Operation] key and press the “[F2]: All initialization” key, the encoder offset compensation will be conducted for all axes at once.

(3)	To save the settings data, press the “[F7]: OK” key. When you press the [ESC] key, the changed data will not be saved.



<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-b001{background-color:#f8ff00;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-b001"><img src="../../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">When performing the encoder data compensation after replacing a motor, first turn Power Ready mode “ON,” and check whether power is supplied to the motor.</td>
  </tr>
</thead>
</table>

