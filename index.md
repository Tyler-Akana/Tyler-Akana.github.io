---
layout: default
title: Home
---

# **Tyler's Portfolio**
#### **Prominent Skills**: CAD, HVAC, Pneumatics, Controls systems, Prototyping Design, Data Analysis and simulation, Load bearing assemblies, Cross-Functional Communication 

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
  .content-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 20px;
  }
  .content-column {
    text-align: center;
    width: 48%;
  }
</style>

---

## **Education**
### **BS, Mechanical Engineering** | *Washington State University* (December 2024)

---

## **Work Experience**

### **Undergraduate Researcher @ Washington State University** | Jan 2024 - Feb 2025
#### **Project Goal**: 
  To design a set of temperature-controlled open lid boxes for the study of climate change-induced heatwaves on potato growth maintiaing at least 5C above ambient.
  
#### **Solution Overview**:
  Combined dryer heating elements, variacs, centrifugal duct fans, and Arduino-controlled systems to adjust variac voltage to heating elements and maintain temperature.

<div class="wide-content">
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="assets/img/Early Prototype Box 2.jpg" alt="Early Prototype">
    <p>Early Prototype</p>
  </div>
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="assets/img/Controls Box.jpg" alt="Controls System">
    <p>Controls System (excluding servo for variac voltage control)</p>
  </div>
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="assets/img/early deployment.jpg" alt="Final Design">
    <p>Final Design</p>
  </div>
</div>

### **Field-Deployed Problems & Solutions**
#### Our final design was deployed in May of 2024 in a field 2hrs out from W.S.U. in Othello, WA. I stayed over a summer to continue development and provide maintenance on the design. 
#### I focused my efforts on increasing reliability of power delivery and sensor systems, and decreasing variability in temperature distribution. While I focused on those three problems I also provided maintenence and fixes for other problems such as electrical faults, and water ingress. With each problem I faced I was able to respond with a unique solution, off the shelf part, or fix in a timely matter.
<div class="wide-content">
  <div class="content-row">
    <div class="content-column">
      <img src="assets/img/Variac Solder joints.jpg" alt="High Current Problem">
      <p><strong>Problem:</strong> High current draw caused solder joints to overheat and disconnect wiring.</p>
    </div>
    <div class="content-column">
      <img src="assets/img/30amp Variac.jpg" alt="High Current Solution">
      <p><strong>Solution:</strong> New power supply supports higher peak and continuous current draw.</p>
    </div>
  </div>

  <div class="content-row">
    <div class="content-column">
      <img src="assets/img/TC testing.jpg" alt="TC Sensors Problem">
      <p><strong>Problem:</strong> Thermocouples reported erroneous readings due to polarity issues and thermal effects on breakout board.</p>
    </div>
    <div class="content-column">
      <img src="assets/img/RTD Logger.jpg" alt="TC Sensors Solution">
      <p><strong>Solution:</strong> RTD sensors provided accurate readings, enabling better voltage control.</p>
    </div>
  </div>

  <div class="content-row">
    <div class="content-column">
      <img src="assets/img/Wilting picture.jpg" alt="Temp Distribution Problem">
      <p><strong>Problem:</strong> Uneven temperature distribution visually identified by wilting foliage.</p>
    </div>
    <div class="content-column">
      <img src="assets/img/PVC System.jpg" alt="Temp Distribution Solution">
      <p><strong>Solution:</strong> Redesigned airflow system using PVC pipes ensured even temperature.</p>
    </div>
  </div>
</div>

### **Research Outcomes**
<div class="wide-content">
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="assets/Plots-Data/Research Project/long term plot.JPG" alt="Long term plot">
    <p>Heat box was activated 70 days after planting and remained operational until day 87.</p>
  </div>
  <div style="text-align: center; margin-bottom: 20px;">
    <img src="assets/Plots-Data/Research Project/Long term data.JPG" alt="Long term data summary">
    <p>Maintained at least 5°C above ambient average temperature; RTD sensors were pending installation.</p>
  </div>
   <div style="text-align: center; margin-bottom: 20px;">
    <img src="assets/img/Study Presentation.jpg" alt="Presentation Picture">
    <p>Potato field day presentation at WSU Othello research unit(2024)</p>
  </div>
