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

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2021</div><img src='images/HPM-PAMI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Bootstrap Masked Visual Modeling Via Hard Patch Mining** [[Paper](https://arxiv.org/pdf/2312.13714) [Code](https://github.com/Haochen-Wang409/HPM)]

Haochen Wang, Junsong Fan, **Yuxi Wang**, Kaiyou Song, Tiancai Wang, Xiangyu Zhang, Zhaoxiang Zhang.

IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI 2025)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/U2PL-IJCV.png' alt="sym" width="70%" height="30%"></div></div>
<div class='paper-box-text' markdown="1">

**Using unreliable pseudo-labels for label-efficient semantic segmentation** [[Paper](https://arxiv.org/pdf/2306.02314) [Code](https://github.com/Haochen-Wang409/U2PL)]

Haochen Wang, Yuchao Wang, Yujun Shen, Junsong Fan, **Yuxi Wang**, Zhaoxiang Zhang. 

International Journal of Computer Vision (IJCV 2025)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">T-PAMI 2024</div><img src='images/ATP-PAMI.png' alt="sym" width="70%" height="30%"></div>
<div class='paper-box-text' markdown="1">

**A Curriculum-style Self-training Approach for Source-free Semantic Segmentation** [[Paper](https://arxiv.org/pdf/2106.11653)] [[code](https://github.com/yxiwang/ATP)] \\

**Yuxi Wang**, Jian Liang, Zhaoxiang Zhang. 

IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2024</div><img src='images/T2S-DA-IJCV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Pulling target to source: A new perspective on domain adaptive semantic segmentation** [[Paper](https://arxiv.org/pdf/2305.13752)]

Haochen Wang, Yujun Shen, Jingjing Fei, Wei Li, Liwei Wu, **Yuxi Wang#**, Zhaoxiang Zhang. 

International Journal of Computer Vision (IJCV 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2024</div><img src='images/SACL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Enhancing Sound Source Localization via False Negative Elimination** [[Paper](https://arxiv.org/pdf/2408.16448) [Code](https://github.com/zjsong/SACL)]

Zengjie Song, Jiangshe Zhang, **Yuxi Wang**, Junsong Fan, Zhaoxiang Zhang. 

IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TPAMI 2023</div><img src='images/MMT-PAMI.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MMT: Cross Domain Few-shot Learning via Meta-memory Transfer** [[Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10224305)]

Wenjian Wang, Lijuan Duan, **Yuxi Wang**, Junsong Fan, Zhaoxiang Zhang. 

IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI 2023)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/SceneX.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SceneX : Procedural Controllable Large-scale Scene Generation** [[Paper](https://arxiv.org/pdf/2403.15698) [Project](https://zhouzq1.github.io/SceneX/)]

Mengqi Zhou*, **Yuxi Wang***, Jun Hou, Shougao Zhang, Yiwei Li, Chuanchen Luo, Junran Peng, Zhaoxiang Zhang. 

Proceedings of the AAAI Conference on Artificial Intelligence （AAAI 2025）

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/Material3DSeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Materialseg3d: Segmenting dense materials from 2d priors for 3d assets** [[Paper](https://dl.acm.org/doi/pdf/10.1145/3664647.3680757) [Code](https://github.com/PROPHETE-pro/MaterialSeg3D) [Project](https://materialseg3d.github.io/)[Data](https://drive.google.com/file/d/1wDJg7Rp4AYn1OAKvZONrKj62Jd2cdID0/view)]

Zeyu Li, Ruitong Gan, Chuanchen Luo, **Yuxi Wang**, Jiaheng Liu, Ziwei Zhu, Qing Li, Xucheng Yin, Man Zhang, Zhaoxiang Zhang, Junran Peng. 

Proceedings of the 32nd ACM International Conference on Multimedia (ACM MM 2024) (*Oral*)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/StableMotion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Stablemofusion: Towards robust and efficient diffusion-based motion generation framework** [[Paper](https://arxiv.org/pdf/2405.05691) [Code](https://github.com/Linketic/StableMoFusion) [Project](https://h-y1heng.github.io/StableMoFusion-page/)]

Yiheng Huang, Hui Yang, Chuanchen Luo, **Yuxi Wang**, Shibiao Xu, Zhaoxiang Zhang, Man Zhang, Junran Peng. 

Proceedings of the 32nd ACM International Conference on Multimedia (ACM MM 2024) (*Oral*)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/GGSD-ECCV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Open vocabulary 3d scene understanding via geometry guided self-distillation** [[Paper](https://arxiv.org/pdf/2407.13362?) [Code](https://github.com/Wang-pengfei/GGSD)]

Pengfei Wang, **Yuxi Wang**, Shuai Li, Zhaoxiang Zhang, Zhen Lei, Lei Zhang.

European Conference on Computer Vision (ECCV 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/HardMo-CVPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hardmo: A large-scale hardcase dataset for motion capture** [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Liao_HardMo_A_Large-Scale_Hardcase_Dataset_for_Motion_Capture_CVPR_2024_paper.pdf) [Project](https://ljqnb.github.io/HardMo.github.io/)]

Jiaqi Liao, Chuanchen Luo, Yinuo Du, **Yuxi Wang**, Xucheng Yin, Man Zhang, Zhaoxiang Zhang, Junran Peng. 

Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images/ContiouFL-CVPR.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Continual forgetting for pre-trained vision models** [[Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Zhao_Continual_Forgetting_for_Pre-trained_Vision_Models_CVPR_2024_paper.pdf) [Code](https://github.com/bjzhb666/GS-LoRA)]

Hongbo Zhao, Bolin Ni, Junsong Fan, **Yuxi Wang**, Yuntao Chen, Gaofeng Meng, Zhaoxiang Zhang. 

Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2024)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/DropPos-NeurIPS.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**DropPos: Pre-Training Vision Transformers by Reconstructing Dropped Positions** [[Paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/9098e2901b4eb54772f83535f89cb8ac-Paper-Conference.pdf) [Code](https://github.com/Haochen-Wang409/DropPos)]

Haochen Wang, Junsong Fan, **Yuxi Wang**, Kaiyou Song, Tong Wang, Zhaoxiang Zhang.

Advances in Neural Information Processing Systems (NeurIPS 2023)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/SSF-ICCV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**SSF: Accelerating training of spiking neural networks with stabilized spiking flow** [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_SSF_Accelerating_Training_of_Spiking_Neural_Networks_with_Stabilized_Spiking_ICCV_2023_paper.pdf)]

Jingtao Wang, Zengjie Song, **Yuxi Wang**, Jun Xiao, Yuran Yang, Shuqi Mei, Zhaoxiang Zhang. 

Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV 2023)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2023</div><img src='images/IDM-ICCV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Informative data mining for one-shot cross-domain semantic segmentation** [[Paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_Informative_Data_Mining_for_One-Shot_Cross-Domain_Semantic_Segmentation_ICCV_2023_paper.pdf) [Code](https://github.com/yxiwang/IDM)]

**Yuxi Wang**, Jian Liang, Jun Xiao, Shuqi Mei, Yuran Yang, Zhaoxiang Zhang. 

Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV 2023)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2022</div><img src='images/HardPatch.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Hard patches mining for masked image modeling** [[Paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Wang_Hard_Patches_Mining_for_Masked_Image_Modeling_CVPR_2023_paper.pdf) [Code](https://github.com/Haochen-Wang409/HPM)]

Haochen Wang, Kaiyou Song, Junsong Fan, **Yuxi Wang**, Jin Xie, Zhaoxiang Zhang. 

Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR 2022)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2021</div><img src='images/UncerDA.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Uncertainty-aware pseudo label refinery for domain adaptive semantic segmentation** [[Paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Uncertainty-Aware_Pseudo_Label_Refinery_for_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.pdf)]

**Yuxi Wang**, Junran Peng, Zhaoxiang Zhang. 

Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV 2021)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2021</div><img src='images/I2I-TIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Multi-domain image-to-image translation via a unified circular framework** [[Paper](https://ieeexplore.ieee.org/abstract/document/9262049)]

**Yuxi Wang**, Zhaoxiang Zhang, Wangli Hao, Chunfeng Song. 

IEEE Transactions on Image Processing (IEEE TIP 2021)

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TIP 2021</div><img src='images/MSDA-TIP.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Attention guided multiple source and target domain adaptation** [[Paper](https://ieeexplore.ieee.org/abstract/document/9242273/)]

**Yuxi Wang**, Zhaoxiang Zhang, Wangli Hao, Chunfeng Song. 

IEEE Transactions on Image Processing (IEEE TIP 2021)

</div>
</div>


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
