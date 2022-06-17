# Public Life in Public Space (PLPS): A multi-task, multi-group video dataset for pubic life research.
This repository contains the information about the PLPS dataset.

<center>
  
![image](https://github.com/li-lindong/PLPS/blob/f48d6e98add50fb03b348296909b28358c85c3bf/Samples.png)
  
</center>

**<p align="center">Fig. Samples of actions/activities, emotions and social relations.</p>**

## Paper
[Public Life in Public Space (PLPS): A multi-task, multi-group video dataset for pubic life research](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Qing_Public_Life_in_Public_Space_PLPS_A_Multi-Task_Multi-Group_Video_ICCVW_2021_paper.pdf)

Linbo Qing, Lindong Li, Shengyu Xu, Yibo Huang, Mei Liu, Rulong Jin, Bo Liu, Tong Niu, Hongqian Wen, Yuchen Wang, Xue Jiang, Yonghong Peng

2021 IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)

If you find our dataset useful, please cite our [paper](https://openaccess.thecvf.com/content/ICCV2021W/ABAW/papers/Qing_Public_Life_in_Public_Space_PLPS_A_Multi-Task_Multi-Group_Video_ICCVW_2021_paper.pdf):

```
@INPROCEEDINGS{PLPS-Dataset,  
  author={Qing, Linbo and Li, Lindong and Xu, Shengyu and Huang, Yibo and Liu, Mei and Jin, Rulong and Liu, Bo and Niu, Tong and Wen, Hongqian and Wang, Yuchen and Jiang, Xue and Peng, Yonghong},  
  booktitle={2021 IEEE/CVF International Conference on Computer Vision Workshops (ICCVW)},   
  title={Public Life in Public Space (PLPS): A multi-task, multi-group video dataset for public life research},   
  year={2021}, 
  pages={3611-3620},  
  doi={10.1109/ICCVW54120.2021.00404}}
```

## Dataset Contents
This dataset version consists of 71 videos with multi-group and multi-level labels, which may surpporting gender/age classification, group detection, action/activity recognition, emotion analysis and social relation understanding.
* **Video frame**
* **2D bounding boxes**
* **Gender**: Male, Female, Unknown
* **Age**: Infant, Child, Teenager, Adult, Old People
* **Social groups**: individuals and clusters with two or more people
* **Action/Activity**: NA, Crossing, Waiting, Queueing, Talking, Dancing, Sitting, Jogging, Playing, Riding, Doing Sport
* **Individual/Group Emotion**: Valance (-2, -1, 0, +1, +2), Arousal (-2, -1, 0, +1, +2), Dominant (-2, -1, 0, +1, +2)
* **Social Relation**: Friend, Family, Couple, Professional, Commercial, No Relation

## Privacy Protection
The original data are from real public spaces, hence the dataset contains some clear faces inevitably. It is very necessary to blur the faces before releasing the dataset. Meanwhile, we also present some experimental results to discuss the influence of blurring. 
|Group Clustering|Individual Action|Group Activity|

## Copyright
The PLPS dataset is available for the academic purpose only. Any researcher who uses the PANDA dataset should obey the licence as below:

All of the PLPS Dataset (data, annotation and software) are copyright by College of Electronics and Information Engineering, Sichuan University and published under [the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/). This means that you must attribute the work in the manner specified by the authors, you may not use this work for commercial purposes and if you alter, transform, or build upon this work, you may distribute the resulting work only under the same license.

This dataset is for non-commercial use only. However, if you find yourself or your personal belongings in the data, please contact us, and we will immediately remove the respective images from our servers.

## Download
To download the PLPS dataset, please agree on the license and provide the below information via email. We will only take applications from organization email (Please **DO NOT** use the emails from gmail/163/qq). Anyone who uses the PLPS dataset should obey the license and send us an email for registration.

**Please use the following email template:**
```
To: qing_lb@scu.edu.cn
Subject: Apply for Using PLPS Dataset

I am aware of PLPS Terms of Use and I confirm to comply with it.

Name: xxx
Organization: xxx
Email: xxx
Tel: xxx
```
