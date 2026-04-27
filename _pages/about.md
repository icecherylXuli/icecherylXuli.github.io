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

<section class="homepage-section" markdown="1">

<h2 class="section-heading"><span class="section-icon" aria-hidden="true">👤</span> Profile</h2>
I am a Postdoctoral Research Fellow at the State Key Laboratory of Integrated Service Networks, Xidian University. I work on learning-based video compression and visual representation under resource-constrained scenarios, aiming to unify efficient transmission, high-quality reconstruction, and machine understanding. I have published papers in leading conferences and journals, including CVPR, AAAI, ACM MM, IJCAI, IEEE T-CSVT, and IEEE T-IV. I serve as a reviewer for CVPR, AAAI, IJCAI, ACM MM, IEEE T-CSVT, IEEE TNNLS, and IJCV.

<!-- My research lies at the intersection of visual signal processing, learned compression, and computational imaging. I develop learning-based methods for efficient, high-fidelity, and semantically meaningful visual media representation. -->

</section>

<section class="homepage-section" markdown="1">

<h2 class="section-heading"><span class="section-icon" aria-hidden="true">🎯</span>  Research Interests</h2>

<div class="research-grid">
  <div class="research-card">
    <strong>Visual Compression</strong>
    <p>Learned compression and variable-rate representation</p>
  </div>
  <div class="research-card">
    <strong>Visual Restoration</strong>
    <p>Image/video enhancement and high-fidelity reconstruction</p>
  </div>
  <div class="research-card">
    <strong>Human-Machine Representation</strong>
    <p>Bridging human perception and machine understanding</p>
  </div>
</div>

</section>


<!-- ## Academic Service
I serve as a reviewer for CVPR, AAAI, IJCAI, ACM MM, IEEE T-CSVT, IEEE TNNLS, and IJCV. -->

<section class="homepage-section" markdown="1">

<span class='anchor' id='news'></span>

<h2 class="section-heading"><span class="section-icon" aria-hidden="true">🔥</span> News</h2>
<div class="news-scroll" markdown="1">
- *2026.02*: 🎉 Two papers are accepted by CVPR 2026 
- *2025.11*: 🎉 One paper is accepted by AAAI 2026 as an oral presentation
- *2025.07*: 🎉 Received funding from China Postdoctoral Science Foundation under Grant 2025M773501
- *2025.04*: 🎉 Two papers are accepted by IJCAI 2025
- *2025.03*: 🎉 Received funding from the Fundamental Research Funds for the Central Universities under Grant ZYTS25270
- *2024.07*: 🎉 One paper is accepted by IEEE Transactions on Intelligent Vehicles
- *2024.07*: 🎉 One paper is accepted by ACM MM 2024
- *2024.06*: 🎉 Completed my Ph.D. at Xidian University 
- *2024.04*: 🎉 One paper is accepted by IJCAI 2024

</div>


</section>


<span class='anchor' id='publications'></span>

# 📝 Selected Publications 
<!-- RealRep -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2026 Oral</div><img src='images/RealRep.png?v={{ site.asset_version }}' alt="RealRep overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RealRep: Generalized SDR-to-HDR Conversion via Attribute-Disentangled Representation Learning](https://arxiv.org/abs/2505.07322v3)

**Li Xu**, Siqi Wang, Kepeng Xu, Gang He, Lin Zhang, Weiran Wang, Yu-Wing Tai.

- Attribute-disentangled representation learning for more generalizable real-world SDR-to-HDR conversion.
</div>
</div>

<!-- hdfacerestoration -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='images/hdfacerestoration.jpg?v={{ site.asset_version }}' alt="Face restoration overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Unleashing the Potential of Transformer Flow for Photorealistic Face Restoration](https://www.ijcai.org/proceedings/2025/234)

Kepeng Xu, **Li Xu**, Gang He, Wei Chen, Xianyun Wu, Wenxin Yu.

