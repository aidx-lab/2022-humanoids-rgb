---
layout: page
title: 
---

This site accompanies the paper 
[**Self-Contained Calibration of an Elastic Humanoid Upper Body Using Only a Head-Mounted RGB Camera**](https://ieeexplore.ieee.org/document/10000184) by
[Johannes Tenhumberg](https://scholar.google.com/citations?user=2RZuYZMAAAAJ), 
[Dominik Winkelbauer](https://scholar.google.com/citations?user=kduGd8wAAAAJ), 
[Darius Burschka](https://scholar.google.com/citations?user=y-MzVoUAAAAJ), and 
[Berthold Bäuml](https://scholar.google.com/citations?user=fjvpDsEAAAAJ) presented at the 
2022 IEEE-RAS International Conference on Humanoid Robots in Ginowan, Japan.


![Error Histogram](/assets/imgs/calibration_sketch.png){:.this
style="width: 600px;
display: block;
margin-left: auto;
margin-right: auto"}

# Abstract
---
When a humanoid robot performs a manipulation task, it first makes a model of the world using its visual sensors and then plans the motion of its body in this model. 
For this, precise calibration of the camera parameters and the kinematic tree is needed. 
Besides the accuracy of the calibrated model, the calibration process should be fast and self-contained, i.e., no external measurement equipment should be used. 
Therefore, we extend our prior work on calibrating the elastic upper body of DLR’s Agile Justin by now using only its internal head- mounted RGB camera and simple visual markers at the ends of the kinematic chain and one in front of the robot, mounted on a pole. 
To ensure that the task-relevant cartesian error at the end-effectors is minimized, we introduce virtual noise to fit our imperfect robot model in a way where the pixel error has a higher weight when the marker is further away from the camera. 
This correction reduces the cartesian error by more than 20%, resulting in a final accuracy of 3.9mm on average and 9.1 mm in the worst case. 
So, we achieve the same precision as in our [previous work](https://ieeexplore.ieee.org/document/9555793) where a whole external cartesian tracking system was used.

---

Cite this paper as:

    @inproceedings{Tenhumberg2022rgb,
        author = {Johannes Tenhumberg and Dominik Winkelbauer and Darius Burschka and Berthold B{\"a}uml},
        title = {Self-Contained Calibration of an Elastic Humanoid Upper Body Using Only a Head-Mounted RGB Camera},
        booktitle = {IEEE-RAS International Conference on Humanoid Robots (Humanoids)},
        year = 2022}

[arxiv](https://arxiv.org/abs/2311.08338)