</div>

---

## **Kenworth-PACCAR Senior Design Project** | Aug - Dec 2024
#### **Problem**  
W990 Hood Struts are sized inaccurately, not providing enough assistance for initial hood lift-off. Struts were originally based on simulation solutions, which are reported to be inaccurate. 

#### **Solution**  
Utilize two pneumatic cylinders to open and close the hood in place of the mechanical struts, simultaneously measuring force at strut locations using load cells attached to the cylinders. This solution outputs force and hood angle data from the arduino system to a python program for post processing, and graphical representation. The processed data is stored in a .csv file and can be used to correctly size a W990 strut. Alternativley the pneumatic cylinders can replace the struts themselves eliminating difficultly with opening and closing the hood entirley.

#### **System Diagrams**
<div class="content-row">
  <div class="content-column">
    <img src="assets/img/Kenworth/Controls.png" alt="Controls Schematic">
    <p><strong>Controls System:</strong> Controls solenoids on main valve using relays, and gathers data from load cells.</p>
    <p><strong>Main Components:</strong> Futek load cells, load cell amplifiers, Arduino Uno, Adafruit MPU 6050, 2CH relay, and valve solenoids.</p>
  </div>
  <div class="content-column">
    <img src="assets/img/Kenworth/Pneumatic.png" alt="Pneumatic Schematic">
    <p><strong>Pneumatic System:</strong> Configures airflow to dual-action cylinders.</p>
    <p><strong>Main Components:</strong> 5/3 way closed-center valve, flow restrictors, dual-action cylinders, and exhaust flow restrictors.</p>
  </div>
</div>

### **Cylinder Components**
<div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/img/Kenworth/ActuatorAssembly.JPG" alt="Actuator Assembly">
  <p>Yellow parts designed in CAD for connecting the load cell, cylinder, and swivel joints together.</p>
</div>
### **Electrical Housing**

<div class="content-row">
    <div class="content-column">
      <img src="assets/img/Kenworth/systemhousing.gif" alt="system housing cad">
      <p>Houses electrical components and provides holes for cable management and ziptie strain relief on cable connections.</p>
    </div>
    <div class="content-column">
      <img src="assets/img/Kenworth/Controls system.jpg" alt="picture of system housing">
      <p>Picture of components mounted in compact housing.</p>
    </div>
  </div>

### **Test Rig**
<div style="text-align: center; margin-bottom: 20px;">
  <video width="80%" controls muted>
    <source src="assets/img/Kenworth/TestRig.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Test rig replicating strut mounting positions, allowing testing without access to a W990 truck (sped up 4x).</p>
  <p>System "walks" due to inaccuracy in hole position on wood frame, PSI is heavily reduced due to weaker wood structure used</p>
</div>

### **Final Validation**
<div style="text-align: center; margin-bottom: 20px;">
  <video width="80%" controls muted>
    <source src="assets/img/Kenworth/Extension.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Hood Extension</p>
  <p>Chassis and hood mounts on truck are positioned symetrically eliminating "walking", system operating at designed 100-120PSI speeding up actuator motion.</p>
</div>
<div style="text-align: center; margin-bottom: 20px;">
  <video width="80%" controls muted>
    <source src="assets/img/Kenworth/Retraction.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <p>Hood Retraction</p>
</div>

### **Data From Final Tests**
<div class="content-row">
  <div class="content-column">
    <img src="assets/img/Kenworth/Extension.png" alt="Extension Graph">
    <p>Extension Force Graph</p>
  </div>
  <div class="content-column">
    <img src="assets/img/Kenworth/Retraction.png" alt="Retraction Graph">
    <p>Retraction Force Graph</p>
  </div>
</div>

---

## **Certifications**
### Engineer In Training (EIT)
  <div style="text-align: center; margin-bottom: 20px;">
  <img src="assets/EIT.jpg" alt="EIT license">
  <p>*Address removed from certificate*</p>
</div>

---


