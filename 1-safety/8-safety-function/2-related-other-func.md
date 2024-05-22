# 1.8.2. Other Related Functions

If a person gets crushed in an accident caused by the robot arm, please fully understand the following and take action accordingly.

* Releasing the manual brake


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
    <td class="tg-0lax">Additional issues may occur because of gravity or the release of the brake, so the ropes and cranes specified for the transportation of the robot must be used to prevent the brakes from dropping when they are released and other accidents from occurring.</td>
  </tr>
</thead>
</table>


- The power to the controller should be cut off, the brake release unit should be connected to the designated robot connector or controller’s internal board connector, and the manual brake release should be performed for each axis as needed.

- Please refer to “3.3 How to Transport” for information on the axes and the designated transportation equipment (e.g. ropes, cranes) of the robot.

* When the robot is stopped by the limit switch
When the robot is stopped by the limit switch, the position of the robot can be changed by jogging the robot with the teach pendant in the integer setting mode. Soft limits should be specified according to the conditions of the site, and hardware limits should then be installed and applied by trained workers.



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
    <td class="tg-cly1">Our company is not responsible for the failure of the jogging operation due to the failure of the limit switch.<br>
Inspections must be performed periodically. For troubleshooting, please refer to the troubleshooting manual.
</td>
  </tr>
</thead>
</table>

