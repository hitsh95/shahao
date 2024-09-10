---
permalink: /
title: "Hao Sha's academic personal websites"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a 4th year PhD student in the department of <a href="http://cs.hitsz.edu.cn/">Computer Science</a>, <a href="http://en.hitsz.edu.cn/">Harbin Institute of Technology (ShenZhen)</a>. Previously, I received my MSE and BSE degrees from <a href="https://en.csu.edu.cn/">Central South University</a> and <a href="https://www.lit.edu.cn/">LuoYang Institute of Technology</a> in 2020 and 2017. My Ph.D. supervisors are <a href="https://faculty.hitsz.edu.cn/zhangyongbing">Prof. Yongbing Zhang</a> from <a href="http://en.hitsz.edu.cn/">Harbin Institute of Technology (ShenZhen)</a>, <a href="http://houlab.szbl.ac.cn/"> Assistant Prof. Shangguo Hou</a> from <a href="https://www.szbl.ac.cn/en/"> Shenzhen Bay Laboratory</a> and <a herf="https://rieslab.de/">Prof.Jonas Ries</a> from <a herf="https://www.maxperutzlabs.ac.at/research/research-groups/ries">Max Perutz Lab</a>. My research interests lie primarily in super-resolution imaging and single-molecule tracking. During my study in HIT and SZBL, I developed a single molecule spectrum tracking system. With this system, we can track the spectrum of single molecules at the spatiotemporal scale of millisecond-nanometers. Besides, I also had a good time with <a href="https://www.sigs.tsinghua.edu.cn/hsy_en/main.htm">Assistant Prof. Sanyang Han</a> and <a href="https://ee.jlu.edu.cn/en/info/1028/1106.htm"> Prof. Chenguang Wang</a>.


Education Background
======

**Harbin Institute of Technology (Shenzhen)** `2021.09 - `

- Ph.D. in Electronic Information, School of Computer Science and Technology
- Computing imaging, Artificial intelligence
- advised by [Prof. Yongbing Zhang](https://scholar.google.com/citations?user=0KlvTEYAAAAJ&hl=en)

**University of Vienna** `2024.09 - 2025.09`

- Joint Ph.D. in Advanced Microscopy and Cellular Dynamics at the Max Perutz labs
- Computing imaging, Artificial intelligence
- advised by [Prof. Jonas Ries](https://rieslab.de/)

**Shenzhen Bay Laboratory** `2022.01 - 2024.09`

- Visiting student at the Institute of Systems and Physical Biology
- Single particle tracking, super-resolution imaging, spectrum imaging
- Co-advised by [Assistant Prof. Shangguo Hou](https://www.szbl.ac.cn/en/scientificresearch/researchteam/2044.html) 


**Central South University** `2017.9 - 2020.6`

- GPA 3.6/4.0, Ranked 11 out of 168 students
- M.S. in Mechanical engineering, _Summa Cum Laude_
- Intelligent detection, Automation

**LuoYang Institute of Technology** `2013.9 - 2017.6`

- GPA 3.5/4.0, Ranked No.1 totally
- B.S. in Automation, _Summa Cum Laude_
- Mechanical Engineering Departmental Honors

Breaking News
------
[10/09/2024] Our manuscript titled "Reliable deep learning in anomalous diffusion against out-of-distribution dynamics" has been accepted by Nature Computation Science! I am the co-first author and congratulations to Xiaochen!

[19/08/2024] Congratulations to Senior Brother Liu Shuai on successfully defending his PhD thesis. Wishing him all the best in his future endeavors!!

[19/07/2024] I have been awarded the CSC scholarship and will soon join Professor Jonas Ries’s research group at the University of Vienna for a one-year research project. I hope to have an exciting experience in the next year.


Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
