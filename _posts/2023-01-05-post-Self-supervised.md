---
title: "SMM: Self-supervised Multi-Illumination Color Constancy Model with Multiple Pretext Tasks. Proceedings of the 31st ACM International Conference on Multimedia."
modified: 2024-01-25T12:24:42-04:00
categories:
  - 期刊文章
tags:
  - update
---
<div style="font-weight: lighter;size:22px">Z. Feng, Z. Xu , H. Qin, C. Lang, B. Li, W. Xiong</div>
<div style="font-weight: lighter;size:22px;margin-bottom=20px">2023</div>

<h4>摘要</h4>
Color constancy is an important ability of the human visual system to perceive constant colors across different illumination. In this paper, we study a more practical yet challenging task, removing color cast by multiple spatial-varying illumination. Previous methods are limited by the scale of the current multi-illumination datasets, which hinders them from learning more discriminative features. Instead, we first propose a self-supervised multi-illumination color constancy model that leverages multiple pretext tasks to fully explore lighting color contextual information and inherent color information without using any manual annotations. During the pre-training phase, we train multiple Transformer-based encoders by learning multiple pretext tasks: (i) the local color distortion recovery task, which is carefully designed to learn lighting color contextual representation, and (ii) the colorization task, which is utilized to acquire inherent knowledge. In the downstream color constancy task, we fine-tune the encoders and design a lightweight decoder to obtain better illumination distributions with fewer parameters. Our lightweight architecture outperforms the state-of-the-art methods on the multi-illuminant benchmark (LSMI) and got robust performance on the single illuminant benchmark (NUS-8). Additionally, extensive ablation studies and visualization results demonstrate the effectiveness of integrating lighting color contextual and inherent color information learning in a self-supervised manner.
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

href="https://dl.acm.org/doi/abs/10.1145/3581783.3612057" target="\_blank" rel="noopener"> Link </a>

</div>
