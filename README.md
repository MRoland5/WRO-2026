<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
</head>
<body>

<h1>WRO Future Engineers 2026 - Error 404</h1>
<h2>Introduction To The Team</h2>
<ul>
<li>Hatala Dániel Electrical Engeneer student at VTS Subotica 2nd year</li>
<li>Német Dominik Mechatronics Engineer student at VTS Subotica 2nd year</li>
<li>Majoros Roland Mechatronics Engineer student at VTS Subotica 2nd year</li>
<li>With the base we had quite a few difficulties, for starters we did know we wanted to build a car thats reliable and a one we can be proud of. The 1st big problem we got into what will be our standard look a V shape a Cube we do more floors we all accunted those and came up with a little sketch</li>
<img width="400" height="600" [https://github.com/MRoland5/WRO-2026/blob/d4c010425c326278c10e56961478d99546dc7c18/Photos/image%20(1).png](https://github.com/MRoland5/WRO-2026/blob/main/Photos/image%20(1).png?raw=true) />

<h2>Project Overview</h2>
<p>
The robot was developed for the WRO Future Engineers category with a focus on stability, controllability, and efficient energy usage.
The final system is built around a <b>Raspberry Pi 4</b> as the main control unit, powered by a <b>VARTA 10000mAh battery pack</b>.
Locomotion is achieved using <b>N20 6V 30 RPM DC motors</b>.
</p>

<h2>System Architecture</h2>
<ul>
  <li>Controller: Raspberry Pi 4</li>
  <li>Motors: N20 DC Gear Motors (6V, 30 RPM)</li>
  <li>Power Supply: VARTA 10000mAh battery pack</li>
  <li>Chassis: 3D printed structural frame</li>
</ul>

<h2>Torque and Speed Selection Rationale</h2>
<p>
The selection of the N20 30 RPM motors was based on a trade-off between <b>torque and rotational speed</b>.
Initial calculations showed that higher RPM motors would reduce torque significantly, leading to instability under load,
especially during directional changes and surface friction variations.
</p>

<p>
The chosen configuration prioritizes:
</p>
<ul>
  <li>High torque for consistent movement under load</li>
  <li>Low RPM for precise control and smoother navigation</li>
  <li>Improved stability during turning maneuvers</li>
</ul>

<p>
This balance ensures that the robot maintains reliable traction while still achieving acceptable movement speed for competition tasks.
</p>

<h2>Design Iterations and Development Process</h2>

<h3>Initial Concept – LEGO Prototype</h3>
<p>
The first prototype was constructed using LEGO components to quickly validate mechanical concepts.
However, significant structural deformation occurred under load, particularly around the chassis center and power unit mounting points.
</p>
<h3>Second Iteration – Steel Frame</h3>
<p>
The next version utilized a laser-cut steel frame to improve rigidity.
While structural strength increased significantly, the system became overly heavy, resulting in reduced motor efficiency and higher current draw.
This negatively impacted battery life and acceleration performance.
</p>
<h3>Final Design – 3D Printed Chassis</h3>
<p>
The final iteration adopted a 3D printed chassis, optimized for both weight reduction and structural integrity.
This solution provided the best balance between stiffness, weight, and manufacturability.
</p>
<h2>Impact of Testing and Iteration</h2>
<p>
Each design iteration directly influenced both mechanical structure and system performance:
</p>

<ul>
  <li><b>LEGO phase:</b> Identified structural weakness and torsional instability</li>
  <li><b>Steel phase:</b> Improved rigidity but introduced excessive mass and energy inefficiency</li>
  <li><b>3D print phase:</b> Achieved optimal balance between weight reduction and structural durability</li>
</ul>

<p>
Through iterative testing, the final design significantly improved:
</p>
<ul>
  <li>Energy efficiency</li>
  <li>Directional stability</li>
  <li>Motor load distribution</li>
  <li>Overall maneuverability</li>
</ul>

<h2>Final System Evaluation</h2>
<p>
The final robot configuration demonstrates a balanced engineering approach where mechanical design, power efficiency, and control precision are optimized together.
The combination of Raspberry Pi control, N20 geared motors, and a lightweight 3D printed structure ensures consistent performance in competition scenarios.
</p>
</body>
</html>
