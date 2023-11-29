# Project 4: Machine Learning Fairness

### [Project Description](doc/project4_desc.md)

Term: Fall 2023

+ Team #
+ Projec title: Machine Learning Fariness
+ Team members
	+ Jingxuan Wang (jw4311)
	+ Puqi Song (ps3387)
	+ Feiyu Guo (fg2545)
	+ Haixin Shu (hs3372)
	+ Yoojin Lee (yl4477)
+ Project summary: This project aims to deal with the fairness problem in machine learning. We use the the dataset in https://github.com/propublica/compas-analysis/raw/master/compas-scores-two-years.csv to figure out the difference crimme rate in different race, mainly focus on Black and Caucasian. We worked on paper A4: Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment (DM and DM-sen), and paper A5: Fairness-aware Classifier with Prejudice Remover Regularizer (PR). We use the calibration score indicator to show the fairness of the algorithm and we use the FPR constraints, FNR constraints and prejudice remover regularizer.
	
**Contribution statement**: [default] All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement. 

Jingxuan Wang and Feiyu Guo work on the paper A5 prejudice remover regularizer.
Puqi Song, Haixin Shu, and Yoojin Lee work on the paper A4 Disparate Treatment & Disparate Impact

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
