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

I am currently an final-year undergraduate student in Data Science & AI at Hanoi University of Science & Technology (HUST). Besides, I am a research intern at Aural & Language Intelligence Dept., I2R, A*STAR Singapore under the supervision of [Dr. Tran Huy Dat](https://research.a-star.edu.sg/researcher/huy-dat-tran/).


My research interest includes technologies and industrial-oriented solutions to __speech processing__: recognition, diarization, emotion recognition, spoof detection; __speaker processing__: recognition, verification, representation. I also have some experience in working with and delivering Large Language Models on the application level. I have had a few publications at the top-ranked conferences in speech and signal processing and technologies (ICASSP, Interspeech). <a href='https://scholar.google.com/citations?user=m3UGj48AAAAJ&hl'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

Currently, I am open to PhD opportunities in Speech understanding and Technologies.

<!-- # 📑 Research Areas -->






# 📖 Educations
- *2020 - 2025 (now)*, Bachelor in Data Science & AI, Hanoi University of Science and Technology.


# 📝 Publications 
\*Equal contribution.
## 2025
[VoxVietnam: a Large-Scale Multi-Genre Dataset for Vietnamese Speaker Recognition](https://arxiv.org/pdf/2501.00328) [<img src="images/hf_mini.png" alt="HuggingFace" style="vertical-align: middle; width: 20px;">HuggingFace](https://huggingface.co/datasets/hustep-lab/VoxVietnam-Dataset)  
**Hoang Long Vu**, Phuong Tuan Dat, Pham Thao Nhi, Nguyen Song Hao, Nguyen Thi Thu Trang. *IEEE ICASSP 2025.*
<details>
<summary>TL;DR</summary>
Recent research in speaker recognition aims to address vulnerabilities due to variations between enrolment and test utterances, particularly in the multi-genre phenomenon where the utterances are in different speech genres. Previous resources for Vietnamese speaker recognition are either limited in size or do not focus on genre diversity, leaving studies in multi-genre effects unexplored. This paper introduces VoxVietnam, the first multi-genre dataset for Vietnamese speaker recognition with over 187,000 utterances from 1,406 speakers and an automated pipeline to construct a dataset on a large scale from public sources. Our experiments show the challenges posed by the multi-genre phenomenon to models trained on a single-genre dataset, and demonstrate a significant increase in performance upon incorporating the VoxVietnam into the training process. Our experiments are conducted to study the challenges of the multi-genre phenomenon in speaker recognition and the performance gain when the proposed dataset is used for multi-genre training.
</details>

## 2024
[VSASV: A Vietnamese dataset for spoofing-aware speaker verification](https://www.isca-archive.org/interspeech_2024/hoang24b_interspeech.pdf) [<img src="images/hf_mini.png" alt="HuggingFace" style="vertical-align: middle; width: 20px;">HuggingFace](https://huggingface.co/datasets/hustep-lab/VSASV-Dataset)    
**Vu Hoang\***, Viet Thanh Pham\*, Hoa Nguyen Xuan\*, Nhi Pham, Phuong Dat, Thi Thu Trang Nguyen. *ISCA Interspeech 2024 **(Oral)**.*
<details>
<summary>TL;DR</summary>
Recent research in improving speaker verification systems to detect spoofed speech has seen a concentrated focus on English language, while the performance of such systems in other languages remains unexplored. This paper introduces the VSASV dataset for Spoofing-Aware Speaker Verification (SASV) in Vietnamese language. The dataset comprises over 174,000 spoofed utterances and 164,000 authentic utterances from 1,382 speakers, which were generated with the latest spoofing techniques to encourage the development of SASV systems in this language. We also provide experimental results on the efficacy of the different state-of-the-art anti-spoofing systems on Vietnamese language.
</details>
## 2023
[Vietnam-Celeb: a large-scale dataset for Vietnamese speaker recognition](https://www.isca-archive.org/interspeech_2023/pham23b_interspeech.pdf)[<img src="images/hf_mini.png" alt="HuggingFace" style="vertical-align: middle; width: 20px;">HuggingFace](https://huggingface.co/datasets/hustep-lab/Vietnam-Celeb)   
Pham Viet Thanh, Nguyen Xuan Thai Hoa, **Hoang Long Vu**, Nguyen Thi Thu Trang. *ISCA Interspeech 2023.*
<details>
<summary>TL;DR</summary>
The success of speaker recognition systems heavily depends on large training datasets collected under real-world conditions. While common languages like English or Chinese have vastly available datasets, low-resource ones like Vietnamese remain limited. This paper presents a large-scale spontaneous dataset gathered under noisy environments, with over 87,000 utterances from 1,000 Vietnamese speakers of many professions, covering 3 main Vietnamese dialects. To build the dataset, we propose a sophisticated construction pipeline that can also be applied to other languages, with efficient visual-aided processing techniques to boost data precision. With the state-of-the-art x-vector model, training with the proposed dataset shows an average absolute and relative EER improvement of 5.48% and 41.61% when compared to the model trained on VLSP 2021, a publicly available Vietnamese speaker dataset.
</details>

# 🎖 Honors, Awards and Activities
- *Mar. 2025* I was given the President Certificate of Merit from HUST for students with excellent results and active contributions.
- *Jun. 2024* I was nominated by HUST to join the [2024 National University of Singapore (NUS) Young Fellowship Programme](https://nusgs.nus.edu.sg/2024-nus-young-fellowship/). My team and I won the Best Pitching Award for the Effects of Generative AI on PhD research.
- *From 2022 to 2024*, I participated and organised various challenges for Speaker Verification task, as a part of Vietnamese Language & Speech Processing ([VLSP](https://vlsp.org.vn/)) annual workshops.


# 💻 Internships and Research Collaborations
- *01/2025-Now* [I2R, A*STAR](https://www.a-star.edu.sg/i2r), Singapore.
- *10/2022-Now* [HuSTeP Lab](https://huggingface.co/hustep-lab), Hanoi, Vietnam. This is a speech technology research lab at HUST, founded by Dr. NGUYEN Thi Thu Trang. I was the research assistant and lab manager between 10/2023-01/2025.
- *10/2023-01/2025*, [Vbee JSC.](https://vbee.ai/), Hanoi, Vietnam.
- *08/2023-10/2023*, [AIV Group](https://mindmaid.ai/), Hanoi, Vietnam.