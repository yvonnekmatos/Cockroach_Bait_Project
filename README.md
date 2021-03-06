# Cockroach_Bait_Project
Project and tutorial for analyzing datasets with Python, pandas, lifelines, matplotlib, statsmodels, and seaborn

The datasets come from experiments testing an insecticidal bait on cockroaches. The data fall into two main sets of experiments that dictate the type of statistical analysis we will do.

Raw data csv files can be found in the data folder. 

[Here](https://github.com/yvonnekmatos/Cockroach_Bait_Project/files/1444580/jee.tow092.full.pdf) is a copy of the white paper if you want to learn about this study in more detail.

The Lifelines_matplotlib.ipynb file features data collected from lab experiments testing two types of insecticidal bait. We want to know how fast the baits kill cockroaches and how well they work. In this study, cockroaches were offered bait or normal food as a control, and dead cockroaches were recorded every 2 hours.  We'll use Kaplan-Meier survivorship in the lifelines library to analyze this data, and matplotlib to visualize the data. 

The RMANOVA_seaborn.ipynb file features data collected from field plots outside where cockroaches were living. The study design is below, and we want to know if the bait reduced the cockroach population within treated plots, and between the treated and control plots on each measurement day. Since the same plots were measured over and over, we'll analyze differences within treatments using a repeated measures ANOVA in the statsmodels library. Differences between treatment and control groups can be found with t-tests. We'll use seaborn to visualize the data.

<img width="712" alt="zy_slide1" src="https://user-images.githubusercontent.com/29462745/32420536-3ce00f86-c251-11e7-9974-053b09816dd3.png">
<img width="706" alt="zy_slide2" src="https://user-images.githubusercontent.com/29462745/32420537-3cfdc67a-c251-11e7-92e8-50391e75b9fa.png">
