# Electrical Engineering Student @ UIUC


## WORK EXPERIENCE
**KAUTEX TEXTRON - Manufacturing Engineering Intern (May 2024-Present)**

- Automated parameter logging system of Siemens PLCs using ThingWorx IIoT platform allowing for real-time data visualization and monitoring of connected devices and sensors
- Integrated OPC UA communication protocol between Beckhoff PLC and eWON Flexy router to develop an HMI to display sensor data of welding machines
- Troubleshot Ladder Diagram (LD) of integrated camera sensor on blow-molding machines to recognize scrapped gas tanks leading to 25% decrease in cycle time

*Skills: PLC Programming, ThingWorx, Siemens TIA Portal, Industrial Robotics, Ladder Logic, Sensor Integration, HMI Configuration, Automation, Electrical Wiring*

![Kautex Textron](/img/Kautex_Textron.png)

## RESEARCH EXPERIENCE

**PROMOTING UNDERGRADUATE RESEARCH IN ENGINEERING (PURE) - Robotics/Acoustics Researcher (January 2024-Present)**

- Developed stepper motor control scheme for automated acoustic sensor-source positioning system using ROS2 and Raspberry Pi resulting in precise motion trajectories
- Integrated acoustic sensor to analyze noise produced by system in operation allowing for optimized orientation of motors to minimize audio interference
- Utilized Python to program communication over CAN bus to robotics components enabling motion synchronization
- Simulated testing of “SpiderBot” in virtual environment using Gazebo physics engine 

*Skills: ROS2, Python, Gazebo, CAN, Motor Control, Electrical Wiring, Raspberry Pi, Simulation*

![PURE Research Poster](/img/PURE_Research_Poster.png)
       ***PURE Research Poster for 2024 Symposium***

## PROJECTS

**PURE TONE DETECTOR**
- Designed LED display that shines light according to sound frequency input allowing for pitch visualization
- Developed band-pass filter bank to process sound frequencies through continuous analog signal processing testing
- Incorporated filtering and signal averaging techniques to minimize noise improving pitch detection accuracy

![Filter Design](/img/Filter.png)


***Basic design of low-pass filter***

The low-pass filter frequency cutoff is calculated according to the RC values which follow a specific formula. The filter amplifies the input frequency signal the greatest if the signal is closest to the target frequency set by the filter.

![FRA](/img/FRA.png)


***Frequency-response graph of filter corresponding to C4 note (261.63 Hz)***

The frequency-response graph displays the peak of the blue curve which corresponds to the band-pass filter frequency cutoff.

![Peak Hold](/img/Peak_Hold.png)


***Peak hold detector which captures the peak of the input frequencies***

The peak hold detector holds the peak of the incoming frequency wave. It converts the analog signal into a DC signal which the comparator works with more easily.

![Compare](/img/Comparator_Mux.png)


***Comparator mux compares frequencies to determine which frequency is closest to the input frequency***

The comparator mux compares the DC signals corresponding to each respective filter. The filter that corresponds the closest to the input frequency should be the one that makes it through the mux.

[PURE TONE DETECTOR PROJECT: 10-PAGE FINAL REPORT (LINK)](https://docs.google.com/document/d/1KftHK9rTrtopyynFVfxw2QYx5-WAYjdU_OKWd9vxZMs/edit)

*Skills: Signal Processing, Circuit Design, Filter Design, Oscilloscope Testing, FRA Analysis*


**ARDUINO SALINITY CONDUCTIVITY PROBE**
- Designed a conductivity probe utilizing Arduino and C++ to analyze the NaCl concentrations of various water samples with over 90% accuracy
- Utilized LCD screen to display salt concentration data and developed calculations to find voltage produced by probe

![Probe](/img/Probe.png)

[LINK TO ARDUINO CODE](https://github.com/akad88/ArduinoSalinityProbe)

*Skills: Arduino, C++, Probe Design, Salinity Analysis, Circuit Design*

**ESP32 THERMOMETER**
- Interfaced ESP32 with AD8495 Thermocouple Amplifier to measure and display temperature of various room settings
- Developed separate web server to display temperature and voltage data with real-time readings

[LINK TO ESP32 AND WEB SERVER CODE](https://github.com/akad88/ESP32_Thermometer)

*Skills: ESP32, Sensor Configuration, Web Server Configuration, HTML*

**MOTION DETECT**
- Designed an algorithm to detect motion by comparing consecutive frames through applied blurs and grayscales
- Developed a graphic rectangle that is placed on the object in motion

[LINK TO MOTION DETECT CODE](https://github.com/akad88/MotionDetect)

*Skills: Computer Vision, OpenCV, Python*






