---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

# 🔥 News

- _2022.07_: &nbsp;🎉🎉 I was taking the wheeled robot challenges in the ETH RobotX summer school at Geneve !

# 📝 Publications

Working on it ....

<!-- <div class='paper-box'>

<div class='paper-box-image'>
    <div>
        <div class="badge">CVPR 2016</div>
        <img src='images/500x300.png' alt="sym" width="100%">
    </div>
</div>

<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>

- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
</div>

</div> -->


# 📝 Projects and Researches


<div class='paper-box'>
<div class='paper-box-image'><div>
        <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/500x300.png' alt="sym" width="100%">
</div></div>

<div class='paper-box-text' markdown="1">

[(Project) Lidar-Visual-Inertial Odometry with Gaussian Splatting]()
- Incorporation of LiDAR depth information instead of Stereo based depth improving accuracy and consistency of GS SLAM
- Implemented a loosely coupled, optimization-based LVIO system via fusing Lidar and RGB data.
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
        <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/500x300.png' alt="sym" width="100%">
</div></div>

<div class='paper-box-text' markdown="1">

[(Master’s Project) 6D Pose Tracking and Reconstruction of Objects with RGB only]()
- Object pose estimation and reconstruction in scenarios with static camera and hand-held moving object
- Used metric mono-depth prediction with noisy- scale and estimated object poses by a robust optimizer
- Reconstruction and enforcing scale-consistency via Gaussian Splatting
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
        <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/500x300.png' alt="sym" width="100%">
</div></div>

<div class='paper-box-text' markdown="1">

[(Project) Head-Worn Camera Image Stabilization using Neural Radiance Field]()
- Modified and extended the ‘Depth-Supervised NeRF’ pipeline for reconstructing indoor environments using the depth prior.
- Achieved good reconstruction quality in the bedroom scene given limited training frames (Sparse NeRF)
</div>
</div>



<div class='paper-box'>
<div class='paper-box-image'><div>
        <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/500x300.png' alt="sym" width="100%">
</div></div>

<div class='paper-box-text' markdown="1">

[(Bachelor’s Thesis) Neural Representation-based Medical Microscopic Image Compression]()
- Designed an Embedding-MLP-PixelShuffle pipeline to compress single image based on neural representation.
- Designed a medical microscope image-based subsampling algorithm to reduce image size at the sending end and deployed a neural representation network for super-resolution of the decompressed image at the receiving end.
</div>
</div>



<div class='paper-box'>
<div class='paper-box-image'><div>
        <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/500x300.png' alt="sym" width="100%">
</div></div>

<div class='paper-box-text' markdown="1">

[(Bachelor’s Thesis) Multi-Arm Concentric Tube Robot for Minimally Invasive Surgery]()
- Designed a fully functional system for clinical minimally invasive surgery. Including design of the mechanical structure, kinematic modeling, calibration on the concentric tube arm, and calibration on the Multi-Arm C.T.R. system.
- Designed a 6D pose detection algorithm for the end vision tag of the continuum robot (C++)
- Designed a calibration algorithm for C.T.R.  and deployed inter-arm hand-eye calibration on the Multi-Arm CTR system
- Achieved inter-arm motion independence and a more concentrated distribution of surgery arms (closer to each other)
</div>
</div>


<div class='paper-box'>
<div class='paper-box-image'><div>
        <!-- <div class="badge">CVPR 2016</div> -->
        <img src='images/500x300.png' alt="sym" width="100%">
</div></div>

<div class='paper-box-text' markdown="1">

[(Project) Orbital Inspection Robot]()
- A security robot patrols on a suspended track. Mainly a two-axis gimbal with a camera mounted underneath the robot, which scans the surrounding environment and identifies safety hazards through a neural network.
- Design and implementation of an object-oriented code framework for embedded system of robots
- Including an embedding C code OOP framework (STM32), and a modified YOLOv5 classification network (Intel NUC).
</div>
</div>



# 📖 Educations

- _2022.09 - present_, M.Sc. in Informatics, **University of Zurich**, Switzerland
- _2018.09 - 2022.06_, B.Eng. in Mechanical Engineering & B.Eng. in Computer Science, **Harbin Institute of Technology**, China

# 💻 Workings

- _2024.02 - 2024.06_, Teaching Assistant of [Informatics II](https://www.ifi.uzh.ch/en/dbtg/teaching/courses/infoII.html), University of Zurich, Switzerland.


# 🎖 Honors and Awards

- _2021, 2022_ National First Prize in the 20th / 21th China National College Robotic Competition ‘RoboMaster’
- _2020_ Regional Second Prize in the 12th Mathematics Competition of Chinese College Students
- _2020_ Regional First Prize in the 9th China National College Mechanical Innovation Competition
- _2021_ National Scholarship for Undergraduates
- _2022_ Outstanding graduators award (top 7%)
- _2019, 2020_ Outstanding Scholarship of School of M.E.A of Harbin Institute of Technology (top 5%)
- _2019, 2020, 2021_ Outstanding Student Award (Merit Student) of Harbin Institute of Technology (top 10%)


<!-- # 💬 Invited Talks

- _2021.06_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.
- _2021.03_, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. \| [\[video\]](https://github.com/) -->


# Miscellaneous

- _2019 - 2021_ Team leader of the robotic competition team at HIT Shenzhen campus
- _2019_ Champion of the university’s football match, as captain and defender.
- _2019_ Third place as a team in University's badminton matches, Men’s doubles.