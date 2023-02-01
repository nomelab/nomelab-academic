---
date: "2022-03-23"
diagram: true
image:
  caption: 'NOME Group, Spring 2022, PML'
  placement: 1
math: true
title: A database of files for ML integration with the Theiascope
---

A couple of select files will be used for the training:

#Weight Files

<a href="https://www.nomelab.com/files/YOLOv5s_blackdots">Black Dots</a>: This 1 class weight file was trained to enable detection of black dots and small <111> and <100> loops during 2-beam (g=200) imaging of bcc FeCrAl during in-situ TEM ion irradiations. The details about the database and an analogous YOLOv3 model is outlined <a href="https://doi.org/10.1016/j.commatsci.2021.110560">here</a>.

<a href="https://www.nomelab.com/files/YOLOv5s_bccloops">BCC loops</a>: This 3 class weight file was trained to enable the detection of black dots, <111>, and <100> loops in on zone (S)TEM imaging conditions where <100> loops appear as edge on and in-plane, <111> loops appear as ellipses, and black dots appear as small "dots" in the image. The training was done with either 512x512 or 640x640 images. The details about the database and an analogous Mask R-CNN model is outlined <a href="https://doi.org/10.1016/j.xcrp.2022.100876">here</a>.

<a href="https://www.nomelab.com/files/YOLOv5s_blackdots">Cavities</a>: This 1 class weight file was trained to enable detection of voids and helium bubbles imaged in bright field defocused condition from ex-situ irradiations. The model has been trained on both fcc and bcc materials that underwent both ion and neutron irradiation. The images must be in the underfocused condition with white contrast in the central portion of the cavities. The details about the database and an analogous Mask R-CNN model is outlined <a href="https://arxiv.org/abs/2208.01460">here</a>.

#Images

##Cavities
![Cavity 1](https://www.nomelab.com/files/Cavity1.jpg "Image of cavities in irradiated material")
<a href="https://www.nomelab.com/files/Cavity1.jpg">Download</a>



