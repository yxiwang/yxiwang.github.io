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

I am currently an Associate Professor in the [Faculty of Information Science and Engineering,](https://it.ouc.edu.cn/) [Ocean University of China](www.ouc.edu.cn). Before I joined OUC, I worked as an Assistant Professor in [Centre for Artificial Intelligence and Robotics (CAIR), Hong Kong Institute of Science & Innovation, Chinese Academy of Sciences](https://www.cair-cas.org.hk/) from 2022 to 2025. I received my Ph.D. degree from [Institute of Automation, Chinese Academy of Sciences](http://www.ia.cas.cn/) (Beijing, China), under the supervision of [Prof. Zhaoxiang Zhang](https://www.zhaoxiangzhang.net) in 2022. I received my B.E. degree from [Northeastern University](https://www.neu.edu.cn/) (Shenyang, China) in 2016.

My research interests focus on 3D generative AI and Embodied AI, including 3D scene generation, 3D reconstruction, MLLMs, image/video generation and robotics. 
Please do not hesitate to reach out if you would like to explore possible collaboration.



# 🔥 News
- *2025.06*: &nbsp;🎉🎉 One paper has been accepted by [MICCAI 2025](https://conferences.miccai.org/2025/en/). 
- *2025.04*: &nbsp;🎉🎉 One paper has been accepted by IEEE TPAMI.
- *2025.04*: &nbsp;🎉🎉 One paper has been accepted by IJCV.


# 📝 Selected Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2025</div><div style="width:40px; height:20px; object-fit:contain;"></div><img src='images/HardPatchMining.png' alt="sym" width="100%" height="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bootstrap Masked Visual Modeling Via Hard Patch Mining** [[Paper](https://arxiv.org/pdf/2312.13714) [Code](https://github.com/Haochen-Wang409/HPM)]

Haochen Wang, Junsong Fan, **Yuxi Wang**, Kaiyou Song, Tiancai Wang, Xiangyu Zhang, Zhaoxiang Zhang. **IEEE TPAMI 2025**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/U2PL.png' alt="sym" width="200" height="60"></div></div>
<div class='paper-box-text' markdown="1">

**Using unreliable pseudo-labels for label-efficient semantic segmentation** [[Paper](https://arxiv.org/pdf/2306.02314) [Code](https://github.com/Haochen-Wang409/U2PL)]

Haochen Wang, Yuchao Wang, Yujun Shen, Junsong Fan, **Yuxi Wang**, Zhaoxiang Zhang. **IJCV 2025**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">T-PAMI 2024</div><img src='images/ATP.png' alt="sym" width="100%" height="30%"></div>
<div class='paper-box-text' markdown="1">

**A Curriculum-style Self-training Approach for Source-free Semantic Segmentation** [[Paper](https://arxiv.org/pdf/2106.11653)] [[code](https://github.com/yxiwang/ATP)] \\
**Yuxi Wang**, Jian Liang, Zhaoxiang Zhang. **IEEE TPAMI 2024**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2024</div><img src='images/T2S-DA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Pulling target to source: A new perspective on domain adaptive semantic segmentation** [[Paper](https://arxiv.org/pdf/2305.13752)]

Haochen Wang, Yujun Shen, Jingjing Fei, Wei Li, Liwei Wu, **Yuxi Wang#**, Zhaoxiang Zhang. **IJCV 2024**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/SACL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Enhancing Sound Source Localization via False Negative Elimination** [[Paper](https://arxiv.org/pdf/2408.16448) [Code](https://github.com/zjsong/SACL)]

Zengjie Song, Jiangshe Zhang, **Yuxi Wang**, Junsong Fan, Zhaoxiang Zhang. **IEEE TPAMI 2024**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/SACL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MMT: Cross Domain Few-shot Learning via Meta-memory Transfer** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10224305)]

Wenjian Wang, Lijuan Duan, **Yuxi Wang**, Junsong Fan, Zhaoxiang Zhang. **IEEE TPAMI 2024**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/SceneX.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SceneX : Procedural Controllable Large-scale Scene Generation** [[Paper](https://arxiv.org/pdf/2403.15698) [Project](https://zhouzq1.github.io/SceneX/)]

Mengqi Zhou*, **Yuxi Wang***, Jun Hou, Shougao Zhang, Yiwei Li, Chuanchen Luo, Junran Peng, Zhaoxiang Zhang. **AAAI 2025**

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/Material3DSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Materialseg3d: Segmenting dense materials from 2d priors for 3d assets** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3680757) [Code](https://github.com/PROPHETE-pro/MaterialSeg3D) [Project](https://materialseg3d.github.io/)[Data](https://drive.google.com/file/d/1wDJg7Rp4AYn1OAKvZONrKj62Jd2cdID0/view)]

Zeyu Li, Ruitong Gan, Chuanchen Luo, **Yuxi Wang**, Jiaheng Liu, Ziwei Zhu, Qing Li, Xucheng Yin, Man Zhang, Zhaoxiang Zhang, Junran Peng. **ACM MM 2024** (*Orial*)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/Material3DSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Stablemofusion: Towards robust and efficient diffusion-based motion generation framework** [[Paper](https://arxiv.org/pdf/2405.05691) [Code](https://github.com/Linketic/StableMoFusion) [Project](https://h-y1heng.github.io/StableMoFusion-page/)]

Yiheng Huang, Hui Yang, Chuanchen Luo, **Yuxi Wang**, Shibiao Xu, Zhaoxiang Zhang, Man Zhang, Junran Peng. **ACM MM 2024** (*Orial*)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/GGSD.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Open vocabulary 3d scene understanding via geometry guided self-distillation** [[Paper](https://arxiv.org/pdf/2407.13362?) [Code](t https://github.com/Wang-pengfei/GGSD)]

Pengfei Wang, **Yuxi Wang**, Shuai Li, Zhaoxiang Zhang, Zhen Lei, Lei Zhang. **ECCV 2024** 

</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**

# 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
