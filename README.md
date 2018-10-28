## Welcome to my homepage

Hi, I am Xiang Zhang, a senior student in Department of Precision Machinery and Instrumentation, [School of Engineering Science](https://http://en.ses.ustc.edu.cn/), at [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/).

Currently, I am a senior research assistant in [Laser Laboratory for Trace Analysis and Precision Measurements](http://atta.ustc.edu.cn/en-us/index.html), supervised by [Prof. Dong Sheng](http://atta.ustc.edu.cn/en-us/members/faculty/dsheng.html).

As a self-motivated student, my rank is 1st out of 60 students in my department with a GPA of 3.91/4.3 and won the GuoMoruo Scholarship which is the highest honor awarded to most excellent undergraduates at USTC.

## Research Experience

### Atomic Devices Lab

I joined [Laser Laboratory for Trace Analysis and Precision Measurements](http://atta.ustc.edu.cn/en-us/index.html) in 2017. In the past two years, I participated in two projects of this lab, which are a Miniaturized Optically-pumped Magnetometer and Data Analysis of GNOME Experiment.

#### Project I: A Miniaturized Optically-pumped Magnetometer

##### Background

##### Shape Design and Manufacture

In this project, we try to build a miniaturized optically-pumped magnrtometer by reducing the size of optical path and using customized small-sized lenses. However, this task is challenging because the distance between the lenses need to be more accurate than common optically-pumped magnrtometers, which requires a thoughful design of the shape and a precise way to fabricate it.

I designed the 3D structure of the magnetometer by SolidWorks and used 3D printing to bring it from design to reality. With a size of 20mm*20mm*25mm, it contains all the lenses, a cubic cell filled with Rb and K, a flexible resistive foil heater for the cell and a PCB to turn light signal to electrical signal. Here are photos of the design and the 3D printed magnetometer.

<div align=center>![3D structure](http://m.qpic.cn/psb?/V12VczHP0k2BU4/sBDzNjTV6e8x.AGWyEa28NHl9hTR3orW7NpZ87.hIOA!/b/dDcBAAAAAAAA&bo=wwTLAgAAAAARBz4!&rf=viewer_4) 
FIG. 1. 3D Structure
</div>

<div align=center>![3D printing](http://m.qpic.cn/psb?/V12VczHP0k2BU4/Qjvx98MxD.52iremOkTIFZ2CwaNOfT9HyS3PdXjmq9I!/b/dEYBAAAAAAAA&bo=OgKAAQAAAAARB4k!&rf=viewer_4)
FIG. 2. 3D Printng
</div>

##### Signal Processing Circuit

Electrical signal we get form PCB contains information about the magnetic field, so we use a signal processing circuit to decouple the signal and feed it back to a Helmholtz coil to generate a low magnetic field required by our magnetometer.  In order to do so, I developed a schematic diagram including a lock-in amplifier and a PID. Then I designed the PCB by KiCad. Here are photos of our circuit design and PCB.

<div align=center>![circuit design](http://m.qpic.cn/psb?/V12VczHP0k2BU4/hwKczpLzAx4FMGyZAdZVC1jP5LNxIAy0KBPc7aaTHSI!/b/dDcBAAAAAAAA&bo=OgPIAAAAAAADF8M!&rf=viewer_4)
FIG. 3. circuit design
</div>

<div align=center>![PCB of Lock-in amplifer](http://m.qpic.cn/psb?/V12VczHP0k2BU4/Vmw.6kdj.p1tcCOmPSHnY6Ki1e.otwGnP40fXccrw2I!/b/dFMBAAAAAAAA&bo=OQKrAQAAAAARF7E!&rf=viewer_4)
FIG. 4. PCB of Lock-in amplifer
</div>

<div align=center>![PCB of Lock-in amplifer](http://m.qpic.cn/psb?/V12VczHP0k2BU4/F1hScvA69*UJj5ngUfQeXTmEpL2Y0rOebv4nBh5xiMo!/b/dFIBAAAAAAAA&bo=NQKrAQAAAAARF70!&rf=viewer_4)
FIG. 5. PCB of PID
</div>

##### Flexible Resistive Foil Heater With Magnetic Field Suppression

While our magnetometer is working, the cubic cell filled with Rb and K need to be heated to 150°C. Of course, there are many ways to heat up it, but what we need is a heater which is small, flexible, at the same time, with magnetic field suppression because the space of the magnetometer is limited and the magnetic field the heater generated will interfer with the detection of the magnetic field. In order to solve this problem, I developed a flexible resistive foil heater. It is flexible because it is manufured by FPC technology and it suppresses the magnetic field by making current go back and forth and using alternating current to power it. Here is a photo of heater.

<div align=center>![heater](http://m.qpic.cn/psb?/V12VczHP0k2BU4/NmoLPb97dNuOhHRVxeFN6mXXUcSuxo83BWN*mWVcdVA!/b/dAgBAAAAAAAA&bo=aQLHAgAAAAADR8w!&rf=viewer_4)
FIG. 6. flexible resistive foil heater
</div>
