### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

Before running these codes, make sure Python versions 3.*, Go are configured properly. If using the ai code module (mainly used for merge photo, recognize article type etc), python packages including numpy, cv2, PIL, qrcode, skimage are installed with proper version, which could refer the requirement.txt in specific module foler.

After above installation, the code should run with no issues.

## Project Motivation<a name="motivation"></a>

This is a project record of three-day hacker marathon. The competition topic is "wildfire", in Chinese "野火". Among this topic, there are many derivations idea happened in our mind: flourish news, courage to break-up, never-stopped data flow and etc. Finally, we made a decision to design a browser plugin,named "Share Card" (分享卡片), to record *each moving moment, mood, thought* when surfing.  

It has three main fucntions: 
- *share* fuction allows you to input whatever touchs you and why, then a share card photo is generated available for saving and sharing to your friends. 
- *hot list* functin allows you to check out the moving moment and comments that are shared most. Meanwhile, it also support check the hot list by article type.
- *heat map* function allows you to see the distributions of share and comments on the article you are reading. The deeper the color, the hotter the discussions. You can also check the hot comment by hovering your mouse over the sentences waiting for a pop-up for a moment. (AH, this fuction is still under-development, aplogize @-@ 

## File Descriptions <a name="files"></a>

The usage data is not collected here yet. The 1.0 version demo is stored in folder *demo* (PS: Cause this plugin have not released in Google Store, please open the develop mode and loading the *demo1.0* folder instead of crx file). The folder *codes* includes the ai module and backend. Related documents are saved in folder "doc" mainly including procedure design between front and backend, prototype of demo and some arrangement records. 

## Results<a name="results"></a>

We've provided a video to record the usage of three fuctions of this plugin [here](https://github.com/PaperStrange/Hackday_2019/blob/master/demo1.0%E5%B1%95%E7%A4%BA.mp4).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

This repository is distributed under the GNU license.

Must give credit to kaggle for the data. Anyway, feel free to use the code here as you would like!

