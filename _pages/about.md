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

<div style='font-size:14pt; text-align:justify; font-family:Georgia; margin-top: 50pt'>
  <div style='width: 95%; vertical-align: middle; margin-left: 3%'>
Bo Zhang received the Ph.D. degree in electronic engineering from the School of Information Science and Technology, Fudan University. He is currently a research scientist in Shanghai AI Laboratory. His work has led to many awards, including **Shanghai Rising Star** under Grant No. 23QD1401000, awarded by the Shanghai Municipal Commission of Science and Technology, the National Scholarship 2021 China Award, the 2019 Excellent Doctoral Scholarship of Fudan University Award, and various awards from VALSE China and Shanghai Government. His research outcomes have some impacts on industrial applications like airport checkpoint security perceptual recognition and localization of concealed or dangerous objects. 

He has published 30+ papers in top-tier international conferences and journals such as CVPR, NeurIPS, ICLR, T-PAMI, TIP, T-MM, and IJCV. He also serves as a reviewer for several prestigious academic conferences and journals, including CVPR, ECCV, ICCV, ICLR, and ICML. Professionally, he led the development of the 3DTrans general scene representation open-source project, which won the Waymo Challenge international competition and accumulated over 10k stars. Additionally, he is committed to promoting the rapid application of multi-modal large language models in various scenarios, such as scientific document understanding, scientific research surveys, mathematical reasoning, and autonomous driving.
  </div>
</div>

<div style='margin-top: 30pt'></div>

