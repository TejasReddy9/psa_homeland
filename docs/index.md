---
layout: default
---

# Overview

You might've heard that TSA Security screeners failed 95% of tests conducted by Federal officials of Homeland Security. This revealed that several explosives and weapons are undetected through the body scanners. It was allegedly said that the reason is because of poor maintenance of the security screeners. But, the ground fact is that the algorithm itself is faulty which couldn't classify better. There are many false negatives leading to long-lasting queues also. 

As they have put their 3D-image screening dataset on Kaggle, I got an opputinity to explore the data for exploration. They splitted the problem into two stages, this project considers only stage-1 data. I arrived at converting 3D-image to 2D-image patches, took a particular patch, trained a model with all data corresponding to that patch. Then I wanted to scale it for whole 3D-image, but couldn't finish due to lack of requirements (Data is in TBs and examining in AWS Cloud Platform consuming lot of runtime).

## Dataset

Find the dataset at [Kaggle PSA dataset](https://www.kaggle.com/c/passenger-screening-algorithm-challenge/data). Data is pretty standard and all the cleaning is  done by themselves before exposing it to Kaggle, hence I started making my EDA report(Exploratory Data Analysis). 

Zones about how many ways do they examine using the 3D-image from the body scanner is provided as shown below. Instrument used is also displayed.

![body_zones](https://github.com/TejasReddy9/psa_homeland/blob/master/body_zones.png?raw=true)

![instrument](https://github.com/TejasReddy9/psa_homeland/blob/master/millimeter_scanner.jpg?raw=true)
