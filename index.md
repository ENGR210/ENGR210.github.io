
# Welcome to ENGR 210 ( CSCI B441 )

Spring 2021 

This course provides a strong foundation for modern digital system design using hardware description languages. We start with basics of digital electronics and learn how digital gates are used to build large digital systems. We will practice modern digital system design by using state of the art software tools and implementation of the digital systems on a programmable hardware platform.  At the end of the course, students will be familiar with modern approach for designing digital systems, using hardware description languages along with an appropriate methodology.

## Quick Links

### [Syllabus](syllabus.md)

### [Lecture Slides](http://github.com/engr210/lecture_slides)

### [Downloads](http://github.com/engr210/downloads) 

### [Autograder](https://autograder.sice.indiana.edu) 

### [Canvas](https://iu.instructure.com/courses/1947790) _(registered students only)_

### Zoom _(registered students only)_

 - [Lectures](https://iu.zoom.us/j/86581937943) 

 - [Labs/Office Hours](https://iu.zoom.us/j/89702983096)

### [Slack](https://engr210-sp21.slack.com)

### [Remote Setup](https://uisapp2.iu.edu/confluence-prd/pages/viewpage.action?pageId=280461906)
<!--
[RED Desktop](https://docs.google.com/document/d/1GuOK0B6Irj_u6LjxMiwTBXgFvxtb-kuTXEFyj7-wQYI)
-->

## Projects

<!-- [P0 - Vivado
Tutorial](https://docs.google.com/document/d/1ydtvsCJaGSUWNMd3byvegsMfa6kRY8q1nOXQNVc5FVE)
-->

[P0 - Logic Gates](https://docs.google.com/document/d/1OZPhRJoNW6variLEV1iyCQ5HWxGvJrfiC3c3eMZx8vo)

[P1 - Demultiplexer](https://docs.google.com/document/d/1o02Y2rexq2IHROQaUYS6GD_TwUbfTaikeP8ysp6FJi8)

[P2 - Arithmetic Logic Unit](https://docs.google.com/document/d/1uhQR3LDZLIDAheTqNy58HJ456uEFfEh4IH7j1ZReyHM/edit?usp=sharing)

<!-- [P3 - Countdown
Timer](https://docs.google.com/document/d/1HnWBiIqMQZvTv-P2DLUMM38fX2hg8FhBwA005HwC-YI/edit?usp=sharing)
-->
[P3 - Saturating Counter](https://docs.google.com/document/d/1JLgk0VguSrih_h3BsMyMtInTJ4Qrl--Hv2jkxK4chZw)

[P4 - Elevator Control](https://docs.google.com/document/d/1IdqlRf4rqOpv0cBeurJ29rpMXwudnfIx8i1Z8IPmqxI/edit?usp=sharing)

[P5 - Raspberry Pi Setup](P5.md)

<!--
[PX - UART](https://docs.google.com/document/d/1dxm55Ct0wDpdce9y02u2D1DiFJ1YpZUdxzTfeGLi05A/edit?usp=sharing)

[PY - Postfix Calculator](https://docs.google.com/document/d/1ApDEDIPBYUmE_dggMogTmvb7Bb1qxodMbxjTzoPfIqs/edit?usp=sharing)
-->

## Course Schedule

### Computer Engineering Introduction

| Weekly Focus          | Monday                | Wed               | Lab               | 
| -----                 | ------                | ---               | ---               | 
| Introduction          | --                    | Intro / Logic Gates| Demultiplexer    |
| Combinational Logic   | Truth Tables          | Verilog Basics    | Demultiplexer     |  
| Combinational Logic   | Addition              | Subtraction       | Arith. Logic Unit |
| State in Hardware     | Latches               | Flip-Flops        | Arith. Logic Unit |
| Sequential Logic      | Sequential Logic      | FSMs I            | Saturating Counter|
| Finite State Machines | FSMs II               | FSMs III          | Saturating Counter|
| Timing / Memory       | Timing / Memory       | Review            | Elev.  Controller |
| -                     | Exam I                | Raspberry Pi      | Elev.  Controller |

### Cyber-Physical Systems Introduction

#### Reading References:
1. [Introduction to Embedded Systems - A Cyber-Physical Systems Approach](https://ptolemy.berkeley.edu/books/leeseshia/releases/LeeSeshia_DigitalV2_2.pdf)
2. [Pro Git Book](https://git-scm.com/book/en/v2)
3. [Sparkfun I2C Tutorial](https://learn.sparkfun.com/tutorials/i2c/all)
4. [Python Classes](https://docs.python.org/3/tutorial/classes.html)
5. [ST LPS331 Pressure Sensor](docs/LPS331AP.pdf)
6. [Sparkfun SPI Tutorial](https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi/all)
7. [Cyber-Physical Systems - a Computational Perspective](https://iucat.iu.edu/catalog/16065139)
8. [Dive Into Python 3](https://diveintopython3.net/)

| Weekly Focus          | Reading                | Monday                    | Wed                       | Lab                                       | 
| -----                 | ------                 | ------                    | ---                       | ---                                       | 
| Exam/CPS Introduction | Ref 1 Chapter 1        | **3/8:** Exam 1               | **3/10:** [CPS Introduction](lectures/CPS_Introduction.pdf)   | **[Project 5 Raspberry PI Setup](P5.md)** |
| Raspberry Pi          | Ref 2 Chapter 1-3      | **3/15:** [Pi Intro/UART Bus](lectures/RaspberryPi_UART.pdf)   | **3/17:** [Git/Github](lectures/PI_Setup_Git_Intro.pdf)    |                                           |
| I2C Bus               | Ref 3                  | **3/22:** [I2C Bus](lectures/I2C_Introduction.pdf)      | **3/24:** Wellness Day        | **[Project 6 I2C Pressure Sensor](P6.md)**         |
| Python/Sensor         | Ref 4, Ref 5           | **3/29:** [Classes/Modules](lectures/Python_Classes.pdf)     | **3/31:** [Pressure Sensor](lectures/LPS331AP_Pressure_Sensor.pdf)   |                                           |
| SPI                   | Ref 6                  | **4/5:** [SPI Bus Overview](lectures/SPI_bus.pdf)  | **4/7:** [SPI HDL Design](lectures/SPI_System_Verilog.pdf)       | **Project 7 GPIO Connected I/O**      |
    | SPI                   | Ref 7 Chapter 1        | **4/12:** [SPI HDL Design](lectures/SPI_SystemVerilog_2.pdf)     | **4/14:** [Networking Overview](lectures/Networking_Overview.pdf) |                                           |
| Network Interface     | Ref 7 Chapter 2        | **4/19:** MQTT  | **4/21:** Flask               | **Project 8 Network Interface**           |
| MQTT/Flask            | Ref 7 Chapter 14       | **4/26:** Open Topic               | **4/29:** Open Topic          |                                           |

**Final Exam Tues 5/4 10:10-12:10**
