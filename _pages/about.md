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

<!-- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->

<!-- I am a second-year master's student at <span style="color:purple">**the School of Cyber Science and Engineering, Wuhan University**</span>. I will start my Ph.D. program this year (Successive Master-Doctor Program), advised by <span style="color:purple">**Prof. Juan Wang**</span>. My research mainly focuses on <span style="color:purple">**Trustworthy AI**</span>, especially privacy attacks/defenses in distributed learning paradigms (e.g., Split Learning, Federated Learning). -->

I am a first-year Ph.D. student at <span style="color:purple">**the School of Cyber Science and Engineering, Wuhan University**</span>, advised by <span style="color:purple">**Prof. Juan Wang**</span>. My research mainly focuses on <span style="color:purple">**Trustworthy AI**</span>, especially privacy attacks/defenses in distributed learning paradigms (e.g., Split Learning, Federated Learning).


# 🔥 News
- *2025.03.01*: &nbsp;One paper has been accepted by CVPR 2025 🎉🎉. 
- *2024.09.10*: &nbsp;One paper has been accepted by COMPSAC 2024 🎉🎉. 
- *2024.04.28*: &nbsp;Published vulnerability: CVE-2024-4291 🎉🎉. 
- *2024.04.26*: &nbsp;The MV for "WanganjiDi" has been released [Audio](images_LZA/WanganjiDi.wav) 🎉🎉. 
  [![Watch the video](images_LZA/7.jpg){:width="12%"}](images_LZA/WanganjiDi.MP4)
  <!-- <div style="text-align: center;">
      <a href="images_LZA/WanganjiDi.MP4"><img src="images_LZA/7.jpg" width="25%"/></a>
  </div> -->
  <!-- <div style="text-align: center;">
    <a href="images_LZA/WanganjiDi.MP4">
        <img src="images_LZA/7.jpg" style="width: 25%; transform: translateX(-%25);" />
    </a>
  </div> -->
- *2024.03.03*: &nbsp;One paper has been accepted by FGCS 🎉🎉. 
- *2024.03.01*: &nbsp;One paper has been accepted by CVPR 2024 🎉🎉. 
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images_LZA/9.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[From Head to Tail: Efficient Black-box Model Inversion Attack via Long-tailed Learning](https://github.com/L1ziang/SMILE)

**Ziang Li**, Hongguang Zhang, Juan Wang*, Meihui Chen, Hongxin Hu, Wenzhe Yi, Xiaoyang Xu, Mengda Yang, Chenjun Ma

- We introduce SMILE, an efficient black-box MIA. By combining long-tailed surrogate training and gradient-free black-box optimization, SMILE outperforms existing black-box MIAs with about 5% of the query overhead. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">COMPSAC 2024</div><img src='images_LZA/8.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[CCall: Recovering Indirect Call Targets from Binaries With Cross-Domain Fine-Tuning](https://ieeexplore.ieee.org/abstract/document/10633585)

Bin Weng, Yunru Wang, juan Wang*, Mengda Yang,  **Ziang Li**, Fei Li

- We propose a novel cross-domain fine-tuning strategy based on domain adaptation, which can further study the semantics from the unlabeled test samples. This cross-domain finetuning strategy can also be applied in other AI-based downstream binary analysis tasks.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">FGCS</div><img src='images_LZA/5.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Penetralium: Privacy-preserving and memory-efficient neural network inference at the edge](https://www.sciencedirect.com/science/article/pii/S0167739X24000797)

Mengda Yang, Wenzhe Yi, Juan Wang*, Hongxin Hu, Xiaoyang Xu, **Ziang Li**

- Penetralium is a novel model inference system that we design to provide robust security for deep learning computation at the edge. Penetralium is created with system and algorithm co-design, and has little overhead and no impact on prediction accuracy.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2024</div><img src='images_LZA/6.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Stealthy Wrongdoer: Feature-Oriented Reconstruction Attack against Split Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Xu_A_Stealthy_Wrongdoer_Feature-Oriented_Reconstruction_Attack_against_Split_Learning_CVPR_2024_paper.html)

Xiaoyang Xu, Mengda Yang, Wenzhe Yi, **Ziang Li**, Juan Wang, Hongxin Hu, Yong Zhuang, Yaxin Liu

- We propose a novel attack, named Feature-Oriented Reconstruction Attack (FORA). As far as we know, FORA is the first work enabling a semi-honest server to perform powerful DRA in more realistic and challenging SL systems.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images_LZA/2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[GAN You See Me? Enhanced Data Reconstruction Attacks against Split Inference](https://proceedings.neurips.cc/paper_files/paper/2023/hash/ab003a4f85ecb1b7b1514ff539dc7395-Abstract-Conference.html)

**Ziang Li**, Mengda Yang, Yaxin Liu, Juan Wang*, Hongxin Hu, Wenzhe Yi, Xiaoyang Xu

- We propose GLASS and GLASS++, which are enhanced DRAs combined with pre-trained
StyleGAN models. We conduct a systematic evaluation and comparison of various DRAs against seven defense mechanisms.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2022</div><img src='images_LZA/3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Measuring Data Reconstruction Defenses in Collaborative Inference Systems](https://proceedings.neurips.cc/paper_files/paper/2022/hash/53f1c3ec5df814b5aabe9ae88a29bb49-Abstract-Conference.html)

Mengda Yang, **Ziang Li**, Juan Wang*, Hongxin Hu, Ao Ren, Xiaoyang Xu, Wenzhe Yi

- We are the first to experimentally verify the robustness of reconstruction defenses for inference data privacy in collaborative systems. We devise a technique called SFD against the existing defense mechanisms. 
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TrustCom 2022</div><img src='images_LZA/1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ProcGuard: Process Injection Behaviours Detection Using Fine-grained Analysis of API Call Chain with Deep Learning](https://ieeexplore.ieee.org/abstract/document/10063560)

Juan Wang*, Chenjun Ma, **Ziang Li**, Huanyu Yuan, Jie Wang

- We present a framework for detecting process injection attacks called ProcGuard, which adopts API call chain analysis and deep learning. 
</div>
</div>

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- *2024.11* Lei Jun Computer Science Graduate Scholarship
- *2023.11* DataCon2023 Big Data Security Analysis Competition - AI Security, Outstanding Team.
- *2023.11* DataCon2023 Big Data Security Analysis Competition - Email Security, Outstanding Team. 
- *2022.10* The 1st Privacy Computing and Data Security Challenge, Second Prize. 
- *2021.12* Wuhan University's Outstanding Student Third-Class Scholarship. 
- *2021.08* The 14th National College Student Information Security Competition - Works Competition, First Prize.

# 📖 Educations
- *2024.09 - (now)*, Wuhan University, Successive Master-Doctor Program (Ph.D. in progress) - SCHOOL OF CYBER SCIENCE AND ENGINEERING
- *2022.09 - 2024.06*, Wuhan University, Successive Master-Doctor Program - SCHOOL OF CYBER SCIENCE AND ENGINEERING
- *2018.09 - 2022.06*, Wuhan University, Bachelor of Engineering - SCHOOL OF CYBER SCIENCE AND ENGINEERING

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->