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
<div style="text-align: justify"> 
I am currently an final-year undergraduate student in Data Science & AI at Hanoi University of Science & Technology (HUST). Besides, I am a research intern at Aural & Language Intelligence Dept., I2R, A*STAR Singapore under the supervision of <a href="https://research.a-star.edu.sg/researcher/huy-dat-tran/">Dr. Tran Huy Dat</a>.
<br>
<br>
My research interest includes technologies and industrial-oriented solutions to <strong>speech processing</strong>: recognition, diarization, emotion recognition, spoof detection; <strong>speaker processing</strong>: recognition, verification, representation. I also have some experience in working with and delivering Large Language Models on the application level. I have had a few publications at the top-ranked conferences in speech and signal processing and technologies (ICASSP, Interspeech). 
<!-- <a href='https://scholar.google.com/citations?user=m3UGj48AAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. -->

</div>
# 🎉 News in 2025
- (10th June) I got accepted to a funded PhD position at Trinity College Dublin, Ireland! I will be supversied by Prof. Naomi Harte.
- (19th May) Two first-authored papers are accepted at Interspeech 2025!
- (25th Jan) I started doing my internship at I2R, A\*STAR Singapore under a project scholarship. I will be supervised by Dr. Tran Huy Dat.


# 📖 Educations
- *2025 - 2029 (Incoming)*, Doctor of Philosophy, School of Engineering, Trinity College Dubilin.<br>
Topic: Multimodal speech recognition and understanding.
- *2020 - 2025 (Now)*, Bachelor in Data Science & AI, Hanoi University of Science and Technology.


# 📝 Publications 
\* denotes equal contribution.  
Count=6
## 2025
[Pushing the Performance of Synthetic Speech Detection with Kolmogorov-Arnold Networks and Self-Supervised Learning Models]()  
**Long-Vu Hoang\***, Phuong Tuan Dat\*, Tran Huy Dat. *ISCA Interspeech 2025.*
<details>
<summary>TL;DR</summary>
<div style="text-align: justify"> 
Synthetic speech detection systems based on self-supervised learning (SSL) models, particularly the XLSR-Conformer model, have demonstrated remarkable performance in synthetic speech detection. In this paper, we propose a novel approach that replaces the traditional Multi-Layer Perceptron in the baseline model with a Kolmogorov-Arnold Network (KAN), as a projector between the upstream SSL and downstream Conformer model. We achieved SOTA results on various ASVspoof benchmarks (LA, DF).<br>
These findings suggest that incorporating KAN into SSL-based models is a promising direction for advances in synthetic speech detection.
</div>
</details>
<br>

[Acoustic scattering AI for non-invasive object classifications: A case study on hair assessment]()  
**Long-Vu Hoang\***, Tuan Nguyen\*, Tran Huy Dat. *ISCA Interspeech 2025.*
<details>
<summary>TL;DR</summary>
<div style="text-align: justify"> 
This paper presents a novel non-invasive object classification approach using acoustic scattering, demonstrated through a case study on hair assessment.<br>
When an incident wave interacts with an object, it generates a scattered acoustic field encoding structural and material properties. By emitting acoustic stimuli and capturing the scattered signals from head-with-hair-sample objects, we classify hair type and moisture using AI-driven, deep-learning-based sound classification. The experimental results highlight acoustic scattering as a privacy-preserving, non-contact alternative to visual classification, opening huge potential for applications in various industries.
</div>
</details>
<br>