# 🔥 News
**2024:**
  - <p style='text-align:justify'><i>2024.10</i>: &nbsp;🎉🎉 Grateful for the heartfelt recognition and thoughtful sharing of my research work <font color="red">[Fudan_CYL](https://mp.weixin.qq.com/s/KVAI0Q7spu6yot-6oQOewQ) and [Fudan_SIST](https://mp.weixin.qq.com/s/7Uka2AwZEqsGIp_5mDu6-A)</font>.</p>
  - <p style='text-align:justify'><i>2024.10</i>: &nbsp;🎉🎉 The technical report for <font color="red">[MinerU](https://arxiv.org/abs/2409.18839)</font>, an open-source solution for high-precision document content extraction, has been published. </p>
  - <p style='text-align:justify'><i>2024.09</i>: &nbsp;🎉🎉 Three papers ([AdaptiveDiffusion](https://arxiv.org/abs/2410.09873), [ZOPP](https://arxiv.org/abs/2411.05311), [LeapAD](https://arxiv.org/abs/2405.15324) <font color="red">NeurIPS 2024</font>.</p>
  - <p style='text-align:justify'><i>2024.09</i>: &nbsp;🎉🎉 Previous evaluation metrics for Formula and Table Recognition tasks, such as BLEU and Edit Distrance, exhibit limitations. <font color="red"> [CDM](https://github.com/opendatalab/UniMERNet/tree/main/cdm)</font> has been released to ensure the evaluation objectivity by designing an image-level rather than LaTex-level metric score for Formula and Table Recognition evaluation.</p>
  - <p style='text-align:justify'><i>2024.08</i>: &nbsp;🎉🎉 Bo Zhang was invited to serve as a PC member of <font color="red">AAAI 2025</font>.</p>
  - <p style='text-align:justify'><i>2024.08</i>: &nbsp;🎉🎉 We open-sourced Table Structural Extraction Model <font color="red">[Models](https://huggingface.co/U4R/StructTable-base) and [StructEqTable-Deploy](https://github.com/UniModal4Reasoning/StructEqTable-Deploy)</font>.It is a open-source repository to support the structuring tasks of visual tables.</p>
  - <p style='text-align:justify'><i>2024.08</i>: &nbsp;🎉🎉 We collaborated with the OpenDataLab team to open-source the <font color="red">[PDF-Extract-Kit](https://github.com/opendatalab/PDF-Extract-Kit?tab=readme-ov-file)</font>. It can extract high-quality and structured content from PDFs and has gained **6K+** stars.</p>
  - <p style='text-align:justify'><i>2024.07</i>: &nbsp;🎉🎉 One paper (Reg-TTA3D) is accepted by <font color="red">ECCV 2024</font>. We explore test-time adaptive 3d object detection for the first time.</p>
  - <p style='text-align:justify'><i>2024.03</i>: &nbsp;🎉🎉 One paper is accepted by <font color="red">ACL 2024</font>. We propose All Experts are Equal: Efficient Expert Pruning and Skipping for Mixture-of-Experts Large Language Models.</p>
  - <p style='text-align:justify'><i>2024.01</i>: &nbsp;🎉🎉 One paper (Once for Both) is accepted by <font color="red">CVPR 2024</font>. Once for Both: Single Stage of Importance and Sparsity Search for Vision Transformer Compression.</p>
  - <p style='text-align:justify'><i>2024.01</i>: &nbsp;🎉🎉 One paper (ReSimAD) is accepted by <font color="red">ICLR 2024</font>. We propose a zero-shot generalization framework by reconstructing mesh and simulating target point clouds.</p>
  - <p style='text-align:justify'><i>2024.01</i>: &nbsp;🎉🎉 Two papers ([IPNet](https://ieeexplore.ieee.org/abstract/document/10516600) and [MVNet](https://ieeexplore.ieee.org/abstract/document/10360874)) are accepted by <font color="red">TCSVT</font>. </p>

**2023:**
  - <p style='text-align:justify'><i>2023.02</i>: &nbsp;🎉🎉 Two Papers (Bi3D and Uni3D) are accepted by <font color="red">CVPR 2023</font>. One is about active domain adaptation for 3D object detection, another is about multi-dataset training for 3d object detection.</p>
  - <p style='text-align:justify'><i>2022.07</i>: &nbsp;🎉🎉 One Paper (HelixFormer) is accepted by <font color="red">ACM'MM 2022</font>. We explore Transformer architecture on few-shot fine-grained classification task.</p>

<div style='margin-top: 30pt'></div>

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/aiostereo.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[All-in-One: Transferring Vision Foundation Models into Stereo Matching]()

Jingyi Zhou<sup>\*</sup>, Haoyu Zhang<sup>\*</sup>, Jiakang Yuan<sup>\*</sup>, Peng Ye, Tao Chen, Hao Jiang, Meiya Chen, Yangyang Zhang

[[**Project**]]()[[**Paper**]]()
- Propose AIOStereo to flexibly select and transfer knowledge from multiple heterogeneous VFMs to a single stereo matching model. (<font color="red">Rank 1st</font> on [Middlebury Stereo Evaluation](https://vision.middlebury.edu/stereo/eval3/)) 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/adaptivediffusion.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Training-Free Adaptive Diffusion with Bounded Difference Approximation Strategy]()

Hancheng Ye<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Renqiu Xia, Xiangchao Yan, Tao Chen, Junchi Yan, Botian Shi, Bo Zhang

[[**Project**]](https://jiakangyuan.github.io/AdaptiveDiffusion-project-page/)[[**Paper**]]()
- Propose AdaptiveDiffusion to adaptively reduce the noise prediction steps during the denoising proces guided by the third-order latent difference. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/3detmamba.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[3DET-Mamba: State Space Model for End-to-End 3D Object Detection]()

Mingsheng Li<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Sijin Chen, Lin Zhang, Anyu Zhu, Xin Chen, Tao Chen

[[**Project**]]()[[**Paper**]]()
- Exploit the potential of Mamba architecture on 3D scene-level perception for the first time.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/regtta3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Reg-TTA3D: Better Regression Makes Better Test-time Adaptive 3D Object Detection]()

**<u>Jiakang Yuan</u>**, Bo Zhang, Kaixiong Gong, Xiangyu Yue, Botian Shi, Yu Qiao, Tao Chen

[[**Project**]]()[[**Paper**]]()
- Explore a new task named test-time domain adaptive 3D object detection and propose a pseudo-label-based test-time adaptative 3D object detection method.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2024</div><img src='images/resimad.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ReSimAD: Zero-Shot 3D Domain Transfer for Autonomous Driving with Source Reconstruction and Target Simulation](https://arxiv.org/abs/2309.05527)

Bo Zhang<sup>\*</sup>, Xinyu Cai<sup>\*</sup>, **<u>Jiakang Yuan</u>**, Donglin Yang, Jianfei Guo, Xiangchao Yan, Renqiu Xia, Botian Shi, Min Dou, Tao Chen, Si Liu, Junchi Yan, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2309.05527)
- Provide a new perspective and approach of alleviating the domain shifts, by proposing a Reconstruction-Simulation-Perception scheme.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/adpt.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[AD-PT: Autonomous Driving Pre-Training with Large-scale Point Cloud Dataset](https://arxiv.org/abs/2306.00612)

**<u>Jiakang Yuan</u>**, Bo Zhang, Xiangchao Yan, Tao Chen, Botian Shi, Yikang Li, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2306.00612)
- Build a large-scale pre-training point-cloud dataset with diverse data distribution, and meanwhile learn generalizable representations.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/bi3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Bi3D: Bi-domain Active Learning for Cross-domain 3D Object Detection](https://arxiv.org/abs/2303.05886)

**<u>Jiakang Yuan</u>**, Bo Zhang, Xiangchao Yan, Tao Chen, Botian Shi, Yikang Li, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2303.05886)
- Propose a Bi-domain active learning approach which select samples from both source and target domain to solve the cross-domain 3D object detection task.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/uni3d.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Uni3D: A Unified Baseline for Multi-dataset 3D Object Detection](https://arxiv.org/abs/2303.06880)

Bo Zhang, **<u>Jiakang Yuan</u>**, Botian Shi, Tao Chen, Yikang Li, Yu Qiao

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2303.06880)
- Present a Uni3D which tackle multi-dataset 3D object detection from data-level and semantic-level.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM'MM 2022</div><img src='images/helixformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Learning Cross-Image Object Semantic Relation in Transformer for Few-Shot Fine-Grained Image Classification](https://arxiv.org/abs/2207.00784)

Bo Zhang<sup>\*</sup>, **<u>Jiakang Yuan</u><sup>\*</sup>**, Baopu Li, Tao Chen, Jiayuan Fan, Botian Shi

[[**Project**]]()[[**Paper**]](https://arxiv.org/abs/2207.00784)
- Propose a Transformer-based double-helix model to achieve the cross-image object semantic relation mining in a bidirectional and symmetrical manner.
</div>
</div>

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<div style='margin-top: 30pt'></div>



# 💬 Invited Talks
- *2023.09*, Invited talk of **Effcient Pre-training of Autonomous Driving**. [[Video]](https://www.bilibili.com/video/BV1Sh4y1h7JK/?spm_id_from=333.337.search-card.all.click&vd_source=6efc9ee7fe0b74418e81b9b883e2a403)
- *2023.07*, Invited talk of **Towards 3D General Representation** at Techbeat. [[Video]](https://www.techbeat.net/talk-info?id=795)
- *2023.03*, Invited talk of **Transferable Pwerception of Autonomous Driving**. [[Video]](rom=333.337.search-card.all.click&vd_source=6efc9ee7fe0b74418e81b9b883e2a403)

<div style='margin-top: 30pt'></div>

# 💻 Internships

- *2021.12 - 2022.06*, [Shanghai AI Laboratory](), China.

<div style='margin-top: 30pt'></div>

# 📝 Collaborators

- <a href="https://thinklab.sjtu.edu.cn/">ReThinkLab</a>
- <a href="http://leibai.site/">Lei Bai</a>
- <a href="https://gaopengcuhk.github.io/">Peng Gao</a>
- <a href="https://www.rjchen.site/">Runjian Chen</a>
- <a href="https://xyue.io/">Xiangyu Yue</a>