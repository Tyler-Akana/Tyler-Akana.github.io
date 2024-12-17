---
layout: default
title: Home
---

# **Tyler's Portfolio**
#### **Prominent Skills**: CAD, HVAC, Pneumatics, Prototyping Design, Data Analysis, Technical Communication  

<style>
  body {
    max-width: 1200px;
    margin: 0 auto;
  }
  img {
    max-width: 100%;
    height: auto;
  }
  .wide-content {
    display: flex;
    justify-content: center;
    flex-direction: column;
  }
</style>

---

## **Education**
### **BS, Mechanical Engineering** | *Washington State University* (December 2024)

---

## **Work Experience**

### **Undergraduate Researcher @ Washington State University**
- **Project Goal**: To design a set of temperature controlled open lid boxes for study of climate change induced heatwaves on potato growth, maintaining a temperature above ambient of at least 5 degrees celsius.
- **Solution Overview**: Our solution combines off the shelf componnents such as dryer heating elements, and centrifugal duct fans along with an arduino based controls system to regulate voltage to the heaters, and thus the temperature of the box. We also explored an air curtain system to keep heated air from escaping, and reducing the cooling effect of wind but ultimately left the system unfinished due to time constraints.

<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/img/Early Prototype Box 2.jpg" alt="Early Prototype" style="width: 80%;">
  <p>Early Prototype</p>
</div>

<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/img/Controls Box.jpg" alt="Final Design" style="width: 80%;">
  <p>Controls System (not including servo on variac for voltage control)</p>
</div>

<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/img/early deployment.jpg" alt="Final Design" style="width: 80%;">
  <p>Final Design</p>
</div>

### **Field-Deployed Problems & Solutions**:
#### Our final design was deployed in May of 2024 in a field 2hrs out from W.S.U. in Othello, WA. I stayed over a summer to continue development and provide maintenance on the design. 
#### I focused my efforts on increasing reliability of power delivery and sensor systems, and decreasing variability in temperature distribution. While I focused on those three problems I also provided maintenence and fixes for other problems such as electrical faults, and water ingress. With each problem I faced I was able to respond with a unique solution, off the shelf part, or fix in a timely matter.

<div style="display: flex; flex-direction: column;">
  <div style="display: flex; justify-content: space-between; margin-bottom: 20px;">
    <div style="text-align: center; width: 45%;">
      <img src="assets/img/Variac Solder joints.jpg" alt="High Current Problem" style="width: 100%;">
      <p><strong>Problem:</strong> High current draw heats up solder joints, melting and disconnecting internal wiring or blowing 20A fuse.</p>
    </div>
    <div style="text-align: center; width: 45%;">
      <img src="assets/img/30amp Variac.jpg" alt="High Current Solution" style="width: 100%;">
      <p><strong>Solution:</strong> New power supply supports higher continuous and peak current draw.</p>
    </div>
  </div>
  <div style="display: flex; justify-content: space-between; margin-bottom: 20px;">
    <div style="text-align: center; width: 45%;">
      <img src="assets/img/TC testing.jpg" alt="TC Sensors Problem" style="width: 100%;">
      <p><strong>Problem:</strong> Thermocouple sensors in field reported erroneous readings. After testing several factors while sensors are submerged in an ice bath (0C), polarity issues and heat on the breakout board caused inaccuracies.</p>
    </div>
    <div style="text-align: center; width: 45%;">
      <img src="assets/img/RTD Logger.jpg" alt="TC Sensors Solution" style="width: 100%;">
      <p><strong>Solution:</strong> RTD Sensors performed more accurately than TC sensors within our temperature range, enabling smoother voltage control in the algorithm.</p>
    </div>
  </div>
  <div style="display: flex; justify-content: space-between;">
    <div style="text-align: center; width: 45%;">
      <img src="assets/img/Wilting picture.jpg" alt="Temp Distribution Problem" style="width: 100%;">
      <p><strong>Problem:</strong> Uneven temperature distribution observed in testing. Wilting foliage directly in front of the inlet visually indicated this issue.</p>
    </div>
    <div style="text-align: center; width: 45%;">
      <img src="assets/img/PVC System.jpg" alt="Temp Distribution Solution" style="width: 100%;">
      <p><strong>Solution:</strong> A redesigned temperature distribution system directs airflow through PVC pipes, ensuring even temperature across the setup.</p>
    </div>
  </div>
