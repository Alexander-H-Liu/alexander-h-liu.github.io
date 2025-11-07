---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


# Bio

Alexander Liu is a final year Ph.D. candidate in Computer Science at MIT Computer Science and Artificial Intelligence Laboratory (CSAIL).
He is a member of the Spoken Language System (SLS) Group led by [Dr. James Glass](http://people.csail.mit.edu/jrg/). 
His work focuses on natural language and speech processing for artificial intelligence, with the goal of building machines human can seamlessly interact with through voice. Examples include multimodal audio representation learning, multimodal alignment, large language models and generative models for audio.

Prior to joining MIT, Alex received his M.S. and B.S. degrees in Computer Science & Information Engineering (CSIE) from National Taiwan University (NTU).
He was a member of the Speech Processing Lab working with [Lin-shan Lee](http://speech.ee.ntu.edu.tw/previous_version/lslNew.htm) and Prof. [Hung-yi Lee](http://speech.ee.ntu.edu.tw/~tlkagk/) in the area of machine learning and speech processing.
During his undergraduate years, he worked with [Yu-Chiang Frank Wang](http://vllab.ee.ntu.edu.tw/members.html) in computer vision and representation learning.
Besides academic labs, he also spent time working at Facebook AI Research (now FAIR at Meta AI) and Nvidia Applied Deep Learning Research (ADLR) as a research intern.

[Selected Publications](#selected-publications) / [Selected Reports](#selected-reports)/ [Teaching](#teaching) / [Honors](#honors) / [Open-source Contributions](#open-source-contributions)
<!-- / [CV](files/cv.pdf) -->

# News

- I'm currently on leave until Spring 2026, working at Mistral AI to build frontier open audio models such as [Voxtral](#selected-reports). (Our speech team is growing, please reach out if you are interested!)

- Inspired by [Wei-Chiu Ma](https://people.csail.mit.edu/weichium/), I would like to commit 1-2 hours per week to provide suggestions and/or mentorships to junior students in need, especially those from underrepresented groups. Please fill out [this form](https://forms.gle/EmwuCPpxqEoLyCfi7) if you are interested.

# Selected Publications

For the complete list, please visit [google scholar](https://scholar.google.com/citations?user=LIiCDa0AAAAJ).

- **SHuBERT: Self-Supervised Sign Language Representation Learning via Multi-Stream Cluster Prediction**<br/>
    Shester Gueuwou, Xiaoyi Du, Gregory Shakhnarovich, Karen Livescu, <u>Alexander H. Liu</u><br/>
    *Annual Meeting of the Association for Computational Linguistics (ACL) 2025 (Oral)*<br/>
    [ [paper](https://arxiv.org/pdf/2411.16765) | [project page](https://shubert.pals.ttic.edu/) | [code](https://github.com/ShesterG/SHuBERT) | [interactive demo](https://huggingface.co/spaces/ShesterG/TTIC-SHuBERT-ASLVideo-to-EnglishText) ]

- **UniWav: Towards Unified Pre-training for Speech Representation Learning and Generation**<br/>
    <u>Alexander H. Liu</u>, Sungho Lee, Chien-Hsin H. Yang, Yu Gong, Yu-Chiang Frank Wang, James R. Glass, Rafael Valle, Bryan Catanzaro<br/>
    *International Conference on Learning Representations (ICLR) 2025*<br/>
    [ [paper](https://arxiv.org/pdf/2503.00733) ]

- **Generative Speech Foundation Model Pretraining for High-Quality Speech Extraction and Restoration**<br/>
    Po-Jui Ku, <u>Alexander H. Liu</u>, Roman Korostik, Sung-Feng Huang, Szu-Wei Fu, Ante Jukić<br/>
    *IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2025*<br/>
    [ [paper](https://arxiv.org/pdf/2409.16117) | [code](https://github.com/NVIDIA-NeMo/NeMo/blob/main/examples/audio/conf/flow_matching_generative_ssl_pretraining.yaml) | [demo](https://kuray107.github.io/ssl_gen25-examples/index.html) ]

- **Generative Pre-training for Speech with Flow Matching**<br/>
    <u>Alexander H. Liu</u>, Matthew Le, Apoorv Vyas, Bowen Shi, Andros Tjandra, Wei-Ning Hsu<br/>
    *International Conference on Learning Representations (ICLR) 2024*<br/>
    [ [paper](https://openreview.net/forum?id=KpoQSgxbKH) ]

- **Revisiting Self-supervised Learning of Speech Representation from a Mutual Information Perspective**<br/>
    <u>Alexander H. Liu</u><sub>(co-first)</sub>, Sung-Lin Yeh<sub>(co-first)</sub>, James Glass<br/>
    *In IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2024*<br/>
    [ [paper](http://arxiv.org/abs/2401.08833) ]

- **DinoSR: Self-Distillation and Online Clustering for Self-supervised Speech Representation Learning**<br/>
    <u>Alexander H. Liu</u>, Heng-Jui Chang, Michael Auli<sub>(co-last)</sub>, Wei-Ning Hsu<sub>(co-last)</sub>, James Glass<sub>(co-last)</sub><br/>
    *In Advances in Neural Information Processing Systems (NeurIPS) 2023*<br/>
    [ [paper](https://arxiv.org/pdf/2305.10005) | [code](https://github.com/Alexander-H-Liu/dinosr) ]

- **Joint Audio and Speech Understanding**<br/>
    Yuan Gong, <u>Alexander H. Liu</u>, Hongyin Luo, Leonid Karlinsky, James Glass<br/>
    *IEEE Automatic Speech Recognition and Understanding Workshop (ASRU) 2023*<br/>
    [ [paper](https://arxiv.org/pdf/2309.14405) | [interactive demo](https://huggingface.co/spaces/yuangongfdu/ltu-2) ]

- **Listen, Think, and Understand**<br/>
    Yuan Gong, Hongyin Luo, <u>Alexander H. Liu</u>, Leonid Karlinsky, James Glass<br/>
    *International Conference on Learning Representations (ICLR) 2024*<br/>
    [ [paper](https://arxiv.org/pdf/2305.10790) | [interactive demo](https://huggingface.co/spaces/yuangongfdu/ltu) ]

- **Contrastive Audio-Visual Masked Autoencoder**<br/>
    Yuan Gong, Andrew Rouditchenko, <u>Alexander H. Liu</u>, David Harwath, Leonid Karlinsky, Hilde Kuehne, James Glass<br/>
    *International Conference on Learning Representations (ICLR) 2023*<br/>
    [ [paper](https://openreview.net/forum?id=QPtMRyk5rb) | [code](https://github.com/YuanGongND/cav-mae) ]

- **Simple and Effective Unsupervised Speech Synthesis**<br/>
    <u>Alexander H. Liu</u> <sub>(co-first)</sub>, Cheng-I Jeff Lai <sub>(co-first)</sub>, Wei-Ning Hsu, Michael Auli, Alexei Baevskiv, James Glass<br/>
    *InterSpeech 2022*<br/>
    [ [paper](https://arxiv.org/abs/2204.02524) | [demo](https://people.csail.mit.edu/clai24/unsup-tts/) ]

- **Towards End-to-end Unsupervised Speech Recognition**<br/>
    <u>Alexander H. Liu</u>, Wei-Ning Hsu, Michael Auli, Alexei Baevski<br/>
    *Spoken Language Technology Workshop (SLT) 2022*<br/>
    [ [paper](https://arxiv.org/abs/2204.02492) | [code](https://github.com/pytorch/fairseq/blob/main/examples/wav2vec/unsupervised) ]

- **Cross-Modal Discrete Representation Learning**<br/>
    <u>Alexander H. Liu</u>, SouYoung Jin, Cheng-I Jeff Lai, Andrew Rouditchenko, Aude Oliva, James Glass<br/>
    *Annual Meeting of the Association for Computational Linguistics (ACL) 2022*<br/>
    [ [paper](https://arxiv.org/abs/2106.05438) ]

- **Spoken moments: Learning Joint Audio-visual Representations from Video Descriptions**<br/>
    Mathew Monfort <sub>(co-first)</sub>, SouYoung Jin <sub>(co-first)</sub>, <u>Alexander H. Liu</u>, David Harwath, Rogerio Feris, James Glass, Aude Oliva<br/>
     *In IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2021*<br/>
    [ [paper](https://openaccess.thecvf.com/content/CVPR2021/html/Monfort_Spoken_Moments_Learning_Joint_Audio-Visual_Representations_From_Video_Descriptions_CVPR_2021_paper.html) | [dataset](http://moments.csail.mit.edu/spoken.html) ]

- **Non-Autoregressive Predictive Coding for Learning Speech Representations from Local Dependencies**<br/>
    <u>Alexander H. Liu</u>, Yu-An Chung, James Glass<br/>
    *InterSpeech 2021*<br/>
    [ [paper](https://arxiv.org/abs/2011.00406) | [code](https://github.com/Alexander-H-Liu/NPC) ]

- **Towards Unsupervised Speech Recognition and Synthesis with Quantized Speech Representation Learning**<br/>
    <u>Alexander H. Liu</u> <sub>(co-first)</sub>, Tao Tu <sub>(co-first)</sub>,  Hung-yi Lee, Lin-shan Lee<br/>
    *In IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2020*<br/>
    [ [paper](https://arxiv.org/abs/1910.12729) | [demo](https://ttaoretw.github.io/SeqRQ-AE/demo.html) ]

<!-- - **Sequence-to-sequence Automatic Speech Recognition with Word Embedding Regularization and Fused Decoding**<br/>
    <u>Alexander H. Liu</u>, Tzu-Wei Sung, Shun-Po Chuang, Hung-yi Lee, Lin-shan Lee<br/>
    *In IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2020*<br/>
    [ [paper](https://arxiv.org/abs/1910.12740) | [code](https://github.com/Alexander-H-Liu/End-to-end-ASR-Pytorch) ] -->

- **Towards Scene Understanding: Unsupervised Monocular Depth Estimation with Semantic-Aware Representation**<br/>
    <u>Alexander H. Liu</u> <sub>(co-first)</sub>, Po-Yi Chen <sub>(co-first)</sub>, Yen-Cheng Liu, Yu-Chiang Frank Wang<br/>
    *In IEEE Conference on Computer Vision and Pattern Recognition (CVPR), 2019*<br/>
    [ [paper](http://openaccess.thecvf.com/content_CVPR_2019/papers/Chen_Towards_Scene_Understanding_Unsupervised_Monocular_Depth_Estimation_With_Semantic-Aware_Representation_CVPR_2019_paper.pdf) | [oral](https://www.youtube.com/watch?v=BQZ5xKd5kis&t=4717s) | [supplementary](http://openaccess.thecvf.com/content_CVPR_2019/html/Chen_Towards_Scene_Understanding_Unsupervised_Monocular_Depth_Estimation_With_Semantic-Aware_Representation_CVPR_2019_paper.html) ]
    
<!-- - **Adversarial Training of End-to-end Speech Recognition Using a Criticizing Language Model**<br/>
    <u>Alexander H. Liu</u>, Hung-yi Lee, Lin-shan Lee<br/>
    *In IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) 2019*<br/>
    [ [paper](https://arxiv.org/abs/1811.00787) | [code](https://github.com/Alexander-H-Liu/End-to-end-ASR-Pytorch) ] -->
    
- **A Unified Feature Disentangler for Multi-Domain Image Translation and Manipulation**<br/>
    <u>Alexander H. Liu</u>, Yen-Cheng Liu, Yu-Ying Yeh, Yu-Chiang Frank Wang<br/>
    *In Advances in Neural Information Processing Systems (NeurIPS) 2018*<br/>
    [ [paper](http://papers.nips.cc/paper/7525-a-unified-feature-disentangler-for-multi-domain-image-translation-and-manipulation.pdf) | [code](https://github.com/Alexander-H-Liu/UFDN) | [supplementary & reviews](http://papers.nips.cc/paper/7525-a-unified-feature-disentangler-for-multi-domain-image-translation-and-manipulation)  ]

# Selected Reports

- **Voxtral**<br/>
    <u>Alexander H. Liu</u>, Andy Ehrenberg, Andy Lo, Clément Denoix, Corentin Barreau, Guillaume Lample, Jean-Malo Delignon, Khyathi Raghavi Chandu, Patrick von Platen, Pavankumar Reddy Muddireddy,
Sanchit Gandhi, Soham Ghosh, Srijan Mishra, Thomas Foubert, et al.<br/>
    *Mistral AI, 2025*<br/>
    [ [technical report](https://arxiv.org/pdf/2507.13264) | [model weights](https://huggingface.co/mistralai/models?search=voxtral) | [blog](https://mistral.ai/news/voxtral) ]

- **Towards Audio Language Modeling - An Overview**<br/>
    Haibin Wu, Xuanjun Chen, Yi-Cheng Lin, Kai-Wei Chang, Ho-Lam Chung, <u>Alexander H. Liu</u>, Hung-yi Lee<br/>
    *arXiv preprint, 2024*<br/>
    [ [paper](https://arxiv.org/pdf/2402.13236) ]

# Teaching

- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Guest Lecturer, Spoken Language Processing</span> <span style="flex:  0 0 auto"><i>MIT, Spring 2024</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">TA of <a href="https://www.mit.edu/~jda/teaching/6.864/">Natural Language Processing</a></span> <span style="flex:  0 0 auto"><i>MIT, Fall 2021</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Head TA of <a href="http://speech.ee.ntu.edu.tw/DSP2018Autumn/">Fundamentals of Speech Signal Processing</a></span> <span style="flex:  0 0 auto"><i>NTU, Academic Year 2018</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">TA of <a href="http://speech.ee.ntu.edu.tw/~tlkagk/courses.html">Deep Learning for Human Language Processing</a></span> <span style="flex:  0 0 auto"><i>NTU, Fall 2018</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">TA of <a href="http://speech.ee.ntu.edu.tw/~tlkagk/courses_MLDS18.html">Machine Learning and having it Deep and Structured</a></span> <span style="flex:  0 0 auto"><i>NTU, Spring 2018</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">TA of Deep Learning for Computer Vision</span> <span style="flex:  0 0 auto"><i>NTU, Spring 2018</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">TA of Advanced Deep Learning</span> <span style="flex:  0 0 auto"><i>NTU, Spring 2018</i></span></p>

<!-- 
# Talks
- [Towards Scene Understanding: Unsupervised Monocular Depth Estimation With Semantic-Aware Representation](http://aliensunmin.github.io/aii_workshop/3rd/) , *3rd AII workshop, New Taipei, Taiwan, July 2019*
- [Towards Scene Understanding: Unsupervised Monocular Depth Estimation With Semantic-Aware Representation](https://www.youtube.com/watch?v=BQZ5xKd5kis&t=4717s) , *CVPR, CA, USA, June 2019*
- [Towards Scene Understanding: Unsupervised Monocular Depth Estimation With Semantic-Aware Representation]() , *Yahoo! Inc., Taipei, Taiwan, May 2019*
-->

# Honors

- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">MOE Taiwan Scholarship</span> <span style="flex:  0 0 auto"><i>Ministry of Education, Taiwan 2022-2023</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Outstanding Master's Thesis Award</span> <span style="flex:  0 0 auto"><i>ACLCLP 2020</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Excellent Teaching Assistant Award</span> <span style="flex:  0 0 auto"><i>NTU CSIE Dept. 2019</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Advanced Speech Technologies Scholarship</span> <span style="flex:  0 0 auto"><i>NTU EECS 2019</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Verizon Media AI Scholarship</span> <span style="flex:  0 0 auto"><i>Verizon (Taiwan) 2019</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Best Student Speaker Award</span> <span style="flex:  0 0 auto"><i>3rd Augmented Intelligence and Interaction (AII) Workshop 2019</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">1st Prize, Formosa Spoken QA Challenge</span> <span style="flex:  0 0 auto"><i>Ministry of Science and Technology, Taiwan 2019</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Technology Scholarship</span> <span style="flex:  0 0 auto"><i>Foxconn Education Foundation 2018</i></span></p>
- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto">Presidential Awards (top 5%)</span> <span style="flex:  0 0 auto"><i>National Taiwan University 2017/2018</i></span></p>


# Open-source Contributions

- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><strong><a href="https://huggingface.co/mistralai/models?search=voxtral">Voxtral</a></strong><br/>Core contributor -- state-of-the-art large spoken language models, 400k total downloads</span> <span style="flex:  0 0 auto"><i>2025</i></span></p>

- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><strong><a href="https://github.com/facebookresearch/fairseq">Fairseq -- wav2vec-U 2.0</a></strong><br/>Contributor -- speech recognition algorithm to the well-known NLP toolkit, 31.9k stars</span> <span style="flex:  0 0 auto"><i>2022</i></span></p>

- <p style="display: flex; flex-direction: row; justify-content: space-between; margin: 0 0 0.5em;"><span style="flex: 0 0 auto"><strong><a href="https://github.com/Alexander-H-Liu/End-to-end-ASR-Pytorch">End-to-end-ASR-Pytorch</a></strong><br/>Creator -- one of the first deep speech recognition model in Pytorch, 1.2k stars</span> <span style="flex:  0 0 auto"><i>2018</i></span></p>
