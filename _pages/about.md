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

Hi, I’m Jun Liu (刘俊). I am currently a Postdoctoral Research Fellow at <a href='https://zhanggroup.org/'>ZhangLab</a>, Cancer Science Institute of Singapore (CSI), National University of Singapore (NUS), under the supervision of Prof. <a href='https://csi.nus.edu.sg/researcher/yang-zhang/'>Yang Zhang</a>. I received my Ph.D. in Control Science and Engineering from Zhejiang University of Technology (China), where I was advised by Prof. <a href='http://zhanglab-bioinf.com/people/guijunz/'>Guijun Zhang</a>. 

My research interests focus on AI-driven computational structural biology, including protein structure prediction and model quality assessment, protein–protein and antibody–antigen interaction modeling, and therapeutic antibody design and engineering.


# 🔥 News
- *2026.01*: &nbsp;🎉 Our PPLM paper on protein–protein interaction, affinity, and interface contact prediction has been accepted in Nature Communications.
- *2025.09*: Invited to give a talk at the <a href='https://csi.nus.edu.sg/event/csi-research-meeting-5-sep-2025/'>CSI Research Meeting</a>, National University of Singapore (NUS).
- *2025.06*: &nbsp;🎉 Received the <a href='https://www.nmrc.sg/grants/competitive-research-grants/of-yirg/'>OF-YIRG (Open Fund – Young Individual Research Grant)</a> award from the National Medical Research Council (NMRC) of Singapore — <a href='https://csi.nus.edu.sg/congratulations-on-the-nmrc-of-yirg-award-dr-jun-liu/'>my first independent, national-level research grant as a new investigator</a>.


# 💰 Funding
- Genome-Wide Antibody–Antigen Interaction Prediction Through Large Language Models. **National Medical Research Council (NMRC), Singapore — Open Fund – Young Individual Research Grant (OF-YIRG)**. Award No. MOH-OFYIRG25jan-0011. 01 Aug 2025 – 31 Jul 2028 (**PI**). 


# 📝 Publications 
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div> -->
<!-- <div class='paper-box-text' markdown="1"> -->

† indicates equal contribution, * indicates the corresponding author.

- ***Jun Liu***, Hungyu Chen, Yang Zhang\*.
  A Corporative Language Model for Protein–Protein Interaction, Binding Affinity, and Interface Contact Prediction.
  ***Nature Communications***, in press, 2026. <a href='https://zhanggroup.org/PPLM'>[Server]</a>

- ***Jun Liu***, Guangxing He, Kailong Zhao, Xiaogen Zhou, Guijun Zhang\*.
  De novo protein structure prediction by model quality assessment dynamic feedback mechanism using deep learning.
  ***IEEE Transactions on Computational Biology and Bioinformatics***, 22(6): 3476-3485, 2025. <a href='https://pubmed.ncbi.nlm.nih.gov/41201924/'>[Paper]</a>

- Dong Liu, ***Jun Liu***, Haodong Wang, Fang Liang, Guijun Zhang\*.
  DeepUMQA-X: Comprehensive and insightful estimation of model accuracy for protein single-chain and complex.
  ***Nucleic Acids Research***, 53(W1): W219–W227, 2025. <a href='https://academic.oup.com/nar/advance-article-abstract/doi/10.1093/nar/gkaf380/8124942/'>[Paper]</a>

- Chunxiang Peng, Xiaogen Zhou, ***Jun Liu***, Minghua Hou, Stan Z. Li, Guijun Zhang\*.
  Multiple conformational states assembly of multidomain proteins using evolutionary algorithm based on structural analogues and sequential homologues.
  ***Fundamental Research***, in press, 2024. <a href='https://www.sciencedirect.com/science/article/pii/S2667325824002103'>[Paper]</a>

