---
layout: page
title: Projects
subtitle: Here is what I have done so far...
---
### Projects

**Ongoing Projects**
* [Fast Fourier Transform (FFT) Implementation with Software and Hardware, 2023.09 - 2023.12, Pre-capstone Project, KwangWoon University]()

**Completed Projects**
* [Understanding Data Conversion by implementing Delta Sigma and Flash Analog to Digital Convertors, 2023.09 - 2023.12, Term Project, KwangWoon University]()
* [Analog Computer, 2022.03 - 2022.06, 전자회로실험1 Term Project, KwangWoon University]()
* [Development of a Simple Graphics Card and Sound Card, using DE1 - SoC FPGA Board, 2019.09 - 2019.12, 기초전자실험 Term Project, KwangWoon University]()
* [Development of a Calculator using C++ and MFC, 2019.03 - 2019.06, 소프트웨어설계 Term Project, KwangWoon University]()
* [LASER Communication, 2019.03 - 2019.06, 기초전자실험 Term Project, KwangWoon University]()
* [Handicapped and IoT (Canes for the Challenged), 2018.10 - 2018.12, 공학설계과제, KwangWoon University](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=kwceie&logNo=221409352534)

---
### Contest
* [2018년도 공학설계입문, 2018.11.29, 최우수 수상](https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=kwceie&logNo=221409352534)

---

### Project Details
### Understanding Data Conversion by implementing Delta Sigma and Flash Analog to Digital Convertors

![PCM Boards](/assets/images/mul.png)


### Analog Computer

![Multiplication Module](/assets/images/mul.png)


> Multiplication Module


![DUT](/assets/images/mul2.png)


> Multiplication Module Under Test


![Analog Computer Final Product](/assets/images/mul_f.png)


> Analog Computer Final Product


* Project Name: Analog Computer

* Main Function: Operates Arithmetic operations using only analog circuits.

* Detail: This device is designed to operate addition, subtraction, multiplication and division. The operation can withstand up to 12 Volts. This project was done to understand the basics of Operational amplifiers and how computation was done before the digital age emerged.

### Development of a Simple Graphics Card and Sound Card, using DE1 - SoC FPGA Board

![System Simulation](/assets/images/fpga.png)


> System Simulation


![System Integration Test](/assets/images/fpga2.png)


> System Integration Test


![Image Test](/assets/images/fpga_f.gif)


> Image Test, MAGIC!


* Project Name: Making a Simple Graphic Card & a Simple Sound Card

* Main Function: Graphic Card Part (electron65 part) A digital signal from the Arduino Uno is sent throught the DE1-SoC FPGA Board. In the process of being sent, it is sent by SPI protocol. From the inside of the FPGA board, the signal is set to coordinate with a specific timmings(Horizontal, Vertical timming). The digital signal is then stored in the DPRAM. In the meantime the data from the DPRAM is transfered through the DAC(Digitial to Analog Converter), changing the signal from digital to analog. From there the data goes through the VGA cable. The data we made from the Arduino Uno finally prints on the monitor.

Detail: Outputs signals through a monitor and a speaker from an Arduino Uno or an SD card.

### LASER Communication


![Laser Communication Test](/assets/images/laser2.png)


> Laser Communication Test


![Laser Communication Final Product](/assets/images/laser_f.png)


> Laser Communication Final Product


![Laser Communication!](/assets/images/laser.gif)


> Laser Communication!


* Project Name: Laser Communication

* Main function: Communicates using laser pulses.

* Detail: A user will type a character or a string. The data is converted into binary numbers. Each binary number is matched to "On" or "Off" (ex. 1 - ON, 0 - OFF). The laser module then blinks at each data. On the other side of the laser would be a Photolight sensor. The senser takes the light being sent. The "On" and "Off" is then again matched to each binary number. Finally the binary number is converted back and printed on the screen.

### Handicapped and IoT (Canes for the Challenged)


![Cane Device](/assets/images/cane.png)


> Cane Device


![Cane Device Final Product](/assets/images/cane_f.png)


> Cane Device Final Product


* Project Name: Handicapped & IoT Technology

* Main Function: Helps people who have trouble seeing or are blinded, find there way anywhere and anytime by directing them through sound signals.

* Detail: Bluetooth modules that are installed in everyday items or facilities such as phones, hospitals or even traffiic lights can communicate with the challenged, especially through the cane. The user first makes a interaction (ex. taps the button 2 times) with the cane. The corresponding reponse from the challenged will be sent to the current connected device (ex. traffic light). The device will then respond with an answer sent back to the cane. The respond then will be read in voice, giving a possibly current location, direction or other cases which correspond to the users demand.

---
