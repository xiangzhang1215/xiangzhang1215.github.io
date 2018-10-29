## Welcome to my homepage

Hi, I am Xiang Zhang, a senior student in Department of Precision Machinery and Instrumentation, [School of Engineering Science](https://http://en.ses.ustc.edu.cn/), at [University of Science and Technology of China (USTC)](https://www.ustc.edu.cn/).

Currently, I am a senior research assistant in [Laser Laboratory for Trace Analysis and Precision Measurements](http://atta.ustc.edu.cn/en-us/index.html), supervised by [Prof. Dong Sheng](http://atta.ustc.edu.cn/en-us/members/faculty/dsheng.html).

As a self-motivated student, my rank is 1st out of 60 students in my department with a GPA of 3.91/4.3 and won the GuoMoruo Scholarship which is the highest honor awarded to most excellent undergraduates at USTC.

## Research Experience

### Atomic Devices Lab

I joined [Laser Laboratory for Trace Analysis and Precision Measurements](http://atta.ustc.edu.cn/en-us/index.html) in 2017. In the past two years, I participated in two projects of this lab, which are a Miniaturized Optically-pumped Magnetometer and Data Analysis of GNOME Experiment.

### Project I: A Miniaturized Optically-pumped Magnetometer

#### Shape Design and Manufacture

In this project, we try to build a miniaturized optically-pumped magnetometer by reducing the size of optical path and using customized small-sized lenses. However, this task is challenging because the distance between the lenses need to be more accurate than common optically-pumped magnetometers, which requires a thoughtful design of the shape and a precise way to fabricate it.

I designed the 3D structure of the magnetometer by SolidWorks and used 3D printing to bring it from design to reality. With a size of 20mm*20mm*25mm, it contains all the lenses, a cubic cell filled with Rb and K, a flexible resistive foil heater for the cell and a PCB to turn light signal to electrical signal. Here are photos of the design and the 3D printed magnetometer.

![3D structure](http://m.qpic.cn/psb?/V12VczHP0k2BU4/sBDzNjTV6e8x.AGWyEa28NHl9hTR3orW7NpZ87.hIOA!/b/dDcBAAAAAAAA&bo=wwTLAgAAAAARFy4!&rf=viewer_4) 
FIG. 1. 3D Structure

![3D printing](http://m.qpic.cn/psb?/V12VczHP0k2BU4/ydZnNYSX2xt4FD4D2gnwqQaCwuHjmk4G17jvNz7R5dU!/b/dFQBAAAAAAAA&bo=oAU4BAAAAAARB6k!&rf=viewer_4)
FIG. 2. 3D Printing under heating test

#### Signal Processing Circuit

Electrical signal we get form PCB contains information about the magnetic field, so we use a signal processing circuit to decouple the signal and feed it back to a Helmholtz coil to generate a low magnetic field required by our magnetometer.  In order to do so, I developed a schematic diagram including a lock-in amplifier and a PID. Then I designed the PCB by KiCad. Here are photos of our circuit design and PCB.

![circuit design](http://m.qpic.cn/psb?/V12VczHP0k2BU4/hwKczpLzAx4FMGyZAdZVC1jP5LNxIAy0KBPc7aaTHSI!/b/dDcBAAAAAAAA&bo=OgPIAAAAAAADF8M!&rf=viewer_4)
FIG. 3. circuit design

![PCB of Lock-in amplifer](http://m.qpic.cn/psb?/V12VczHP0k2BU4/Vmw.6kdj.p1tcCOmPSHnY6Ki1e.otwGnP40fXccrw2I!/b/dFMBAAAAAAAA&bo=OQKrAQAAAAARF7E!&rf=viewer_4)
FIG. 4. PCB of Lock-in amplifier

![PCB of Lock-in amplifer](http://m.qpic.cn/psb?/V12VczHP0k2BU4/F1hScvA69*UJj5ngUfQeXTmEpL2Y0rOebv4nBh5xiMo!/b/dFIBAAAAAAAA&bo=NQKrAQAAAAARF70!&rf=viewer_4)
FIG. 5. PCB of PID

#### Flexible Resistive Foil Heater With Magnetic Field Suppression

While our magnetometer is working, the cubic cell filled with Rb and K need to be heated to 150°C. Of course, there are many ways to heat up it, but what we need is a heater which is small, flexible, at the same time, with magnetic field suppression because the space of the magnetometer is limited and the magnetic field the heater generated will interfere with the detection of the magnetic field. 

In order to solve this problem, I developed a flexible resistive foil heater. It is flexible because it is manufactured by FPC technology and it suppresses the magnetic field by making current go back and forth and using alternating current to power it. Here is a photo of heater.

![heater](http://m.qpic.cn/psb?/V12VczHP0k2BU4/NmoLPb97dNuOhHRVxeFN6mXXUcSuxo83BWN*mWVcdVA!/b/dAgBAAAAAAAA&bo=aQLHAgAAAAADR8w!&rf=viewer_4)
FIG. 6. flexible resistive foil heater

### Project II: GNOME Data Analysis

#### Background
[Global Network of Optical Magnetometers for Exotic physics](https://budker.uni-mainz.de/gnome/) is an international collaboration searching for transient events caused by dark matter and dark energy. Our lab is one of the stations of GNOME and providing data for GNOME. 

 In January 2018, I joined GNOME Data analysis group and analyzed the data of the science run in December 2017 using the methods such as the Power Spectral Density, FFT, Continuous Wavelet Transform (CWT), Allan Deviation and the Excess Power method.

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/anWqaCLeBxf7PR*49VD5lka5ZM8en91GkgcRLY2uyz0!/b/dFYBAAAAAAAA&bo=YQQwAwAAAAADN0Q!&rf=viewer_4)

FIG. 7. The GNOME Experiment

#### Time Series and Frequency Series

Most of the data collected by stations are noise, and the signals may be submerged in noise. Therefore, the purpose of data analysis is to analyze the experimental data of GNOME and search for signals from noise. 

In the first place, I analyze the signal in frequency domain and time domain using Fourier transform and Wavelet transform. Here are some results.

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/5XXUsH5b9nTtEGi5vfRbRU*ZyHtjV3D.j531eVTqPQQ!/b/dFIBAAAAAAAA&bo=sAS8AgAAAAADFzg!&rf=viewer_4)

FIG. 8. Power Spectral Density using [Welch's Method](https://docs.scipy.org/doc/scipy/reference/generated/scipy.signal.welch.html#scipy.signal.welch)

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/IBDU.XVQXYWOztuY631RdXu0ueGaJ8lzo2CpDsnUpWE!/b/dFMBAAAAAAAA&bo=sAS8AgAAAAADV3g!&rf=viewer_4)

FIG. 9. power spectrogram

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/drHtnkN96.N7fp8vDmXJA5u*05HZwpnbZ0nH*eMhJU4!/b/dFIBAAAAAAAA&bo=sASEAwAAAAADJzE!&rf=viewer_4)

FIG. 10. Scalogram

#### Allan Variance

[The Allan variance](https://en.wikipedia.org/wiki/Allan_variance) is a way to measure the frequency stability in clocks, oscillators and amplifiers. In general, when the average time increases, a station's Allan variance value drop at the start because the average on time limited the short-time uncertainties and then rise because of the influence of time drift. When variance reachs the minimum, the average time is the most stable time of the magnetometer.

 Here are Allan standard deviation of USTC station.

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/VM7ymi0vl3ET1qnesyjD11KthdLlQvXdjGsO9k9KrZ8!/b/dDQBAAAAAAAA&bo=gAfDAwAAAAARF2c!&rf=viewer_4)

FIG. 11.  Allan standard deviation

#### Excess Power Search

The Excess Power method is designed to detect burst signals of unknown waveform. Its idea is that if there is no signal in the data, what we detected is noise which obeys some kinds of distribution and if signal is in the data, what we detected no longer obeys the distribution. So we can tell whether there are signals in the data by testing the data in time and frequency domain and if there is more power than we expected, we would call it excess power and know that there are signals in the data. Here is a trigger map of USTC station which shows the time and frequency of the signal.

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/EuZbQKzQDxXc.poCzmESdQ9hnJvIad0mwAaTpZKb0*w!/b/dFQBAAAAAAAA&bo=cAg4BAAAAAADN1Y!&rf=viewer_4)

FIG. 12.  trigger map

### Simulation of Electric Field Based on Mathematica

In December 2016, I participated in the Essay Competition held by  Electromagnetism teaching-research group of USTC as a sophomore.  Supervised by Prof. Xia Sun, I developed a Mathematica program to calculate the electric field of any distribution of point charge based on Maxwell's equations and drew some gif images to show the changing electric field in three dimensions.

This work won the 1st price of Essay Competition. Here are some gifs of the changing electric field.

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/Z.01d2ezebJVA.f2AeKSlFwR2AdWmeXLmwM*Wu7I7dI!/b/dDQBAAAAAAAA&bo=aAFoAQAAAAACl7M!&rf=viewer_4)

GIF. 1.  A rotating electric dipole

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/JagV*erEppDd8AvbL3NmGxtH6zVNY*HaMMEFZKRO80U!/b/dFMBAAAAAAAA&bo=aAGaAQAAAAACZ7E!&rf=viewer_4)

GIF. 2.  A  electric quadrupole with one changing its charge amount

## Activities

### International Summer Design Experience in OSU

In the summer of 2018, I went to [the Ohio State University (OSU)](https://www.osu.edu/) to participate [the International Summer Design Experience](https://bme.osu.edu/bme-summer-design-experience) held by [Department of Biomedical Engineering](https://bme.osu.edu/) of OSU. 

Supervised by [Prof.  Mark Ruegsegger](https://bme.osu.edu/people/ruegsegger.1), our team designed a device helping Boccia players with disabilities to roll the ball onto the court and built a prototype which can be used as an assistive device in Boccia based on our design.  Boccia, a modified version of the popular European sport of Bocce, is a Paralympic sport designed for athletes with disabilities. 

Here are some photos in Ohio.

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/IY5xqbS*2L8SRuBcNR.cGJXkkbFruqjXP.uuotJuY5M!/b/dDYBAAAAAAAA&bo=ogU6BKIFOgQDWXw!&rf=viewer_4)

PIC . 1.  I am giving a presentation about our prototype

![GNOME](http://m.qpic.cn/psb?/V12VczHP0k2BU4/Ara3DKVPLZZ6NqAMDQW8BforRNHb1EsWBd*Qiczed2U!/b/dDEBAAAAAAAA&bo=ogU6BKIFOgQDCSw!&rf=viewer_4)

PIC . 2.  my work: structure design of Boccia device

## More information about me will be updated in the future, thank you for your visit.
