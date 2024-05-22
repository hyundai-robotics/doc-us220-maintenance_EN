# 1.11.2. Safety Measures for Operating the Robot for Testing

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
    <td class="tg-cly1">When the test operation is conducted, there may be design errors, teaching errors, or manufacturing defects in the entire system including the teaching program, jigs, and sequences. Therefore, it is necessary to work with more safety awareness in performing the test operation. In some cases, safety accidents may occur because of complex factors. Safety is very important during the robot test operation, so the following should be observed.</td>
  </tr>
</thead>
</table>


*	Prior to operation, check whether the switches or signals that stop the robot, such as the emergency stop switch, stop switch, or the equivalent, are operational. After that, check the operations related to the detection of abnormalities. First, it is most important to check all signals that are designed to stop the robot. When an accident is predicted, the most important thing is to stop the robot.

*	When required to perform a test operation of the robot, first set it to manual mode, input data into a job program that tests all axes, and then check the operation for more than one cycle in the unit of steps. While the robot is moving, open the safety guard or remove the enabling switch (enabling the teach pendant) to check whether the robot stops. If a problem is found, press the emergency stop button, and check whether the robot stops. If the emergency stop device does not perform its function, immediately cut off the main power. After that, please call the responsible after-sales person. After that, increase the speed sequentially (50% → 75% → 100%) and operate the robot repeatedly for more than one cycle at each speed to check the operation. If the robot is operated at high speed from the beginning, it may cause a severe accident.

*	It is impossible to foresee what problems may arise during the test operation. During the test operation, never go inside the safety fence. Because of low reliability of the system, there is a high possibility that unexpected accidents occur.

