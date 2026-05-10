<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>WRO Future Engineers Robot Documentation</title>
</head>
<body>

<h1>WRO Future Engineers Robot – Design & Development Report</h1>

<h2>1. Project Overview</h2>
<p>
The robot was developed for the WRO Future Engineers category with a focus on stability, controllability, and efficient energy usage.
The final system is built around a <b>Raspberry Pi 4</b> as the main control unit, powered by a <b>VARTA 10000mAh battery pack</b>.
Locomotion is achieved using <b>N20 6V 30 RPM DC motors</b>.
</p>

<h2>2. System Architecture</h2>
<ul>
  <li>Controller: Raspberry Pi 4</li>
  <li>Motors: N20 DC Gear Motors (6V, 30 RPM)</li>
  <li>Power Supply: VARTA 10000mAh battery pack</li>
  <li>Chassis: 3D printed structural frame</li>
</ul>

<h2>3. Torque and Speed Selection Rationale</h2>
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

<h2>4. Design Iterations and Development Process</h2>

<h3>4.1 Initial Concept – LEGO Prototype</h3>
<p>
The first prototype was constructed using LEGO components to quickly validate mechanical concepts.
However, significant structural deformation occurred under load, particularly around the chassis center and power unit mounting points.
</p>

<img src="https://example.com/lego_prototype.jpg" alt="LEGO prototype" width="400">

<h3>4.2 Second Iteration – Steel Frame</h3>
<p>
The next version utilized a laser-cut steel frame to improve rigidity.
While structural strength increased significantly, the system became overly heavy, resulting in reduced motor efficiency and higher current draw.
This negatively impacted battery life and acceleration performance.
</p>

<img src="https://example.com/steel_frame.jpg" alt="Steel frame prototype" width="400">

<h3>4.3 Final Design – 3D Printed Chassis</h3>
<p>
The final iteration adopted a 3D printed chassis, optimized for both weight reduction and structural integrity.
This solution provided the best balance between stiffness, weight, and manufacturability.
</p>

<img src="https://example.com/3d_printed_robot.jpg" alt="Final 3D printed robot" width="400">

<h2>5. Impact of Testing and Iteration</h2>
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

<h2>6. Final System Evaluation</h2>
<p>
The final robot configuration demonstrates a balanced engineering approach where mechanical design, power efficiency, and control precision are optimized together.
The combination of Raspberry Pi control, N20 geared motors, and a lightweight 3D printed structure ensures consistent performance in competition scenarios.
</p>

<h2>7. Notes</h2>
<p>
Further improvements under consideration include closed-loop motor control (PID), optimized wheel traction materials, and weight distribution refinement.
</p>

</body>
</html>
