---
permalink: /
title: "个人简历"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

教育经历
======
2016.09-至今     天津大学 电气与信息工程学院 信息与通信工程 硕士生（保研）  
2012.09-2016.07 天津大学 电子信息工程学院   电子信息工程   本科生  

个人能力
======
理解熟习ML、DL中的算法和模型，在计算机视觉和模式识别领域有一定的科研经验，能熟练运用Keras等深度学习框架搭建神经网络  
具备扎实的数学基础，能熟练运用Python、Matlab等脚本语言进行算法开发，能使用C语言实现实际工程  
CET 4/6，能无障碍进行专业文献的阅读写作和行业内学术交流  
计算机二级（C++, MySQL）、计算机三级（计算机网络技术）、计算机四级（网络工程师）

发表论文
======
我们提出使用角点响应特征图来定位人工文本区域；采用投影法将候选文本区域分割成候选文本行；构建融合不同语义层级特征的卷积神经网络，进行真假文本行的判别；对判定为真的文本行图片进行基于颜色和位置五维信息的FCM聚类分层，提取出干净的文本层；将文本层图片送入OCR软件，实现视频中人工文本的识别。该工作已发表在IEEE Access，导师一作本人二作。  
W. Lu, H. Sun, J. Chu, X. Huang and J. Yu, "A Novel Approach for Video Text Detection and Recognition Based on a Corner Response Feature Map and Transferred Deep Convolutional Neural Network," IEEE Access, vol. 6, pp. 40198-40211, 2018.

项目经验
======
视频事件识别  
调研当前视频事件识别方法和数据集，搭建环境并复现LRCN等架构，提出利用前景背景分别提取特征并进行融合的思路，目前正处于论文学习和实验探索阶段。

学校工作
======
天津大学电气自动化与信息工程学院信息与通信工程二班班长  
天津大学电气自动化与信息工程学院研究生会骨干（学术部）

奖项荣誉
======
天津大学原电子信息工程学院院长奖  
2016年BOE创新挑战赛全国三等奖，获得Special Offer  
天津大学校级“三好学生”   
天津大学优秀学生干部

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
