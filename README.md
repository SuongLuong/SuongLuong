
# TCS34725 RGB Color Sensor & the Raspberry Pi
## TABLE OF CONTENT
I.   [Introduction](#i-introduction)

II.  [Thing used in this Project](#ii-things-used-in-this-project)

III. [Project Schedule](#iii-overheat-sensor-schedule)

IV.  [Assembly Code](#iv-assembly-code)

V.   [Printed Circuit Board PCB and Soldering](#v-printed-circuit-board-pcb-and-soldering)

VI.  [Power Up and Unit Testing](#vi-power-up-and-unit-testing)

VII. [Production Testing](#vii-production-testing)

### I. Introduction
The TCS34725 RGB color sensor board can be used to detect the color of objects. It works with the Raspberry Pi using an I2C connection.  When used to detect the color of things, the led should be on and the object should be put on the top of the enclosure closely. The theory of sensing the color of objects is Reflective Sensing Theory as below.

![d](https://user-images.githubusercontent.com/43184936/49826532-1f102780-fd55-11e8-8695-47e925f3c31f.png)
(retrieved from home.roboticlab)

An System Diagram for the Project (Combination of hardware, software and database)



### II. Things used in this project
- The TCS34725 Color Sensor
- Rasberry Pi 3 B+ module
- 6-pin Headers
- 2x20-pin Header
- Essential Softwares: Remote Desktop Connection / VNC Viewer, Fritzing(PCB Designing), CorelDraw(Enclosure Design), Product Printer in Prototype Lab.

The TCS3472 device provides a digital return of red, green, blue (RGB), and clear light sensing values. An IR blocking filter, integrated on-chip and localized to the color sensing photodiodes, allows color measurements to be made accurately. The TCS3472 an ideal color sensor solution for use under varying lighting conditions and through attenuating materials. 

![sensor](https://user-images.githubusercontent.com/43184936/49824796-e2dac800-fd50-11e8-8d7f-00377f148ccd.jpg)

![raspberry](https://user-images.githubusercontent.com/43184936/49824862-0a319500-fd51-11e8-9716-404b64f69bb5.jpg)

![2x20pins](https://user-images.githubusercontent.com/43184936/49826920-12d89a00-fd56-11e8-876b-23ddb2447342.jpeg)

![6pinsstackableheader](https://user-images.githubusercontent.com/43184936/49826921-13713080-fd56-11e8-9ddc-2c08ae6f2c13.jpg)

- Bill of Materials/Budgets: Total for hardware components. More detail <a href="https://github.com/SuongLuong/Portable-Color-Dectection-Device/files/2669320/Buget317.xlsx">Budget</a>

![image](https://user-images.githubusercontent.com/43184936/49828283-7dd7a000-fd59-11e8-9aae-924e75a76793.png)


### III. Project Schedule

The schedule for my whole project. 

![image](https://user-images.githubusercontent.com/43184936/49830020-06f0d600-fd5e-11e8-9068-03cf894a4bb1.png)

This project can be done in about 1 week time if all components are ready. The ordering process may be longer if you order outside Canada. Some websites to purchase: <a href="https://elmwoodelectronics.ca/">ElmWoodElectronic</a>

### IV. Assembly Code

### V. Printed Circuit Board PCB and Soldering
- The Breadboard view of the connection:

![image](https://user-images.githubusercontent.com/43184936/49830355-ee34f000-fd5e-11e8-82f9-a9ec99e9e771.png)

- The design for PCB on Fritzing: <a href="https://github.com/SuongLuong/Portable-Color-Dectection-Device/files/2669423/gerberfiles.zip">FritzingGerberFiles</a>

![image](https://user-images.githubusercontent.com/43184936/49830428-250b0600-fd5f-11e8-8b99-ff5a83d2960c.png)

- Soldering Process: By using IntelliHeat in the Lab, it may take 1 hour. Be carefull with the PCB sides to be connected properly.

![image](https://user-images.githubusercontent.com/43184936/49830749-107b3d80-fd60-11e8-8114-dd1dacf86bb6.png)

![solder](https://user-images.githubusercontent.com/43184936/49830819-3ef91880-fd60-11e8-87f6-ffeedf95c4a3.jpeg)

![48100858-f8f5e580-e1f2-11e8-9daf-02c232f5b149](https://user-images.githubusercontent.com/43184936/49830858-618b3180-fd60-11e8-88bf-d1194a70eeca.jpeg)

#### Enclosure (Case for the whole hardware]

For this part, we need to work on CorelDraw. All the hardware dimensions should be measured carefully to fit the case. The default file for RPI case can be found on CENG317 folder. We need to modify this case and send the design files to Prototype Lab (prototypelab@humber.ca) to get the case. This case can be laser cut just in 5 minitues but you need to wait in line for other people.

My design file in the same directory with the name Pi2CaseX6.cdr

The complete product:

![image](https://user-images.githubusercontent.com/43184936/49831439-e62a7f80-fd61-11e8-8572-3d28de42fa03.png)

![image](https://user-images.githubusercontent.com/43184936/49831448-eb87ca00-fd61-11e8-98b0-95c825fcbdde.png)
      
### VI. Power Up and Unit Testing
- Power Up: Through Ethernet cable, and Remote Desktop Control, you can connect and check your I2C address.

### VII. Production Testing
