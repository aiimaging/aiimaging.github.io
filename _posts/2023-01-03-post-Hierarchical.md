---
title: "Hierarchical Curriculum Learning for No-reference Image Quality Assessment, International Journal of Computer Vision (IJCV)"
modified: 2024-01-25T12:24:42-04:00
categories:
  - 期刊文章
tags:
  - update
---
<div style="font-weight: lighter;size:22px"> J. Wang, Z. Chen, C. Yuan, B. Li, W. Ma, W. Hu</div>
<div style="font-weight: lighter;size:22px;margin-bottom=20px">2023</div>

<h4>摘要</h4>
Despite remarkable success has been achieved by convolutional neural networks (CNNs) in no-reference image quality assessment (NR-IQA), there still exist many challenges in improving the performance of IQA for authentically distorted images. An important factor is that the insufficient annotated data limits the training of high-capacity CNNs to accommodate diverse distortions, complicated semantic structures and high-variance quality scores of these images. To address this problem, this paper proposes a hierarchical curriculum learning (HCL) framework for NR-IQA. The main idea of the proposed framework is to leverage the external data to learn the prior knowledge about IQA widely and progressively. Specifically, as a closely-related task with NR-IQA, image restoration is used as the first curriculum to learn the image quality related knowledge (i.e., semantic and distortion information) on massive distorted-reference image pairs. Then multiple lightweight subnetworks are designed to learn human scoring rules on multiple available synthetic IQA datasets independently, and a cross-dataset quality assessment correlation (CQAC) module is proposed to fully explore the similarities and diversities of different scoring rules. Finally, the whole model is fine-tuned on the target authentic IQA dataset to fuse the learned knowledge and adapt to the target data distribution. Experimental results show that our model achieves state-of-the-art performance on multiple standard authentic IQA datasets. Moreover, the generalization of our model is fully validated by the cross-dataset evaluation and the gMAD competition. In addition, extensive analyses prove that the proposed HCL framework is effective in improving the performance of our model.
<br>
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

href="https://link.springer.com/article/10.1007/s11263-023-01851-5" target="\_blank" rel="noopener"> Link </a>

</div>
