---
title: "Ranking-based color constancy with limited training samples. IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)"
modified: 2024-01-25T16:03:49-04:00
header:
  teaser: "https://farm5.staticflickr.com/4076/4940499208_b79b77fb0a_z.jpg"
categories:
  - 期刊文章
tags:
  - update
---

<div style="font-weight: lighter;size:22px"> B. Li, H. Qin, W. Xiong, Y. Li, S. Feng, W. Hu and S. Maybank</div>
<div style="font-weight: lighter;size:22px;margin-bottom=20px">2023</div>


<h4>摘要</h4>
Computational color constancy is an important component of Image Signal Processors (ISP) for white balancing in many imaging devices. Recently, deep convolutional neural networks (CNN) have been introduced for color constancy. They achieve prominent performance improvements comparing with those statistics or shallow learning-based methods. However, the need for a large number of training samples, a high computational cost and a huge model size make CNN-based methods unsuitable for deployment on low-resource ISPs for real-time applications. In order to overcome these limitations and to achieve comparable performance to CNN-based methods, an efficient method is defined for selecting the optimal simple statistics-based method (SM) for each image. To this end, we propose a novel ranking-based color constancy method (RCC) that formulates the selection of the optimal SM method as a label ranking problem. RCC designs a specific ranking loss function, and uses a low rank constraint to control the model complexity and a grouped sparse constraint for feature selection. Finally, we apply the RCC model to predict the order of the candidate SM methods for a test image, and then estimate its illumination using the predicted optimal SM method (or fusing the results estimated by the top $k$ SM methods). Comprehensive experiment results show that the proposed RCC outperforms nearly all the shallow learning-based methods and achieves comparable performance to (sometimes even better performance than) deep CNN-based methods with only 1/2000 of the model size and training time. RCC also shows good robustness to limited training samples and good generalization crossing cameras. Furthermore, to remove the dependence on the ground truth illumination, we extend RCC to obtain a novel ranking-based method without ground truth illumination (RCC_NO) that learns the ranking model using simple partial binary preference annotations provided by untrained annotators rather than experts. RCC_NO also achieves better performance than the SM methods and most shallow learning-based methods with low costs of sample collection and illumination measurement.
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

href="https://ieeexplore.ieee.org/abstract/document/10130607" target="\_blank" rel="noopener"> Link </a>

</div>