[VoxVietnam: a Large-Scale Multi-Genre Dataset for Vietnamese Speaker Recognition](https://arxiv.org/pdf/2501.00328) [<img src="images/hf_mini.png" alt="HuggingFace" style="vertical-align: middle; width: 20px;">HuggingFace](https://huggingface.co/datasets/hustep-lab/VoxVietnam-Dataset)  
**Hoang Long Vu**, Phuong Tuan Dat, Pham Thao Nhi, Nguyen Song Hao, Nguyen Thi Thu Trang. *IEEE ICASSP 2025.*
<details>
<summary>TL;DR</summary>
<div style="text-align: justify"> 
Recent research in speaker recognition aims to address vulnerabilities due to variations between enrolment and test utterances, particularly in the multi-genre phenomenon where the utterances are in different speech genres. Previous resources for Vietnamese speaker recognition are either limited in size or do not focus on genre diversity, leaving studies in multi-genre effects unexplored.<br>   

This paper introduces VoxVietnam, the first multi-genre dataset for Vietnamese speaker recognition with over 187,000 utterances from 1,406 speakers and an automated pipeline to construct a dataset on a large scale from public sources.
</div>
</details>

## 2024
[VSASV: A Vietnamese dataset for spoofing-aware speaker verification](https://www.isca-archive.org/interspeech_2024/hoang24b_interspeech.pdf) [<img src="images/hf_mini.png" alt="HuggingFace" style="vertical-align: middle; width: 20px;">HuggingFace](https://huggingface.co/datasets/hustep-lab/VSASV-Dataset)    
**Vu Hoang\***, Viet Thanh Pham\*, Hoa Nguyen Xuan\*, Nhi Pham, Phuong Dat, Thi Thu Trang Nguyen. *ISCA Interspeech 2024 **(Oral)**.*
<details>
<summary>TL;DR</summary>
<div style="text-align: justify"> 
Recent research in improving speaker verification systems to detect spoofed speech has seen a concentrated focus on English language, while the performance of such systems in other languages remains unexplored. This paper introduces VSASV - the first Spoofing-Aware Speaker Verification (SASV) in Vietnamese language. 
<br>
The dataset comprises over 174,000 spoofed utterances and 164,000 authentic utterances from 1,382 speakers, generated with 3 techniques: voice conversion, replay, and adversarial attack.</div>
</details>
<br>

[MSV challenge: Language-adversarial training for indic multilingual speaker verification](https://vjs.ac.vn/index.php/jcc/article/view/18320)  
**Vu Hoang\***, Nguyen Van Huy\*, Ngo Thi Thu Huyen\*, Viet Thanh Pham. *Journal of Computer Science and Cybernetics.*
<details>
<summary>TL;DR</summary>
<div style="text-align: justify"> 
We propose an ensemble system submitted to the I-MSV Challenge 2022 (Indic multilingual speaker verification). The system is built upon the ECAPA and RawNet model with additional adversarial training layers to remove language information. We achieved the third rank in the competition.</div>
</details>
## 2023
[Vietnam-Celeb: a large-scale dataset for Vietnamese speaker recognition](https://www.isca-archive.org/interspeech_2023/pham23b_interspeech.pdf)[<img src="images/hf_mini.png" alt="HuggingFace" style="vertical-align: middle; width: 20px;">HuggingFace](https://huggingface.co/datasets/hustep-lab/Vietnam-Celeb)   
Pham Viet Thanh, Nguyen Xuan Thai Hoa, **Hoang Long Vu**, Nguyen Thi Thu Trang. *ISCA Interspeech 2023.*
<details>
<summary>TL;DR</summary>
<div style="text-align: justify"> 
The success of speaker recognition systems heavily depends on large training datasets collected under real-world conditions. While common languages like English or Chinese have vastly available datasets, low-resource ones like Vietnamese remain limited.<br>

This paper presents a large-scale spontaneous dataset gathered under noisy environments, with over 87,000 utterances from 1,000 Vietnamese speakers of many professions, covering 3 main Vietnamese dialects.</div>
</details>

# 🎖 Honors, Awards and Activities
- *Mar. 2025* I was given the President Certificate of Merit from HUST for students with excellent results and active contributions.
- *Jun. 2024* I was nominated by HUST to join the [2024 National University of Singapore (NUS) Young Fellowship Programme](https://nusgs.nus.edu.sg/2024-nus-young-fellowship/). My team and I won the Best Pitching Award for the Effects of Generative AI on PhD research.
- *From 2022 to 2024*, I participated and organised various challenges for Speaker Verification task, as a part of Vietnamese Language & Speech Processing ([VLSP](https://vlsp.org.vn/)) annual workshops.


# 💻 Internships and Research Collaborations
- *01/2025-Now* [I2R, A*STAR](https://www.a-star.edu.sg/i2r), Singapore.  
Reference: Dr. Tran Huy Dat, Senior Principal Scientist, Head of Audio Analytics and Speech Recognition.
- *10/2022-Now* [HuSTeP Lab](https://huggingface.co/hustep-lab), Hanoi, Vietnam. This is a speech technology research lab at HUST, founded by Dr. NGUYEN Thi Thu Trang. I was the research assistant and lab manager between 10/2023-01/2025.  
Reference: Dr. Nguyen Thi Thu Trang, Senior Lecturer at SoICT, HUST.
- *10/2023-01/2025*, [Vbee JSC.](https://vbee.ai/), Hanoi, Vietnam.
- *08/2023-10/2023*, [AIV Group](https://mindmaid.ai/), Hanoi, Vietnam.