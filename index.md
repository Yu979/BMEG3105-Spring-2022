---
layout: default
title: BMEG3105-Fall 2021
---

## BMEG3105: Data analytics for personalized genomics and precision medicine-Fall 2021

[<a href="https://forms.gle/574xARzoAmoc4EPS8">Pre-course survey</a>, <a href="http://piazza.com/cuhk.edu.hk/fall2021/bmeg3105">Piazza</a>, 
<a href="https://docs.google.com/spreadsheets/d/1yHtmqTbYZ754VE4yb6gazJM3jgnpIgOadQ0M7NIq9X0/edit?usp=sharing">Scribing preference</a>,
<a href="#logistics">Logistics</a>, <a href="#schedule_materials">Course schedule and materials</a>, <a href="#assignments">Assignments</a>]

### <a>Course description</a>
With social-economic development, people are increasingly caring about health. Consequently, in the field of genomics and healthcare, especially personalized genomics and precision medicine, we have accumulated a tremendous amount of data, which are waiting to be analyzed. This course is designed to equip students with the ability to analyze such data, which would benefit both the students' personal development and society. In the course, we will cover high-throughput experimental methods, standard data processing pipelines, sequence alignment and mapping, foundational concepts of data analytics, data exploration and visualization, clustering and classification, dimension reduction, and their applications in personalized genomics and precision medicine. 
For personalized genomics, we will also cover the integration of heterogeneous sequencing and non-sequencing data, single-cell data analysis, multi-omics analysis methods, and cancer genomics.
For precision medicine, we will cover protein-RNA interactions, biological graph analysis, and a gentle introduction to biomedical imaging and electronic health records.

#### Teaching team
Lecturer: 
Yu LI (<span style="color: #0099e6">liyuATcse.cuhk.edu.hk</span>), SHB-106. Office hour: 3pm-5pm, Friday <br>
TA: <br>
Licheng ZONG (<span style="color: #0099e6">lczong21ATcse.cuhk.edu.hk</span>), SHB-1026. Office hour: 3pm-5pm, Monday <br>
Xinyi ZHOU (<span style="color: #0099e6">xyzhou21ATcse.cuhk.edu.hk</span>), SHB-903. Office hour: 9am-11am, Thursday <br>

#### Time and location
<b>Wednesday</b>: <b>9:30am-11am</b>, <b>SC-L3</b>. <br>
<b>Friday</b>: <b>9:30am-10:15am</b>, <b>ERB-803</b>. <br>
Friday: <b>10:30-11:15am</b>, <b>ERB-803</b>. Tutorial <br>

#### Format
Mixed. Slides will be available the day before the lecture day. Video recordings will be available after the lecture.

### <a id="logistics">Logistics</a>



