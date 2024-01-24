---
title: "Open-book video captioning with retrieve-copy-generate network"
modified: 2021-01-01T16:03:49-04:00
header:
  teaser: "https://farm5.staticflickr.com/4076/4940499208_b79b77fb0a_z.jpg"
categories:
  - Jekyll
tags:
  - update
---

<div style="font-weight: lighter;size:22px">Ziqi Zhang, Zhongang Qi, Chunfeng Yuan, Ying Shan, Bing Li, Ying Deng, Weiming Hu</div>
<div style="font-weight: lighter;size:22px;margin-bottom=20px">January 2021</div>
<div > 
<a style="
width:50px; 
height:30px; 
display:inline-block; 
color:darkblue; 
background-color:white;
text-decoration: none;
border-radius: 5px;
text-align: center;
border: 1px solid darkblue;
line-height: 30px;
"
onmouseover="this.style.backgroundColor='darkblue'; this.style.color='white';" 
onmouseout="this.style.backgroundColor='white'; this.style.color='darkblue';"

href="https://arxiv.org/pdf/2103.05284.pdf" target="\_blank" rel="noopener"> PDF </a>

</div>

<h4>摘要</h4>
Due to the rapid emergence of short videos and the requirement for content understanding and creation, the video captioning task has received increasing attention in recent years. In this paper, we convert traditional video captioning task into a new paradigm, \ie, Open-book Video Captioning, which generates natural language under the prompts of video-content-relevant sentences, not limited to the video itself. To address the open-book video captioning problem, we propose a novel Retrieve-Copy-Generate network, where a pluggable video-to-text retriever is constructed to retrieve sentences as hints from the training corpus effectively, and a copy-mechanism generator is introduced to extract expressions from multi-retrieved sentences dynamically. The two modules can be trained end-to-end or separately, which is flexible and extensible. Our framework coordinates the conventional retrieval-based methods with orthodox encoder-decoder methods, which can not only draw on the diverse expressions in the retrieved sentences but also generate natural and accurate content of the video. Extensive experiments on several benchmark datasets show that our proposed approach surpasses the state-of-the-art performance, indicating the effectiveness and promising of the proposed paradigm in the task of video captioning.

<br>
<h4>出版物</h4>
IEEE Conference on Computer Vision and Pattern Recognition (CVPR)
