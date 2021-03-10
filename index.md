
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

| Date  |   Day     | Lecture Topic         |  Project Topic    | 
| --    |  -----    |   -----               |     -----         | 
| 1/20  | Wednesday | Intro / Logic Gates   |                   |
| 1/25  | Monday    | Truth Tables          | Demultiplexer     |
| 1/27  | Wednesday | Verilog Basics        |                   |
| 2/01  | Monday    | Addition/Subtraction  | Arith. Logic Unit | 
| 2/03  | Wednesday | Addition/Subtraction  |                   |
| 2/08  | Monday    | Latches               | Arith. Logic Unit |
| 2/10  | Wednesday | Flip Flops            |                   |
| 2/15  | Monday    | Sequential Logic      | Saturating Counter| 
| 2/17  | Wednesday | Finite State Machines |                   |
| 2/22  | Monday    | Finite State Machines | Saturating Counter| 
| 2/24  | Wednesday | Memory                |                   |
| 3/01  | Monday    | Timing                | Elevator Controller |
| 3/03  | Wednesday | Review                |                   |
| 3/08  | Monday    | Exam I                | Elevator Controller |
| 3/10  | Wednesday | Raspberry Pi Intro    |                   |

### Cyber-Physical Systems Introduction

#### Reading References:
1. [Introduction to Embedded Systems - A Cyber-Physical Systems Approach](https://ptolemy.berkeley.edu/books/leeseshia/releases/LeeSeshia_DigitalV2_2.pdf)
2. [Pro Git Book](https://git-scm.com/book/en/v2)
3. [Sparkfun I2C Tutorial](https://learn.sparkfun.com/tutorials/i2c/all)
4. [Python Classes](https://docs.python.org/3/tutorial/classes.html)
5. [ST LPS331 Pressure Sensor](docs/LPS331AP.pdf)
6. [Sparkfun SPI Tutorial](https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi/all)
7. [Cyber-Physical Systems - a Computational Perspective](https://iucat.iu.edu/catalog/16065139)

| Weekly Focus          | Reading                | Monday                    | Wed                       | Lab                                       | 
| -----                 | ------                 | ------                    | ---                       | ---                                       | 
| Exam/CPS Introduction | Ref 1 Chapter 1        | **3/8:** Exam 1               | **3/10:** CPS Introduction    | **[Project 5 Raspberry PI Setup](P5.md)** |
| Raspberry Pi          | Ref 2 Chapter 1-3      | **3/15:** Pi Intro/UART Bus   | **3/17:** Git/Github          |                                           |
| I2C Bus               | Ref 3                  | **3/22:** I2C Bus             | **3/24:** Wellness Day        | **Project 6 I2C Pressure Sensor**         |
| Python/Sensor         | Ref 4, Ref 5           | **3/29:** Classes/Modules     | **3/31:** Pressure Sensor     |                                           |
| SPI                   | Ref 6                  | **4/5:** SPI Bus Overview     | **4/7:** SPI HDL Design       | **Project 7 SPI Connected I/O**           |
| SPI                   | Ref 7 Chapter 1        | **4/12:** SPI HDL Design      | **4/14:** Sensor Memory       |                                           |
| Network Interface     | Ref 7 Chapter 2        | **4/19:** Ethernet Interface  | **4/21:** MQTT                | **Project 8 Network Interface**           |
| MQTT/Flask            | Ref 7 Chapter 14       | **4/26:** Flask               | **4/29:** Open Topic          |                                           |

**Final Exam Tues 5/4 10:10-12:10**
