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

Hello! I'm Guanwen Xie, a first-grade graduate student from Tsinghua University, supervised by Prof. Daoyi Chen and Yong Ren. Before this, I've obtained B. Eng. of ocean technology in Zhejiang University, supervised by Prof. Dongfang Ma.

Since my undergraduate studies, I have been passionate about underwater robotics. My interest lies in integrating the ocean with the latest advancements in reinforcement learning and machine learning, such as learning from demonstrations (LfD) and experience mining, intelligent large language models(LLMs) , etc. I continuously explore new possibilities and strive to make research outcomes as universal and user-friendly as possible for researchers.

Feel free to email me at [gwxie360@outlook.com](mailto:gwxie360@outlook.com) !


# 🔥 News

- *2024.09*: &nbsp;🎉🎉 I have reconstruct my homepage to make it more compact and easy-to-read.
- *2024.09*: The record of my first long-distance car driving experience - Beihai-Shenzhen POV video has uploaded to [Bilibili](https://www.bilibili.com/video/BV195t7eeEWb).
- *2024-08*: I start a new stage of my study in Tsinghua University.

# 📝 Publications 

( \* denotes equal contribution )

---
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='files/images/llmrsearcher.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">




LLMs as Efficient Reward Function Searchers for Custom-Environment MORL

**Guanwen Xie**, Jingzehua Xu, Yiyuan Yang, Yimian Ding, Shuai Zhang

[[**Website&Code**]](https://360zmem.github.io/LLMRsearcher/)  [[**Arxiv**]](https://arxiv.org/abs/2409.02428)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/xiellmrsearcher.bib) 

**TLDR:** An efficient reward function searcher using LLMs (ERFSL) is achieved by decomposing multi-objective tasks to provide clear textual task feedback, utilizing LLM's strong semantic understanding capabilities, and incorporating versatile search strategies.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Transactions on Mobile Computing 2024 </div><img src='files/images/fisher.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">





 Is FISHER All You Need in The Multi-AUV Underwater Target Tracking Task?

**Guanwen Xie\***, Jingzehua Xu\*, Ziqi Zhang, Xiangwang Hou, Dongfang Ma, Shuai Zhang, Yong Ren, Dusit Niyato

[[**PDF**]](https://360zmem.github.io/files/PDF/FISHER_tmc.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/FISHERconf2024.bib) 

**TLDR:** Leveraging sim2sim expert trajectories transformation process facilitates the generation of demonstrations. Based on this, a two-stage framework called FISHER of MADAC imitation learning (IL) and MAIGDT offline reinforcement learning (ORL) is employed to achieve high generalized and applicable multi-AUV target tracking policies without designating reward functions.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Internet of Things Journal 2024</div><img src='files/images/hptvsim.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">




HPTVSim: A Simulator for Unmanned Underwater Vehicles Dedicated in the Underwater Pursuit-Evasion Game

Jingzehua Xu\*, **Guanwen Xie\***, Zekai Zhang, Xiangwang Hou, Shuai Zhang, Yong Ren, Dusit Niyato

[[**PDF**]](https://360zmem.github.io/files/PDF/hptvsim.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/hptvsim.bib) 

**TLDR:** A highly customizable and high-precision physics simulation platform called HPTVsim has been developed based on ROS and Gazebo. Combined with the RL compatibility layer based on RoboEnv Class, it can be easily applied to a variety of RL tasks. Based on this platform, an efficient training framework of scenario transfer RL training and offline reinforcement learning is utilized for underwater pursuit-evasion game (UPEG).

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Arxiv</div><img src='files/images/extreme.png' alt="sym" width="90%"></div></div>
<div class='paper-box-text' markdown="1">



USV-AUV Collaboration Framework for Underwater Tasks under Extreme Sea Conditions

 Jingzehua Xu\*, **Guanwen Xie\***, Xinqi Wang, Yimian Ding, Shuai Zhang

[[**Code**]](https://github.com/360ZMEM/USV-AUV-colab) [[**Arxiv**]](https://arxiv.org/abs/2409.02444)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/extreme.bib) 

**TLDR:** By utilizing the USV-AUV collaborative framework, the accuracy of AUV positioning can be enhanced in extreme sea conditions. USV and AUV cooperatively execute the data collection task of internet of underwater things (IoUT).

</div>
</div>

- Environment and Energy-Aware AUV-Assisted Data Collection for the Internet of Underwater Things, Zekai Zhang\*, Jingzehua Xu\*, **Guanwen Xie**, Jingjing Wang, Zhu Han and Yong Ren. **IEEE Transactions on Mobile Computing 2024** [[**Online Publication**]](https://ieeexplore.ieee.org/document/10516675/) [[**PDF**]](https://360zmem.github.io/files/PDF/iout2024.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/iout2024.bib) 

- FISHER: An Efficient Sim2sim Training Framework Dedicated in Multi-AUV Target Tracking via Learning from Demonstrations, **Guanwen Xie\***, Xinqi Wang\*, Yimian Ding, Jingzehua Xu, Dongfang Ma, Jingjing Wang and Yong Ren. **ICONIP 2024** [[**PDF**]](https://360zmem.github.io/files/PDF/FISHER_conf.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/FISHERconf2024.bib)
- IMTVSim: An Integrated Modular Training and Verification Simulator for Unmanned Underwater Vehicles, Jingzehua Xu\*, **Guanwen Xie\***, Zekai Zhang, Tianxiang Xing, Jingjing Wang and Yong Ren. **OCEANS 2024 Halifax** [[**PDF**]](https://360zmem.github.io/files/PDF/OCEANS1.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/oc_imtvsim.bib)
- Advanced Framework for Underwater Node Repair via Multi-AUV Based on Multi-Agent Offline Reinforcement Learning, Yimian Ding\*, Jingzehua Xu\*, **Guanwen Xie**, Gang Li, Jingjing Wang and Yong Ren. **OCEANS 2024 Halifax** [[**PDF**]](https://360zmem.github.io/files/PDF/OCEANS2.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/oc_noderepair.bib)

- Enhancing Information Freshness: An AoI Optimized Markov Decision Process Dedicated in The Underwater Task, Yimian Ding\*, Jingzehua Xu\*, Yiyuan Yang, **Guanwen Xie** and Shuai Zhang. **Arxiv** [[**Code**]](https://github.com/Xiboxtg/AoI-MDP)  [[**Arxiv**]](https://arxiv.org/abs/2409.02424)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/dingaoimdp.bib) 
- Multi-AUV Assisted Seamless Underwater Target Tracking Relying on Deep Learning and Reinforcement Learning, Jingzehua Xu\*, Yimian Ding\*, Zekai Zhang, **Guanwen Xie**, Ziyuan Wang, Yongming Zeng and Gang Li. **IEEE WCCI 2024**  [[**PDF**]](https://360zmem.github.io/files/PDF/edatacol.pdf)  [[**BibTeX**]](https://360zmem.github.io/files/BibTeX/edatacol.bib) [[**News Coverage**(中文报道)]](http://oc.zju.edu.cn/2024/0329/c29862a2896096/page.htm)
- Fisher-Information-Matrix-Based USBL Cooperative Location in USV--AUV Networks, Ziyuan Wang, Jingzehua Xu, Yuanzhe Feng, Yijing Wang, **Guanwen Xie**, Xiangwang Hou, Wei Men, and Yong Ren. **Sensors 2023** **[[Online Publication]](https://www.mdpi.com/1424-8220/23/17/7429) [[PDF]](https://360zmem.github.io/files/PDF/w2023.pdf) [[BibTeX]](https://360zmem.github.io/files/BibTeX/w2023.bib)**

# 🥇 Selected Honors and Awards

**Scholarship**

- **2024** Outstanding Graduate **(awarded to top undergraduates in Zhejiang University)**
- **2023** Runhe Scholarship **(1% Top in ZJU)**
- **2022** Zhejiang Provincal Government Scholarship **(3% Top in ZJU)**

**Experience**

- **2023** First Prize of "Aotuo Cup" National Underwater Robot Designing Competition **(Top 5% of all participants of finals)**
- **2022** First Prize of Zhejiang Provincal Student Physics Innovation Competition (Theory)

# 📖 Educations & Skills

2024.09 - present, **Tsinghua University**, M. S. in Electric Information

*2020.09 - 2024.06*, **Zhejiang University**, B. Eng. in Ocean Technology

- GPA: 4.74 / 5.00 or score 92.4 / 100 (rank 1st / 143)

Programming💻 & Debugging 🐛🔧:  Python/Pytorch, C/C++, ROS, Linux(Arch Linux/Ubuntu...), $\LaTeX$ 

Languages: English CET6 600

# 📊 Selected Experiences

**2024.6 - 2024.12** New Jersey Institute of Technology, Department of Data Science, Research Assistant (Advisor - Prof. Shuai Zhang)

- **Efficient LLM reward searcher for MORL:** An efficient reward function searcher using LLMs (ERFSL) is achieved by decomposing multi-objective tasks to provide clear textual task feedback, utilizing LLM's strong semantic understanding capabilities, and incorporating versatile search strategies.

**2023.7 - 2024.9**  Zhejiang University & Tsinghua University, Undergraduate Dissertation (Advisor - Prof. Dongfang Ma (ZJU) & Yong Ren (THU) )

- **AUV Target Tracking via Learning from Demonstration deployed on high-precision simulation platform:** A highly customizable and high-precision physics simulation platform called HPTVsim has been developed based on ROS and Gazebo. Combined with the RL compatibility layer based on RoboEnv Class, it can be easily applied to a variety of RL tasks. Then, a two-stage framework called FISHER of MADAC imitation learning (IL) and MAIGDT offline reinforcement learning (ORL) is employed to achieve high generalized and applicable multi-AUV target tracking policies without designating reward functions.

**2023.2 - 2023.6**  Zhejiang University, Ocean College, Undergraduate Researcher (Advisor - Prof. Yulin Si)

- **Underwater Robot Design:** Developed a compact, energy-save and easy-to-control underwater robot via Raspberry Pi, STM32 with the functions of navigation, obstacle avoidance, letter and color recognition. Data augmentation procedure based on BAGAN is utilized for enhancing the accuracy of the recognition task. We participated in the "Aotuo Cup" national underwater robot designing competition and won the first prize.

**2022.10 - 2023.7**  Zhejiang University, Intelligent Underwater Optical Laboratory, Undergraduate Researcher (Advisor - Prof. Hong Song)

- **Underwater Image Enhancement Based on Polarization Imaging:** A enhancing procedure maximizing the EME(measure of enhancement by entropy) of underwater polarized images based on stoke vector paramization and haze removal algorithm is proposed. I’ve also participated in applying this algorithm to a project concerning underwater 3D reconstruction and studied the basic knowledge about SLAM.



# 💻 Miscellaneous

I have a passion for computer-related knowledge and have a wide range of interests. I enjoy video editing and used to be a video uploader on a website called [bilibili](https://space.bilibili.com/21927744/), where I uploaded fun videos about computer knowledge and computer viruses. Up to 2019.6, I gained 22k+ subscribers, ranking within the top 10,000 of bilibili. During my university experiences, I accumulated two years of computer repair experience within the electrical volunteer association(EVA) of Zhejiang University. I also love running and during my college years, I keep running 10 kilometers daily during the winter vacation of final year of undergraduate study. These experiences have taught me that no matter how difficult the situation, I have the courage to persevere!



This page was last updated at UTC 2024/09/27 14:39.

