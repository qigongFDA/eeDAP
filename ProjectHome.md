# eeDAP #
## _Evaluation Environment for Digital and Analog Pathology_ ##

eeDAP is a software and hardware platform for designing and executing digital and analog pathology studies where evaluation regions of interest (ROIs) in the digital image are registered to the real-time view on the microscope. This registration allows for the reduction or elimination of a large source of variability in comparing these modalities in the hands of the pathologist: the field of view (the tissue) being evaluated. In fact, the current registration precision of eeDAP allows for the presentation of the same individual cell in both domains. As such, a study can be designed where pathologists are asked to evaluate a pre-selected list of individual cells in Digital mode and Microscope real-time mode (MicroRT mode). eeDAP collects the pathologist evaluations while cycling through the list of cells. In Digital mode, the pathologist can enter the evaluations himself or herself. In MicroRT mode, an administrator enters the evaluations while confirming and maintaining a high level of registration precision. The paired observations allow for comparisons of WSI and traditional optical microscopy using several forms of agreement or performance when a reference standard can be established.

[Jump Down to Current Version and Download Link](http://code.google.com/p/eedap#Current_Version)

# Status #
New version imminent. Main improvement: the requirements for ImageScope and Windows OS have been overcome with the Bioformat libraries from the Open Microscopy Environment.

_This software works, but it is still a work in progress. More accurately, there are sure to be gaps in the user manual, especially regarding the set up of the hardware. We hope that other investigators will be interested enough to try it out and provide feedback. Please contact us with any issues via the issues tab or by email (see the SPIE proceedings paper linked below)._

## Journal of Medical Imaging ##
Gallas, B. D.; Gavrielides, M. A.; Conway, C.; Ivansky, A.; Keay, T.; Cheng, W.-C.; Hipp, J. & Hewitt, S. M. (2014), <br>
'Evaluation Environment for Digital and Analog Pathology (eeDAP): a platform for validation studies.' <i>J Med Img</i>, <b>1</b>, (3), 037501.<br>
<a href='http://spie.org/Publications/Journal/10.1117/1.JMI.1.3.037501'>http://spie.org/Publications/Journal/10.1117/1.JMI.1.3.037501</a>

<h2>Pathology Informatics 2014</h2>
<i>"Pilot Reader Studies Comparing Whole Slide Images with Different Gamma Settings"</i> <br>
<a href='http://eedap.googlecode.com/svn/trunk/000_docs/20140515_PI_BrandonGallas_Slides-4.pdf'>Click to download the conference slides (20140415_PI_BrandonGallas_Slides-4.pdf)</a>

<h2>SPIE Medical Imaging Conference 2014</h2>
proceedings paper: <br>
<i>"eeDAP: An Evaluation Environment for Digital and Analog Pathology"</i> <br>
<a href='http://eedap.googlecode.com/svn/trunk/000_docs/20140224_SPIE_9037-8_BrandonGallas-proceedings-8.pdf'>Click to download (20140224_SPIE_9037-8_BrandonGallas-proceedings-8.pdf)</a>

<i>"Pilot reader studies to compare digital microscopic images versus the microscope"</i> <br>
presentation slides: <br>
<a href='http://eedap.googlecode.com/svn/trunk/000_docs/20140224_SPIE_9037-8_BrandonGallas-Slides-3.pdf'>Click to download (20140224_SPIE_9037-8_BrandonGallas-Slides-3.pdf)</a>

<h1>Current Version</h1>
Version 2.0 posted 2014-02-14<br>
<br>
Make sure to refer to the user manual for instructions on software install. Feel free to download the sample WSI to test the application. The software is a little sensitive to long file names (including the directory). It is recommended that you create a directory at the root, for example <code>c:\000_whole_slides\100113_ThorLabs_20x.ndpi</code>

<a href='http://eedap.googlecode.com/svn/packages/eedap_2p0_pkg_exe'>Click to download application package (eedap_2p0_pkg_exe)</a> <br>
Rename file to be .exe instead of <i>exe</i>

<a href='http://eedap.googlecode.com/svn/trunk/000_docs/eeDAP_manual.pdf'>Click to download user manual (eedap_manual.pdf)</a>

<a href='ftp://taxp2.cdrh.fda.gov/eedap/000_whole_slides/100113_thorlabs_20x.ndpi'>Click to download a sample WSI</a> <br>

<br>

<h3><a href='http://eedap.googlecode.com/svn/'>Direct Access to Repository Contents</a></h3>

<br>

<h1>License and Copyright</h1>

This software and documentation (the "Software") were developed at the Food and Drug Administration (FDA) by employees of the Federal Government in the course of their official duties. Pursuant to Title 17, Section 105 of the United States Code, this work is not subject to copyright protection and is in the public domain. Permission is hereby granted, free of charge, to any person obtaining a copy of the Software, to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, or sell copies of the Software or derivatives, and to permit persons to whom the Software is furnished to do so. FDA assumes no responsibility whatsoever for use by other parties of the Software, its source code, documentation or compiled executables, and makes no guarantees, expressed or implied, about its quality, reliability, or any other characteristic. Further, use of this code in no way implies endorsement by the FDA or confers any advantage in regulatory decisions. Although this software can be redistributed and/or modified freely, we ask that any derivative works bear some notice that they are derived from it, and any modified versions bear some notice that they have been modified.