#### Communications
<b>Blackboard</b> is the main software to manage the course, and grading will be through blackboard. We will use <b>Piazza</b> (<a href="www.piazza.com/cuhk.edu.hk/fall2021/bmeg3105
">BMEG3105</a>) for discussion. You can ask questions through Piazza, even anonymously. For a personal matter, please use the private post to the instructor and the TA. You are also very welcomed to send <b>emails</b> to the instructor and TAs.


#### Grading
<ul>
<li><b>Homework (20%)</b>: Three grading homework (5%+5%+5%) and one non-grading programming assignment (5%, make sure you learn something from it).</li>
<li><b>Scribing (10%)</b>: Grading scribing. Summarize one of the lectures. Submit it within one week after the course. Each student should do at least one lecture. You can sign for at most two, for additional 1%.</li>
<li><b>In-class quiz (10%)</b>: Two in-class quizzes. The questions will be simple. Mainly for checking the participation. The exact date are in the below <a href="#schedule_materials">schedule</a>.</li>
<li><b>Midterm (20%)</b>: A grading midterm exam. One bonus question (2%). </li>
<li><b>Project (20%)</b>: A grading project. You can give us your project and seek our help or we will predefine some projects for you to choose (You should submit a mid-term report (5%), a final report (7%) + presentation (3%) together with the implementation (5%).) </li>
<li><b>Final (20%)</b>: A grading finals.</li>
</ul>

<b>Bonus (up to 6%)</b>: One bonus question in Midterm. One additional scribing: 1%. <b>Pre-course survey</b> + <b>Post-lecture survey</b>: 0.5% for each, and the maximum is 3%. I do encourage you to complete all of them so that to let me know your feedback and adjust the course accordingly. Send your names to the TA. 

#### Open-book quiz and exam policy
All exams and quiz are open-book. You are allowed to take any <b>paper-based materials</b>. However, no phone or computer is allowed. Other communication tools are also not allowed. Discussion is not allowed.


#### Programming
Python (the TA will prepare a recitation class to introduce it, mainly for the non-grading homework and your project) or any other you are familiar with. For python, we suggest you to use <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>. <br>
The programming credits include Non-grading assignment (10%) and Grading programming included in the project (5%). The bonus is sufficient to cover all the programming credit. If you really do not want to try hand-on experiments at all. We do encourage you try.

#### Scribing
Please sign <a href="https://docs.google.com/spreadsheets/d/1yHtmqTbYZ754VE4yb6gazJM3jgnpIgOadQ0M7NIq9X0/edit?usp=sharing">Scribing preference</a>. We should have at least one student for each lecture. We may adjust the assignment if necessary. Notice that your note and scribing will be posted online, for others reference. You can choose to remove your name or not. Deadline for signing the scribing: **<span style="color:red;">11:59 pm on 12th Sep</span>**. After that, the Google sheet will be closed.

#### Projects
We will do the project individually. You can give us your project and seek our help or we will predefine some projects for you to choose. Some potential projects:
<ul>
<li>From reads to gene expression matrix processing pipeline.</li>
<li>Gene expression matrix processing pipeline.</li>
<li>Single-cell RNA-seq processing pipeline.</li>
<li>Bio-image classification. </li>
<li>Cancer gene identification. </li>
<li>Gene enrichment analysis.</li>
</ul>
Both the mid-term report (1 page) and the final report should be submitted.

#### Late days
Each student will have <b>6 late days</b> to turn in assignments, which can be used on A1, A2, A3, PA1, and the project mid-term report. They cannot be used on the project final report and the scribing note. A maximum of 2 late days can be used for each assignment. Grades will be deducted by 25% for each additional late day. 

#### Post-lecture survey 
Deadline for each survey: **<span style="color:red;">11:59pm on the day before the next lecture</span>**. We do this because I could have time to answer the questions you mentioned in the survey. Please fill 1 in the Google sheet: <a href="https://docs.google.com/spreadsheets/d/11BZVDMN3RALPWu3mVp87uXOBjmtQQMQR7L1ZIA4-v8Y/edit?usp=sharing">Survey results</a>, once you have finished one survey. Usually, we will trust the 1s you fill in the Google sheet. But we will check the things in detail if the number of survey forms we received and the number of 1s on the Google sheet is not consistent.


### <a id="schedule_materials">Course schedule and materials</a>



| Lecture | Date  |Location| Topic | Slides/Video | Notes | Reading | Important dates (All due at **<span style="color:red;">11:59 pm</span>**)
| ------- |------- |-------| ------| -------|-------|---------|----------------
| 1       | Sep 8 (Wed)  | SC-L3  | Introduction    | <a href="https://www.dropbox.com/s/qvw0w98dz7i6cg2/lec1-Intro.pdf?dl=0">Lec-1</a>, <a href="https://youtu.be/n9ETjvekg4w">YouTube</a>, <a href="https://www.bilibili.com/video/BV1gv411w7Yw/">Bilibili</a> | <a href="https://www.dropbox.com/s/qg7avta8vrg14w2/Lec1-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/m6ffsfie76o25iy/Lec1-Scribing-2.pdf?dl=0">Note-2</a> | <a href="https://www.dropbox.com/s/zy6ss035yxd9miy/BMEG3150_Course%20Information_1st%20Term_2021-22.pdf?dl=0">Learning objectives</a>
| 2       | Sep 10 (Fri) | ERB-803| Data & Python   | <a href="https://www.dropbox.com/s/lkkqlwp6nz4unkx/lec2-data%20and%20python.pdf?dl=0">Lec-2</a>, <a href="https://www.youtube.com/watch?v=J2holV5Eiro">YouTube</a>, <a href="https://www.bilibili.com/video/BV1dg411F7rp/">Bilibili</a> | <a href="https://www.dropbox.com/s/vqns9o5f2ffv8fw/Lec2-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/v68sd1c3fihstk3/Lec2-Scribing-2.pdf?dl=0">Note-2</a> | <a href="https://colab.research.google.com/drive/1cdbEwWRqw2QUtITqvBj7u5m8NRgnY89Y?usp=sharing">Sample code</a> | <a href="#assignments">PA 0</a> posted
| 3       | Sep 15 (Wed) | SC-L3  | Sequence and DP | <a href="https://www.dropbox.com/s/z3nr6stjkncqkty/lec3-DP.pdf?dl=0">Lec-3</a>,  <a href="https://youtu.be/bdypTaNHx9g">YouTube</a>, <a href="https://www.bilibili.com/video/BV1vR4y1H7kL/">Bilibili</a> | <a href="https://www.dropbox.com/s/ef2hgl5rmaxcki6/Lec3-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/iljcqqaoijipp9v/Lec3-Scribing-2-Han%20Yi%20WANG.pdf?dl=0">Note-Wang,Han-Yi</a> | <a href="https://colab.research.google.com/drive/1QmT6a7XumAYbd_9NhVfLuu9VvpR7-mtP?usp=sharing">Sample code</a>, <a href="https://www.dropbox.com/s/tdxlt6yaigvj6jy/chapter2%263.pdf?dl=0">Chapter 2&3</a>| **<span style="color:red;">PA0 due</span>**
| 4       | Sep 17 (Fri) | ERB-803| Assembly & Mapping| <a href="https://www.dropbox.com/s/5f7hmhltqlqk8x3/lec4-Assembly%20and%20mapping.pdf?dl=0">Lec-4</a>, Video unavailable due to technical issue, <a href="https://www.youtube.com/watch?v=GZmkwBt51Xc">Makeup video YouTube</a>, <a href="https://www.bilibili.com/video/BV1v34y1S7QJ/">Makeup video Bilibili</a> | <a href="https://www.dropbox.com/s/xr8h6pe9o2o4r63/Lec4-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/ga0sk4x9u4s96l1/Lec4-Scribing-2.pdf?dl=0">Note-2</a> | <a href="https://www.dropbox.com/s/j6gu44xszr9e8jk/A%20survey%20of%20best%20practices%20for%20RNA-seq%20data%20analysis.pdf?dl=0">RNA-seq analysis</a>| A1 posted
|-| Sep 22 (Wed)| - |- |- |- |- | Mid-Autumn Festival
| 5       | Sep 24 (Fri) | ERB-803| Data exploration| <a href="https://www.dropbox.com/s/jeyfmvqp6dzh2oz/lec5-Exploration%20and%20cleaning.pdf?dl=0">Lec-5</a>, <a href="https://www.youtube.com/watch?v=3ETug0GChXA">YouTube</a>, <a href="https://www.bilibili.com/video/BV1nL41147iK/">Bilibili</a> | <a href="https://www.dropbox.com/s/annnxe9x8sjfiog/Lec5-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/9h5fyend3q3r8iv/Lec5-Scribing-2.pdf?dl=0">Note-2</a> |<a href="https://www.dropbox.com/s/7deoatc1jehuock/Repetitive%20DNA%20and%20next-generation%20sequencing-computational%20challenges%20and%20solutions.pdf?dl=0">Repetitive DNA</a>, <a href="https://github.com/chenomg/CS_BOOKS/blob/master/Python%20for%20Data%20Analysis%2C%202nd%20Edition.pdf">Python for DA</a>, <a href="https://colab.research.google.com/drive/1z0_IEP-tOZgt7auZqEMtLvmafVuHRP0d?usp=sharing">Sample code</a>, <a href="https://colab.research.google.com/drive/1p22oCIaFFfDU9BwzwdBVq3KPvD4BqBMS?usp=sharing">Sample code-2</a>|
| 6       | Sep 29 (Wed) | SC-L3  | Clustering      | <a href="https://www.dropbox.com/s/dn35jvi7l95f63h/lec6-Distance%20and%20clustering.pdf?dl=0">Lec-6</a>, <a href="https://www.youtube.com/watch?v=zqT7In24tHE">YouTube</a>, <a href="https://www.bilibili.com/video/BV1Wb4y1a7gY/">Bilibili</a> | <a href="https://www.dropbox.com/s/pls5e204th3mkld/Lec6-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/oqcxukdz4az2xmh/Lec6-Scribing-2.pdf?dl=0">Note-2</a>, <a href="https://www.dropbox.com/s/km4h00p4ifc5lvs/Lec6-Scribing-3.pdf?dl=0">Note-3</a> | <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a> | **<span style="color:red;">A1 due</span>**
|-| Oct 1 (Fri)| - |- |- |- |- | National Day
| 7       | Oct 6 (Wed)  | SC-L3  | Clustering & Classification  | <a href="https://www.dropbox.com/s/g585x9csl9h9w39/lec7-Classification.pdf?dl=0">Lec-7</a>, <a href="https://www.youtube.com/watch?v=o1aYNBtkJdY">YouTube</a>, <a href="https://www.bilibili.com/video/BV13r4y127PD/">Bilibili</a>| <a href="https://www.dropbox.com/s/1ss5p4ro7e0jc2r/Lec7-Scribing-1.pdf?dl=0">Note-1</a>,  <a href="https://www.dropbox.com/s/3m42p6xhmjkchub/Lec7-Scribing-2.pdf?dl=0">Note-2</a> | <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a>, <a href="https://colab.research.google.com/drive/1ogX-QiR1jBWuZjbTXGFhi9H-0XdpGNhU?usp=sharing">Correlation</a> | A2 posted
| 8       | Oct 8 (Fri)  | ERB-803| Classification | <a href="https://www.dropbox.com/s/bjfwtqk5ik7f9zo/lec8-Classification.pdf?dl=0">Lec-8</a>, <a href="https://www.youtube.com/watch?v=ylN8_C_aAKY">YouTube</a>, <a href="https://www.bilibili.com/video/BV17Q4y1X7D8/">Bilibili</a> | <a href="https://www.dropbox.com/s/hhzhde36b7gfvmi/Lec8-Scribing-1.pdf?dl=0">Note-1</a> | <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a> | 
| 9       | Oct 13 (Wed) | SC-L3  | Perf evaluation | <a href="https://www.dropbox.com/s/2yo6ecfwi7gpjno/lec9%2C10-Performance%20evaluation.pdf?dl=0">Lec-9,10</a>  | | | Cancelled due to typhoon
| 10       | Oct 15 (Fri)| ERB-803| Perf evaluation   | <a href="https://www.dropbox.com/s/2yo6ecfwi7gpjno/lec9%2C10-Performance%20evaluation.pdf?dl=0">Lec-9,10</a>, <a href="https://www.youtube.com/watch?v=T9Wamvx9DAM">YouTube</a>, <a href="https://www.bilibili.com/video/BV1gf4y1g7hC/">Bilibili</a> |  <a href="https://www.dropbox.com/s/l4ia6tkha939eny/Lec9%2610-Scribing-Chan%2C%20Wai%20Shing.pdf?dl=0">Note-Chan, Wai Shing</a>,  <a href="https://www.dropbox.com/s/tyy6h8hhj4wrdep/Lec9%2610-Scribing-1.pdf?dl=0">Note-1</a>  | <a href="https://github.com/FaizSaeed/Data-Science-Course/blob/master/Book/Introduction%20to%20Data%20Mining_Pang%20Ning%20Tan.pdf">Data mining book</a> | 
| 11       | Oct 20 (Wed)| SC-L3  | Mid-term review | <a href="https://www.dropbox.com/s/a5f06ybjid47lnm/lec11-Mid-term%20review%20and%20Feature%20selection%20and%20DR.pdf?dl=0">Lec-11</a>, <a href="https://www.youtube.com/watch?v=E60R67ELzp4">YouTube</a>, <a href="https://www.bilibili.com/video/BV16h411b7zB/">Bilibili</a> | <a href="https://www.dropbox.com/s/0yweq74fcpulrdj/Lec11-Scribing-CHAN%2C%20Chi%20Chung.pdf?dl=0">Note-CHAN, Chi Chung</a>, <a href="https://www.dropbox.com/s/yxrofxzizicuxpt/Lec11-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/zqvv6b6dzp0l8kx/Lec11-Scribing-2.pdf?dl=0">Note-2</a>, <a href="https://www.dropbox.com/s/fzt4jppzabyrd0p/Lec11-Scribing-3.pdf?dl=0">Note-3</a>| | **<span style="color:red;">ParticipationQ,</span>** **<span style="color:red;">A2 due</span>**
| 12       | Oct 22 (Fri)| ERB-803| - |- |- |- |**<span style="color:red;">8:30am-11:15am, Mid-term</span>**
||||<span style="color:blue;">Module 2 start</span>|
| 13       | Oct 27 (Wed)| SC-L3  |  Dim reduction   | <a href="https://www.dropbox.com/s/thobkc2lc2z1b0q/lec13-Feature%20selection%20and%20DR.pdf?dl=0">Lec-13</a>, <a href="https://www.youtube.com/watch?v=_FgkixErkak">YouTube</a>, <a href="https://www.bilibili.com/video/BV1j44y1i7Pw/">Bilibili</a> | <a href="https://www.dropbox.com/s/wdqnoepqkgrnna4/Lec13-Scribing-LI%2C%20Xuanxuan.pdf?dl=0">Note-LI, Xuanxuan</a>, <a href="https://www.dropbox.com/s/c1a14rb3vz89yu7/Lec13-Scribing-FUNG%2C%20Cheuk%20Wa.pdf?dl=0">Note-FUNG, Cheuk Wa</a>, <a href="https://www.dropbox.com/s/zav88afbrdd9nps/Lec13-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/3kotn1v134nslt4/Lec13-Scribing-2.pdf?dl=0">Note-2</a> | <a href="https://github.com/probml/pml-book">PML book</a>| PA1 posted
| 14       | Oct 29 (Fri)| ERB-803| Multi-omics & cancer genomics overview | <a href="https://www.dropbox.com/s/4afxnvc2czrree6/lec14-multi-omics.pdf?dl=0">Lec-14</a>, <a href="https://www.youtube.com/watch?v=Jj5Eezp4DHY">YouTube</a>, <a href="https://www.bilibili.com/video/BV1yT4y1R7kZ/">Bilibili</a> | <a href="https://www.dropbox.com/s/96b3d2upln8yzuu/Lec14-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/on6v35tocw8bpyv/Lec14-Scribing-2.pdf?dl=0">Note-2</a>, <a href="https://www.dropbox.com/s/b0lpro4rp5n9s8x/Lec14-Scribing-3.pdf?dl=0">Note-3</a> | <a href="https://www.cancer.gov/about-cancer/understanding/what-is-cancer">Intro to cancer</a>, <a href="https://www.ebi.ac.uk/training/materials/cancer-genomics-materials/">Cancer genomics</a> | 
| 15       | Nov 3 (Wed) | SC-L3  | TUT | | | | 
| 16       | Nov 5 (Fri) | ERB-803| Cancer genomics     | <a href="https://www.dropbox.com/s/s8vylebf6f5lxjn/lec16-cancer%20genomics.pdf?dl=0">Lec-16</a>, <a href="https://www.youtube.com/watch?v=JVDalTxYYNc">YouTube</a>, <a href="https://www.bilibili.com/video/BV14S4y1d7A3/">Bilibili</a>  | <a href="https://www.dropbox.com/s/nmgpmvs59emtwbc/Lec16-Scribing-WONG%2C%20Wing%20Hei.pdf?dl=0">Note-WONG, Wing Hei</a>, <a href="https://www.dropbox.com/s/67p6rn4sqequmra/Lec16-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/ldbqtp1pggjdom0/Lec16-Scribing-2.pdf?dl=0">Note-2</a> | <a href="https://www.ebi.ac.uk/training/materials/cancer-genomics-materials/">Cancer genomics</a>, <a href="https://drive.google.com/drive/folders/1y7q0gJ-ohNDhKG85UTRTwW1Jkq4HJ5M3">GATK</a>, <a href="https://www.youtube.com/watch?v=xw419NKqMqw">GWAS</a>, <a href="https://www.youtube.com/watch?v=IAu44BkOaSs">Epigenetics</a>, <a href="https://www.encodeproject.org/atac-seq/">ENCODE</a>| 
| 17       | Nov 10 (Wed)| SC-L3  | Single cell & visualization   | <a href="https://www.dropbox.com/s/233xl5kp7p612f9/lec17-single%20cell.pdf?dl=0">Lec-17</a>, <a href="https://www.youtube.com/watch?v=V_LLp6jRg94">YouTube</a>, <a href="https://www.bilibili.com/video/BV1Sf4y1u7bf/">Bilibili</a> | <a href="https://www.dropbox.com/s/ssxhpf3m8j1pclc/Lec17-Scribing-LO%2C%20Yue%20Lung%20Edison.pdf?dl=0">Note-LO, Yue Lung Edison</a>, <a href="https://www.dropbox.com/s/nd0k5t3zb76hn4r/Lec17-Scribing-1.pdf?dl=0">Note-1</a> | <a href="https://www.dropbox.com/s/7kqrm7jdn4swsor/Single%20cell-Current%20best%20practice.pdf?dl=0">Current best practice</a>, <a href="https://www.dropbox.com/s/ibcw0mlsq4f2zl2/Single%20cell-Tutorial.pdf?dl=0">Tutorial-1</a>, <a href="https://broadinstitute.github.io/2019_scWorkshop/">Tutorial-2</a>, <a href="https://www.singlecellcourse.org/index.html">Tutorial-3</a>, <a href="https://www.dropbox.com/s/99o7ph37b9uveau/Single%20cell-Clustering%20challenges.pdf?dl=0">Clustering challenges</a> | **<span style="color:red;">Project M-report</span>**
| 18       | Nov 12 (Fri)| ERB-803| Protein-RNA     | <a href="https://www.dropbox.com/s/8lrim5j3zqnb7na/lec18-visualization.pdf?dl=0">Lec-18</a>, <a href="https://www.youtube.com/watch?v=HHPlVM6hwYs">YouTube</a>, <a href="https://www.bilibili.com/video/BV14b4y1t7UR/">Bilibili</a> | <a href="https://www.dropbox.com/s/js8ni9dtdz1tl7k/Lec18-Scribing-CHAN%2C%20Yun%20Lam.pdf?dl=0">Note-CHAN, Yun Lam</a>, <a href="https://www.dropbox.com/s/c0zw4s72rk4jyk8/Lec18-Scribing-LO%2C%20Yue%20Lung%20Edison.pdf?dl=0">Note-LO, Yue Lung Edison</a> | <a href="https://www.dropbox.com/s/idrobwfp4clars3/lec18-IntroductionToSequenceMotifs.pdf?dl=0">Sequence motif</a>, <a href="https://colab.research.google.com/drive/1Mmtu4pLfj1Cak-MaWaB5f7y6XvqiO1tc?usp=sharing">PCA-tSNE-UMAP</a> | 
| |||<span style="color:blue">Module 3 start</span>|
| 19       | Nov 17 (Wed)| SC-L3  | Deep learning  | <a href="https://www.dropbox.com/s/zhscu1ldu0gflej/lec19-deep%20learning.pdf?dl=0">Lec-19</a>, <a href="https://www.youtube.com/watch?v=euz7bNbqo-8">YouTube</a>, <a href="https://www.bilibili.com/video/BV1HR4y1t7Yh/">Bilibili</a> | <a href="https://www.dropbox.com/s/9hn05plnjlg931s/Lec19-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/ycd3stvy9rdhdyj/Lec19-Scribing-2.pdf?dl=0">Note-2</a>| <a href="https://colab.research.google.com/drive/1CEF_yzuCazecajrDblegX6hw3pBPm-qN?usp=sharing">Pytorch examples</a> | **<span style="color:red;">PA1 due</span>**, A3 posted
| 20       | Nov 19 (Fri)| ERB-803| How to present| <a href="https://www.dropbox.com/s/0ag7qqcas12q1qy/lec20-presentation.pdf?dl=0">Lec-20</a>, <a href="https://www.youtube.com/watch?v=Xe7lV3XlU7U">YouTube</a>, <a href="https://www.bilibili.com/video/BV1CF411h7e1/">Bilibili</a> | <a href="https://www.dropbox.com/s/nmi84cgane79ic4/Lec20-Scribing-1.pdf?dl=0">Note-1</a> | <a href="https://colab.research.google.com/drive/1CEF_yzuCazecajrDblegX6hw3pBPm-qN?usp=sharing">Pytorch examples</a> |
| 21       | Nov 24 (Wed)| SC-L3  | EHRs & How to learn | <a href="https://www.dropbox.com/s/36q6xjxr61tu36h/lec21-ehr.pdf?dl=0">Lec-21</a>, <a href="https://www.youtube.com/watch?v=KCTJwAsWqmY">YouTube</a>, <a href="https://www.bilibili.com/video/BV1FU4y1T7sp/">Bilibili</a> | <a href="https://www.dropbox.com/s/ypbhpnn8uybmadl/Lec21-Scribing-1.pdf?dl=0">Note-1</a>, <a href="https://www.dropbox.com/s/l9gc9k8mddi2ez7/Lec21-Scribing-2.pdf?dl=0">Note-2</a>, <a href="https://www.dropbox.com/s/ovmhpaf9meo755p/Lec21-Scribing-3.pdf?dl=0">Note-3</a> | <a href="https://towardsdatascience.com/introduction-to-clinical-natural-language-processing-predicting-hospital-readmission-with-1736d52bc709">EHRs processing</a> |
| 22       | Nov 26 (Fri)| ERB-803| Project pres   | <a href="https://docs.google.com/spreadsheets/d/1_D_mAbF9LZiJwA8Jug6if9phoOjg5FIi_Vq23ADnxY0/edit?usp=sharing">Presentation schedule</a>| | | **<span style="color:red;">A3 due</span>**
| 23       | Dec 1 (Wed) | SC-L3  | Course review | <a href="https://www.dropbox.com/s/j0ckfwk7fhu8nd8/lec23-Course%20review.pdf?dl=0">Lec-23</a>, <a href="https://www.youtube.com/watch?v=Uf9uD5dwbfc">YouTube</a>, <a href="https://www.bilibili.com/video/BV1DP4y1V7Bh/">Bilibili</a> | | | **<span style="color:red;">ParticipationQ</span>**
| 24       | Dec 3 (Fri) | ERB-803| Project pres  |<a href="https://docs.google.com/spreadsheets/d/1_D_mAbF9LZiJwA8Jug6if9phoOjg5FIi_Vq23ADnxY0/edit?usp=sharing">Presentation schedule</a> | | | **<span style="color:red;">Project report</span>**

### <a id="assignments">Assignments</a>
<ul>
<li>Programming Assignment 0: Get yourself familiar with <a href="https://colab.research.google.com/notebooks/intro.ipynb">Colab</a>, set up the environment and run this <a href="https://colab.research.google.com/drive/1cdbEwWRqw2QUtITqvBj7u5m8NRgnY89Y?usp=sharing
">code</a>. </li>

<li>Assignment 1: Basic concept of data analytics-1</li>

<li>Assignment 2: Basic concept of data analytics-2</li>

<li>Programming Assignment 1: Application of DA to biology</li>

<li>Assignment 3: DA in Personalized Genomics and Precision Medicine</li>

</ul>
