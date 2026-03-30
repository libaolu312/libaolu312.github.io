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


Hi there! My name is Baolu Li (李宝璐), currently a second-year Master's student at the [IIAU-Lab](https://iiaulab.github.io/), Dalian University of Technology, advised by [Prof. Xu Jia](https://stephenjia.github.io/). During a collaboration with Shanghai AI Lab, I was also fortunate to receive guidance from [Dr. Zhenfei Yin](https://yinzhenfei.github.io/) and [Dr. Lei Bai](http://leibai.site/). I received my Bachelor's degree from Hefei University of Technology, where I also interned at the [LMC-Lab](https://ci.hfut.edu.cn/info/1162/14469.htm). 

My current research interests primarily focus on **Video/Image Generation** and **World Model**. Please feel free to contact me if you are interested in my research or potential collaborations.





# 🔥 News
- *2026.03*: &nbsp;🎉🎉 One Paper is accepted by CVPR 2026. 
- *2026.01*: Release paper and code "[MultiShotMaster: A Controllable Multi-Shot Video Generation Framework](https://qinghew.github.io/MultiShotMaster/)".
- *2025.10*: Release paper "[VFXMaster: Unlocking Dynamic Visual Effect Generation via In-Context Learning](https://libaolu312.github.io/VFXMaster/)".
- *2025.07*: &nbsp;🎉🎉 One Paper is accepted by ICCV 2025. 
- *2025.03*: Release paper and code "[VLIPP: Towards Physically Plausible Video Generation with Vision and Language Informed Physical Prior](https://madaoer.github.io/projects/physically_plausible_video_generation/)".
- *2025.03*: &nbsp;🎉🎉 One Paper is accepted by TIP 2025. 
- *2024.05*: Release paper "[CharacterFactory: Sampling Consistent Characters with GANs for Diffusion Models](https://qinghew.github.io/CharacterFactory/)", [Codes](https://github.com/qinghew/CharacterFactory) and [Gradio Demo](https://huggingface.co/spaces/DecoderWQH666/CharacterFactory) of "CharacterFactory". Welcome to use!






# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv</div><img src='images/VFXMaster.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VFXMaster: Unlocking Dynamic Visual Effect Generation via In-Context Learning](https://libaolu312.github.io/VFXMaster/)

**Baolu Li**<sup>*</sup>, Yiming Zhang<sup>*</sup>, Qinghe Wang<sup>*†</sup>, Liqian Ma<sup>✉</sup>, Xiaoyu Shi, Xintao Wang, Pengfei Wan, Zhenfei Yin, Yunzhi Zhuge, Huchuan Lu, Xu jia<sup>✉</sup>.

<sup>*</sup>Equal Contribution    <sup>†</sup>Project Leader    <sup>✉</sup>Corresponding Author

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
[[**Project Page**](https://libaolu312.github.io/VFXMaster/)]
[[**Paper**](https://arxiv.org/abs/2510.25772)]
<!-- [[**机器之心🔥**](https://mp.weixin.qq.com/s/6XddT1q0_yFO0hhQvmEwAQ)]
[[**Paper**](https://arxiv.org/pdf/2503.23368)]
[[**Code**](https://github.com/Madaoer/VLIPP)] -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/multishot.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MultiShotMaster: A Controllable Multi-Shot Video Generation Framework](https://qinghew.github.io/MultiShotMaster/)

Qinghe Wang, Xiaoyu Shi<sup>✉</sup>, **Baolu Li**, Weikang Bian, Quande Liu, Huchuan Lu, Xintao Wang, Pengfei Wan, Kun Gai, Xu jia<sup>✉</sup>.

<sup>✉</sup>Corresponding Author

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
[[**Project Page**](https://qinghew.github.io/MultiShotMaster/)]
[[**Paper**](https://arxiv.org/abs/2512.03041)]
<!-- [[**机器之心🔥**](https://mp.weixin.qq.com/s/6XddT1q0_yFO0hhQvmEwAQ)]
[[**Paper**](https://arxiv.org/pdf/2503.23368)]
[[**Code**](https://github.com/Madaoer/VLIPP)] -->
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='images/vlipp.gif' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[VLIPP: Towards Physically Plausible Video Generation with Vision and Language Informed Physical Prior](https://madaoer.github.io/projects/physically_plausible_video_generation/)

Xindi Yang<sup>*</sup>, **Baolu Li<sup>*</sup>**, Yiming Zhang, Zhenfei Yin, Lei Bai<sup>✉</sup>, Liqian Ma, Zhiyong Wang, Jianfei Cai, Tien-Tsin Wong, Huchuan Lu, Xu jia<sup>✉</sup>.

<sup>*</sup>Equal Contribution    <sup>✉</sup>Corresponding Author

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
[[**Project Page**](https://madaoer.github.io/projects/physically_plausible_video_generation/)]
[[**机器之心🔥**](https://mp.weixin.qq.com/s/6XddT1q0_yFO0hhQvmEwAQ)]
[[**Paper**](https://arxiv.org/pdf/2503.23368)]
[[**Code**](https://github.com/Madaoer/VLIPP)]
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIP 2025</div><img src='images/characterfactory.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CharacterFactory: Sampling Consistent Characters with GANs for Diffusion Models](https://qinghew.github.io/CharacterFactory/)

Qinghe Wang, **Baolu Li**, Xiaomin Li, Bing Cao, Liqian Ma, Huchuan Lu, Xu jia✉.
<sup>✉</sup>Corresponding Author

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
[[**Project Page**](https://qinghew.github.io/CharacterFactory/)]
[[**Gradio Demo🤗**](https://huggingface.co/spaces/DecoderWQH666/CharacterFactory)]
[[**Paper**](https://arxiv.org/pdf/2404.15677)]
[[**Code**](https://github.com/qinghew/CharacterFactory)]
<!-- - Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>






# 📖 Educations
- *2024.09 - now*, Master, Dalian University of Technology, Dalian.
- *2020.09 - 2024.06*, Undergraduate, Hefei University of Technology, Hefei. 

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->
# 💬 Service
**Conference Reviewer**
<ul>
    <li>ICLR 2025、2026</li>
    <li>CVPR 2025、2026</li>
    <li>ICCV 2025</li>
    <li>ACMMM 2025</li>
    <li>ICME 2026</li>
</ul>


<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->