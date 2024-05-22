# Manipulator Maintenance Manual - US220

{% hint style="warning" %}
The information provided in this manual is the property of Hyundai Robotics.

The manual may not be copied, in part or in full, nor redistributed without a prior written consent from Hyundai Robotics. It may not be provided to any third party nor used for any other purposes.


The manual may be changed without prior notification.



**Copyright ⓒ 2023 by Hyundai Robotics**
{% endhint %}
# 1. Safety
# 1.1. Applicable Standards

The safety standards that apply to this product are as follows.

* ANSI/RIA/ISO 10218-1:2011 Robots and robotic devices - Safety requirements for industrial robots - Part 1: Robots

* ANSI/RIA R15.06-2012 - Industrial Robots and Robot Systems - Safety Requirements

* ISO 10218-2:2011 Robots and robotic devices - Safety requirements for industrial robots - Part 2: Robot systems and integration

* IEC 61508-1:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 1: General requirements

* IEC 61508-2:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 2: Requirements for electrical/electronic/programmable electronic safety-related systems

* IEC 61508-3:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 3: Software requirements 
  
* IEC 61508-4:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 4: Definitions and abbreviations

* IEC 61508-5:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 5: Examples of methods for the determination of safety integrity levels

* IEC 61508-6:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 6: Guidelines on the application of IEC 61508-2 and IEC 61508-3 

* IEC 61508-7:2010 Functional safety of electrical/electronic/programmable electronic safety-related systems - Part 7: Overview of techniques and measures 
  
* IEC 61800-5-1:2007/A1:2017 Adjustable speed electrical power drive systems - Part 5-1: Safety requirements - Electrical, thermal and energy 

* IEC 61800-5-2:2015 Adjustable speed electrical power drive systems - Part 2: General requirements - Rating specifications for low voltage adjustable speed a.c. power drive systems

* ISO 13849-1:2015 Safety of machinery - Safety-related parts of control systems - Part 1: General principles for design

* ISO 13849-2:2012 Safety of machinery - Safety-related parts of control systems - Part 2: Validation

* IEC 62061:2005/A2:2015 Safety of machinery. Functional safety of safety-related electrical, electronic and programmable electronic control systems

* IEC 61800-3:2017 Adjustable speed electrical power drive systems - Part 3: EMC requirements and specific test methods

* IEC 61000-6-7:2014 Electromagnetic compatibility (EMC) - Part 6-7: Generic standards - Immunity requirements for equipment intended to perform functions in a safety-related system (functional safety) in industrial locations

* IEC 61326-3-1:2017 Electrical equipment for measurement, control and laboratory use. EMC requirements. Part 3-1: Immunity requirements for safety-related systems and for equipment intended to perform safety-related functions (functional safety) - General industrial applications

* IEC 60204-1:2016 Safety of machinery - Electrical equipment of machines - Part 1: General requirements

* ISO 11161:2007 Safety of machinery - Integrated manufacturing systems - Basic requirements
# 1.2. Safety Performance

The performance of the safety modules of the industrial robot is as follows.

Table 1-1 Safety Performance of the Safety Module
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-nrix">Item</th>
    <th class="tg-nrix">Safety Performance</th>
    <th class="tg-nrix">Applicable Standards</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">HFT</td>
    <td class="tg-nrix">1</td>
    <td class="tg-nrix" rowspan="2">IEC 61508/62061/61800-5-2</td>
  </tr>
  <tr>
    <td class="tg-nrix">SIL (Safety Integrity Level)</td>
    <td class="tg-nrix">2</td>
  </tr>
  <tr>
    <td class="tg-nrix">Category</td>
    <td class="tg-nrix">3</td>
    <td class="tg-nrix" rowspan="2">ISO 13849-1</td>
  </tr>
  <tr>
    <td class="tg-nrix">PL (Performance Level)</td>
    <td class="tg-nrix">d</td>
  </tr>
</tbody>
</table># 1.3. Safety Training

To use the product’s functions effectively, users should fully understand the contents of the manual and properly install, use, and maintain the product. Users of the product are responsible for fully understanding and complying with the robot-related safety laws and regulations in the region where the robot is installed and used and properly designing, installing, and operating safety devices to ensure the safety of the users working with the robot system.

*	All workers who install, use, or maintain the robotic system must fully read and understand the contents of this manual. In particular, they must fully understand the safety precautions (![](../_assets/작은주의표시.png)).

*	Our company plans and implements training sessions related to the installation, use, and maintenance of the product. The users and operators of the product must complete the relevant training course before using the product.

*	Workers responsible for teaching and inspecting the robots must complete training courses related to robot usage and safety. The contents of the safety training courses are as follows.

    *	The concept of safety and the purpose and function of safety devices

    *	Procedures for handling the robot safely

    *	Performance and potential risk factors of the robot and robot system

    *	Works related to the applications of specific robots, etc.

# 1.4. Risk assessment

Risk assessment is one of the most important factors in constructing an integrated system, including robots, to the extent that it is treated as a legal requirement in most countries. Depending on how the robot is integrated into the system, the safety assessment related to the installation of the robot will vary, so it is impossible to assess the risk of an integrated system only based on the robot alone.

The system manager should conduct risk assessment by configuring and operating a robotic system according to the guidelines of ISO 12100 and ISO 10218-2.

Risk assessment should be conducted considering the entire process of the integrated system, including the robot. The main objectives of risk assessment are as follows.

*	Basic settings for using and teaching the robot

*	Diagnosis of issues and maintenance

*	Normal operation of the installed robot

Users must perform risk assessment after installing the robot and configuring the system. Risk assessment primarily judges the adequacy of the safety devices in the robot integrated system as well as the necessity for additional emergency stop devices and other safety devices. It is very important to properly configure the robot integrated system by identifying the appropriate safety devices. Users are required to configure the robot integrated system by referring to the relevant information in the manual. For details on configuring safety functions, please refer to “1.8. Safety Functions.” In addition, when required to install a robot in a specific location or configure safety-related functions using safety I/O, the important items regarding the risk assessment of the robot integrated system are as follows.

*	Severity

*	Frequency of exposure to risk

*	Possibility of occurrence

*	Possibility of avoidance

When configuring an integrated system, if the safety-related functions of the robot do not sufficiently eliminate risk factors, a risk assessment may identify the need for additional protective devices.

# 1.5. Potential Risks

If the risk assessment of the integrated system linked to the robot derives results showing that the safety-related functions of the robot alone do not sufficiently eliminate risk factors, additional protective measures must be established.

The things to consider when establishing additional protective measures are as follows.

*	Fingers caught (crushed) between the robot base and the installation platform during installation

*	Injuries (punctures, penetration, etc.) caused by sharp edges or the pointed parts of the obstacles or tools in the work envelope.

*	Injuries (bruises, falls, fractures, etc.) caused by collision with the robot

*	Injuries (punctures, penetration, fractures, etc.) caused by obstacles around the robot

*	Injuries that may occur if a fastened part is not completely fixed

*	Injuries (skin damage, breathing difficulties, etc.) that may occur when working with toxic or hazardous substances

*	A workpiece dislodged from a tool because of a sudden power interruption

*	Mistakes caused by confusion with emergency stop switches on other equipment

*	Errors caused by arbitrarily changing the settings of safety-related functions, etc.

Because the types of risks that may occur vary depending on the system configuration, users must conduct a risk assessment before using the integrated system.

# 1.6. Effectiveness and Responsibility

Safety requirements should be followed according to the safety regulations and laws of the country and region where the robot is installed and used. Suppliers and users of the robot integrated systems have a variety of responsibilities, including the following.

*	Risk assessment of the robot integrated system

*	Addition and removal of safety devices according to risk assessment results

*	Verification of whether the integrated system is correctly configured, installed, and set up

*	Establishment of usage methods and guidelines for the integrated system, and training of users for it

*	Management of safety devices (prohibition of arbitrary modification or manipulation of safety devices by users)

*	Provision of important information regarding product use and safety as well as contact information

*	Provision of all types of technical documentation, including manuals, etc.

The safety-related contents in this manual do not cover all risk factors and situations that may arise during the use of the product. 

# 1.7.1. High Temperature Caution Label


![](../../_assets/그림_1.1_고온주의라벨.png  )

Figure 1.1 High Temperature Caution Label

Please note that areas where this label is attached radiate heat. If you are required to work while the robot is in a heated state, makes sure to wear protective gear, such as heat-resistant gloves.# 1.7.2. Collision Risk Label


![](../../_assets/그림_1.2_충돌위험라벨.png  )

Figure 1.2 Collision Risk Label

If a person is located within the robot’s work envelope, accidents may occur from collision, crushing, etc., because of the unexpected operation of the robot. During operation, make sure that no one is inside the work envelope and the operator is in a safe position. If a problem occurs, press the emergency stop button immediately.
# 1.7.3. Grease Replenishment/Replacement Label


![](../../_assets/그림_1.3_그리스보충교환라벨.png  )

Figure 1.3 Grease Replenishment/Replacement Label

Follow the instructions on this label when replenishing or replacing grease.

For the specified grease, grease injection amount, and locations of the grease inlet and outlet, please refer to “5.1.1. Grease Injection After Grease Replacement and Reducer Replacement.”

# 1.7.4. Crushing Caution Label


![](../../_assets/그림_1.4_협착주의라벨.png  )

Figure 1.4 Crushing Caution Label

When performing the teaching work within the robot’s work envelope, do not get close to the operating robot. Contact with the robot during operation is prohibited, and noncompliance may result in injury.
# 1.7.5. Caution Label Regarding Transport


![](../../_assets/그림_1.5_운반시주의라벨.png  )

Figure 1.5 Caution Label Regarding Transport

When transporting the robot, refer to the transport label. For the transport posture, refer to “3.3. How to Transport.”
# 1.7.6. Electric Shock Caution Label


![](../../_assets/그림_1.6_감전주의라벨.png  )

Figure 1.6 Electric Shock Caution Label

Please be careful, as there is a risk of electric shock in areas where this label is attached. If you have no choice but to touch the area, turn off the power and make sure to prepare protective gear, such as insulating gloves.
# 1.7.7. Caution Label Regarding the Disassembly of the Motor


![](../../_assets/그림_1.7_모터분해주의라벨.png  )

Figure 1.7 Caution Label Regarding the Disassembly of the Motor

Do not disconnect the motor while the frame is not secured. Noncompliance with this safety measure may result in injury because of the unexpected rotation of the robot’s arm. 
# 1.7.8. Gas Spring Disassembly Prohibition Label


![](../../_assets/그림_1.8_가스스프링분해금지라벨.png  )

Figure 1.8 Gas Spring Disassembly Prohibition Label

Do not disassemble the gas spring; it is very dangerous, as it is filled with high-pressure nitrogen. Make sure to use nitrogen gas when filling.

# 1.7.9. Caution Label Regarding the Replacement of the Gas Spring

![](../../_assets/그림_1.9_가스스프링교체시주의라벨.png)

Figure 1.9 Caution Label Regarding the Replacement of the Gas Spring

If the gas spring pressure drops, the robot arm may drop, so never approach below the arm’s dropping direction. 

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
# 1.8.1. Main Safety Functions