- Dong Liu, Biao Zhang, ***Jun Liu***, Hui Li, Le Song, Guijun Zhang\*.
  Assessing protein model quality based on deep graph coupled networks using protein language model.
  ***Briefings in Bioinformatics***, 25(1): bbad420, 2024. <a href='https://academic.oup.com/bib/article/25/1/bbad420/7450272'>[Paper]</a>

- ***Jun Liu***, Dong Liu, Guijun Zhang\*.
  DeepUMQA3: A web server for accurate assessment of interface residue accuracy in protein complexes.
  ***Bioinformatics***, 39(10): btad591, 2023. <a href='https://academic.oup.com/bioinformatics/article/39/10/btad591/7280696'>[Paper]</a> <a href='http://zhanglab-bioinf.com/DeepUMQA_server/'>[Server]</a>

- ***Jun Liu***, Dong Liu, Guangxing He, Guijun Zhang\*.
  Estimating protein complex model accuracy based on ultrafast shape recognition and deep learning in CASP15.
  ***Proteins: Structure, Function, and Bioinformatics***, 91(12): 1861-1870, 2023. <a href='https://onlinelibrary.wiley.com/doi/abs/10.1002/prot.26564'>[Paper]</a>

- Guangxing He†, ***Jun Liu†***, Dong Liu, Guijun Zhang\*.
  GraphGPSM: A global scoring model for protein structure using graph neural networks.
  ***Briefings in Bioinformatics***, 24(4): bbad219, 2023. <a href='https://academic.oup.com/bib/article/24/4/bbad219/7197734'>[Paper]</a>

- ***Jun Liu***, Kailong Zhao, Guijun Zhang\*.
  Improved model quality assessment using sequence and structural information by enhanced deep neural networks.
  ***Briefings in Bioinformatics***, 24(1): bbac507, 2022. <a href='https://academic.oup.com/bib/article-abstract/24/1/bbac507/6865134'>[Paper]</a>

- Chunxiang Peng, Xiaogen Zhou, Yuhao Xia, ***Jun Liu***, Minghua Hou, Guijun Zhang\*.
  Structural analogue-based protein structure domain assembly assisted by deep learning.
  ***Bioinformatics***, 38(19): 4513-4521, 2022. <a href='https://academic.oup.com/bioinformatics/article-abstract/38/19/4513/6665901'>[Paper]</a>

- Zhongze Yu, Chunxiang Peng, ***Jun Liu***, Biao Zhang, Xiaogen Zhou, Guijun Zhang\*.
  DomBpred: Protein domain boundary prediction based on domain-residue clustering using inter-residue distance.
  ***IEEE/ACM Transactions on Computational Biology and Bioinformatics***, 20(2): 912-922, 2022. <a href='https://ieeexplore.ieee.org/abstract/document/9779486/'>[Paper]</a>

- Qiongqiong Feng, Minghua Hou, ***Jun Liu***, Kailong Zhao, Guijun Zhang\*.
  Construct a variable-length fragment library for de novo protein structure prediction.
  ***Briefings in Bioinformatics***, 23(3): bbac086, 2022. <a href='https://academic.oup.com/bib/article-abstract/23/3/bbac086/6547572'>[Paper]</a>

- Saisai Guo†, ***Jun Liu†***, Xiaogen Zhou, Guijun Zhang\*.
  DeepUMQA: Ultrafast shape recognition-based protein model quality assessment using deep learning.
  ***Bioinformatics***, 38(7): 1895-1903, 2022. <a href='https://academic.oup.com/bioinformatics/article-abstract/38/7/1895/6520805'>[Paper]</a>

- ***Jun Liu***, Kailong Zhao, Guangxing He, Liujing Wang, Xiaogen Zhou, Guijun Zhang\*.
  A de novo protein structure prediction by iterative partition sampling, topology adjustment, and residue-level distance deviation optimization.
  ***Bioinformatics***, 38(1): 99-107, 2022. <a href='https://academic.oup.com/bioinformatics/article-abstract/38/1/99/6359814'>[Paper]</a>