[**Project**](https://kepengxu.github.io/projects/onmiface/)
- Transformer flow matching for high-quality photorealistic face restoration.
</div>
</div>

<!-- realhdrtvnet -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='images/realhdrtvnet.png?v={{ site.asset_version }}' alt="RealHDRTVNet overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Feature Mapping GAP: Integrating Real HDRTV Priors for Superior SDRTV-to-HDRTV Conversion](https://www.ijcai.org/proceedings/2025/122)

Gang He, Kepeng Xu, **Li Xu**, Zhiqiang Zhang, Wenxin Yu, Shihao Wang, Dajiang Zhou, Yunsong Li.

- Real HDRTV priors for improved SDR-to-HDR conversion in practical scenarios.
</div>
</div>

<!-- PVIM -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE T-IV</div><img src='images/PCIP.png?v={{ site.asset_version }}' alt="PVIM overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Pedestrian-Vehicle Information Modulation for Pedestrian Crossing Intention Prediction

**Li Xu**, Shaodi You, Gang He, Yunsong Li. [![](https://img.shields.io/github/stars/icecherylXuli/PVIM?style=social&label=Code+Stars)](https://github.com/icecherylXuli/PVIM)


[**Project**](https://icecherylxuli.github.io/projects/PVIM/)
- Pedestrian-vehicle information modulation for pedestrian crossing intention prediction.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/framework.png?v={{ site.asset_version }}' alt="RealCamNet overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[An End-to-End Real-World Camera Imaging Pipeline](https://kepengxu.github.io/projects/realcamnet/realcamnet.pdf)

Kepeng Xu, Zijia Ma, **Li Xu**, Gang He, et al. [![](https://img.shields.io/github/stars/kepengxu/RealCamNet?style=social&label=Code+Stars)](https://github.com/kepengxu/RealCamNet)


[**Project**](https://kepengxu.github.io/projects/realcamnet/)
- End-to-end real-world camera imaging pipeline for complex distortions.
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2024</div><img src='images/PGTFormer.png?v={{ site.asset_version }}' alt="PGTFormer overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Beyond Alignment: Blind Video Face Restoration via Parsing-Guided Temporal-Coherent Transformer](https://arxiv.org/abs/2404.13640)

Kepeng Xu, **Li Xu**, Gang He, et al. [![](https://img.shields.io/github/stars/kepengxu/PGTFormer?style=social&label=Code+Stars)](https://github.com/kepengxu/PGTFormer)

[**Project**](https://kepengxu.github.io/projects/pgtformer/)
- Parsing-guided temporal-coherent transformer for clearer and more consistent video face restoration.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2022</div><img src='images/mmimage.jpg?v={{ site.asset_version }}' alt="HDCFM overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SDRTV-to-HDRTV via Hierarchical Dynamic Context Feature Mapping](https://arxiv.org/abs/2207.00319)

Gang He, Kepeng Xu, **Li Xu**, Chang Wu, Ming Sun, Xing Wen, Yu-Wing Tai. [![](https://img.shields.io/github/stars/iii935/HDCFM?style=social&label=Code+Stars)](https://github.com/iii935/HDCFM)


[**Project**](https://arxiv.org/abs/2207.00319)
- Hierarchical dynamic context feature mapping for high-quality HDR conversion.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/tsan.png?v={{ site.asset_version }}' alt="TSAN overview" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Transcoded Video Restoration by Temporal Spatial Auxiliary Network](https://ojs.aaai.org/index.php/AAAI/article/view/20192)

**Li Xu**, Gang He, Jinjia Zhou, Jie Lei, Weiying Xie, Yunsong Li, Yu-Wing Tai. [![](https://img.shields.io/github/stars/icecherylXuli/TSAN?style=social&label=Code+Stars)](https://github.com/icecherylXuli/TSAN)

- Temporal-spatial auxiliary network for improving transcoded video quality.
</div>
</div>



<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

- `AAAI 2026 Oral` **Li Xu**, Siqi Wang, Kepeng Xu, Gang He, Lin Zhang, Weiran Wang, Yu-Wing Tai. [RealRep: Generalized SDR-to-HDR Conversion via Attribute-Disentangled Representation Learning](https://arxiv.org/abs/2505.07322v3) [C]. Proceedings of the AAAI Conference on Artificial Intelligence, 2026.

- `IJCAI 2025` Kepeng Xu, **Li Xu**, Gang He, Wei Chen, Xianyun Wu, Wenxin Yu. [Unleashing the Potential of Transformer Flow for Photorealistic Face Restoration](https://www.ijcai.org/proceedings/2025/234) [C]. Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence, Montreal, Canada, 2025.

- `IJCAI 2025` Gang He, Kepeng Xu, **Li Xu**, Zhiqiang Zhang, Wenxin Yu, Shihao Wang, Dajiang Zhou, Yunsong Li. [Beyond Feature Mapping GAP: Integrating Real HDRTV Priors for Superior SDRTV-to-HDRTV Conversion](https://www.ijcai.org/proceedings/2025/122) [C]. Proceedings of the Thirty-Fourth International Joint Conference on Artificial Intelligence, Montreal, Canada, 2025.

- `T-IV` **Li Xu**, Shaodi You, Gang He, Yunsong Li. Pedestrian-Vehicle Information Modulation for Pedestrian Crossing Intention Prediction [J]. IEEE Transactions on Intelligent Vehicles.

- `ACM MM 2024` Kepeng Xu, Zijia Ma, **Li Xu**, Gang He, Yunsong Li, Wenxin Yu, Taichu Han, Cheng Yang. An End-to-End Real-World Camera Imaging Pipeline, Melbourne, Australia, 2024.

- `IJCAI 2024` Kepeng Xu, **Li Xu**, Gang He, Wenxin Yu, Yunsong Li. Beyond Alignment: Blind Video Face Restoration via Parsing-Guided Temporal-Coherent Transformer [C]. Proceedings of the Thirty-Third International Joint Conference on Artificial Intelligence, Jeju, Korea, 2024.

- `NC` Gang He, Shaoyi Long, **Li Xu**, Chang Wu, Jinjia Zhou, Ming Sun, Yurong Dai. [Global priors guided modulation network for joint super-resolution and SDRTV-to-HDRTV](https://www.sciencedirect.com/science/article/pii/S0925231223007130?casa_token=dyd1LXpYIiMAAAAA:VkaC2NOqCTZDUS4vr8ZiilAxnEWV4glmh41ZVysOZxYflDq4o8pvlsDiup1QMjHUF6ETQyFAYbs) [J]. Neurocomputing 554 (2023): 126590.

- `Arxiv` Kepeng Xu*,* **Li Xu**, Gang He, Wenxin Yu, Yunsong Li. [Towards Robust SDRTV-to-HDRTV via Dual Inverse Degradation Network](https://arxiv.org/html/2307.03394v2). 2023.

- `AAAI 2022` **Li Xu**, Gang He, Jinjia Zhou, Jie Lei, Weiying Xie, Yunsong Li, Yu-Wing Tai. [Transcoded Video Restoration by Temporal Spatial Auxiliary Network](https://ojs.aaai.org/index.php/AAAI/article/view/20192) [C]. Proceedings of the AAAI Conference on Artificial Intelligence, Vancouver, BC, Canada, 2022: Vol. 36. No. 3. 2022.

- `DSP` **Li Xu**, Chang Wu, Linyi Huang, Shengyu Wei, Gang He, Yunsong Li. [Towards coding for VoD application: An enhanced video compression system with a content-fitted recursive restoration network](https://www.sciencedirect.com/science/article/pii/S1051200421004073?casa_token=8Rsj7-0wZbEAAAAA:AVv60Slq58gU2cNRgq646DUqCYdKYUSxjTd8gpgQSIGqAS6uOJNvRkFO2EVyx_cSc-j_rrrMPqg) [J]. Digital Signal Processing 122 (2022): 103368.

- `T-CSVT` Gang He, **Li Xu**, Jie Lei, Weiying Xie, Yunsong Li, Yibo Fan, Jinjia Zhou. [Interlayer Restoration Deep Neural Network for Scalable High Efficiency Video Coding](https://ieeexplore.ieee.org/abstract/document/9478899?casa_token=B-0pVbIE9ukAAAAA:ruhL1iy5v-7wXbgrPnwhAzLtTZnWVqZH7fDx3BbSy45nSzqL-c8WsKHN366HalEbIJxJEjbGBb4) [J]. IEEE Transactions on Circuits and Systems for Video Technology, vol. 32, no. 5, pp. 3217-3234, May 2022.
- `ACM MM 2022` Gang He, Kepeng Xu, **Li Xu**, Chang Wu, Ming Sun, Xing Wen, Yu-Wing Tai. [SDRTV-to-HDRTV via Hierarchical Dynamic Context Feature Mapping](https://dl.acm.org/doi/abs/10.1145/3503161.3548043?casa_token=MzdmjSMySG0AAAAA:rixAN9lAaYMVVkVJVHCthNt2X_0bjOk98GM8xSr9s38wQj9J1Zlo8zhgs6bEdei7oQ2OU4h0jQtgwQ) [C]. Proceedings of the 30th ACM International Conference on Multimedia, Lisbon, Portugal, 2022. p. 2890-2898.
- `CVPRW 2022` Gang He, Yong Wang, Li Xu, Wenli Zhang, Ming Sun, Xing Wen. [Focused Feature Differentiation Network for Image Quality Assessment](https://openaccess.thecvf.com/content/CVPR2022W/CLIC/html/He_Focused_Feature_Differentiation_Network_for_Image_Quality_Assessment_CVPRW_2022_paper.html) [C]. Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshop, New Orleans, Louisiana, USA, 2022. p. 1800-1804.
- `Arxiv` Kepeng Xu, **Li Xu**, Zijia Ma, Ming Sun, Yu-Wing Tai. [Sdrtv-to-hdrtv conversion via spatial-temporal feature fusion](https://arxiv.org/pdf/2211.02297). 2022.




<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards

- 2022 **Chinese National Scholarship** for Ph.D. Students
- 2022 **The 5th Challenge on Learned Image Compression, CVPR workshop (3rd Place)**
- 2020 Outstanding Graduate Student at Xidian University

<section class="homepage-section" markdown="1">

<!-- ## Achievements
My research team, Kingslayer, secured third place in the Perceptual Metric Track at the 5th Workshop and Challenge on Learned Image Compression, held with CVPR 2022. -->


<!-- </section> -->

<section class="homepage-section" markdown="1">


</section>

<span class='anchor' id='education'></span>

# 📖 Education

- *2020.03 - 2024.06*, Ph.D. in Information and Communication Engineering, Xidian University, Xi’an, China
- *2022.10 - 2024.01*, Guest Researcher, Faculty of Science, University of Amsterdam, Amsterdam, Netherlands
- *2018.09 - 2020.02*, M.S. in Information and Communication Engineering, Xidian University, Xi’an, China
- *2014.09 - 2018.06*, B.S. in Communication Engineering, Chongqing University, China


<!-- # 💬 Invited Talks
- *2023.01*, Real World HDR video generation technology Alipay internal talk.
- *2022.10*, HDR video generation technology talk ACM MM.
- *2022.08*, HDR video generation key technology solves MEGVII internal talk.
- *2022.05*, Talk 3D Rendering Course. 
- *2022.06*, HDR video generation technology MEGVII internal talk.
- *2022.06*, Video compression technology solution talk, CLIC2022 (CVPR).
<!-- - *Test*,   \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2022.05 - 2022.10*, [MEGVII], China. --> 