* Emergency Stop ((IEC 60204-1,10,7)

There is one emergency stop button on the controller and teach pendant respectively. If necessary, additional emergency buttons can be connected to the robot’s safety chain circuit. The emergency stop function is applied with priority over all other control functions of the robot. It will bring the robot to a halt by immediately cutting off the power supply to the motors of individual axes of the robot and also disabling the use of safety-related functions controlled by the robot. 


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
    <td class="tg-cly1">The emergency stop immediately cuts off the motor power, so indiscriminate use of this function may cause accumulation of fatigue in terms of the robot’s durability. You must use it only in emergency situations.</td>
  </tr>
</thead>
</table>


![](../../_assets/그림_1.10_제어기_티치펜던트_비상정지_스위치.png)

Figure 1.10 Emergency Stop Switches on the Controller and Teach Pendant

![](../../_assets/그림_1.11_추가_비상정지_장치_연결.png  )

Figure 1.11 Connection of an Additional Emergency Stop Device

*	Protective Stop (ISO 10218-1:2011)

The robot should have multiple safety inputs that can be used in connection with external safety devices, such as safety guards, safety pads, safety lights, etc. Coming from the robot itself, surrounding facilities, etc., these safety inputs will make the robot stop, ensuring a safe state. For details on safety input connections, see “4.3.2. Safety Modules (BD632) in the Hi6-N Controller Maintenance Manual.”

*	Speed Limitation (EN ISO 10218-1:2011)

In manual operation mode, the maximum speed of the robot is limited to 250 mm/s. The speed limit applies not only to the tool center point (TCP) but to all parts of the robot that can be manually operated. Additionally, it should be able to monitor the speed of the equipment mounted on the robot.

*	Work Envelope Restriction (ANSI/RIA R15.06-2012)

When operating the robot, the user can limit its work envelope using limit switches and stoppers to secure a sufficient safe area. This function can minimize possible damages if the robot collides with an external safety device, such as a safety guard. The work envelope of axes 1, 2, and 3 is limited by stoppers or limit switches. If the work envelope is changed by a stopper or limit switch, its limit parameters should be changed in the software as well. For the changes, please refer to “7.4.3. Soft Limit in the Hi6 Controller Manual.” The limit of the work envelope of each axis can be changed by the user and is set to the maximum work envelope of the robot at the time of shipment. The Hi6 controller’s safety system can support up to four limit switches as an option. For matters related to connection, refer to “4.3.2. Safety Module (BD632) in the Hi6-N Controller Maintenance Manual.

*	Selection of Operation Mode (ANSI/RIA R15.06-2012)

The robot can be operated manually, automatically, or in remote mode. In manual mode, the maximum speed is limited to 250 mm/s, and operation can be performed only through the teach pendant. A mode switch can be additionally installed on the control panel by configuring the options. For details on operation, please refer to “2. Operation in the Hi6 Controller Operation Manual.”

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
    <td class="tg-b001"><img src="../../_assets/작은주의표시.png"> 주의</td>
    <td class="tg-cly1">Our company is not responsible for the failure of the jogging operation due to the failure of the limit switch.<br>
Inspections must be performed periodically. For troubleshooting, please refer to the troubleshooting manual.
</td>
  </tr>
</thead>
</table>

# 1.9. Stopping

The Hi6 controller’s safety system can handle the following stop. The classification of each safety input according to the stop classification criteria specified in IEC 60204-1 is as follows.

* Stop Classified 0: Stopping by immediately removing the power to the mechanical actuator (uncontrolled stopping)

    →  Emergency stop button

* Stop Classified 1: Controlled stopping in which the power is available to the machine actuator to perform stopping and the power is to be removed once stopping is performed

    →  Safety inputs other than the emergency stop button
# 1.10. Safety Measures for Installation
# 1.10.1. Installation of Safety Guards

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">Because there is a risk of collision between the robot and the worker when the robot operates, a safety fence should be installed to prevent workers from getting too close to the robot.</td>
  </tr>
</thead>
</table>


Because there is a risk of collision between the robot and the worker when the robot operates, a safety fence should be installed according to ISO 13855:2010 to prevent workers from getting too close to the robot. The robot should be configured such that it can stop if there is any act of opening the safety fence gate and accessing the facility during the operation of the robot for any reason, such as inspection of the robot or welding fixture, tip dressing, or tip changing.

![](../../_assets/그림_1.12_안전펜스_연결.png  )

Figure 1.12 Connection of the Safety Fence

Source: ISO 13855:2010 Safety of machinery — Positioning of safeguards with respect to the approach speeds of parts of the human body


Table 1-1 Installation Standard of the Safety Fence

![](../../_assets/표_1.1_안전펜스_설치_규격.png)

Source: ISO 13855:2010 Safety of machinery - Positioning of safeguards with respect to the approach speeds of parts of the human body

*	Enough space for the safety fence should be secured to cover the work envelope and allow the workers to teach and repair without difficulty, and the safety fence should be sturdy enough to prevent it from being moved easily and structured so that people cannot easily step over it.

*	In principle, the safety fence should be installed in fixed manner. Please use a safety fence that does not have dangerous parts such as irregularities or sharp parts.

*	An entrance gate to allow entry inside the safety fence should be installed, and a safety plug must be installed on the entrance gate to prevent the gate from opening unless the plug is pulled out. Also, wiring should be carried out so that the robot will be in the Motor Off / Brake Hold state when the safety plug is pulled out or the safety fence is opened.

*	Wiring should be performed so that low-speed playback can occur when the robot needs to be operated while the safety plug is pulled out.
*	The emergency stop button should be installed at a place where it can be pushed quickly by the worker. 

*	If no safety fence is to be installed, safety devices such as photoelectric switches and mat switches, which can replace the safety plugs, should be installed for the entire area that falls within the specification of the safety guard of the robot such that the robot can be stopped automatically when a person enters the covered area.

*	It should be made possible to identify the work envelope (dangerous area) of the robot by a method such as painting the floor. 

# 1.10.2. Placement of the Robot and Peripheral Devices

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, the relevant requirements of the applicable international standards and national laws should be observed. <br>
When it comes to the accidents that may occur because of failure to comply with the relevant requirements of international standards and national laws, or failure to review our company (or the manufacturer) will not be responsible for them.</td>
  </tr>
</thead>
</table>

The installation should be performed by qualified installation personnel and conform with the relevant regulations and laws of the concerned country and region.

*	When unpacking the robot, check it for any possible damages that could occur during transporting or unpacking.

*	Before installing the product after unpacking it, the user must check the safety regulations and instructions and product installation and use environment information and fully understand the installation method.

*	When required to connect the primary power of the controller or peripheral device, check first if the supply side power is off before proceeding with the work. There is a risk of electric shock because of the use of high voltage as the primary power source. 

*	Attach the [Do Not Enter During Operation] sign to the entrance gate of the safety fence and inform the workers of its intent. 

*	Place the controller, interlock panel, and other operation panels in a way that they can be operated outside the safety fence. 

*	When installing an operation stand, attach an emergency stop button to it as well. It should be made possible to stop the robot in an emergency situation at any location from which the robot is operated. 

*	Make sure that the wires and pipes for the manipulator, controller, interlock panel, and timer are not caught on the feet of the workers or directly stepped on by the forklift. There is a risk of electric shock to workers, and disconnection of wiring can occur. 

*	Place the controller, interlock panel, operation stand, etc., in a location from which the movement of the manipulator can be seen sufficiently. There is a risk of major accident if the robot is malfunctioning or a worker is working in a location where you cannot see the operation of the robot.

*	Restrict the robot’s work envelope if the necessary work envelope is narrower than the area where the robot can operate. The work envelope can be limited by soft limits, limit switches, and stoppers. Even when the robot moves beyond the restricted area because of abnormal operation, such as by operating the robot incorrectly, the robot will be automatically stopped in advance by the work envelope limitation function. 

*	During welding, spatter may fall on the workers or surroundings, causing burns or fires. Install light shields, covers, etc., such that the movement of the manipulator can be seen sufficiently.

*	In the case of a device that shows the auto or manual mode of the robot, install the device conspicuously so that the operation status can be recognized even from a distance. An alarm from a buzzer or alarm light is useful when starting of the auto operation.

*	Make sure there is no protruding part on the peripheral devices around the robot. If necessary, cover them. In general, accidents may occur when a worker touches one of the devices, and major accidents may occur when a worker falls over after being surprised by the sudden movement of the robot.

*	Please do not design a system that requires putting your hand inside the safety fence to carry in or take out workpieces. There is a risk of being crushed or cut. 


![](../../_assets/그림_1.13_산업용_로봇의_원통형_안전펜스.png  )

Figure 1.13 Cylinder-Type Safety Fence for Industrial Robots


# 1.10.3. Installation of the Robot

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">The robot should be installed and operated according to the guidelines of ISO 10218-2. In addition, the relevant requirements of the applicable international standards and national laws should be observed. 
When it comes to the accidents that may occur because of failure to comply with the relevant requirements of international standards and national laws, or failure to review our company (or the manufacturer) will not be responsible for them. </td>
  </tr>
</thead>
</table>

The installation should be performed by qualified installation personnel and conform with the relevant regulations and laws of the concerned country and region.

*	When unpacking the robot, check it for any possible damages that could occur during transporting or unpacking.

*	Before installing the product after unpacking it, the user must check the safety regulations and instructions and product installation and use environment information and fully understand the installation method.

*	Workers who use the robot should fully understand the contents described in application and supplementary manuals to skillfully operate and handle the industrial robot. 

*	Workers who install the robot should be able to apply safety instructions if problems occur during installation. 

*	System suppliers should ensure that all circuits using safety functions surely perform the functions. 

*	The main power supplied to the robot should be installed so that it can be cut off from outside the work envelope of the robot. 

*	The system suppliers should clearly ensure that all circuits using the emergency stop function perform the function in a safe manner. 

*	For a case that requires stopping the robot abruptly, the emergency stop button should be located in a place where workers can easily access it.

*	Should take into consideration the size of the manipulator and the operation range to ensure that there is no interference with peripheral devices. 

*	Avoid installing the robot in places that can be reached by direct sunlight, where humidity is high, oil or chemicals are present, or a lot of metal powder or explosive gasses are in the air.

*	Install the robot where the ambient temperature is within the range of 0℃–45℃.

*	Secure enough space to easily disassemble and inspect the robot.

*	Install a safety fence and prevent people from entering the work envelope of the robot.

*	Make sure that there is no obstacle in the work envelope of the robot.

*	When required to install the robot in a place exposed to direct sunlight or near a heating element, you should take measures in consideration of the thermodynamic state of the controller.

*	When required to install the root in a place where there is a lot of dust such as metal powder in the air, you should take separate measures.

*	Install the robot in a way that the welding current never flows to the robot. In other words, there must be insulation between the spot gun and the wrist of the robot.

*	Considering that grounding is very important in preventing a false operation because of noise and an electric shock, you should carry out installation as follows.

    - A dedicated grounding terminal should be installed, and its grade must be higher than class 3 grounding. 

    - The grounding wire should be connected to the grounding bus bar inside the control panel. 

    -	When the manipulator is installed, if it is directly grounded to the floor by an anchor, etc., the controller side and the manipulator side constitute two grounding points, conversely causing a closed circuit to be formed with a risk of a false operation because of noise conversely. In this case, connect the grounding wire to the base of the manipulator and do not connect it to the controller side. Also, if vibration occurs when the robot is stopped, it is highly likely that the grounding is incomplete or a closed circuit has formed. Check the grounding again. 

    -	When a transformer-embedded gun is used, there is a risk of falling because the primary power cable is directly connected to the spot gun. In this case, to protect the control panel and prevent an electric shock, you should connect the grounding wire directly to the manipulator base and do not connect it to the controller.


*	Install by referring to “3.4. Installation Methods.”

*	Specify the soft limit according to the site conditions. After that, you must ensure that the location and adjustment of the hardware limit is performed by a trained operator. You must check whether it is working when installed.

# 1.11. Safety Works in Operating the Robot


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">Must follow safety work procedures to prevent safety accidents In no circumstance, do not change or ignore the safety systems and circuits, and be careful of electric shocks. 
In auto mode, all normal work should be performed from outside the safety guard. Before carrying out works, you must ensure that there is no one in the work envelope of the robot. </td>
  </tr>
</thead>
</table>

# 1.11.1. Safety Measures for Handling the Robot

Please observe the following measures because safety is very important when operating the robot.

*	The workers who operate or may operate the robot, and the supervisors must fully recognize the safety and the function of the robot by taking prescribed trainings. The robot must not be operated by anyone other than those who have been so trained and designated.

*	Before operating the robot, a qualified installation expert must confirm that the product has been installed in compliance with the relevant regulations and laws of the concerned country or region.

*	Before operating the robot, check whether the safety functions are working normally.

*	Must wear a safety hat, protective glasses and safety shoes. 

*	The work must be done by two people. One person performs teaching and the other monitors from the operation panel. One person should be ready to press the emergency stop switch at any time, and the other one should proceed with the works quickly while paying much attention in the work envelope. In addition, workers should check the evacuation routes in advance before the work.

*	Supply the power after confirming that there are no workers inside the safety guard.

*	In principle, work such as teaching should be performed outside the robot safety guard. However, when required to stop the robot and work within the work envelope, please go inside while carrying the safety plug, which is the mode switch key (or switch to change to automatic operation). It is necessary to ensure that other workers do not mistakenly switch the robot to auto operation. In addition, pay special attention to the operational direction of the robot in preparation for an unexpected situation such as false operations or wrong conditions. 


※	A supervisor should observe the following items.

    -	Position yourself in a place where you can see the entire robot and devote yourself to the monitoring work.
    -	When there is an abnormality, press the emergency stop button immediately.
    -	Make sure that no one other than those involved in the work is within the work envelope


*	Basically, the maximum speed during manual operation is limited to 250 mm/s. At this time, the workers inside and outside the guard should be prepared to press the emergency stop switch at any time if a problem occurs.

*	During manual operation at a high-speed mode, the operation should be performed from outside the safety guard.

*	When performing the teaching work, you should put a sign saying [Teaching in Progress.]

*	When entering a safety guard, the workers must pull the safety plug or an equivalent device and bring it with themselves.

*	Do not use equipment that may cause noise in or around the place where teaching work is performed.

*	Handle the teach pendant button while looking at the teaching point with your naked eyes, not by handling it just relying on the feeling of your hands. 


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">When teaching, workers should perform the work while carefully checking under their feet. In particular, when teaching at high speeds (over 250 mm/s), they must work from outside the safety guard. </td>
  </tr>
</thead>
</table>

*	Take the following measures when an abnormality occurs.

    -	If there is an abnormal operation spotted, press the emergency stop button immediately.

    -	When checking for an abnormality following an emergency stop, you must check the state of the stopping of the related facilities.

    -	If the robot automatically stops because of an abnormality in the power supply, you should first confirm that the robot has stopped completely and then investigate the cause and take measures.

    -	If the emergency stop system does not perform its functions, you should cut off the main power immediately, investigate the causes, and take measures.

    -	No one except for the designated person should investigate the cause. Restarting after an emergency stop should be performed in sequence after the cause of the error is clearly identified and measures are taken.

*	Create appropriate work regulations regarding not only the methods to drive and operate the robot but also the measures to take against abnormalities, considering the location of the installation and content of the work. In addition, work according to the work regulations.

*	Precautions When the Robot is Stopped

    -	You must avoid blindly approaching the robot assuming it is stationary. There are many cases where a person approached a robot the person thought was stationary, but the robot suddenly moved, resulting in a disaster. When the robot is stopped, it is in the following states.



Table 1-2 State of the Robot When It is Stopped
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-62g5{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:top}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-62g5">No.</th>
    <th class="tg-62g5">State of the robot</th>
    <th class="tg-62g5">Driving source</th>
    <th class="tg-62g5">Accessibility</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">1</td>
    <td class="tg-0lax">In temporary stop<br>(attributable to a minor abnormality or the temporary stop switch)</td>
    <td class="tg-baqh">ON</td>
    <td class="tg-baqh">X</td>
  </tr>
  <tr>
    <td class="tg-baqh">2</td>
    <td class="tg-0lax">In emergency stop<br>(attributable to a major abnormality, the temporary stop switch, or the safety door)</td>
    <td class="tg-baqh">OFF</td>
    <td class="tg-baqh">O</td>
  </tr>
  <tr>
    <td class="tg-baqh">3</td>
    <td class="tg-0lax">Waiting for an input signal from peripheral devices<br>
(START INTERLOCK)</td>
    <td class="tg-baqh">ON</td>
    <td class="tg-baqh">X</td>
  </tr>
  <tr>
    <td class="tg-baqh">4</td>
    <td class="tg-0lax">Playback being completed</td>
    <td class="tg-baqh">ON</td>
    <td class="tg-baqh">X</td>
  </tr>
  <tr>
    <td class="tg-baqh">5</td>
    <td class="tg-0lax">In standby</td>
    <td class="tg-baqh">ON</td>
    <td class="tg-baqh">X</td>
  </tr>
</tbody>
</table>

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
    <td class="tg-cly1">Even when access is possible, you should not neglect to pay attention to any possibility of sudden movements.<br>
In any case, you must avoid approaching the robot without preparing for an emergency.
</td>
  </tr>
</thead>
</table>

*	During a temporary stop, when opening the entrance gate to handle a minor abnormality (nozzle contact, detection of deposition, arc error, etc.), the same measures applied for entering and exiting for teaching work should be taken to enter and exit.

*	After completing the operation of the robot, you should clean the inside of the safety fence and make sure that no tools, oil, foreign substances, etc. are left there. If the work envelope is dirty with oil or littered with tools left, an accident such as a falling over may be caused. Always make it a habit to keep things organized and tidy. 

# 1.11.2. Safety Measures for Operating the Robot for Testing

{% hint style="info" %}
When the test operation is conducted, there may be design errors, teaching errors, or manufacturing defects in the entire system including the teaching program, jigs, and sequences. Therefore, it is necessary to work with more safety awareness in performing the test operation. In some cases, safety accidents may occur because of complex factors. Safety is very important during the robot test operation, so the following should be observed.
{% endhint %}


*	Prior to operation, check whether the switches or signals that stop the robot, such as the emergency stop switch, stop switch, or the equivalent, are operational. After that, check the operations related to the detection of abnormalities. First, it is most important to check all signals that are designed to stop the robot. When an accident is predicted, the most important thing is to stop the robot.

*	When required to perform a test operation of the robot, first set it to manual mode, input data into a job program that tests all axes, and then check the operation for more than one cycle in the unit of steps. While the robot is moving, open the safety guard or remove the enabling switch (enabling the teach pendant) to check whether the robot stops. If a problem is found, press the emergency stop button, and check whether the robot stops. If the emergency stop device does not perform its function, immediately cut off the main power. After that, please call the responsible after-sales person. After that, increase the speed sequentially (50% → 75% → 100%) and operate the robot repeatedly for more than one cycle at each speed to check the operation. If the robot is operated at high speed from the beginning, it may cause a severe accident.

*	It is impossible to foresee what problems may arise during the test operation. During the test operation, never go inside the safety fence. Because of low reliability of the system, there is a high possibility that unexpected accidents occur.

# 1.11.3. Safety Measures for Auto Operation

Safety is very important when operating the robot automatically, so the following should be observed.

*	Put a [Do Not Enter During Operation] sign on the entrance gate of the safety fence, and strictly ask workers to refrain from entering during the operation. If the robot is stopped, you may go inside the safety fence after judging the situation

*	When required to start auto operation, you must check whether there is a worker inside the safety fence. If you work without checking for the presence of a worker, an accident involving a person may occur. 

*	When required to start auto operation, start it after confirming that the program number, the step number, the mode, the selection for staring, etc. are all in a state that auto operation can be performed. If you start auto operation while a different program or step is selected, the robot may perform an unexpected operation, causing an accident. 

*	When required to start auto operation, start it after confirming that the robot is in a position that enables the start of the auto operation. Check whether the program number or step number matches the position of the robot. Even when the program number or step number is correct, if the robot is in a different position, an accident may occur because of an operation that is different from usual operations. 

*	When required to start auto operation, you should be prepared to press the emergency stop switch immediately. If an unexpected operation of the robot or an unexpected situation occurs, press emergency stop switch immediately. 

*	Identify the operation path, operation status, operation sound, etc. of the robot in a way to judge whether there is any abnormal state. Robots may suddenly malfunction or cause abnormalities. However, there are cases where the robot shows some signs before it fails. To foresee a failure in advance, you should grasp the state of the normal operation of the robot. 

*	If you identified any abnormality, immediately perform an emergency stop and take appropriate measures against the abnormality. If the robot is used without proper measures taken, not only the production will stop but also a severe failure that may cause a major accident that involves a person may occur. 

*	When required to complete the actions after an abnormality has occurred, do not operate the robot while a worker is inside the safety fence. Otherwise, because of low reliability, an unexpected accident, such as occurrence of abnormality, may occur. 

*	Before selecting automatic mode, if any safety device function that has been halted is found, recover it fully before carrying out the next task.
# 1.12. Safety Measures for Going Inside the Safety Fence

When required to enter a safety gate in the robot’s work envelope, a worker and supervisor who have received the necessary training should work as a team of two. Also, they must wear safety hats, protective glasses, and safety shoes. The supervisor should be prepared to press the emergency stop switch at any time, and the worker must bring the teach pendant along when going inside to prevent others from operating the robot. You must hang a sign on the operation panel of the controller to indicate that the robot is currently being operated. 

If a person enters the robot’s work envelope, the person must fully understand the following.

*	No one except for the person performing the teaching work should enter the work envelope of the robot.

*	The operation setting mode of the controller should be in manual mode on the operation panel of the controller.

*	Always wear certified working clothes.

*	Do not wear gloves when operating the controller.

*	Do not let your underwear, shirts, ties, etc. to come out of the working clothes.

*	Do not wear large jewelry such as earrings, rings, necklaces, etc.

*	Must wear safety shoes, safety hat, and protective glasses. If necessary, you should wear safety gear such as safety gloves.

*	Before operating the robot, check if the emergency stop circuit works properly to turn off the motor when the emergency stop switches on the control panel and teach pendant are pressed respectively.

*	Work in a posture that makes you face the manipulator.

*	Follow pre-determined work procedures.

*	Assume that a robot may unexpectedly charge at you, and prepare an evacuation method or place for evacuation accordingly.


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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">Even when access is possible, you should not neglect to pay attention to any possibility of sudden movements.
In any case, you must avoid approaching the robot without preparing for an emergency.</td>
  </tr>
</thead>
</table># 1.13. Safety Measures for Inspection and Maintenance
# 1.13.1. Safety Measures for Inspecting and Maintaining the Controller

Please observe the following safety measures when inspecting and maintaining the robot controller.

*	Inspection and maintenance works should be performed only by those who have received special maintenance trainings and fully understand the relevant contents.

*	Progress the works according to the procedures for inspecting and maintaining the controller.

*	Must perform the inspection and maintenance works safely after securing a passage or a place to avoid danger by checking the safety of the surroundings.

*	Must turn off the power when required to perform daily inspections, repairs, or replacement of parts of the robot. In addition, put a warning sign such as [Do Not Supply Power] on the primary power source so that other workers cannot turn on the power carelessly.

*	Use only the designated replacement parts.

*	When required to open the controller door, you must turn off the power and then wait for about three minutes before starting the work.

*	When carrying out maintenance or inspection work inside the controller, if sufficient illumination is not secured, use external lighting.

*	Do not touch the heat radiation plate and regenerative resistor of the servo amplifier because they generate excessive heat. After completing maintenance, you should check if tools or other things are left inside the controller and then securely close the door.

# 1.13.2. Safety Measures for Inspecting and Maintaining the Robot System or Manipulator

Please observe the following safety measures when inspecting and maintaining the robot system or manipulator.
	
*	When inspecting and maintaining the robot system or manipulator, you should progress the work by referring to ”4. Inspection” and “5. Maintenance.”

*	You must turn off the main power of the controller. In addition, put a warning sign such as [Do Not Supply Power] on the primary power source so that other workers cannot turn the power back on carelessly.
 

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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">When inspecting or maintaining the manipulator, the arm of the robot may fall and other hazards may occur, so you must proceed, keeping in mind the instructions.</td>
  </tr>
</thead>
</table>

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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">When moving the axis of the robot that has no braking force, additional hazards may occur because of the axis falling because of gravity or the release of the brake device, so you must proceed, keeping in mind the given instructions.</td>
  </tr>
</thead>
</table>
# 1.13.3. Actions to be Taken After Inspection and Maintenance

Please observe the following actions after inspection and maintenance.

*	After completing maintenance, check whether if any tools and materials are left in or around the controller, manipulator, or the system, and make sure to keep things organized and tidy. Close the controller’s door and mechanical manipulator’s cover.

*	Do not power on the robot if a problem or critical defect is found.

*	Turn on the power circuit breaker inside the control panel.

*	Check the current position and status of the robot.

*	Check the robot for its operation state manually at low speed. 

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
    <td class="tg-cly1">Before supplying the power, you should ensure that there is no worker in the robot’s work envelope and that you are in a safe place.</td>
  </tr>
</thead>
</table>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">In the case of the change of components or addition of optional devices (both hardware and software) to the robot that may affect safety-related functions, the user must check whether their functions are normal by carefully referring to the content described in “1.11 Safety Works When Operating the Robot.”</td>
  </tr>
</thead>
</table>

# 1.14. Safety Related to End Effectors


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">You must comply with ISO 10218-1:2018 when applying, repairing, and operating an end effector. </td>
  </tr>
</thead>
</table># 1.14.1. Gripper

*	When required to use a gripper, there should be preparatory measures in place in case the workpiece unexpectedly falls.

*	When required to mount a device to the top of an end effector or arm, use the bolts of specified sizes in specified counts, and use a torque wrench to tighten them with the specified torques. Also, the bolts that are not rusted or contaminated should be used.

*	Manufacture the end effectors by reviewing whether it can be used within the allowable load range of the wrists of the robot. In addition, the end effectors should be structured such that the gripped object will not be released or dropped even when the power or air supply is stopped and also that its corners or protruding parts are finished to prevent damage to people/objects. 

# 1.14.2. Tools/Workpieces

*	It should be made possible to replace tools, such as milling cutters, safely. The safety devices should perform their functions until the cutters stop rotating.

*	The tool should be designed so that the workpiece does not fail even when a sudden power outage or control failure occurs. In manual operation mode, it should be made possible to detach the workpiece. 

# 1.14.3. Pneumatic/Hydraulic Systems

*	Special safety regulations apply even to the pneumatic and hydraulic systems. 

*	These systems may have residual energy even after they’ve stopped, which requires your attention to safety. When required to repair the pneumatic and hydraulic systems, you must remove the residual pressure inside them beforehand. 

# 2. 사양
# 2.1. Format for the Robot Mechanical Part

![](../_assets/그림_2.1_로봇기구부형식.png)

Figure 2.1 Format for the Robot Mechanical Part

# 2.2. Location of the Robot Nameplate

The robot type, serial number, and manufacturing date are written down in the nameplate.

The nameplate is located at the bottom (left or right) of the manipulator, as shown in the picture below.


![](../_assets/그림_2.2_로봇명판부착위치.png)

Figure 2.2 The Attachment Location of the Robot Nameplate
# 2.3. Basic Specifications

Table 2-1 Basic Specification for Each Model

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-pchv{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-lput{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-qai4{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" colspan="4">Item</th>
    <th class="tg-yhpm">Specifications</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-lput" colspan="4">Specifications</td>
    <td class="tg-pchv">US220</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Model</td>
    <td class="tg-qai4">220 kg</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Structure</td>
    <td class="tg-qai4">Articulated</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Degree of freedom</td>
    <td class="tg-qai4">6</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Drive method</td>
    <td class="tg-qai4">AC servo method</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Installation type</td>
    <td class="tg-qai4">Floor mount</td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="11">Max.work envelope</td>
    <td class="tg-lput" rowspan="8">Main axis</td>
    <td class="tg-lput" rowspan="2">1(S)</td>
    <td class="tg-lput" rowspan="2">Swivel</td>
    <td class="tg-qai4">±180° (±3.142 rad) </td>
  </tr>
  <tr>
    <td class="tg-qai4">±180°(±3.142 rad)<sup>1</sup></td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="2">2(H)</td>
    <td class="tg-lput" rowspan="2">Forward and backward</td>
    <td class="tg-qai4">+155°~ +10°(+2.705 ~ 0.175 rad)</td>
  </tr>
  <tr>
    <td class="tg-qai4">+157.5°~ +7.5° (+2.749 ~ 0.131 rad)<sup>1</sup></td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="2">3(V)</td>
    <td class="tg-lput" rowspan="2">Upward and downward</td>
    <td class="tg-qai4">+190°~ -80° (+3.316 ~ -1.396 rad)</td>
  </tr>
  <tr>
    <td class="tg-qai4">+190.5°~ -79.5° (+3.325 ~ -1.388 rad)<sup>1</sup></td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="2">H/V</td>
    <td class="tg-lput" rowspan="2">Interference</td>
    <td class="tg-qai4">10°~ 280°(0.175 ~ 4.887 rad)</td>
  </tr>
  <tr>
    <td class="tg-qai4">10.5°~ 280.5°(0.183 ~ 4.896 rad)<sup>1</sup></td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="3">Wrist axis</td>
    <td class="tg-lput">4(R2)</td>
    <td class="tg-lput">Rotation 2</td>
    <td class="tg-qai4">±360°(±6.283 rad)</td>
  </tr>
  <tr>
    <td class="tg-lput">5(B)</td>
    <td class="tg-lput">Bending</td>
    <td class="tg-qai4"> ±128°(±2.234 rad)</td>
  </tr>
  <tr>
    <td class="tg-lput">6(R1)</td>
    <td class="tg-lput">Rotation 1</td>
    <td class="tg-qai4">±360°(±6.283 rad)</td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="6">Maximum speed</td>
    <td class="tg-lput" rowspan="3">Main axis</td>
    <td class="tg-lput">1(S)</td>
    <td class="tg-lput">Swivel</td>
    <td class="tg-qai4">120°/s (2.094 rad/s)</td>
  </tr>
  <tr>
    <td class="tg-lput">2(H)</td>
    <td class="tg-lput">Forward and backward</td>
    <td class="tg-qai4">105°/s (1.833 rad/s)</td>
  </tr>
  <tr>
    <td class="tg-lput">3(V)</td>
    <td class="tg-lput">Upward and downward</td>
    <td class="tg-qai4">110°/s (1.920 rad/s)</td>
  </tr>
  <tr>
    <td class="tg-lput" rowspan="3">Wrist axis</td>
    <td class="tg-lput">4(R2)</td>
    <td class="tg-lput">Rotation 2</td>
    <td class="tg-qai4">145°/s (2.531 rad/s)</td>
  </tr>
  <tr>
    <td class="tg-lput">5(B)</td>
    <td class="tg-lput">Bending</td>
    <td class="tg-qai4">145°/s (2.531 rad/s)</td>
  </tr>
  <tr>
    <td class="tg-lput">6(R1)</td>
    <td class="tg-lput">Rotation 1</td>
    <td class="tg-qai4">220°/s (3.840 rad/s)</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="2" rowspan="3">Wrist torque</td>
    <td class="tg-lput">4(R2)</td>
    <td class="tg-lput">Rotation 2</td>
    <td class="tg-qai4">1421 N·m(145kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-lput">5(B)</td>
    <td class="tg-lput">Bending</td>
    <td class="tg-qai4">1421 N·m(145kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-lput">6(R1)</td>
    <td class="tg-lput">Rotation 1</td>
    <td class="tg-qai4">774 N·m(79 kgf·m)</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Accuracy of position repeatability [Note 1]</td>
    <td class="tg-qai4">±0.07 mm</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="4">Manipulator weight</td>
    <td class="tg-qai4">938 kg</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="2" rowspan="3">Installation environment</td>
    <td class="tg-lput" colspan="2">Ambient temperature</td>
    <td class="tg-qai4">0 ~ 45℃ (273 ~ 318 K)</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="2">Relative humidity</td>
    <td class="tg-qai4">20 ~ 85 %RH</td>
  </tr>
  <tr>
    <td class="tg-lput" colspan="2">Vibration</td>
    <td class="tg-qai4">0.5G or lower</td>
  </tr>
</tbody>
</table>

<sup>1</sup> LS Option: This is the maximum operation angle when an angle restriction limit switch is attached.

[Note 1] Conforms to ISO 9283.# 2.4. External Dimensions of the Manipulator and the Work Envelope



![](../_assets/그림_2.3_로봇_본체_외형_치수_및_동작_영역.png)

Figure 2.3 External Dimensions of the Manipulator and the Work Envelope (US220)

# 2.5. Names of Operation Axes


Table 2-2 Rotational Direction of Each Axis
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-lput{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm">Axis name</th>
    <th class="tg-yhpm">Operation</th>
    <th class="tg-yhpm" colspan="2">Button on the Teach Pendant</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-lput">1-Axis (S)</td>
    <td class="tg-nrix">Swivel</td>
    <td class="tg-nrix">X+(1+)</td>
    <td class="tg-nrix">X-(1-)</td>
  </tr>
  <tr>
    <td class="tg-lput">2-Axis (H)</td>
    <td class="tg-nrix">Forward and backward</td>
    <td class="tg-nrix">Y+(2+)</td>
    <td class="tg-nrix">Y-(2-)</td>
  </tr>
  <tr>
    <td class="tg-lput">3-Axis (V)</td>
    <td class="tg-nrix">Upward and downward</td>
    <td class="tg-nrix">Z+(3+)</td>
    <td class="tg-nrix">Z-(3-)</td>
  </tr>
  <tr>
    <td class="tg-lput">4-Axis (R2)</td>
    <td class="tg-nrix">Rotation 2</td>
    <td class="tg-nrix">RX+(4+)</td>
    <td class="tg-nrix">RX-(4-)</td>
  </tr>
  <tr>
    <td class="tg-lput">5-Axis (B)</td>
    <td class="tg-nrix">Bending</td>
    <td class="tg-nrix">RY+(5+)</td>
    <td class="tg-nrix">RY-(5-)</td>
  </tr>
  <tr>
    <td class="tg-lput">6-Axis (R1)</td>
    <td class="tg-nrix">Rotation 1</td>
    <td class="tg-nrix">RZ+(6+)</td>
    <td class="tg-nrix">RZ-(6-)</td>
  </tr>
</tbody>
</table>

![](../_assets/그림_2.4_본체_외관_및_동작_축.png)

Figure 2.4 Appearance of the Manipulator, and the Operation Axes

# 2.6. Detailed Diagram of the Wrist Axis Attachment Surface


When attaching a work tool to the flange at the tip of the wrist axis, use the bolts of PCD 125. 


![](../_assets/그림_2.5_손목축_취부면_상세도.png)

Figure 2.5 Detailed Diagram of the Wrist Axis Attachment Surface

# 2.7. Detailed Diagram of the Arm Frame Top Attachment Surface

A tap for attaching a peripheral device is machined on top of the arm frame and arm pipe of the robot. 

Attach peripheral devices (a valve, etc.) within the range indicated by ▦.


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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">Attach a peripheral device to either the top of the arm frame or the top of the arm pipe. Perform attachment such that the central position of the load falls within the range indicated as ▦.</td>
  </tr>
</thead>
</table>



* Maximum load on the arm pipe: 20 kg


![](../_assets/그림_2.6_ARM_FRAME_상부_부착부_상세도.png)

Figure 2.6 Detailed Diagram of the Arm Frame Top Attachment Surface

# 2.8. Wiring and Piping Diagrams for Applications


There are connectors and an air unit for connecting additional devices.
The following pictures show the user application connectors.

[Note] Maximum air pressure: 5 bar (5.1 kgf/cm2,72.5 psi)




![](../_assets/그림_2.7_어플리케이션용_배선_및_배관도_BJ1.png)

Figure 2.7 Wiring and Piping Diagrams for Applications (BJ1 Part)

![](../_assets/그림_2.8_어플리케이션용_배선_및_배관도_BJ3.png)

Figure 2.8 Wiring and Piping Diagrams for Applications (BJ3 Part)

![](../_assets/그림_2.9_어플리케이션_커넥터_상세1.png)


![](../_assets/그림_2.9_어플리케이션_커넥터_상세2.png)


![](../_assets/그림_2.9_어플리케이션_커넥터_상세3.png)

Figure 2.9 Details of the Application Connectors# 2.9. Restricting the Work Envelope

When installing the robot, you can restrict a specific work envelope within the entire work envelope. 

Restricting the work envelope will be useful in the following environments.

-	When there is a collision with a peripheral device
-	When the length of the application cables or hose is limited

The three methods to use to limit the work envelope of the robot are as follows.

-	Software limit (applied to all axes)
-	Limit switch (axes 1–3: optional)
-	Stopper (axis 1)
# 2.9.2. Limit Switch (Option)

# 2.9.2.1. Application of the 1-Axis Limit Switch (Optional)


The 1-axis limit switch is optional, and when applying a limit switch, attach the dog pin to the stopper block by fastening the bolt according to the criteria shown below, by referring to Figure 2.14.

-	Bolt: M5X25L HEX SOCKET BOLT, 1EA
-	Tightening torque: 83 kgf.cm (8.14 N.m)

The 1-axis work envelope can be set by adjusting the position of the stopper block. Please refer to the examples in Table 2 3and Figure 2.13.

Depending on the starting position where the limit switch is pressed by the dog, there may be an error of approximately 0.63˚ in the work envelope.




![](../../../_assets/그림_2.14_1축_리미트_스위치_접촉오차범위.png)

Figure 2.14 1-Axis Limit Switch Contact Error Range
# 2.9.2.2. Application of the 2-Axis Limit Switch (Optional)


The 2-axis limit switch is optional, and when applying a limit switch, attach the dog pin to the limit switch plate by fastening the bolt according to the criteria shown below, by referring to Figure 2.15.


-	Limit switch plate fixing bolt: M5X10L HEX SOCKET BOLT, 2EA
-	Dog pin fixing bolt: M5X10L HEX SOCKET BOLT, 2EA
-	Tightening torque: 83 kgf.cm (8.14 N.m)




![](../../../_assets/그림_2.15_2축_리미트스위치플레이트_및_도그핀설치.png)

Figure 2.15 Installation of the 2-Axis Limit Switch Plate and Dog Pins



The 2-axis work envelope can be basically set by adjusting the position of the two dog pins. Dog pins can be installed at the intervals of 10˚, and when the position of the fixing hole of the plate is changed, the work envelope can be limited at the intervals of 5˚. For the work envelope for each case, refer to Table 2 5, Table 2 6and Figure2.16 – Figure 2.18.


![](../../../_assets/그림_2.16_2축_리미트스위치플레이트_고정위치.png)

Figure 2.16 2-Axis Limit Switch Plate Fixing Position

![](../../../_assets/그림_2.17_2축_동작범위_예시_CASE1.png)


Table 2-5 Cases of the 2-Axis Limit Switch Plate Installation
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-3h1q{background-color:#f8f8be;border-color:inherit;color:#000000;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-3h1q">CASE</th>
    <th class="tg-3h1q">1(basic)</th>
    <th class="tg-3h1q">2</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-3h1q">POSITION SET</td>
    <td class="tg-3h1q">SET(1)</td>
    <td class="tg-3h1q">SET(2)</td>
  </tr>
 <tr>
    <td class="tg-3h1q">Max. work envelope</td>
    <td class="tg-9wq8">7.5˚~157.5˚</td>
    <td class="tg-9wq8">12.5˚~157.5˚</td>
  </tr>
</tbody>
</table>

    
<br>

Table 2-6 Work Envelope for Each Case of the 2-Axis Limit Switch Plate Installation
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-gm1x{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-gm1x" colspan="8">CASE 1(basic)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-gm1x">Operation range</td>
    <td class="tg-nrix">157.5˚</td>
    <td class="tg-nrix">147.5˚</td>
    <td class="tg-nrix">137.5˚</td>
    <td class="tg-nrix">…</td>
    <td class="tg-nrix">27.5˚</td>
    <td class="tg-nrix">17.5˚</td>
    <td class="tg-nrix">7.5</td>
  </tr>
  <tr>
    <td class="tg-gm1x" colspan="8">CASE 2</td>
  </tr>
  <tr>
    <td class="tg-gm1x">Operation range</td>
    <td class="tg-nrix">157.5˚</td>
    <td class="tg-nrix">152.5˚</td>
    <td class="tg-nrix">142.5˚</td>
    <td class="tg-nrix">132.5˚</td>
    <td class="tg-nrix">…</td>
    <td class="tg-nrix">22.5˚</td>
    <td class="tg-nrix">12.5˚</td>
  </tr>
</tbody>
</table>

<br>

![](../../../_assets/그림_2.17_2축_동작범위_예시_CASE1.png)

Figure 2.17 Example of the 2-Axis Work Envelope (case 1)

![](../../../_assets/그림_2.18_2축_동작범위_예시_CASE2.png)

Figure 2.18 Example of the 2-Axis Work Envelope (case 2)


Depending on the starting position where the limit switch is pressed by the dog, there may be an error of approximately 1.07˚ in the work envelope.

![](../../../_assets/그림_2.19_2축_리미트센서_접촉오차범위.png)

Figure 2.19 2-Axis Limit Sensor Contact Error Range# 2.9.2.3. Application of the 3-Axis Limit Switch (Optional)

The 3-axis limit switch is optional, and when applying a limit switch, attach the dog pin to the limit switch plate by fastening the bolt according to the criteria shown below, by referring to Figure 2.20.

-	Limit sensor plate fixing bolt: M5X10L HEX SOCKET BOLT, 4EA
-	Dog pin fixing bolt: M5X10L HEX SOCKET BOLT, 2EA
-	Tightening torque: 83 kgf.cm (8.14 N.m)




![](../../../_assets/그림_2.20_3축_리미트스위치플레이트_및_도그핀설치방법.png)

Figure 2.20 Method for Installation of the 3-Axis Limit Switch Plate and Dog Pins


Axis-3’s work envelope can be basically set by adjusting the position of the two dog pins. Dog pins can be installed at the intervals of 10˚, and when the position of the fixing hole of the plate is changed, the work envelope can be limited at the intervals of 5˚. For the work envelope for each case, refer to Table 2 7, Table 2 8, Figure 2.21, and Figure 2.23.


![](../../../_assets/그림_2.21_2축_리미트스위치플레이트_고정위치.png)

Figure 2.21 2-Axis Limit Switch Plate Fixing Position

Table 2-7 Cases of the 3-Axis Limit Switch Plate Installation
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-9wq8{border-color:inherit;text-align:center;vertical-align:middle}
.tg .tg-3h1q{background-color:#f8f8be;border-color:inherit;color:#000000;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-3h1q">CASE</th>
    <th class="tg-3h1q">1(basic)</th>
    <th class="tg-3h1q">2</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-3h1q">POSITION SET</td>
    <td class="tg-3h1q">SET(1)</td>
    <td class="tg-3h1q">SET(2)</td>
  </tr>
 <tr>
    <td class="tg-3h1q">Max. work envelope</td>
    <td class="tg-9wq8">-74.5˚~190.5˚</td>
    <td class="tg-9wq8">-79.5˚~185.5˚</td>
  </tr>
</tbody>
</table>

    
<br>

Table 2-8 Work Envelope for Each Case of the 3-Axis Limit Switch Plate Installation
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-gm1x{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-gm1x" colspan="10">CASE 1(기본)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-gm1x">Operation range</td>
    <td class="tg-nrix">190.5˚</td>
    <td class="tg-nrix">180.5˚</td>
    <td class="tg-nrix">…</td>
    <td class="tg-nrix">60.5˚</td>
    <td class="tg-nrix">44.5˚</td>
    <td class="tg-nrix">35.5˚</td>
    <td class="tg-nrix">…</td>
    <td class="tg-nrix">-64.5˚</td>
    <td class="tg-nrix">-74.5˚</td>
    </tr>
  <tr>
    <td class="tg-gm1x" colspan="10">CASE 2</td>
  </tr>
  <tr>
    <td class="tg-gm1x">Operation range</td>
    <td class="tg-nrix">185.5˚</td>
    <td class="tg-nrix">175.5˚</td>
    <td class="tg-nrix">…</td>
    <td class="tg-nrix">65.5˚</td>
    <td class="tg-nrix">40.5˚</td>
    <td class="tg-nrix">30.5˚</td>
    <td class="tg-nrix">…</td>
    <td class="tg-nrix">-69.5˚</td>
    <td class="tg-nrix">-79.5˚</td>
    </tr>
</tbody>
</table>

<br>

![](../../../_assets/그림_2.22_3축_동작범위_예시_CASE1.png)

![](../../../_assets/그림_2.22_3축_동작범위_예시_CASE2.png)

Figure 2.22 Examples of the 3-Axis Work Envelope



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
    <td class="tg-b001"><img src="../../../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">In the case of axis 3, never install a dog pin at the position marked X as shown in Figure 2.22.<br>
(actuation of the limit switch will be invalidated)
</td>
  </tr>
</thead>
</table>

<br>

Depending on the starting position where the limit switch is pressed by the dog, there may be an error of approximately 2.5˚ in the work envelope.

![](../../../_assets/그림_2.23_3축_리미트센서_접촉오차범위.png)

Figure 2.23 3-Axis Limit Sensor Contact Range# 2.10. Dustproof and Waterproof Specifications, and Motor Covers (Optional)


In the case of US220, its IP rating is classified as follows depending on the cover option. A cover can be added to suit the IP rating according to the user’s request


![](../_assets/그림_2.24_방진방수사양.png)

Figure 2.24 Dustproof and Waterproof Specifications


Table 2-9 Definitions of IP Ratings

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" rowspan="4">Dustproof</th>
    <th class="tg-yhpm">IP3●</th>
    <th class="tg-nrix">Solid objects such as tools and wires exceeding 2.5 mm in diameter or thickness do not intrude.</th>
  </tr>
  <tr>
    <th class="tg-yhpm">IP4●</th>
    <th class="tg-nrix">Solid objects such as tools and wires exceeding 1.0 mm in diameter or thickness do not intrude.</th>
  </tr>
  <tr>
    <th class="tg-yhpm">IP5●</th>
    <th class="tg-nrix">Dust does not intrude the inside beyond the level that affects operation.</th>
  </tr>
  <tr>
    <th class="tg-yhpm">IP6●</th>
    <th class="tg-nrix">Dust does not intrude the inside.</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-yhpm" rowspan="4">Waterproof</td>
    <td class="tg-yhpm">IP●4</td>
    <td class="tg-nrix">Even when water droplets fly from any direction, it has no harmful effects.</td>
  </tr>
  <tr>
    <td class="tg-yhpm">IP●6</td>
    <td class="tg-nrix">Even when water droplets fly from any direction, it has no harmful effects.
Even when water is sprayed directly from any direction, it has no harmful effects.
</td>
  </tr>
  <tr>
    <td class="tg-yhpm">IP●6</td>
    <td class="tg-nrix">Even when water is sprayed directly from any direction, no water will intrude the inside.</td>
  </tr>
  <tr>
    <td class="tg-yhpm">IP●7</td>
    <td class="tg-nrix">Even when a part is submerged in water under certain conditions, no water intrudes the inside.</td>
  </tr>
</tbody>
</table># 3. Precautions for Handling



# 3.1. Names of Individual Parts

The following picture shows the names of manipulator's individual parts.


![](../_assets/그림_3.1_본체_각_부위_명칭.png)

Figure 3.1 The Names of the Manipulator’s Individual Parts


[Note] Limit switches for axes 1, 2, and 3 are optional.

# 3.2. How to Transport

The robot can be transported using a crane or forklift. When moving the robot, make sure to pose the robot as shown in the table below and then transport it using eye bolts and designated transport equipment. The robot’s posture for transportation is as follows.


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-baqh">1(S)- Axis</th>
    <th class="tg-baqh">0</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">2(H)- Axis</td>
    <td class="tg-baqh">150</td>
  </tr>
  <tr>
    <td class="tg-baqh">3(V)- Axis</td>
    <td class="tg-baqh">-60</td>
  </tr>
  <tr>
    <td class="tg-baqh">4(R2)- Axis</td>
    <td class="tg-baqh">0</td>
  </tr>
  <tr>
    <td class="tg-baqh">5(B)- Axis</td>
    <td class="tg-baqh">-90</td>
  </tr>
  <tr>
    <td class="tg-baqh">6(R1)- Axis</td>
    <td class="tg-baqh">0</td>
  </tr>
</tbody>
</table>



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
    <td class="tg-cly1">-	When moving or lowering the robot, move it slowly and be very careful.<br>
-	When unloading the robot onto the floor, be careful not to cause a strong collision between the bottom installation surface of the robot and the floor’s surface.<br>
-	Never transport the robot with anything other than the specified transport equipment and methods.<br>
-	When transporting the robot, be very careful not to allow its motors, connectors, cables, etc., to be damaged by the crane wire or forklift.<br>
-	When transporting the robot, keep its horizontal level.<br>
-	When transporting the robot using a forklift, check the transport equipment fixing bolts, and tighten any loose bolts.<br>
-	When you disassemble or assemble the transport equipment (forklift brackets), the manipulator may rotate. Fix the robot with bolts using the robot fixing bolt holes to prevent the robot from falling over.
</td>
  </tr>
</thead>
</table>


![](../../_assets/그림_3.2_로봇_고정_볼트_구멍.png)

Figure 3.2 Robot Fixing Bolt Hole# 3.2.1. Using a Crane


The manipulator can be transported using a crane. You can attach an eye bolt or lifting bracket to the robot’s base body and fasten a wire rope to it.

For safety, please observe the following procedures.

*	Never walk under the manipulator.
*	Pose the robot as shown in Figure 3.3.
*	Install four M20 eyebolts or a lifting bracket to the base body.
*	Connect the wire rope (four units) to the eye bolt (four units) or lifting bracket.
*	Minimum crane capacity: 2.5 t. Minimum rope capacity: 1 t/piece
*	Attach a protective hose (50 cm) to prevent the manipulator from being damaged.
*	Follow the safety regulations when lifting the robot.
*	Fix the ropes while being careful not to damage the motors, connectors, and cables of the robot.
*	Manipulator weight: 938 kg


![](../../_assets/그림_3.3_운반방법_크레인이용.png)

Figure 3.3 How to Transport: Using a Crane (When Using Eyebolts)

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
    <td class="tg-cly1">When using eye bolts, be careful not to get the motors, internal wirings, and cables crushed.</td>
  </tr>
</thead>
</table>


![](../../_assets/그림_3.4_운반방법_크레인이용.png)

Figure 3.4 How to Transport: Using a Crane (When Using a Lifting Bracket)

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
    <td class="tg-cly1">The following instructions for lifting the robot are valid for a factory-shipped robot. When an end effector is installed, the above transportation posture cannot be used because of the change of the location of the center of gravity.</td>
  </tr>
</thead>
</table>
# 3.2.2. Using a Forklift

A forklift can be used to transport the manipulator.

For safety, please observe the following procedures.

*	Set the robot into the basic posture by referring to the figure.
*	Check whether the fixing bolts of the transport equipment (forklift bracket) are loose, and tighten them to make sure they are not loose.
*	Be careful to prevent collision between the forklift’s fork and the transport equipment.
*	Before transporting the robot using a forklift, make sure that it keeps its horizontal level.
*	Transport the robot at a slow speed. 
*	Follow safety regulations.


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
    <td class="tg-cly1">-	Do not lean against the robot while transporting it.<br>
-	Make sure the robot does not collide with the floor while you are loading and unloading it.<br>
-	Observe the relevant safety rules while working with the forklift.<br>
-	When transporting a forklift using a skid, check whether the bolts between the robot and the skid are loose, and tighten them to make sure they are not loose.<br>
-	To prevent a collision between the transport equipment and the robot, make sure to disassemble the transport equipment before operating the robot.
</td>
  </tr>
</thead>
</table>


![](../../_assets/그림_3.5_운반방법_지게차이용.png)

Figure 3.5 How to Transport: Use a Forklift (Base Body Type)

![](../../_assets/그림_3.6_운반방법_지게차이용.png)

Figure 3.6 How to Transport: Use a Forklift (Lower Frame Type)


# 3.3. Storage of the robot

To store the robot without installing it, pose it as shown in [Figure 3.7].

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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">If not placed as instructed, the robot may fall over. For long-term storage, take measures to ensure that it does not fall over.
</td>
  </tr>
</thead>
</table>



![](../_assets/그림_3.7_로봇보관자세.png)

Figure 3.7 Posture for Storing the Robot

# 3.4. Installation Methods

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
    <td class="tg-cly1">Must read the safety regulations or related instructions carefully before unpacking and installing the robot.<br>
If you use the robot in an environment other than that in the specified use conditions, please contact the service center.

</td>
  </tr>
</thead>
</table>


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">Installation must be performed by an installation expert, and the relevant regulations of the concerned country or region should be observed.<br>
When unpacking the robot, check whether it was damaged during transport or while being unpacked. In addition, because the installation methods for the manipulator are very important in maintaining the functions of the robot, you should strictly observe the following.
</td>
  </tr>
</thead>
</table>

# 3.4.1. Working Conditions

(1)	Ambient temperature should range from 0℃ to 45℃. 

(2)	Ambient humidity should range from 20% RH to 85% RH, without dew condensation.

(3)	Less dust, oil, or moisture

(4)	No flammable and corrosive liquid or gas

(5)	No large impact and vibration

(6)	There should be no large sources of electrical noise nearby.

(7)	If the robot is not to be installed right away, it should be stored in a dry place with an ambient temperature of -15℃–40℃.


# 3.4.2. Installation of the Manipulator

When considering the rigidity of the foundation floor to be installed, please refer to the maximum load of the robot base in Table 3 1.

Table 3-1 Maximum Loads of the Robot Base

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-69va{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-69va">Vertical reaction moment [M<sub>V</sub>]</th>
    <th class="tg-69va">Vertical reaction [F<sub>V</sub>]</th>
    <th class="tg-69va">Horizontal reaction moment [M<sub>H</sub>]</th>
    <th class="tg-69va">Horizontal reaction [F<sub>H</sub>]</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">31,000 N·m</td>
    <td class="tg-baqh">21,000 N</td>
    <td class="tg-baqh">18,000 N·m</td>
    <td class="tg-baqh">7,900 N</td>
  </tr>
</tbody>
</table>

<br>

![](../../_assets/그림_3.8_로봇_베이스에_작용하는_힘과_모멘트.png  )

Figure 3.8 Forces and Moments Acting on the Robot Base

Place the manipulator on the mounting plate and firmly fasten it with eight M20 bolts.

*	Bolt: M20*70 (strength grade: 12.9) 
*	Plain washer: T = 4 mm or more, inner diameter (ID) = 24, hardness = HrC 35 or more
*	Tightening torque: 5700 kgf·cm (559 N·m)




# 3.4.3. Accuracy of the Installation Surface

The flatness of the robot installation surface should be 0.5 mm or less.
If the flatness exceeds the value, the robot may not perform well because of deformation and damage to the base body.



![](../../_assets/그림_3.9_로봇_설치면_정도.png  )

Figure 3.9 Accuracy of the Robot Installation Surface
# 3.4.4. Dimensions of the Installation Surface

When attaching the manipulator, fix the bottom surface of the swivel base (base body).

Please refer to the pictures below for the dimensions.


![](../../_assets/그림_3.10_로봇_설치면_치수.png  )

Figure 3.10 Dimensions of the Robot Installation Surface# 3.4.5. Connecting the Robot Cables

![](../../_assets/그림_3.11_로봇_케이블_연결.png  )

Figure 3.11 Connecting the Robot Cables



The robot is connected to the controller through the power and signal cables. Connect these cables to the connectors on the back of the robot base body. Also connect the grounding wire.
For connection of the pneumatic and optional cables, refer to “2.8. Wiring and Piping Diagrams for Applications.”


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
    <td class="tg-cly1">Make sure to turn off the power of the controller when connecting the cables.</td>
  </tr>
</thead>
</table>

# 3.4.6. Emergency Stop Time and Distance 


The following items are the response time and distance measured for an emergency stop during the max speed operation of each axis (1 axis [S axis], 2 axis [H axis], and 3 axis [V axis]) with the standard load.


*	US220

    Maximum time	: 0.615 seconds

    Maximum moving distance: 111 cm (43.70 Inch)

# 3.4.7. Connection of the End Effector

For the tool to be attached to the tip of the robot’s wrist axis, the attachment method and form of the tool should be restricted to prevent abrasion from the contact with the 6-axis part that performs relative movement. If the restriction is not appropriate, the seal of the reducer may be damaged because of contact, resulting in oil leakage.


![](../../_assets/그림_3.12_로봇_끝단_취부형태.png  )

Figure 3.12 Form of Attachment to the Tip of the Robot# 3.5. Allowable Load of Wrist Axis



# 3.5.1. Permitted load torque estimation

The load, which will be applied to the mechanical interface of robot's wrist axis, is restricted by allowable weight, allowable load torque and allowable moment of inertia. The direction of coordinate system used to calculate the load torque and inertia moment is the same with the direction of robot base coordinate system. Axis R2 is reviewed in the same manner with the axis B.


*	Step 1

    Calculate the location of the weight center from the B axis rotation center (L<sub>X</sub>, L<sub>Y</sub>, L<sub>Z</sub>.)

    L<sub>x</sub>: Location of weight center in X axis

    L<sub>y</sub>: Location of weight center in Y axis

    L<sub>z</sub>: Location of weight center in Z axis



*	Step 2

    Distance calculation from the axis B and R1 to the center of gravity

    ![](../../_assets/3.6.1_수식1.png)

    L<sub>B</sub> : Length from B axis rotation center to weight center

    L<sub>R1</sub> : Length from R1 axis rotation center to weight center



*	Step 3

    Calculate the load torque from the calculated distance.

    ![](../../_assets/3.6.1_수식2.png)


*	Step 4

    Check if the load torque calculated in the step 3 is the same with or smaller than the limit value, on the basis of allowed load torque table.

 
* Note : If the load mass is similar to the mass on the torque curve below, the torque can be alternatively validated by checking if the distance calculated in the step 2 is distributed in the torque curve, instead of the step 3 and 4. If it is in the torque curve, the calculated load torque is smaller than the allowed load torque but if it is out of the torque curve, the calculated load torque is bigger than the allowed load torque


![](../../_assets/그림_3.13_손목축_토크_선도.png)

Figure 3.13 Wrist Axis Torque Curve
<br></br>

![](../../_assets/작은주의표시.png) <b>Allowable load torque</b>

Table 3-3 Allowable load torque
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
    <th class="tg-zegx" colspan="3">Allowable load torque</th>
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
    <td class="tg-nrix" colspan="2">Within 1,422 N·m (145 kgf·m)</td>
    <td class="tg-nrix">Within 770 N·m (79 kgf·m)</td>
  </tr>
</tbody>
</table>
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
# 4. Inspection

This chapter describes regular inspection, disassembly, and adjustment necessary to maintain the performance of the robot for a long time.# 4.1. Inspection Plan

Inspection is absolutely necessary to maintain high performance when operating the robot for a long period of time.
Inspection consists of daily inspections and periodic inspections. The basic inspection cycles are indicated in [Table 4-1]. The person in charge of inspection must conduct inspections according to the inspection cycles.
Overhauling should be performed every 35,000 operation hours. 

The inspection cycle has been reviewed for the spot welding, so when the inspection cycle is required for high-precision work, such as handling work, it is recommended that you perform the inspections approximately at half of the cycles in [Table 4-1]. If it is difficult to understand the inspection and adjustment methods, contact our Aftersales Service Center (Customer Support Department.)



<br>
Table 4-1 Inspection plan 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-1wig{font-weight:bold;text-align:left;vertical-align:top}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-0lax{text-align:left;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm">Daily inspection</th>
    <th class="tg-1wig">Daily</th>
    <th class="tg-0lax">Manipulator, motors, and reducers</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-yhpm" rowspan="4">Periodic inspection</td>
    <td class="tg-1wig">3 months</td>
    <td class="tg-0lax">Manipulator, wirings, bolts, and reducers</td>
  </tr>
  <tr>
    <td class="tg-1wig">6 months</td>
    <td class="tg-0lax">Gas springs, gas spring bearing</td>
  </tr>
  <tr>
    <td class="tg-1wig">1 year</td>
    <td class="tg-0lax">Limit switches / dogs, brakes</td>
  </tr>
  <tr>
    <td class="tg-1wig">2 years</td>
    <td class="tg-0lax">Batteries, motor cooling fans</td>
  </tr>
</tbody>
</table># 4.2. 점검항목과 주기

Table 4-2 Daily Inspection Items
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm">Inspection object</th>
    <th class="tg-yhpm">Inspection item</th>
    <th class="tg-yhpm">Criteria</th>
    <th class="tg-yhpm">Inspection techniques, and handling</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Manipulator</td>
    <td class="tg-nrix">Robot’s appearance</td>
    <td class="tg-nrix">Check for oil leakage and impurities with the naked eye.</td>
    <td class="tg-nrix">Remove oil leakage and impurities.</td>
  </tr>
  <tr>
    <td class="tg-nrix">Reducers</td>
    <td class="tg-nrix">Noise/vibration</td>
    <td class="tg-nrix">When abnormal noise/vibration occurs</td>
    <td class="tg-nrix">Refer to “6.3.1. Reducers.”</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2">Motors</td>
    <td class="tg-nrix">Heating</td>
    <td class="tg-nrix">Motor encoder’s temperature is 80℃ or above</td>
    <td class="tg-nrix" rowspan="2">Relax the robot driving conditions
Refer to “6.3.3. Motors.”
</td>
  </tr>
  <tr>
    <td class="tg-nrix">Noise/vibration</td>
    <td class="tg-nrix">When abnormal noise/vibration occurs</td>
  </tr>
  <tr>
    <td class="tg-nrix">Teach pendant</td>
    <td class="tg-nrix">Screen</td>
    <td class="tg-nrix">When a warning is generated on the teach pendant’s screen</td>
    <td class="tg-nrix">Refer to “Hi6 Controller Operation Manual.”</td>
  </tr>
</tbody>
</table>

<br>
Table 4-3 Items and Intervals of Periodic Inspections
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-q24q{background-color:#c0c0c0;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm" colspan="4">Inspection interval</th>
    <th class="tg-yhpm" rowspan="2">Inspection object</th>
    <th class="tg-yhpm" rowspan="2">Inspection item</th>
    <th class="tg-yhpm" rowspan="2">Criteria</th>
    <th class="tg-yhpm" rowspan="2">Inspection techniques, and handling</th>
  </tr>
  <tr>
    <th class="tg-yhpm">3 months</th>
    <th class="tg-yhpm">6 months</th>
    <th class="tg-yhpm">1 year</th>
    <th class="tg-yhpm">2 years</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-q24q" colspan="8">Common for the manipulator and each axis</td>
  </tr>
  <tr>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Manipulator</td>
    <td class="tg-nrix">External damage, peeling off of paint</td>
    <td class="tg-nrix">Visual check</td>
    <td class="tg-nrix">If external damage has occurred or the paint peeled off because of interference, eliminate the cause of the interference.</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="3">O</td>
    <td class="tg-nrix" rowspan="3"></td>
    <td class="tg-nrix" rowspan="3"></td>
    <td class="tg-nrix" rowspan="3"></td>
    <td class="tg-nrix" rowspan="3">Cables (wirings)</td>
    <td class="tg-nrix">Damage on cables</td>
    <td class="tg-nrix" rowspan="3">Visual check</td>
    <td class="tg-nrix">Replace the cable</td>
  </tr>
  <tr>
    <td class="tg-nrix">Paint-marking of the cable fixing bracket fastening bolt
</td>
    <td class="tg-nrix">Fasten again with an appropriate torque</td>
  </tr>
  <tr>
    <td class="tg-nrix">Damage on the cable cover</td>
    <td class="tg-nrix">Replace the cable cover</td>
  </tr>
  <tr>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Main external bolts (including end effectors)</td>
    <td class="tg-nrix">Pain-marking of bolts</td>
    <td class="tg-nrix">Visual check</td>
    <td class="tg-nrix">Refer to “4.3. Inspection of Main External Bolts.”</td>
  </tr>
  <tr>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Limit switches / dogs</td>
    <td class="tg-nrix">Check the on-off function of the limit switch</td>
    <td class="tg-nrix">Check whether the emergency lamp is turned on when the limit switch is turned on.</td>
    <td class="tg-nrix">Replace the limit switch / Inspect the internal wirings</td>
  </tr>
  <tr>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Brake</td>
    <td class="tg-nrix">Check whether the brake release switch works in the ON and OFF states.</td>
    <td class="tg-nrix">The arm or end effector keeps its posture while the brake release switch is in the OFF state</td>
    <td class="tg-nrix">Note) When the brake release switch is in the ON state, the arm or operating axis falls, so turn it off within 1 s.</td>
  </tr>
  <tr>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">Battery</td>
    <td class="tg-nrix">(periodic replacement)</td>
    <td class="tg-nrix">Replace it every two years regardless of the operation hours</td>
    <td class="tg-nrix">Refer to “5.2. Replacement of the Battery.”</td>
  </tr>
  <tr>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">Motor cooling fan</td>
    <td class="tg-nrix">Operation of the cooling fan</td>
    <td class="tg-nrix">Whether the cooling fan works</td>
    <td class="tg-nrix">When it does work, replace the cooling fan /  check the internal wirings</td>
  </tr>
  <tr>
    <td class="tg-q24q" colspan="8">1, 2, and 3 axes</td>
  </tr>
  <tr>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix" rowspan="2">Gas spring</td>
    <td class="tg-nrix">Pressure</td>
    <td class="tg-nrix">Appropriate pressure of the gas spring 90–120 bar</td>
    <td class="tg-nrix">Refer to “9.1.1. Checking of the Pressure of the Gas Spring.”</td>
  </tr>
  <tr>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">Bearing part</td>
    <td class="tg-nrix">Generation of impurities, noise / vibration</td>
    <td class="tg-nrix">Maintain an appropriate amount of grease at the bearing part / Replace the battery Refer to “6.3.5. Gas Springs.”</td>
  </tr>
  <tr>
    <td class="tg-nrix" rowspan="2"></td>
    <td class="tg-nrix" rowspan="2">O</td>
    <td class="tg-nrix" rowspan="2"></td>
    <td class="tg-nrix" rowspan="2"></td>
    <td class="tg-nrix" rowspan="2">Stopper</td>
    <td class="tg-nrix" rowspan="2">Variable stopper (1 axis), fixed stopper (2 and 3 axes)</td>
    <td class="tg-nrix">Loosening of the fixing bolt</td>
    <td class="tg-nrix">Fasten again with an appropriate torque</td>
  </tr>
  <tr>
    <td class="tg-nrix">Traces of a stopper being collided with, and its deformation</td>
    <td class="tg-nrix">Replace the stopper</td>
  </tr>
  <tr>
    <td class="tg-q24q" colspan="8">4, 5, and 6 axes</td>
  </tr>
  <tr>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix"></td>
    <td class="tg-nrix">4, 5, and 6 axes</td>
    <td class="tg-nrix">Whether there is any clearance felt when rotated in the forward/reverse direction.</td>
    <td class="tg-nrix">No clearance should be felt with the hands.</td>
    <td class="tg-nrix">Replace the wrist assembly.</td>
  </tr>
</tbody>
</table>
<br>

*	If the robot is utilized in adverse conditions (such as spot welding, grinding, etc.), shorten the inspection cycle to ensure the proper performance of the robot system.


*	Check for any abnormal sounds in auto mode and teaching mode to check the power transmission systems (motors, reducers, etc.) for abnormalities.

*	Inspect the gas spring periodically to maintain the proper working pressure, and inject gas when the pressure drops. 

*	Replace the gas spring after using it for a certain period. Replace the gas spring every 20,000 h or when the proper working pressure (90 bar–120 bar) cannot be maintained even after gas is injected.

*	If the load estimation has been performed correctly, the pressure of the gas spring can be checked from the teach pendant. Therefore, refer to the gas spring pressure test function in the Controller Function Manual.
There are two pressure test methods: “Command-based gas spring pressure test” and “Gas spring pressure test at stop position.” The “Command-based gas spring pressure test” method, which has higher accuracy, is recommended.

*	If the teach pendant generates an error or warning related to the gas spring pressure drop, you must check the pressure of the gas spring.


# 4.3. Inspection of Main External Bolts


The recommended bolt fastening torques are shown in the figure below and the bolts of 12.9 T (strength grade) should be used.

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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">Fasten the bolts using appropriate torques with a calibrated torque wrench, and mark them with paint.</td>
  </tr>
</thead>
</table>

<br>

Table 4-4 Inspection Parts of the Main Bolts 
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-jaud{background-color:#ccf1bc;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
.tg .tg-69va{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-69va">No.</th>
    <th class="tg-69va">Inspection parts</th>
    <th class="tg-69va">No.</th>
    <th class="tg-69va">Inspection parts</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-jaud">1</td>
    <td class="tg-baqh">2-axis (H-axis) reducer attachment bolt</td>
    <td class="tg-jaud">7</td>
    <td class="tg-baqh">Arm pipe attachment bolt</td>
  </tr>
  <tr>
    <td class="tg-jaud">2</td>
    <td class="tg-baqh">2-axis (H-axis) motor attachment bolt</td>
    <td class="tg-jaud">8</td>
    <td class="tg-baqh">4-axis (R2-axis) reducer attachment bolt</td>
  </tr>
  <tr>
    <td class="tg-jaud">3</td>
    <td class="tg-baqh">3-axis (V-axis) reducer attachment bolt</td>
    <td class="tg-jaud">9</td>
    <td class="tg-baqh">Wrist part assembly attachment bolt</td>
  </tr>
  <tr>
    <td class="tg-jaud">4</td>
    <td class="tg-baqh">3-axis (V-axis) motor attachment bolt</td>
    <td class="tg-jaud">10</td>
    <td class="tg-baqh">5-axis (B-axis) reducer attachment bolt</td>
  </tr>
  <tr>
    <td class="tg-jaud">5</td>
    <td class="tg-baqh">Gas lower joint attachment bolt</td>
    <td class="tg-jaud">11</td>
    <td class="tg-baqh">6-axis (R1-axis) reducer attachment bolt</td>
  </tr>
  <tr>
    <td class="tg-jaud">6</td>
    <td class="tg-baqh">Motor attachment bolts of the 4 axis (R2 axis), 5 axis (B axis), and 6 axis (R1 axis)</td>
    <td class="tg-jaud">12</td>
    <td class="tg-baqh">End effector attachment bolt</td>
  </tr>
</tbody>
</table>



![](../_assets/그림_4.1_주요_볼트_점검_부위.png)

Figure 4.1 Inspection Parts of the Main Bolts
# 5. 보수
# 5.1. Grease Injection after Grease Replacement and Reducer Replacement

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
    <td class="tg-cly1">If grease is not injected correctly, the internal pressure may suddenly increase, possibly causing damage to the seal, grease leakage, and abnormal operation. Abnormal sounds may occur when replacing the current grease with new grease of a different specification, so make sure that different types of grease are not mixed. When injecting grease, the user must observe the following.</td>
  </tr>
</thead>
</table>


(1)	Wear safety glasses before injecting grease and conducting inspections.

(2)	Remove the grease inlet and outlet plugs before injecting grease.

(3)	When the plug is loosened, grease and the plug could be discharged abruptly. Block the outlet with a thick cloth to prevent injuries caused by discharged grease or plugs, and keep distance for safety. (Do not look into the grease outlet.)

(4)	If possible, do not use a compressed air pump powered by factory-supplied air, and limit the grease injection pressure to 1.5bar (1.5 kgf/cm2, 0.15 MPa) or less. 

(5)	Use only the specified grease. Otherwise, the reducer may be damaged or other problems may occur.

(6)	After injecting the grease, check for any leakage from the grease outlet and remove residual pressure according to the method suggested for each axis, and then connect the plug.

(7)	To prevent possible accidents, completely remove any excess grease leaked on the manipulator or floor.

(8)	If the robot is used at an ambient temperature of 35℃ or higher, the grease replenishment and replacement cycles should be shortened by half.

(9)	When replacing grease, replace the specified amount. Inject new grease until it is equal in amount to the grease that has been discharged.

(10) Abnormal sounds may be generated from the reducer part during operation after the replenishment or replacement of grease, at low temperature, at low speed, or after long-term nonoperation. In that case, you need to operate the robot while checking the state of the abnormal sounds for 1 to 2 days. Abnormal sounds caused by grease will disappear in normal conditions.

(11) If grease with a different specification is injected into a reducer part greased already, abnormal sounds may occur from the reducer part. Therefore, be careful not to mix different types of grease. Please replace GADUS grease with GADUS grease and RV LB00 grease with RV LB00 grease.

(12) Abnormal sounds may occur even if the old grease is replaced with the new grease of the same designated specification as the old grease.

(13) Replacing the grease does not completely remove the old grease. A significant amount of old grease will remain.



* Grease Replacement Cycle

   -	1-axis (S-axis) reducer, arm frame gearbox  : Every 24,000 h
   -	Other reducers  : Every 12,000 h
   -	Gas spring bearing  : Every 6 months (every 3 months if in hard conditions)


 <br>


* Causes and Measures for Abnormal Sounds with Grease

If there is still noise in the reducer part even after using the specified grease, operate the robot while checking the state closely for 1–2 days. Generally, the noise will go away.

-	You can see that the noise disappears even when you operate the axis at high speeds for more than 5 to 10 min.
-	When the old grease is discharged as much as possible (about 90% or more) and replaced with new grease, abnormal grease sounds can be minimized. (When the grease is discharged while the axis is rotating at a low speed, the grease discharge time can be shortened.)

The noise may be caused by the following.
-	Operation after greasing or replacing the reducer
-	Operation after long-term disuse
-	Operation at a low speed
-	Operation at a low temperature
-	Use of unspecified grease
-	Mixing of grease of different specifications

# 5.1.1. Grease Injection Amount for Each Axis


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-gm1x{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-gm1x" rowspan="3">Axis</th>
    <th class="tg-gm1x" colspan="2">Amount of injection when replacing a reducer (A)</th>
    <th class="tg-gm1x" colspan="2">Amount of injection when replacing the grease (A)*80% or more</th>
  </tr>
  <tr>
    <th class="tg-gm1x" colspan="2">RV GREASE LB00</th>
    <th class="tg-gm1x" colspan="2">RV GREASE LB00</th>
  </tr>
  <tr>
    <th class="tg-gm1x">cc</th>
    <th class="tg-gm1x">g</th>
    <th class="tg-gm1x">cc</th>
    <th class="tg-gm1x">g</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">1(S)</td>
    <td class="tg-nrix">4,222</td>
    <td class="tg-nrix">3,800</td>
    <td class="tg-nrix">3,378</td>
    <td class="tg-nrix">3,040</td>
  </tr>
  <tr>
    <td class="tg-nrix">2(H)</td>
    <td class="tg-nrix">2,889</td>
    <td class="tg-nrix">2,600</td>
    <td class="tg-nrix">2,311</td>
    <td class="tg-nrix">2,080</td>
  </tr>
  <tr>
    <td class="tg-nrix">3(V)</td>
    <td class="tg-nrix">2,778</td>
    <td class="tg-nrix">2,500</td>
    <td class="tg-nrix">2,222</td>
    <td class="tg-nrix">2,000</td>
  </tr>
  <tr>
    <td class="tg-nrix">4(R2)</td>
    <td class="tg-nrix">1,056</td>
    <td class="tg-nrix">950</td>
    <td class="tg-nrix">845</td>
    <td class="tg-nrix">760</td>
  </tr>
  <tr>
    <td class="tg-nrix">5(B)</td>
    <td class="tg-nrix">1,478</td>
    <td class="tg-nrix">1,330</td>
    <td class="tg-nrix">1,182</td>
    <td class="tg-nrix">1,064</td>
  </tr>
  <tr>
    <td class="tg-nrix">6(R1)</td>
    <td class="tg-nrix">211</td>
    <td class="tg-nrix">190</td>
    <td class="tg-nrix">169</td>
    <td class="tg-nrix">152</td>
  </tr>
</tbody>
</table># 5.1.2. Grease Injection Amount for the Arm Frame Gear Box

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-gm1x{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-gm1x" rowspan="3">Classification</th>
    <th class="tg-gm1x" colspan="2">Amount of injection when replacing the grease</th>
    <th class="tg-gm1x" rowspan="3">Remarks</th>
  </tr>
  <tr>
    <th class="tg-gm1x" colspan="2">GADUS S2 V46 2</th>
  </tr>
  <tr>
    <th class="tg-gm1x">CC</th>
    <th class="tg-gm1x">g</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">GEAR BOX</td>
    <td class="tg-nrix">500</td>
    <td class="tg-nrix">450</td>
    <td class="tg-nrix">Inject a specified amount of grease as much as the amount of the discharged grease.</td>
  </tr>
</tbody>
</table># 5.1.3. Grease Injection Amount for the Gas Spring Bearing


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-gm1x{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-gm1x" rowspan="3">Classification</th>
    <th class="tg-gm1x" colspan="2">Amount of injection when replacing the grease</th>
    <th class="tg-gm1x" rowspan="3">Remarks</th>
  </tr>
  <tr>
    <th class="tg-gm1x" colspan="2">GADUS S3 V220C 2</th>
  </tr>
  <tr>
    <th class="tg-gm1x">CC</th>
    <th class="tg-gm1x">g</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Gas spring bearing</td>
    <td class="tg-nrix">15</td>
    <td class="tg-nrix">13.5</td>
    <td class="tg-nrix">Inject a specified amount of grease as much as the amount of the discharged grease.</td>
  </tr>
</tbody>
</table>
# 5.1.4. Plug Size for Each Axis

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-gm1x{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-gm1x">Axis</th>
    <th class="tg-gm1x">Inlet</th>
    <th class="tg-gm1x">Outlet</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">1(S)</td>
    <td class="tg-nrix" rowspan="5">G1/4</td>
    <td class="tg-nrix" rowspan="7">G1/4</td>
  </tr>
  <tr>
    <td class="tg-nrix">2(H)</td>
  </tr>
  <tr>
    <td class="tg-nrix">3(V)</td>
  </tr>
  <tr>
    <td class="tg-nrix">4(R2)</td>
  </tr>
  <tr>
    <td class="tg-nrix">5(B)</td>
  </tr>
  <tr>
    <td class="tg-nrix">6(R1)</td>
    <td class="tg-nrix">M5</td>
  </tr>
  <tr>
    <td class="tg-nrix">GEAR BOX</td>
    <td class="tg-nrix">G1/4</td>
  </tr>
</tbody>
</table># 5.1.5. Plug Tightening Torque

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-62g5{background-color:#f8f8be;color:#000000;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-62g5">Axis plug size</th>
    <th class="tg-62g5">Tightening torque</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">G1/4</td>
    <td class="tg-baqh">200 kgf·cm (19.61 N·m)</td>
  </tr>
  <tr>
    <td class="tg-baqh">M5</td>
    <td class="tg-baqh">30 kgf·cm (2.94 N·m)</td>
  </tr>
</tbody>
</table># 5.1.6. Sequence for Replacing the Grease

(1)	Pose the robot such that grease injection can be performed without any interference from surrounding facilities.

(2)	Pose the robot such that the positions of the grease inlet and outlet are as far apart as possible.

(3)	Turn off the power of the controller.

(4)	Remove the plugs from the grease inlet and outlet.

(5)	When grease is injected while the outlet plug is not removed, the internal pressure will rise and the grease will momentarily spurt out. Before injecting the grease, you must check whether the outlet plug is removed.

(6)	Decrease the air pressure of the oil pump to the minimum pressure at which grease can be discharged (0.025 Mpa or below.)

(7)	Attach a grease receiver such as vinyl with an opened entrance to the grease outlet to prevent the contamination of the surrounding area.

(8)	The entrance of the grease receiver must be kept opened to prevent the pressure inside the grease barrel from rising.

(9)	Prepare the oil pump and grease receiver in a way that enables you to measure the amounts of injected grease and discharged grease.
(10) Inject the grease by connecting the injection hose to the inlet.

(11) Inject the grease until the color of the grease discharged through the grease outlet changes sufficiently to the color of the new grease.

(12) Compare the amounts of injected grease and discharged grease, and then, if grease is excessively injected, subtract the excess grease to make sure that the amount of the injected grease is the same as that of the discharged grease by referring to the “Sequence for Subtracting the Residual Pressure” and the “Sequence for Discharging the Grease.”
# 5.1.7. Sequence for Subtracting the Residual Pressure

(1)	Pose the robot to ensure that it has no interference from surrounding facilities when it is operating.

(2)	Attach a grease receiver such as vinyl with an opened entrance to the grease outlet to prevent the contamination of the surrounding area.

(3)	Operate the robot in the following conditions within the range that will not cause interference with the surroundings.


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-baqh">Axis</th>
    <th class="tg-baqh">Operation angle (1 axis /2 axis/3 axis)</th>
    <th class="tg-baqh">Playback speed</th>
    <th class="tg-baqh">Operation time</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">1 axis–3 axis</td>
    <td class="tg-baqh">80°/90°/70° or above</td>
    <td class="tg-baqh">50%</td>
    <td class="tg-baqh">Minimum 20 min</td>
  </tr>
  <tr>
    <td class="tg-baqh">4 axis–6 axis</td>
    <td class="tg-baqh">60°/120°/60° or above</td>
    <td class="tg-baqh">50~100%</td>
    <td class="tg-baqh">Minimum 20 min</td>
  </tr>
  <tr>
    <td class="tg-baqh">Arm gearbox</td>
    <td class="tg-baqh">60°/120°/60° or above</td>
    <td class="tg-baqh">50~100%</td>
    <td class="tg-baqh">Minimum 20 min</td>
  </tr>
</tbody>
</table>

<br>

(4)	Wipe the outlet with a cloth, and reinstall the plug.

(5)	Measure the discharged grease so that it can be included in the amount of discharged grease.

# 5.1.8. Sequence for Discharging the Grease

(1)	Check the difference between the amount of the injected grease and the amount of the discharged grease, and then determine the amount of grease to be discharged.

(2)	Pose the robot to ensure that it has no interference from surrounding facilities when it is operating.

(3)	Attach a grease receiver such as vinyl with an opened entrance to the grease inlet to prevent the contamination of the surrounding area.

(4)	Prepare a grease receiver of a size that takes into consideration the amount of grease to be discharged.

(5)	Install an air precision regulator set adjusted to 0.025 Mpa to the grease outlet.
The air precision regulator set consists of an air hose, a stop valve, and male push-to-connect fittings. Before installing the set, you need to open and close the stop valve to ensure that the instructed pressure is not exceeded. After that, set the stop valve handle to the Stop state so that air is not supplied.

(6)	When discharging grease, pay attention so that the pressure at the grease injection part does not exceed 0.025 Mpa.

(7)	Check if the plug of the inlet through which the grease will be discharged is removed.

(8)	Open the stop valve to allow the grease to be discharged by air pressure, and check the amount of the discharged grease.

(9)	If the amount of the discharged grease is insufficient, rotate the robot slowly so that the grease can be easily discharged.

(10) When the discharging of the grease is completed, remove the grease receiver and regulator set.

(11) Remove the contaminated grease around the inlet and outlet with a clean cloth.

(12) Connect the plugs to the outlet and inlet.



<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">If air is supplied at too high a pressure to the inside of the grease barrel, etc., of the reducer where grease is injected, there is a risk of sudden grease ejection. It must be covered so that the grease being charged from the grease outlet can only be discharged to the grease receiver. When discharging grease, you should wear protective clothing such as protective glasses, a face shield, etc.<p>

To ensure that the pressure inside the grease barrel does not exceed 0.025 Mpa, set the pressure of the regulator by increasing its pressure from 0 Mpa to 0.025 Mpa gradually before installing it to the grease barrel. After that, check whether the set pressure is appropriate by opening and closing the stop valve several times, and then install the regulator set to the outlet of the grease barrel. After installing the set, open and close the stop valve to check once more if the pressure is appropriate.
</td>
  </tr>
</thead>
</table>


<br>

![](../../_assets/그림_5.1.8_그리스_배출_순서.png  )

# 5.1.9. 1-Axis (S-Axis) Reducer Inlet and Outlet



![](../../_assets/그림_5.1_1축_감속기_그리스_주입_배출구.png  )

Figure 5.1 1-Axis Reducer Grease Inlet / Outlet
# 5.1.10. 2-Axis (H-Axis)] Reducer Inlet and Outlet

![](../../_assets/그림_5.2_2축_감속기_그리스_주입_배출구.png  )

Figure 5.2 2-Axis Reducer Grease Inlet / Outlet
# 5.1.11. 3-Axis (V-Axis) Reducer Inlet and Outlet

![](../../_assets/그림_5.3_3축_감속기_그리스_주입_배출구.png  )

Figure 5.3 3-Axis Reducer Grease Inlet / Outlet
# 5.1.12. 4-Axis (R2-Axis) Reducer Inlet and Outlet

![](../../_assets/그림_5.4_4축_감속기_그리스_주입_배출구.png  )

Figure 5.4 4-Axis Reducer Grease Inlet / Outlet# 5.1.13. 5-Axis (B-Axis) Reducer Inlet and Outlet

![](../../_assets/그림_5.5_5축_감속기_그리스_주입_배출구.png  )

Figure 5.5 5-Axis Reducer Grease Inlet / Outlet
# 5.1.14. 6-Axis (R1-Axis) Reducer Inlet and Outlet

![](../../_assets/그림_5.6_6축_감속기_그리스_주입_배출구.png  )

Figure 5.6 6-Axis Reducer Grease Inlet / Outlet


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
    <td class="tg-cly1">Do not inject grease excessively. Excessive grease may cause an increase in internal pressure, which may result in grease leakage and abnormal operation of the robot.</td>
  </tr>
</thead>
</table>

# 5.1.15. Arm Frame - Gearbox Inlet and Outlet

![](../../_assets/그림_5.7_arm_frame_그리스_주입_배출구.png  )

Figure 5.7 Arm Frame Grease Inlet and Outlet
# 5.1.16. Gas Spring Bearing Inlet

![](../../_assets/그림_5.8_gas-spring_그리스_주입_배출구.png  )

Figure 5.8 Gas Spring Grease Inlet

<br></br>
(1)	Open the nipple cap 1/8, and inject grease through the grease nipple A-PT1/8 using a grease gun (Air pressure 5–7 kg/ cm2, decompression not required.)

-	Grease type: GADUS S3 V220C 2
-	Amount of initially injected grease: 15 cc (13.5 g)
-	Amount of reinjected grease: 7 cc (6.3 g)


(2)	Fill the grease through the grease nipple, and inject it until the new grease comes out in 360° around the bearing through the gap between the Nilos ring and bearing.

(3)	Wipe the grease discharged to the outside because of excessive injection of grease with a cloth.

(4)	Wipe the inlet with a cloth, and assemble the nipple cap back into place.

# 5.2. Replacing the Battery  

The position data of each axis is preserved with a backup battery. The battery must be replaced every two years. For the replacement of the battery, the following procedures should be followed.

(1)	Press the emergency stop button while the controller is in the Power On state.



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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">If you turn off the power and replace the battery, all current position data will be lost. As a result, it will be necessary to set the origin again. Make sure to keep the controller power on</td>
  </tr>
</thead>
</table>


(2)	Remove the cover at the location of the battery of each axis.

(3)	Take out the old battery

(4)	Assemble the new battery. Please pay attention to the direction when assembling it.


-	Battery specification: ER6V-T1 (AA) 3.6V
-	Manufacturer: TOSHIBA


(5)	Reinstall the cover.
 

![](../_assets/그림_5.9_배터리_교환_위치.png  )

Figure 5.9 Location for the Replacement of the Battery



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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">-	Do not throw away the batteries. Dispose of them as industrial waste according to the laws and regulations of the concerned country.<br>
-	Do not recharge the battery. It may explode or get overheated. <br>
-	Do not use a battery other than the ones with designated specifications. <br>
-	Do not short the negative and positive poles of the battery.<br>
-	Do not expose a battery to flame or high temperatures.
</td>
  </tr>
</thead>
</table>
# 5.3. Replacement of Wiring Inside the Manipulator

The following items will affect the replacement cycle of the wiring of the manipulator.

-	Continuous operation
-	Operation speed
-	Ambient environment

Inspect periodically every three months and check for any damage on the cables or cable protective springs. If there are any damages, the damaged ones should be replaced. 

Replace the cables every 24,000 operating hours regardless of the use conditions.



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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">-	Because bending-resistant wires are used, do not use wires other than the specified ones.<br>
-	Wiring replacement should be done by unit.<br> 
-	Do not use any cables, protective springs, and hoses that have external damage, as they may cause problems.<br> 
-	When purchasing the cables for use inside the robot, please contact our service department for the wiring type.<br>
-	Specify the length of the wiring from the manipulator to the controller.
</td>
  </tr>
</thead>
</table>


# 6. Troubleshooting



# 6.1. How to Investigate the Causes of Issues

When an abnormality occurs during the operation the robot, and if it is not a problem with the controller, it is a problem attributable to damaged mechanical parts. To handle issues easily and quickly, it is required to first accurately identify the phenomenon and determine to which parts the defects are attributable.

(1)	Step 1: Which axis has the abnormality?
Check the location of the axis that has an issue. If it is difficult to assess the phenomenon of the issues, investigate the following items.

-	Are there any areas where an abnormal sound is generated?
-	Are there any areas where abnormal heating occurs?
-	Are there any parts that have clearance?

(2)	Step 2: Are there any damaged parts?
If an axis with an abnormality is identified, investigate which part is the cause. There can be multiple causes for one phenomenon. Please refer to [Table 6-1] on the next page for symptoms and causes of issues.

(3)	Step 3: Handling defective parts
Dispose of parts that are found to be defective according to the methods described in “6.3 How to Investigate and Handle Each Part.” For matters other than those that can be handled by your company, please contact our service department.


# 6.2. Symptoms and Causes of Issues 


As shown in [Table 6-1], there can be multiple parts that are thought to be the cause of a single phenomenon. 
Please refer to the next page to determine which parts are damaged.



<br>
Table 6-1 Symptoms and Causes of Troubles
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-62g5{font-weight:bold; background-color:#f8f8be;color:#000000;text-align:center;vertical-align:middle}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-62g5">Location of abnormality / Symptoms of the issue</th>
    <th class="tg-62g5">Reducers</th>
    <th class="tg-62g5">Brake</th>
    <th class="tg-62g5">Motor</th>
    <th class="tg-62g5">Encoder</th>
    <th class="tg-62g5">Backlash</th>
    <th class="tg-62g5">Grease</th>
    <th class="tg-62g5">Gas spring</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-amwm">Overload [Note 1]</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
  </tr>
  <tr>
    <td class="tg-amwm">Position deviated</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
  </tr>
  <tr>
    <td class="tg-amwm">Abnormal sound generated</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O <b>[Note  3]</b></td>
    <td class="tg-baqh">O</td>
  </tr>
  <tr>
    <td class="tg-amwm">Vibration during operation  [Note  2]</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O <b>[Note 3]</b></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-amwm">Trajectory deviated</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
  </tr>
  <tr>
    <td class="tg-amwm">Axis freefalling</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
  </tr>
  <tr>
    <td class="tg-amwm">Abnormal heating</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-amwm">False operation and runaway</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh">O</td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
    <td class="tg-baqh"></td>
  </tr>
</tbody>
</table>

<br>

[Note 1] Overload ------------	A phenomenon that occurs when a load exceeding the conditions of the rated specification of the motor is applied. 
       	Specifically, it occurs when the temperature relay or circuit breaker is cut off.

[Note 2] Vibration during operation ------- Vibration that occurs during operation

[Note 3] If there are noises coming from the greased part of the reducer during low-speed operation, operate the robot while checking the state closely for 1–2 days. Generally, the noise will go away.

-	The noise will go away if you run the axis at high speed for 5–10 min.
-	When the old grease is discharged as much as possible (about 90% or more) and replaced with new grease, abnormal grease sounds can be minimized.

    (When the grease is discharged while the axis is rotating at a low speed, the grease discharge time can be shortened.)

<br>
The noise may be caused by the following.<p>

1.	Operation after greasing or replacing the reducer<br>
2.	Operation after long-term disuse<br>
3.	Operation at a low speed<br>
4.	Operation at a low temperature<br>
5.	Use of unspecified grease<br>
6.	Mixing of grease of different specifications



# 6.3. Diagnostics and Resolutions for Major Parts Failure


<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">-	When required to replace the motors and reducers of the 2 axis (H axis) and 3 axis (V axis), take some arm drop prevention measures (fixing using a pin or fixing using a crane) before doing the work so that the arm does not fall when the brake release switch is turned “On” and “Off.”<br>
-	When required to replace the motors and reducers of the 4 axis (R2 axis), 5 axis (B axis), and the 6 axis (R1 axis), set the robot into a posture such that the tool does not drop considering that the tool may rotate when the brake release switch is turned “On” and “Off.”<br>
-	To prevent accidents because of the dropping of the axis, you must check whether the pressure of the gas spring is appropriate before the work. The 2 axis (H axis) may fall when the robot operates at a pressure lower than the appropriate working pressure.
</td>
  </tr>
</thead>
</table>
# 6.3.1. Reducer

If the reducer is damaged, phenomena such as vibration and abnormal sounds will appear. In this situation, abnormalities such as overload and deviation that will interfere with normal operation and abnormal heating may occur. Also, there are cases wherein the robot does not move at all.

*	When required to replace the reducer, take some arm drop prevention measures (fixing using a pin or fixing using a crane) before doing the work.

    *	Investigation method

        ①	Investigate whether there are any abnormal phenomena, such as vibration, abnormal sound, abnormal heating, an error because of motor overload, etc., during operation.

        ②	Investigate whether there are any abnormal sounds, tool overloads, delays in the replacement of grease, etc.

        ③	Investigate whether the robot has collided with a peripheral system, etc.<br>
        (There are some cases wherein the reducer is damaged because of a collision.)

    *	Handling method

        ①	When it is determined to be the abnormal grease sound,
        -	operate the relevant axis at high speed until the grease sound disappears.
        -	If the abnormal sound does not disappear even after operating the axis at high speed for a long time, you should discharge the existing grease as much as possible and then inject new grease.

        ②	Take measures to prevent tool overload, interference, or collisions with surroundings.
        
        ③	It is necessary to replace the reducer in case of use in an overloaded state, collision, presence of foreign substances inside the reducer, or when grease has not been replaced for a long time. If you have any difficulty in replacing the reducer, please contact our service department.

 



# 6.3.2. Brake

If a problem occurs to the brake, each axis may fall in some cases while in the Operation Ready [OFF] state. Or, conversely, the brake may operate even in the Operation Ready [ON] state. In cases like these, overloading and noise may occur subsequently.

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
    <td class="tg-cly1">When intending to move the manipulator without turning the motor [ON], operate it by turning the brake release switch [ON]. Before turning the switch [ON], take the necessary measures to prevent the robot arm from dropping, as the robot arm will drop because of gravity. </td>
  </tr>
</thead>
</table>



*	Investigation method

    When using the brake release unit (optional) of the controller, first press the Enable button to release the brake of the targeted axis. Press and hold the Enable button and simultaneously press one of the B1–B8 buttons to disable the relevant axis. 
While in the Operation Ready [OFF] state, turn the brake release button [ON] and [OFF] and investigate if the brake makes any operating sounds. If there are no operating sounds, it can be assumed that there is a failure of the motor or disconnection of the internal wiring. 

*	Handling method

    When you check the internal wirings and it is not disconnected, please replace the motor.



# 6.3.3. Motor


If a motor overload error occurs while a program is running in the teach pendant, take the following actions.

*	Investigation method

    Check the motor overload error on the teach pendant.

*	Handling method

    Increase the delay time of the relevant program or reduce the operation speed of the program.

If there is an abnormality in the motor, abnormal motions such as shaking when stopped, irregular cycle (pulsation), and vibration during operation may occur. Abnormal heating and abnormal sounds may also occur.

Considering that a similar phenomenon occurs even when the reducer is damaged, investigate the reducer and bearing at the same time to determine the cause.

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
    <td class="tg-cly1">When required to replace the motor, arm drop prevention measures (fixing using a pin or fixing using a crane) must be taken before doing the work.</td>
  </tr>
</thead>
</table>


*	Investigation method

    Investigate whether there is any abnormal sound or abnormal heating.

*	Handling method

    Replace the motor.
# 6.3.4. Encoder



If an encoder has an abnormality, it may cause position deviation, false operation, runaway, etc., which may lead to shaking when stopping or irregular pulsation. In addition, these issues have nothing to do with the occurrence of abnormal mechanical sounds, heating, and vibration.

*	Investigation method

    ①	Investigate whether there are any abnormalities in the encoder data.
    
    ②	Set to the reference position of the origin setting scale, and check whether there are any errors in the position data.

    ③	While moving each axis of the robot, investigate whether there is an axis showing an irregularity in the data.

    ④	Investigate whether an error does not occur when the servo amplifier board, BD640, is replaced.
 
*	Handling method

    ①	Check the wiring, and if it is not disconnected, replace the encoder.


# 6.3.5. Gas spring

If the pressure of the gas spring drops below the reference value (100 bar), it may cause abnormal heating and overloading in the motor of the 2 axis or cause the arm to fall. 
Fill it with nitrogen gas so that the pressure does not drop more than 5 bar below the reference pressure.

Periodically inject grease into the upper and lower bearings of the gas spring to prevent the bearings from being damaged.


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
    <td class="tg-cly1">Before checking the gas spring, you must ensure that the controller and external power are in the 『OFF』 state. Also, take measures to prevent the controller and external power from being accidently turned 『ON』 by someone else.<br>
You must wear protective glasses when checking the gas pressure.

</td>
  </tr>
</thead>
</table>



*	Investigation method

    ①	Check whether the pressure of the gas spring is appropriate, by referring to “9.1. Checking of the Pressure of the Gas Spring.”

    ②	Check if dust is generated at the bearing part of the gas spring.

    ③	If grease has not been injected into the bearing part for a long time, you should operate the robot to check if there is any abnormal vibration and noise.

*	Handling method

    ①	For the pressure of the gas spring, fill it with nitrogen gas based on Table 9.1.

    ②	Replace the gas spring with a new one when its pressure drops within a short period after the filling of nitrogen gas, or when the gas spring has been in operation for a long time at low pressure.

    ③	Fill the grease in the bearing part by referring to “5.1.16. Gas Spring Bearing Inlet.”

    ④	Replace the bearing if it is abnormal.

    ⑤	If you have any difficulties with the handling method, please contact our service department.

    ⑥	For replenishing the gas, comply with “9.2. Replenishing of the Gas of the Gas Spring.”

    ⑦	For the pressure reference and replacement, comply with “9.4. Replacing (Separating and Assembling) the Gas Spring.”

    
    <br>

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-cly1{text-align:left;vertical-align:middle}
.tg .tg-e3v1{background-color:#f8a102;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <td class="tg-e3v1"><img src="../../_assets/작은주의표시.png"> Warning</td>
    <td class="tg-cly1">-	Keep the appropriate working pressure of the gas spring to prevent the arm from falling.<br>
-	Periodically inject grease into the bearing to prevent early damage to the bearing.

</td>
  </tr>
</thead>
</table>



# 6.4. Motor Replacement


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
    <td class="tg-cly1">When the motor is separated, the arm will drop because of its built-in brakes for holding the robot’s posture. To prevent this, the user should essentially ensure that safety measures, such as suspending the arm using devices like a crane, etc., or fixing the first and second arms with fixing pins, are employed.
</td>
  </tr>
</thead>
</table>



Immediately after the robot stops, the motor is at a high temperature, so make sure to check the motor temperature. 

Motor weights are listed as follows. Be careful when transporting the motor.


Table 6-2 Motor weight of each axis
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-69va{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-69va">Axis</th>
    <th class="tg-69va">1(S)</th>
    <th class="tg-69va">2(H)</th>
    <th class="tg-69va">3(V)</th>
    <th class="tg-69va">4(R2)</th>
    <th class="tg-69va">5(B)</th>
    <th class="tg-69va">6(R1)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">Weight (kg)</td>
    <td class="tg-baqh" colspan="3">24</td>
    <td class="tg-baqh" colspan="3">10</td>
  </tr>
</tbody>
</table>

<br>

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
    <td class="tg-cly1">For this task, there is a part that needs to be performed while in the Operation Ready [ON] state. Therefore, workers should work in a team of two. One person should be ready to press the emergency stop button at any time, and the other person should work quickly while paying particular attention to the robot’s movements. Also, before working, please check the evacuation area.</td>
  </tr>
</thead>
</table>

# 6.4.1. Necessary Tools and Parts

Table 6-3 Necessary Tools
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm">Tool Name</th>
    <th class="tg-yhpm">Axis name</th>
    <th class="tg-yhpm">Part No. (Type)</th>
    <th class="tg-yhpm">Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix" rowspan="2">Torque wrench<br>(to be prepared<br>by the customer)</td>
    <td class="tg-nrix">1(S), 2(H), 3(V)</td>
    <td class="tg-nrix">M8 torque wrench  (Lock type)<br>M10 torque wrench  (Lock type)<br>M12 torque wrench  (Lock type)
</td>
    <td class="tg-nrix" rowspan="2">Use a torque wrench<br>and extension on the market</td>
  </tr>
  <tr>
    <td class="tg-nrix">4(R2), 5(B), 6(R1)</td>
    <td class="tg-nrix">M6 torque wrench  (Lock type)<br>M8 torque wrench  (Lock type)<br>M10 torque wrench  (Lock type)
</td>
  </tr>
</tbody>
</table>

Make sure that the torque wrench is calibrated.
<br>

Table 6-4 Necessary parts

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-yhpm{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-yhpm">Part name</th>
    <th class="tg-yhpm">Axis name</th>
    <th class="tg-yhpm">Use</th>
    <th class="tg-yhpm">Part No. (Type)</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix" rowspan="2">Drop prevention bolt (option)</td>
    <td class="tg-nrix">2 axis (H axis) and 3 axis (V axis)</td>
    <td class="tg-nrix">O</td>
    <td class="tg-nrix">M20×250(standard)</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wrist axis (4(R2), 5(B), 6(R1))</td>
    <td class="tg-nrix">-</td>
    <td class="tg-nrix">-</td>
  </tr>
</tbody>
</table># 6.4.2. How to Replace the Motor

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
    <td class="tg-cly1">When the motor is separated, the arm will drop because of its built-in brakes for holding the robot’s posture. To prevent this, the user must make sure that safety measures, such as suspending the arm using devices like a crane, etc., and fixing the arm by inserting a fixing bolt, are implemented.</td>
  </tr>
</thead>
</table>


(1)	Set the controller to teaching mode, and turn the Operation Ready mode [ON]. 

(2)	Set the axis whose motor is to be replaced into the basic posture. If it is impossible to set the Operation Ready mode to the [ON] state or move the motor’s axis, perform the work starting from step (3).

(3)	When replacing the 2 and 3 axes, insert the arm drop prevention fixing bolts by referring to Figure 6.1–Figure 6.2. If inserting the fixing bolt is not possible, take measures to prevent dropping by using a crane, etc.

(4)	Turn the controller power [OFF], and turn the primary power [OFF].

(5)	Disconnect the motor wiring.

(6)	Remove the motor attachment bolt, and remove the motor from the manipulator.
When disassembling the motors of the 2 axis (H axis) and 3 axis (V axis), you should be careful not to allow the lip of the oil seal to be damaged by the gear attached to the motor’s axis.

(7)	Remove the gear attached to the motor shaft. 
At this time, be careful not to apply strong shock to the motor shaft.

(8)	Apply a thin layer of grease to the shaft of the new motor to be assembled, and then assemble the gear.
At this time, clean and degrease the bolts that will be used to fasten the gear to the motor shaft, and apply loosening prevention bond (Loctite 243) to the entire screw fastening surface. Fasten the bolts according to the specified torque using a torque wrench. Also, when fastening the motor to the manipulator, tighten the bolts slowly in a symmetrical direction.

(9)	Apply a small amount of grease to the lip of the oil seal, and then attach the motor to the manipulator. When attaching the motors of the main axes, you should make sure that the lip of the oil seal is not damaged by the gear attached to the axis of the motor.

(10)	Connect the motor wiring.

(11)	When replacing the motors of the 2 axis (H axis), and 3 axis (V axis), replenish the grease until it is equal in amount to the grease that has leaked.

(12)	Reset the encoder of the axis for which the motor has been replaced.

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
    <td class="tg-cly1">Before compensating the encoder, set the Operation Ready mode to the [ON] state, and press the Enable switch on the teach pendant for two to three seconds to check whether the power is supplied.</td>
  </tr>
</thead>
</table>

(13)	Compensate the encoder of the axis on which the motor was replaced by referring to “7.4.4. Encoder Offset in the Hi6 Controller Operation Manual.”

(14)	Disassemble the M20 bolts, which are the arm drop prevention bolts of the 2 axis (H axis) and 3 axis (V axis) or deactivate the drop prevention measures.

(15)	Check if there are any problems with the robot operation.




![](../../_assets/그림_6.1_arm축_고정용_볼트_삽입_위치.png)

Figure 6.1 Arm (2 axis [H axis]) Fixing Bolt Insertion Location


![](../../_assets/그림_6.2_arm축_고정용_볼트_삽입_위치.png)

Figure 6.2 Arm (3 axis [V axis ]) Fixing Bolt Insertion Location
# 6.5. Setting the Encoder’s Origin 

If the encoder data shows abnormal values because of any problems, or if the motor has been replaced, the robot’s origin should be reset.

As a method for determining the location of the origins of each of the robot’s axes, a scale is used. When the user has replaced motors, the user should reset the encoder using the origin setting scale for each axis.



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
    <td class="tg-cly1">For this task, there is a part that needs to be performed while in the Operation Ready [ON] state. Therefore, workers should work in a team of two. One person should be ready to press the emergency stop button at any time, and the other person should work quickly while paying particular attention to the robot’s movements. Also, before working, please check the evacuation area.</td>
  </tr>
</thead>
</table>
# 6.5.1. Setting the Origin


(1)	Set the controller to teaching mode and the Operation Ready mode to the [ON] state. 
If it is impossible to change the Operation Ready mode to the [ON] state because of abnormal phenomena, set the reference location of the robot using the brake release switch.



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
    <td class="tg-cly1">When the brake is released, the arm will drop, so take measures ahead to prevent the robot from dropping. Therefore, drop prevention measures (use of a crane) must be taken.</td>
  </tr>
</thead>
</table>

(2)	Move each axis to its default position to match the scale’s gridlines.

(3)	Reset the encoder. For the encoder resetting method, refer to “7.6.4. Serial Encoder Resetting in the Controller Operation Manual.”

(4)	Compensate the encoder. Please refer to “6.5.2 Encoder Reset.”

(5)	Check whether there are any problems with robot operation.


![](../../_assets/그림_6.3_원점_설정_방법.png)

Figure 6.3 How to Set the Origin# 6.5.2. Encoder Reset


(1)	Turn off the motor.

(2)	Enter the serial encoder reset window. (“[F2]: System” → “5: Initialization” → “4: Serial Encoder Reset”)



![](../../_assets/그림_6.4_시리얼_엔코더_리셋.png)
 
Figure 6.4 Serial Encoder Reset


(3)	Move to the targeted axis using the [↓] and [↑] keys and then perform the setting using the [Encoder Reset] function by operating the [SHIFT] + [←][→] keys, and then press the Execute key.

(4)	Reset the encoder. The user must change the controller power from the Off state to the On state.
 
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

# 6.5.4. Mastering (option)

When performing the encoder data compensation after replacing a motor, first turn Power Ready mode “ON,” and check whether power is supplied to the motor.

When the mastering option is added, mastering is possible for axes 1 to 5, and the attachment location of each mastering sensor is shown in Figure 6.6.

Mastering should be performed in the following cases:

*	Motor Replacement
*	Replacement of a reducer
*	When the axis is displaced after an external collision

In addition, there is no need to compensate the encoder separately after mastering
For detailed mastering methods, please refer to the Hi6 Controller Manual.



![](../../_assets/그림_6.6_1-5축_마스터링_센서부착위치.png)

Figure 6.6 Mastering Sensor Attachment Location for the 1 axis to 5 axis

- 1 axis

![](../../_assets/그림_6.7_1축_마스터링_센서부착위치.png)

Figure 6.7 Mastering Sensor Attachment Location for the 1 Axis

-2 axis

![](../../_assets/그림_6.8_2축_마스터링_센서부착위치.png)

Figure 6.8 Mastering Sensor Attachment Location for the 2 Axis

-3 axis

![](../../_assets/그림_6.9_3축_마스터링_센서부착위치.png)

Figure 6.9 Mastering Sensor Attachment Location for the 3 axis

-4 axis

![](../../_assets/그림_6.10_4축_마스터링_센서부착위치.png)

Figure 6.10 Mastering Sensor Attachment Location for the 4 axis

-5 axis

![](../../_assets/그림_6.11_5축_마스터링_센서부착위치.png)

Figure 6.11 Mastering Sensor Attachment Location for the 5 Axis# 7. Recommended Spare Parts

The following table shows the recommended spare parts for the robot. When purchasing, please check the manufacturing number and date of the manipulator, and then contact our service department.

[Classification]

A: Parts for regular maintenance (parts to be replaced regularly)

B: Main spare parts (recommended to be prepared as spare parts because of high frequency of operation)

C: Main components

D: Mechanical parts
<br>

Table 7-1 List of Spare Parts

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:middle}
.tg .tg-69va{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-69va">Classification</th>
    <th class="tg-69va">PART No.</th>
    <th class="tg-69va">Part name</th>
    <th class="tg-69va">Quantity</th>
    <th class="tg-69va">Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">A</td>
    <td class="tg-baqh">R7900004402</td>
    <td class="tg-baqh">RV GREASE LB00 1CAN=16KG</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">COMMON</td>
  </tr>
  <tr>
    <td class="tg-baqh">A</td>
    <td class="tg-baqh">R7900054780</td>
    <td class="tg-baqh">GREASE GADUS S2 V46 2 (1CAN=15KG)</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">COMMON</td>
  </tr>
  <tr>
    <td class="tg-baqh">A</td>
    <td class="tg-baqh">P3900007270</td>
    <td class="tg-baqh">BATTERY</td>
    <td class="tg-baqh">6</td>
    <td class="tg-baqh">FOR ENCODER BACKUP</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS900001829</td>
    <td class="tg-baqh">MOTOR</td>
    <td class="tg-baqh">3</td>
    <td class="tg-baqh">1,2,3 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS901003012</td>
    <td class="tg-baqh">MOTOR</td>
    <td class="tg-baqh">3</td>
    <td class="tg-baqh">4,5,6 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS902000096</td>
    <td class="tg-baqh">REDUCER</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">1 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS902000099</td>
    <td class="tg-baqh">REDUCER</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">2 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS902000098</td>
    <td class="tg-baqh">REDUCER</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">3 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS902000033</td>
    <td class="tg-baqh">REDUCER</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">4 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS902000034</td>
    <td class="tg-baqh">REDUCER</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">5 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">B</td>
    <td class="tg-baqh">PS902000032</td>
    <td class="tg-baqh">REDUCER</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">6 AXES</td>
  </tr>
  <tr>
    <td class="tg-baqh">C</td>
    <td class="tg-baqh">P7900027990</td>
    <td class="tg-baqh">WRIST ASSY</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">WRIST ASSY</td>
  </tr>
  <tr>
    <td class="tg-baqh">C</td>
    <td class="tg-baqh">P7000001520</td>
    <td class="tg-baqh">CABLE ASSY</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">CABLE ASSY</td>
  </tr>
  <tr>
    <td class="tg-baqh">C</td>
    <td class="tg-baqh">P7000000710<br>P7000000730</td>
    <td class="tg-baqh">GAS SPRING ASSY</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">GAS SPRING </td>
  </tr>
  <tr>
    <td class="tg-baqh">C</td>
    <td class="tg-baqh">R7900162380</td>
    <td class="tg-baqh">PRESSURE TESTER(FOR MEASURING THE PRESSURE OF THE GAS SPRING)</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">OPTION (FOR GAS SPRING)
</td>
  </tr>
  <tr>
    <td class="tg-baqh">C</td>
    <td class="tg-baqh">R7900164390</td>
    <td class="tg-baqh">REPLENISHING ARMATURE KIT</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">OPTION (FOR GAS SPRING)
<br>- APPLICABLE WHEN THE NITROGEN GAS BOMBE’S PRESSURE EXCEEDS 150 BAR<br>
- ITEM TO BE INCLUDED ON ORDER: GAS BOMBE CONNECTION PART SCREW SPECIFICATION
</td>
  </tr>
  <tr>
    <td class="tg-baqh">C</td>
    <td class="tg-baqh">R7900162750</td>
    <td class="tg-baqh">GAS BOOSTER KIT</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">OPTION (FOR GAS SPRING)
<br>- APPLICABLE WHEN THE NITROGEN GAS BOMBE’S PRESSURE IS 150 BAR OR BELOW<br>
- ITEM TO BE INCLUDED ON ORDER: GAS BOMBE CONNECTION PART SCREW SPECIFICATION
사양</td>
  </tr>
  <tr>
    <td class="tg-baqh">D</td>
    <td class="tg-baqh">R7900162510</td>
    <td class="tg-baqh">REPAIR KIT (FOR DISASSEMBLING INTERNAL PARTS OF THE GAS SPRING)</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">OPTION (FOR GAS SPRING)</td>
  </tr>
  <tr>
    <td class="tg-baqh">D</td>
    <td class="tg-baqh">R7900163080</td>
    <td class="tg-baqh">REPLACEMENT CATRIDGE (GAS SPRING)</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">OPTION (FOR GAS SPRING)
</td>
  </tr>
  <tr>
    <td class="tg-baqh">D</td>
    <td class="tg-baqh">R7900163210</td>
    <td class="tg-baqh">REPLACEMENT PISTON ROD (GAS SPRING)</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh">OPTION (FOR GAS SPRING)
</td>
  </tr>
</tbody>
</table># 8. Dismantle
# 8.1. Material for Each Part

Robots are made of various materials as shown in the table below. To prevent adverse effects on human health or the environment, some parts should be properly and orderly sealed.

Table 8-1 Table of Materials for Each Part

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-jafi{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-jafi">Part</th>
    <th class="tg-jafi">Material</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-nrix">Battery</td>
    <td class="tg-nrix">NiCad or Lithium</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wiring, Motor</td>
    <td class="tg-nrix">Copper</td>
  </tr>
  <tr>
    <td class="tg-nrix">Base body, Lower Frame, Upper Frame etc.</td>
    <td class="tg-nrix">Cast Iron</td>
  </tr>
  <tr>
    <td class="tg-nrix">Brakes, Motors</td>
    <td class="tg-nrix">Samarium Cobalt(or Neodymium)</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wiring, Connectors</td>
    <td class="tg-nrix">Plastic / Rubber</td>
  </tr>
  <tr>
    <td class="tg-nrix">Reducers, Bearings</td>
    <td class="tg-nrix">Oil / Grease</td>
  </tr>
  <tr>
    <td class="tg-nrix">Wrist cover etc.</td>
    <td class="tg-nrix">Aluminum alloy cast</td>
  </tr>
</tbody>
</table># 8.2. Disposal of the Gas Spring

Gas springs are filled with gas with high pressure, so please observe the following procedures at the stage of disposal. Otherwise, damages to life and property may occur.
# 8.2.1. Separation of the Gas Spring

When separating the gas spring, you must keep the robot in the posture shown in Figure 8.1. In this posture, the compression force of the gas spring will be minimized so that it can be separated from the robot. 
However, when required to separate the gas spring to dispose of it or repair its internal parts, first remove the gas completely according to the procedure for discharging gas from the gas spring.


![](../../_assets/그림_8.1_가스스프링_조립_해체_및_유지보수시_자세.png)

Figure 8.1 Postures for Assembling, Dismantling, and Maintaining the Gas Spring

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-baqh">1- Axis</th>
    <th class="tg-baqh">0</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">2- Axis</td>
    <td class="tg-baqh">90</td>
  </tr>
  <tr>
    <td class="tg-baqh">3- Axis</td>
    <td class="tg-baqh">0</td>
  </tr>
  <tr>
    <td class="tg-baqh">4- Axis/td>
    <td class="tg-baqh">0</td>
  </tr>
  <tr>
    <td class="tg-baqh">5- Axis</td>
    <td class="tg-baqh">0</td>
  </tr>
  <tr>
    <td class="tg-baqh">6- Axis</td>
    <td class="tg-baqh">0</td>
  </tr>
</tbody>
</table>


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
    <td class="tg-cly1">-	When assembling and disassembling the gas spring, fasten or dismantle the bolts by rotating the upper and lower bolts alternately at less than 45 degrees as shown in Figure 8.2 to prevent the hinge from being excessively tilted.<br>
-	Excessive tilting of the hinge will damage the bolts, and damaged bolts will damage even the tap of the frame, making it difficult to perform the disassembly and assembly work.<br>
-	The shape of each part, such as the hinge, may change without a notice.
</td>
  </tr>
</thead>
</table>



![](../../_assets/그림_8.2_가스스프링_힌지_고정볼트_분해시_주의사항1.png)

Figure 8.2 Precautions for Dismantling the Gas Spring Hinge Fixing Bolts# 8.2.2. Disposal of the Gas Spring

Because high pressure still remains inside the gas spring separated from the manipulator, remove the gas according to the procedures of “9.3. Releasing of the Gas of the Gas Spring,” confirm that the gas is completely removed, and then dispose of the gas spring. Also, because a small amount of grease will remain inside, it should be handled according to the relevant laws and regulations in an environment sensitive to contamination.

 


# 9. Maintenance of the Gas Spring

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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">Make sure that an appropriate pressure for the gas spring can be maintained through periodic maintenance,<br>and replace the gas spring every 20,000 h or when the proper working pressure (90 bar–120 bar) cannot be maintained even after gas is injected.</td>
  </tr>
</thead>
</table>




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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">-	Nitrogen gas is filled at high pressure, so the safety regulations of the concerned country should be observed.<br>
-	To prevent the arm from falling, maintain the pressure of the gas spring at an appropriate working pressure.<br>
-	When required to operate the 2 axis manually, first check whether the gas spring is at an appropriate working pressure.<br>
-	Never go under the direction of the arm falling.<br>
-	Fill only nitrogen gas.<br>
(Never charge any type of gas or liquid other than nitrogen gas.)<br>
-	Wear safety glasses when working.<br> 
-	Fill nitrogen gas so that the pressure does not drop more than 5 bar below the reference pressure.<br>
-	Never look directly into the gas inlet and pressure gauge.<br>
-	When the internal parts of the gas spring are damaged, secure safety by not placing any part of the body or major equipment in the operation direction of the gas spring, and then completely remove the gas.<br>
(When an internal part is damaged, the compression force causes it to be thrown out at high speed, resulting in accidents.)<br>
-	When required to separate the gas spring assembly unit, separate it while keeping the 2 axis of the robot at an angle of 90 degrees (teach pendant.) When in this posture, the compression force of the gas spring is minimized, making it possible to separate it.<br> 
(When in other postures, the gas spring compression force is high, so the bolts will be thrown out at high speed during the separation work, resulting in accidents.)<br>
-	To consider safety and maintain the performance of the product, the works of disassembling and assembling the internal parts of the gas spring should be performed using only designated standard work tools and equipment as well as with the appropriate trainings and understanding of the product. Please contact us for any inquiries regarding this.<br>
-	When measuring the gas pressure, observe the instruction in “9.1. Checking of the Pressure of the Gas Spring” because incorrect operation of the measuring device or mistakes in operating it may result in a drop in the gas pressure.<br>
-	Before checking the gas spring, you must ensure that the controller and external power are in the 『OFF』 state. Also, take measures to prevent the controller and external power from being accidently turned 『ON』 by someone else.<br>
-	When required to replace the gas spring, you must remove the gas pressure first.<br>
-	When replacing an old gas spring, replace the bearing as well.<br>
-	Regularly inject grease into the bearing part of the gas spring.<br>
(Every 6 months or every 3 months in harsh conditions)<br>
- When purchasing gas injection parts, include the specification of the nitrogen gas bombe connection screws.
</td>
  </tr>
</thead>
</table>



# 9.1. Checking of the Pressure of the Gas Spring


(1)	Set the robot’s 2 axis to a 90° posture, and cut off the power of the controller.

(2)	Remove the plug installed to the gas inlet of the gas spring.

(3)	Check whether the handle of the bleed valve ○P is closed (locked clockwise.)

(4)	Check whether the gas release pin of the marked part ○R is protruding. If it is protruding, turn the knob ○O counterclockwise to prevent the pin from protruding.

(5)	Set the release pin ○R of the pressure tester (= armature) to the center of the gas inlet, and then turn the knob ○N clockwise to completely connect it.

(6)	Turn the knob ○O clockwise and then stop turning it if the pointer of the pressure gauge ○T moves. 
(To avoid making the release pin ○R go inside excessively and damage the check valve inside the gas spring, do not turn the knob ○O excessively.) 
The gas pressure according to the surface temperature of the gas spring is shown in the table below.

(7)	Check the pressure and then turn the knob ○O counterclockwise to retreat it. After that, turn the bleed valve ○P counterclockwise to discharge the residual gas inside the pressure tester.

(8)	Turn the knob ○N of the pressure tester counterclockwise to separate it. After that, reinstall the plug.




![](../_assets/그림_9.1_가스스프링_압력_확인.png)

Figure 9.1 Checking of the Pressure of the Gas Spring

</br>

Table 9-1 Pressure for Each Gas Spring Surface Temperature – The Set Gas Pressure

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:top}
.tg .tg-69va{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:top}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-69va">Temperature (℃)</th>
    <th class="tg-baqh">0</th>
    <th class="tg-baqh">5</th>
    <th class="tg-baqh">10</th>
    <th class="tg-baqh">15</th>
    <th class="tg-baqh">20</th>
    <th class="tg-baqh">25</th>
    <th class="tg-baqh">30</th>
    <th class="tg-baqh">35</th>
    <th class="tg-baqh">40</th>
    <th class="tg-baqh">45</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-69va">Pressure </td>
    <td class="tg-baqh">113</td>
    <td class="tg-baqh">115</td>
    <td class="tg-baqh">117</td>
    <td class="tg-baqh">119</td>
    <td class="tg-baqh">121</td>
    <td class="tg-baqh">123</td>
    <td class="tg-baqh">125</td>
    <td class="tg-baqh">127</td>
    <td class="tg-baqh">130</td>
    <td class="tg-baqh">132</td>
  </tr>
</tbody>
</table>


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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">Each time the gas pressure is measured, the pressure is reduced by about 0.5 bar.
The cross pressure tester (pressure tester = armature) may have different names and handle positions depending on the type.
</td>
  </tr>
</thead>
</table>
# 9.2. Replenishing of the Gas of the Gas Spring


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
    <td class="tg-cly1">
- Nitrogen gas is filled at high pressure, so the safety regulations of the concerned country should be observed.<br>
-	Fill only nitrogen gas.<br>
(Never charge any type of gas or liquid other than nitrogen gas.)<br>
-	Wear safety glasses when working. <br>
-	Never look directly into the gas inlet and pressure gauge.<br>
-	The replenishment and charging of the gas must be carried out while the gas spring has been assembled on the robot.<br>
-	After charging the gas, allow about 30 min for the gas temperature to return to room temperature before use.<br>
-	Before checking the gas spring, you must ensure that the controller and external power are in the 『OFF』 state. Also, take measures to prevent the controller and external power from being accidently turned 『ON』 by someone else.
</td>
  </tr>
</thead>
</table>
# 9.2.1. When the Pressure of the Nitrogen Gas Bombe Exceeds 120 bar

(1)	Set the robot’s 2 axis to a 90° posture, and cut off the power of the controller.

(2)	Remove the plug installed to the gas inlet of the gas spring.

(3)	Check that the bleed valve ○P and shut-off valve ○Q of the pressure tester are closed
(locked clockwise.)

(4)	Turn the knob ○O counterclockwise to prevent the release pin ○R from protruding.

(5)	Turn the knob ○N of the pressure tester clockwise to completely connect it to the gas inlet.

(6)	Check whether the handle ○U and shut-off valve○Q are closed.

(7)	Connect the screw of the connection part of the regulator to the screw of the nitrogen gas bombe. 
(Hoses should be connected as shown in the figure.)
Each country has different specifications for the screw of the nitrogen bombe. Purchase a regulator that meets the specifications for the screw of the nitrogen bombe.
If the pressure of the nitrogen gas bombe is 150 bar or below, a booster should be fitted as well as a regulator. (Condition for a nitrogen gas bombe that can perform the charging without a booster: It can keep the pressure at 150 bar or more and be capable of charging the gas spring with the pressure of 120 bar.)

(8)	The gauge ○Xindicates the set gas pressure, and the gauge ○Y indicates the pressure of the nitrogen gas bombe.

(9)	Open the knob ○Z of the nitrogen gas bombe, and then turn the handle ○U of the regulator (○V) to set the specified gas pressure. (The specified gas pressures are shown in Table 9.1 Pressure for Each Temperature.)

(10)	Open the shut-off valve ○Q slowly and perform the charging until the pressure gauge ○T reaches the set pressure.

(11)	When the set pressure is reached, close the shut-off value ○Q and then open the bleed valve ○P to release the residual pressure remaining inside the 
pressure tester.
Do not unscrew the bleed valve ○P more than 360°.

(12)	Close the bleed valve ○P to adjust the gas pressure in the gas spring.

(13)	While slowly turning the knob ○O clockwise, check the pressure on the pressure gauge ○T.
Take precautions not to allow the release pin ○R to go inside excessively and damage the valve mounted on the gas spring.

(14)	When the set pressure is exceeded, adjust the gas pressure to the desired pressure by opening and closing the bleed valve ○P little by little.

(15)	Turn the knob ○O counterclockwise to retreat the release pin ○R.

(16)	When the pressure is checked, the bleed valve ○P should be opened to completely release the residual pressure remaining inside the pressure tester.

(17)	Close the knob ○Z of the nitrogen gas bombe and loosen the regulator connection part to separate it from the nitrogen gas bombe.

(18)	Loosen the shut-off connection part to separate it from the pressure tester.

(19)	Turn the knob ○N of the pressure tester counterclockwise to disconnect it from the gas spring.

(20)	Check the check valve of the gas spring for oil leakage or gas leakage.
Warning! Do not look directly into the check valve hole if the gas bombe is filled with gas.

(21)	Connect the G1/8 plug to the gas spring.
After charging the gas, allow about 30 min for the gas temperature to return to room temperature before use.




![](../../_assets/그림_9.2_가스스프링_gas_보충.png)

Figure 9.2 Replenishing of the Gas of the Gas Spring


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
    <td class="tg-cly1">The gas replenishing kit may vary in shape and name depending on the type, so please refer to the manual enclosed upon purchase.
</td>
  </tr>
</thead>
</table>
# 9.2.2. When the Pressure of the Nitrogen Gas Bombe is 150 Bar or Below (Replenishing the Gas Using the Booster)


(1)	Set the robot’s 2 axis to a 90° posture, and cut off the power of the controller.

(2)	Remove the plug installed to the gas inlet of the gas spring.

(3)	Check that the bleed valve ○P and shut-off valve ○Q of the pressure tester are closed
(locked clockwise.)

(4)	Turn the knob ○O counterclockwise to prevent the release pin ○R from protruding.

(5)	Turn the knob ○N of the pressure tester clockwise to completely connect it to the gas inlet.

(6)	Check whether the handle ○U, shut-off valve ⓦ, knob ⓢ (the knob of the air hose owned by the customer), and shut-off valve ○Q are locked.

(7)	Connect the screw of the connection part of the regulator to the screw of the nitrogen gas bombe.<br>
(The connection parts of hoses should be connected to each connection inlet.)<br>
Each country has different specifications for the screw of the nitrogen bombe. Purchase a regulator that meets the specifications for the screw of the nitrogen bombe.

(8)	The gauge ○X indicates the set gas pressure of the nitrogen gas bombe, and the gauge ○Y indicates the pressure of the nitrogen gas bombe.

(9)	Open the knob ○Z of the nitrogen gas bombe, and then turn the handle ○U of the regulator ○V to set the set gas pressure. (The specified gas pressures are shown in Table 9.1 Pressure for Each Temperature.)

(10)	 Open the shut-off valve ⓦ of the hose connected to the regulator ○V, and slowly turn the shut-off valve ○Q to be connected to the pressure tester counterclockwise until the pointer of the pressure gauge ○T matches the pointer of the gauge ○X.

(11) Connect the connection part of the air hose to the booster, and then open the knob ⓢ (the knob of the air hose owned by the customer) to operate the booster.<br>          
Charge until the pointer of the pressure gauge ○T reaches the set pressure.<br>
※	During charging, the minimum air pressure should be 5 bar or more.<br>
Replace the nitrogen gas bombe when the residual pressure is 30 bar or less.

(12) When the set pressure is reached, close the shut-off value ○Q and then open the bleed valve ○P to release the residual pressure remaining inside the 
pressure tester.<br>
(Do not unscrew the bleed valve ○P more than 360°.)

(13) Close the bleed valve ○P and turn the knob ○O clockwise little by little while checking that the pointer of the pressure gauge ○T matches the set pressure. Once they match, stop the work.
Take precautions not to allow the release pin ○R to go inside excessively and damage the check valve mounted on the gas spring.

(14) When the set pressure is exceeded, you should adjust the gas pressure to the desired pressure by opening and closing the bleed valve ○P little by little.

(15) Turn the knob ○O counterclockwise to retreat the release pin ○R.

(16) When the pressure is checked, the bleed valve ○P should be opened to completely release the residual pressure remaining inside the pressure tester.

(17) Close the knob ⓢ of the air hose and separate it from the booster.

(18) Close the shut-off valve ⓦ of the hose connected to the regulator and close the handle ○U. 

(19) Close the knob ○Z of the nitrogen gas bombe and separate the hose connected to the regulator ○V from the booster. After that, open the shut-off value ⓦ to completely release the residual pressure remaining inside.

(20) Separate the shut-off valve connection part from the pressure tester.

(21) Turn the knob ○N of the pressure tester counterclockwise to disconnect it from the gas spring.<br>
Connect the G1/8 plug to the gas spring.<br>
After charging the gas, allow about 30 min for the gas temperature to return to room temperature before use.






![](../../_assets/그림_9.3_부스터_가스스프링_gas_보충.png)

Figure 9.3 Replenishing the Gas of the Gas Spring Using the Booster

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
    <td class="tg-cly1">The gas replenishing kit may vary in shape and name depending on the type, so please refer to the manual enclosed upon purchase.
</td>
  </tr>
</thead>
</table>
# 9.3. Releasing of the Gas of the Gas Spring

Release the gas of the gas spring in the following cases.

-	When the gas spring needs to be separated from the robot, but the 2 axis cannot be operated, making it impossible to put the 2 axis at 90°
-	When required to transport the robot by air (The law states that air transport of machinery equipped with high-pressure equipment should be performed after depressurizing it.)


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
    <td class="tg-b001"><img src="../_assets/작은주의표시.png"> Caution</td>
    <td class="tg-cly1">If the gas is rapidly released, colored oil inside the spring may spurt out. Wear protective glasses, and carry out the releasing work slowly.</td>
  </tr>
</thead>
</table>


(1)	Remove the plug installed to the gas inlet of the gas spring.

(2)	Check whether the handle of the bleed valve ○P is closed (locked clockwise.)

(3)	Check whether the gas release pin of the marked part ○R is protruding. If it is protruding, turn the knob ○O counterclockwise to prevent this.

(4)	Turn the knob ○N of the pressure tester clockwise to completely connect it to the gas inlet

(5)	Turn the knob ○O clockwise and then stop turning it if the pointer of the pressure gauge ○T moves.(To avoid making the release pin ○R go inside excessively and damage the valve inside the gas spring, do not turn the knob ○O handle excessively.)

(6)	 Turn the bleed valve ○P counterclockwise slowly to completely release the gas.
Warning! Never look directly into the gas outlet hole.

(7)	Turn the knob ○O handle counterclockwise to retreat the release pin ○R. After that, turn the knob ○N of the pressure tester counterclockwise to separate it.

(8)	Connect the G1/8 plug to the gas spring.


![](../_assets/그림_9.4_가스스프링_gas_배출.png)

Figure 9.4 Releasing of the Gas of the Gas Spring# 9.4. Replacing (Separating and Assembling) the Gas Spring

When replacing the gas spring, replace the bearing assembled to the joint as well.
# 9.4.1. Separating the Gas Spring


You must keep the 2 axis at the posture as shown in Figure 8.1 while separating the gas spring.

In this posture, the compression force of the gas spring will be minimized so that it can be separated from the robot.

Even if the gas spring is separated from the manipulator, the compression force by the spring will be in a balanced state, so the risk factors in the separation process will be minimized. 

However, when required to separate the gas spring to dispose of it or repair its internal parts, if it is impossible to set the 2 axis at 90° because the 2 axis does not operate, remove the gas completely according to the procedures of “9.3 Releasing of the Gas of the Gas Spring.” 




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
    <td class="tg-0lax">-	Postures in which the gas spring must not be separated: Angles of the 2 axis other than 90˚<br>
-	(In the posture of the 2 axis at angles other than 90˚, the compression force of the gas spring will be excessive, so when the bolt of the hinge is loosened, the screw thread will be damaged by the pressure of the gas spring and the bolt will be thrown out, causing accidents involving people and damage to the equipment.)
<br>
<img src="../../_assets/그림_9.4.1_가스_스프링_분리_위험.png">
</td>
  </tr>
</thead>
</table>
# 9.4.2. Assembling the Gas Spring

When required to assemble the gas spring, you must put the 2 axis in the posture shown in Figure 8.1. In this posture, the compression force of the gas spring will be minimized so that it can be assembled on the robot. 

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
    <td class="tg-cly1">-	When assembling and disassembling the gas spring, fasten or dismantle the bolts by rotating the upper and lower bolts alternately at less than 45 degrees as shown in Figure 8.2 to prevent the hinge from being excessively tilted.<br>
-	Excessive tilting of the hinge will damage the bolts, and damaged bolts will damage even the tap of the frame, making it difficult to perform the disassembly and assembly work.<br>
-	The shape of each part, such as the hinge, may change without a notice.
</td>
  </tr>
</thead>
</table>





# 9.4.3. Technical Data of the Gas Spring


Table 9-2 Technical Data of the Gas Spring
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:middle}
.tg .tg-69va{background-color:#f8f8be;color:#000000;font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-69va">Classification</th>
    <th class="tg-69va">DATA</th>
    <th class="tg-69va">Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-amwm">Pressure medium</td>
    <td class="tg-baqh">Nitrogen gas / Hydraulic oil</td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-amwm">Stroke length</td>
    <td class="tg-baqh">160mm</td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-amwm">Operating temperature</td>
    <td class="tg-baqh">0 ℃ ~ 80 ℃</td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-amwm">Gas volume</td>
    <td class="tg-baqh">0.9 liter</td>
    <td class="tg-baqh"></td>
  </tr>
  <tr>
    <td class="tg-amwm">Maximum charging pressure</td>
    <td class="tg-baqh">130 bar</td>
    <td class="tg-baqh">Based on spring surface temperature of 20℃ </td>
  </tr>
  <tr>
    <td class="tg-amwm">Proper working pressure</td>
    <td class="tg-baqh">110 bar ~ 125 bar</td>
    <td class="tg-baqh">Maintenance target pressure<br>
 Based on spring surface temperature of 20℃ </td>
  </tr>
  <tr>
    <td class="tg-amwm">Minimum allowable pressure</td>
    <td class="tg-baqh">100 bar</td>
    <td class="tg-baqh">Based on spring surface temperature of 20℃ </td>
  </tr>
  <tr>
    <td class="tg-amwm">Weight</td>
    <td class="tg-baqh">About 14 kg</td>
    <td class="tg-baqh"></td>
  </tr>
</tbody>
</table>


※	For the pressure, refer to Table 9-1 Pressure for Each Gas Spring Surface Temperature – The Set Gas Pressure of “9.1. Checking of the Pressure of the Gas Spring.”

※	The minimum allowable pressure may change depending on the motor load of the robot.


# 9.4.4. Parts for Gas Spring Pressure Measuring and Gas Charging

Table 9-3 Parts for Gas Spring Pressure Measuring and Gas Charging
<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-baqh{text-align:center;vertical-align:middle}
.tg .tg-amwm{font-weight:bold;text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-amwm">Part NAME AND SPECIFICATION</th>
    <th class="tg-amwm">PART NO</th>
    <th class="tg-amwm">QUANTITY PER UNIT</th>
    <th class="tg-amwm">SHAPE</th>
    <th class="tg-amwm">SUPPLIED BY</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-baqh">GAS SPRING ASSY</td>
    <td class="tg-baqh">P7000000710<br>P7000000730</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh"><img src="../../_assets/표9-3_그림1.png"></td>
    <td class="tg-baqh">Hyundai Robotics<br>(OPTION)</td>
  </tr>
  <tr>
    <td class="tg-baqh">PRESSURE TESTER-1 (FOR MEASURING THE PRESSURE)</td>
    <td class="tg-baqh">R7900162380</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh"><img src="../../_assets/표9-3_그림2.png"></td>
    <td class="tg-baqh">Hyundai Robotics<br>(OPTION)</td>
  </tr>
  <tr>
    <td class="tg-baqh">REPLENISHING ARMATURE KIT-1
+ GAS BOOSTER KIT-1
1. FOR CHARGING THE GAS WHEN THE NITROGEN GAS BOMBE’S PRESSURE IS 150 BAR OR BELOW<br>
2. ITEM TO BE INCLUDED WHEN THE CUSTOMER ORDERS: GAS BOMBE CONNECTION PART SCREW SPECIFICATION
</td>
    <td class="tg-baqh">R7900164390<br>R7900162750</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh"><img src="../../_assets/표9-3_그림3.png"></td>
    <td class="tg-baqh">Hyundai Robotics<br>(OPTION)</td>
  </tr>
  <tr>
    <td class="tg-baqh">REPLENISHING ARMATURE KIT-1<br>
1. . FOR CHARGING THE GAS WHEN THE NITROGEN GAS BOMBE’S PRESSURE 
EXCEEDS 150 BAR
<br>
2. ITEM TO BE INCLUDED WHEN THE CUSTOMER ORDERS: GAS BOMBE CONNECTION PART SCREW SPECIFICATION
</td>
    <td class="tg-baqh">R7900164390</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh"><img src="../../_assets/표9-3_그림4.png"></td>
    <td class="tg-baqh">Hyundai Robotics<br>(OPTION)</td>
  </tr>
  <tr>
    <td class="tg-baqh">GAS BOOSTER KIT-1<br>
1. FOR INCREASING THE PRESSURE WHEN THE NITROGEN GAS BOMBE’S PRESSURE IS 150 BAR OR BELOW<br>
2. AIR INLET PLUG MALE : R1/4<br>
3. ITEM TO BE INCLUDED WHEN THE CUSTOMER ORDERS: GAS BOMBE CONNECTION PART SCREW SPECIFICATION
</td>
    <td class="tg-baqh">R7900162750</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh"><img src="../../_assets/표9-3_그림5.png"></td>
    <td class="tg-baqh">Hyundai Robotics<br>(OPTION)</td>
  </tr>
  <tr>
    <td class="tg-baqh">AIR HOSE AND QUICK COUPLING<br>(FOR SUPPLYING AIR)</td>
    <td class="tg-baqh">-</td>
    <td class="tg-baqh">1</td>
    <td class="tg-baqh"><img src="../../_assets/표9-3_그림6.png"></td>
    <td class="tg-baqh">CUSTOMER</td>
  </tr>
</tbody>
</table>
# 9.4.5. Gas Spring Protection Cover

<style type="text/css">
.tg  {border-collapse:collapse;border-spacing:0;}
.tg td{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  overflow:hidden;padding:10px 5px;word-break:normal;}
.tg th{border-color:black;border-style:solid;border-width:1px;font-family:Arial, sans-serif;font-size:14px;
  font-weight:normal;overflow:hidden;padding:10px 5px;word-break:normal;}
.tg .tg-wa1i{font-weight:bold;text-align:center;vertical-align:middle}
.tg .tg-nrix{text-align:center;vertical-align:middle}
</style>
<table class="tg">
<thead>
  <tr>
    <th class="tg-wa1i">Classification</th>
    <th class="tg-wa1i">Plastic cover</th>
    <th class="tg-wa1i">Remarks</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td class="tg-wa1i">Appearance</td>
    <td class="tg-nrix"><img src="../../_assets/표9-4_그림1.png"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Material</td>
    <td class="tg-nrix">PLASTIC(split type)</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Required to disassemble the gas spring
<br> when replacing the protection cover</td>
    <td class="tg-nrix">X</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">CLAMP 사양</td>
    <td class="tg-nrix">○ Small size : 12W x Φ54<br>○ Large size : 12W x Φ103<br>○ Wrench size : 8mm<br>○ Tightening torque : 60kg/㎠</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Images of clamps</td>
    <td class="tg-nrix"><img src="../../_assets/표9-4_그림2.png"></td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Time for replacement</td>
    <td class="tg-nrix">When damaged because of an external impact occurs</td>
    <td class="tg-nrix"></td>
  </tr>
  <tr>
    <td class="tg-wa1i">Precautions for assembling</td>
    <td class="tg-nrix">Assemble such that there is no gap in the split part.</td>
    <td class="tg-nrix"></td>
  </tr>
</tbody>
</table>


Wirings in the manipulator are branched for each unit, and a relevant connection diagram is shown for each. Please use them when checking or exchanging wirings.

![](../_assets/그림_10.1_본체_부품_배치.png)

Figure 10.1 Placement of Parts inside the Manipulator


![](../_assets/기내배선도_1.png)
![](../_assets/기내배선도_2.png)
![](../_assets/기내배선도_3.png)
![](../_assets/기내배선도_4.png)
![](../_assets/기내배선도_5.png)
![](../_assets/기내배선도_6.png)
![](../_assets/기내배선도_7.png)
![](../_assets/기내배선도_8.png)