- Kailong Zhao, ***Jun Liu***, Xiaogen Zhou, Jianzhong Su\*, Yang Zhang\*, Guijun Zhang\*.
  MMpred: A distance-assisted multimodal conformation sampling for de novo protein structure prediction.
  ***Bioinformatics***, 37(23): 4350-4356, 2021. <a href='https://academic.oup.com/bioinformatics/article-abstract/37/23/4350/6311264'>[Paper]</a>

- Liujing Wang, ***Jun Liu***, Yuhao Xia, Jiakang Xu, Xiaogen Zhou, Guijun Zhang\*.
  Distance-guided protein folding based on generalized descent direction.
  ***Briefings in Bioinformatics***, 22(6): bbab296, 2021. <a href='https://academic.oup.com/bib/article-abstract/22/6/bbab296/6341661'>[Paper]</a>

- Liujing Wang, Xiaogen Zhou, Tengyu Xie, ***Jun Liu***, Guijun Zhang\*.
  Adaptive differential evolution with information entropy-based mutation strategy.
  ***IEEE Access***, 9: 146783-146796, 2021. <a href='https://ieeexplore.ieee.org/abstract/document/9568913/'>[Paper]</a>

- ***Jun Liu***, Xiaogen Zhou, Yang Zhang\*, Guijun Zhang\*.
  CGLFold: A contact-assisted de novo protein structure prediction using global exploration and loop perturbation sampling algorithm.
  ***Bioinformatics***, 36(8): 2443–2450, 2020. <a href='https://academic.oup.com/bioinformatics/article-abstract/36/8/2443/5682409'>[Paper]</a>

- Xiaogen Zhou, Chunxiang Peng, ***Jun Liu***, Yang Zhang\*, Guijun Zhang\*.
  Underestimation-assisted global-local cooperative differential evolution and the application to protein structure prediction.
  ***IEEE Transactions on Evolutionary Computation***, 24(3): 536-550, 2020. <a href='https://ieeexplore.ieee.org/abstract/document/8821307/'>[Paper]</a>


# 🎖 Honors and Awards
- *2024* 🥇 Ranked #1 in protein complex interface residue identification at <a href='https://predictioncenter.org/casp16/zscores_EMA.cgi'>CASP16</a> (group: MQA).
- *2024* 🥇 Ranked #1 in QMODE 3 (MassiveFold model selection) for monomer at <a href='https://predictioncenter.org/casp16/zscores_EMA.cgi'>CASP16</a> (group: MQA).
- *2022* 🥇 Ranked #1 in protein complex local quality assessment at <a href='https://predictioncenter.org/casp15/zscores_EMA.cgi'>CASP15</a> (group: GuijunLab-RocketX).
- *2023* Outstanding Ph.D. Thesis Award, Zhejiang Society for Bioinformatics.
- *2022* Top Ten Academic Stars (Graduate Students), Zhejiang University of Technology.
- *2021* National Scholarship for Doctoral Students (China).
- *2019* Second Prize, 16th “Challenge Cup” National Undergraduate Extracurricular Academic &amp; Technology Competition (China). (Member rank: 1/8)
- *2019* Gold Award, 5th Zhejiang “Internet+” Innovation and Entrepreneurship Competition (China). (Member rank: 1/11)
- *2014* Third Prize, National Finals, China 3D Digitalization Innovation Design Competition (China). (Member rank: 3/3)

# 🧾 Academic Service
- Topic Editor, Frontiers Research Topic: Computer-Aided Approaches in Translational Structural Biology: Toward Future Biotechnological Applications (Frontiers in Chemical Biology).
- Reviewer for Nature biotechnology, Nature machine intelligence, PloS one, etc.

<!--
# 📖 Educations
- *2019.06 - 2022.04 (now)*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2015.09 - 2019.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
-->

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

<!--
# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China.
-->
