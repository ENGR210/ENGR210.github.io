# Welcome to ENGR 210 ( CSCI B441 )

Spring 2022

This course provides a strong foundation for modern digital system
design using hardware description languages. We start with basics of
digital electronics and learn how digital gates are used to build
large digital systems. We will practice modern digital system design
by using state of the art software tools and implementation of the
digital systems on a programmable hardware platform.  At the end of
the course, students will be familiar with modern approach for
designing digital systems, using hardware description languages along
with an appropriate methodology.

## Quick Links

### [Syllabus](syllabus.md)

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

## Labs 

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

| Weekly Focus      | Reading | Monday                                                          | Wed                                                               | Lab                                           |
|-------------------|---------|-----------------------------------------------------------------|--------------------------------------------------------------     |-----------------------------------------------|
| CPS Intro/UART    |         | **1/10:** [CPS Introduction](lectures/CPS_Introduction.pdf)     | **1/12:** [Pi Intro/UART Bus](lectures/RaspberryPi_UART.pdf)      | **Project 0 Raspberry PI Setup**              |
| GPIO/Scope        |         | **1/17:** MLK Day                                               | **1/19:** Electronics/GPIO/LED                                    | **Project 1 UART Controlled LED**             |
| SPI Bus           |         | **1/24:** [SPI Bus Overview](lectures/SPI_bus.pdf)              | **1/26:** SPI Flash Memory                                        | **Project 2 SPI Flash Memory**                |
| I2C Bus           |         | **1/31:** [I2C Bus Overview](lectures/I2C_Introduction.pdf)     | **2/2:** [Pressure Sensor](lectures/LPS331AP_Pressure_Sensor.pdf) | **Project 3 I2C Pressure/Temperature Sensor** |
| Networking        |         | **2/7:**  Networking Overview                                   | **2/9:** [Flask](lectures/Flask.pdf)                              | **Project 4 Flask Web Server**                |
| Web Server        |         | **2/14:** Matplotlib                                            | **2/16:** [CPS Wrapup](lectures/CPS_Wrapup.pdf)                   | **Demultiplexer**                             |
| Evaluation        |         | **2/21:** Exam 1                                                | **2/23:** [CE Intro/ Logic](lectures/00_Logic_Gates.pdf)          | **ALU TB**                                    |
| CPE Intro/Logic   |         | **2/28:** [Truth Tables](lectures/01_Truth_Tables.pdf)          | **3/2:** [Verilog Basics](lectures/02_Verilog_Basics.pdf)         | **ALU**                                       | 
| Combinational Logic|        | **3/7:**  [Testbenches](lectures/03_Testbenches.pdf)            | **3/9:** [Math I](lectures/04_Math_I.pdf)                         | **Saturating Counter TB**                     |
|                   |         | **3/14:** Spring Break                                          | **3/16:** Spring Break                                            |                                               |
| Sequential Logic  |         | **3/14:** [Math II](lectures/05_Math_II.pdf)                    | **3/16:** [Latches](lectures/06_Latches.pdf)                      | **Saturating Counter**                        |
| FSMs              |         | **3/21:** [Flops](lectures/07_Flops.pdf)                        | **3/23:** [Sequential Logic](lectures/08_Sequential.pdf)          | **Elevator Controller TB**                    |
| FSMs              |         | **3/28:** [FSMs I](lectures/09_FSM_I.pdf)                       | **3/31:** [FSMs II](lectures/10_FSM_II.pdf)                       | **Elevator Controller**                       |
| FSM/Timing        |         | **4/4:** [FSMs III](lectures/11_FSM_III.pdf)                    | **4/6:** [Timing](lectures/12_Timing.pdf)                         | **SPI Interface**                             |
| SPI Implementation|         | **4/11:** [SPI I](lectures/13_SPI_I.pdf)                        | **4/13:** [SPI II](lectures/14_SPI_II.pdf)                        | **SPI Elev. Controller**                      |
| Memory Interfaces |         | **4/18:** [MMIO I](lectures/15_MMIO_I.pdf)                      | **4/20:** [MMIO II](lectures/16_MMIO_II.pdf)                      | **Flask/SPI Elev. Controller**                |
| Review            |         | **4/25:** Overflow                                              | **4/27:** [Review](lectures/18_Review.pdf)                        |                                               |
|                   |         | **4/XX:** Final Exam                                            |                                                                   |                                               |



[Old Projects](old_projects.md)
