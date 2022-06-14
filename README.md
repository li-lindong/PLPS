# Public Life in Public Space (PLPS): A multi-task, multi-group video dataset for pubic life research.
This repository contains the information about the PLPS dataset.

<center>
  
![image](https://github.com/li-lindong/PLPS/blob/f48d6e98add50fb03b348296909b28358c85c3bf/Samples.png)
  
</center>

**<p align="center">Fig. Samples of actions/activities, emotions and social relations.</p>**

## Dataset Contents
This dataset version consists of 71 videos with multi-group and multi-level labels, which may surpporting gender/age classification, group detection, action/activity recognition, emotion analysis and social relation understanding.
* Video frame
* 2D bounding boxes
* Gender: Male, Female, Unknown
* Age: Infant, Child, Teenager, Adult, Old People
* Social groups: individuals and clusters with two or more people
* Action/Activity: NA, Crossing, Waiting, Queueing, Talking, Dancing, Sitting, Jogging, Playing, Riding, Doing Sport
* Individual/Group Emotion: Valance (-2, -1, 0, +1, +2), Arousal (-2, -1, 0, +1, +2), Dominant (-2, -1, 0, +1, +2)
* Social Relation: Friend, Family, Couple, Professional, Commercial, No Relation

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