</div>

### Research Outcomes:

<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/Plots-Data/Research Project/long term plot.JPG" alt="Long term plot" style="width: 100%;">
  <p>Heat box was installed and turned on 70 days after planting, and remained on until day 87. </p>
</div>

<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/Plots-Data/Research Project/Long term data.JPG" alt="Long term data summary" style="width: 100%;">
  <p>Results show temperature value above ambient, heat box was able to maintain at least 5C above ambient average. New RTD sensors were not installed at this time meaning controls system was set to a constant voltage.</p>
</div>

---

## **Kenworth-PACCAR Senior Design Project**
#### **Problem**  
-W990 Hood Struts are sized inaccurately, not providing enough assistance for initial hood lift-off. Struts were originally based on simulation solutions which are reported to be innacurate. 

#### **Solution**  
-Utilize pneumatic cylinders to push hood open and closed, and measure force at strut locations using load cells in line with the cylinder. This solution gives an expirimental value that can be used to size a spring pack for use in a better sized W990 mechanical strut.

#### **System Diagrams**
<div style="display: flex; justify-content: space-between;">
  <div style="text-align: center; width: 45%;">
    <img src="assets/img/Kenworth/Controls.png" alt="Controls Schematic" style="width: 100%;">
    <p><strong>Controls System:</strong> Allows control of pneumatics and processes data from load cells.</p>
    <p><strong>Main components:<strong> Futek load cells, load cell amplifiers, MPU 6050, 2ch relay, Arduino Uno, and Solenoids.</p>
  </div>
  <div style="text-align: center; width: 45%;">
    <img src="assets/img/Kenworth/Pneumatic.png" alt="Pneumatic Schematic" style="width: 100%;">
    <p><strong>Pneumatic System:</strong> Configured to control airflow to dual-action cylinders.</p>
    <p><strong>Main components:<strong> 5/3 way closed center valve, inline flow regulators, dual action cylinders, and exhaust flow restrictors.</p>  
  </div>
</div>

### **Cylinder Components**
<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/img/Kenworth/ActuatorAssembly.JPG" alt="ActuatorAssembly" style="width: 80%;">
  <p>Components adapt cylinder and load cell to eachother, and strut mounts.</p>
</div>

### **Test Rig**
<div style="text-align: center; margin-bottom: 20px;">
  <video width="80%" controls>
    <source src="assets/img/Kenworth/TestRig.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Rig built to mimic position of strut mounting points for testing outside of Kenworth (sped up 4x due to lower flow rate in test rig setup)</p>
</div>

#### **Controls and Pneumatic systems**
<div style="display: flex; justify-content: space-between;">
  <div style="text-align: center; width: 45%;">
    <img src="assets/img/Kenworth/Controls system.jpg" alt="Controls System" style="width: 100%;">
    <p>Controls system with housing, and strain releif</p>
  </div>
  <div style="text-align: center; width: 45%;">
    <img src="assets/img/Kenworth/PneumaticSystem.jpg" alt="Pneumatic System" style="width: 100%;">
    <p>Pneumatic system before control system was assembled</p>
  </div>
</div>

#### **Final Validation**
<div style="text-align: center; margin-bottom: 20px;">
  <video width="80%" controls>
    <source src="assets/img/Kenworth/Extension.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Hood Extension</p>
</div>

<div style="text-align: center; margin-bottom: 20px;">
  <video width="80%" controls>
    <source src="assets/img/Kenworth/Retraction.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Hood Retraction</p>
</div>
### **Load cell and MPU Data**
<div style="display: flex; justify-content: space-between;">
  <div style="text-align: center; width: 45%;">
    <img src="assets/img/Kenworth/Extension.png" alt="Extension Graph" style="width: 100%;">
    <p>Extension force graph</p>
  </div>
  <div style="text-align: center; width: 45%;">
    <img src="assets/img/Kenworth/Retraction.png" alt="Retraction Graph" style="width: 100%;">
    <p>Retraction force graph</p>
  </div>
</div>
---

## **Certifications**
- [List any certifications here]

---

[View My GitHub Projects](https://github.com/yourusername)



