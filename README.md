# Project: Can you recognize the emotion from an image of a face? 
<img src="figs/CE.jpg" alt="Compound Emotions" width="500"/>
(Image source: https://www.pnas.org/content/111/15/E1454)

### [Full Project Description](doc/project3_desc.md)

Term: Fall 2019

+ Team 8
+ Team members
	+ Longo, Stefano sl4444@columbia.edu
	+ Meng, Yang ym2696@columbia.edu
	+ Ruan, Qiuyu qr2127@columbia.edu
	+ Schleicher, Tim trs2145@columbia.edu
	+ Zhao, Nuanjun nz2295@columbia.edu

+ Project summary: In this project, we create a classification engine for facial emotion recognition. After testing a variety of different models, we verified that using LDA with a PCA-driven selection of features offers the best improvement over the baseline model of gradient boosting machines.
	
**Contribution statement**: Most team members contributed equally in all stages of this project. Yang is the only team member who contributed substantially to more than one stage of the project. Stefano focused on the variable selection methods. Yang and Nuanjun focused on the baseline model and on which model to feed to gradient boosting. Tim developed a deep learning approach but realised that the amount of data was not sufficient for such type of modelling. Yang designed the PCA part, improved the modelling, and merged all the coding together. All team members approve our work presented in this GitHub repository including this contributions statement. 

Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
