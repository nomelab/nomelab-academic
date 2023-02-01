---
date: "2022-03-23"
diagram: true
image:
  caption: 'NOME Group, Spring 2022, PML'
  placement: 1
math: true
title: A database of files for ML testing;
---

A couple of select files will be used for the training:

# Weight Files

<a href="https://www.nomelab.com/files/YOLOv5s_blackdots">Black Dots</a>: This 1 class weight file was trained to enable detection of black dots and small <111> and <100> loops during 2-beam (g=200) imaging of bcc FeCrAl during in-situ TEM ion irradiations. The details about the database and an analogous YOLOv3 model is outlined <a href="https://doi.org/10.1016/j.commatsci.2021.110560">here</a>.

<a href="https://www.nomelab.com/files/YOLOv5s_bccloops">BCC loops</a>: This 3 class weight file was trained to enable the detection of black dots, <111>, and <100> loops in on zone (S)TEM imaging conditions where <100> loops appear as edge on and in-plane, <111> loops appear as ellipses, and black dots appear as small "dots" in the image. The training was done with either 512x512 or 640x640 images. The details about the database and an analogous Mask R-CNN model is outlined <a href="https://doi.org/10.1016/j.xcrp.2022.100876">here</a>.

<a href="https://www.nomelab.com/files/YOLOv5s_blackdots">Cavities</a>: This 1 class weight file was trained to enable detection of voids and helium bubbles imaged in bright field defocused condition from ex-situ irradiations. The model has been trained on both fcc and bcc materials that underwent both ion and neutron irradiation. The images must be in the underfocused condition with white contrast in the central portion of the cavities. The details about the database and an analogous Mask R-CNN model is outlined <a href="https://arxiv.org/abs/2208.01460">here</a>.

<a href="https://www.nomelab.com/files/defaulty_yolov5s.pt">Common Objects</a>: This 79 class weight file was trained on Microsofts 2017 COCO database. The details about the database is outlined <a href="http://cocodataset.org">here</a>.

# Images

## Cavities

<center>

![Cavity 1](https://www.nomelab.com/files/Cavity1.jpg "Image of cavities in a irradiated material")
<a href="https://www.nomelab.com/files/Cavity1.jpg">Download</a>

![Cavity 2](https://www.nomelab.com/files/Cavity2.jpg "Image of cavities in a irradiated material")
<a href="https://www.nomelab.com/files/Cavity2.jpg">Download</a>

![Cavity 3](https://www.nomelab.com/files/Cavity3.jpg "Image of cavities in a irradiated material")
<a href="https://www.nomelab.com/files/Cavity3.jpg">Download</a>

</center>

## Black Dots

<center>

![Black Dot 1](https://www.nomelab.com/files/18Cr_TEM2beamimage.jpg "Image of black dots in a irradiated material")
<a href="https://www.nomelab.com/files/18Cr_TEM2beamimage.jpg">Download</a>

![Black Dot 2](https://www.nomelab.com/files/BlackDots.jpg "Image of black dots in a irradiated material")
<a href="https://www.nomelab.com/files/BlackDots.jpg">Download</a>

</center>

## BCC loops

<center>

![Loops 1](https://www.nomelab.com/files/FeCrAl1.jpg "Image of loops in a irradiated material")
<a href="https://www.nomelab.com/files/FeCrAl1.jpg">Download</a>

![Loops 2](https://www.nomelab.com/files/FeCrAl2.jpg "Image of loops in a irradiated material")
<a href="https://www.nomelab.com/files/FeCrAl2.jpg">Download</a>

![Loops 3](https://www.nomelab.com/files/FeCrAl3.jpg "Image of loops in a irradiated material")
<a href="https://www.nomelab.com/files/FeCrAl3.jpg">Download</a>

</center>

# Videos


<a href="https://drive.google.com/open?id=16hdVyyrEN3a3Tuqqq5euAEFxkLmTbHz4&authuser=kgfield%40umich.edu&usp=drive_fs">Download an in situ video</a>

<a href="https://drive.google.com/file/d/1-hbfqeLR1LLPTDh4wsfzfk_QR4-F9_y0/view?usp=share_link">Download a cavity imaging session video</a>

