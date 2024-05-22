# 1.8. Safety Functions

The robot’s safety system is designed redundantly (HFT=1) to satisfy the performance level (PL)=d Cat3 of [ISO13849-1:2015] and safety integrity level (SIL) level 2 of [IEC62061:2005] and continuously monitors the status of safety-related devices. When an error detection signal through self-diagnosis or safety-related signal is input, the robot will be stopped according to the stop classification determined through risk assessment. Additionally, if any of the redundant switches in the safety circuit are activated, the motor drive power and brake drive power will be cut off to ensure a safe state. Information about the relevant status can be checked through the teach pendant.

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cgy6{background-color:#fe0000;color:#ffffff;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-cgy6"><img src="../../_assets/작은주의표시.png"> Danger</td>
    <td class="tg-0lax">Safety circuits must never be ignored, modified, or altered in any way.</td>
  </tr>
</thead>
</table>

The robot’s main safety-related functions are as follows.
