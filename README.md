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
	
**Contribution statement**: 

Yang Meng: 

Stefano Longo: focused on the variable selection methods, including best subsets, forward and random forest. 

Nuanjun Zhao: Other models tried including svm and adaboost method with lower accuracy and participation in codes of adaboost combined with LDA by hand which finally failed; Report part in main.pdf. How to reduce the dimension of the duplicated features.

Tim Schleicher: developed a deep learning approach which proved less useful than other models since the amount of data was comparatively limited. 

Qiuyu Ruan: Other models tried including xgboost method with lower accuracy; baseline model: gbm; participation in codes of adaboost combined with LDA by hand which finally failed; Report part in main.pdf. How to reduce the dimension of the duplicated features.


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
