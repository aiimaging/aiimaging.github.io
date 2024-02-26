---
layout: splash
permalink: /airlab
header:
  overlay_color: "#5e616c"
  overlay_image: mm-home-page-feature.jpg
  cta_url: "/docs/quick-start-guide/"
  caption:
excerpt: '智能成像研究小组 (I2Group) 隶属于中国科学院自动化研究所多模态人工智能系统全国重点实验室视频内容安全团队，团队负责人为胡卫明研究员，研究小组负责人为李兵研究员和王隽副研究员。研究小组围绕ISP智能参数优化、图像质量评估、low-level视觉大模型、白平衡等底层视觉方向开展了一系列具有高学术价值的基础理论和创新方法研究，相关成果发表在TPAMI、IJCV、CVPR、ECCV等国际权威期刊和会议上，并获得了AIM 2022 Learned Smart ISP客观指标赛道的第一名，核心技术已在合作企业的产品上实现落地应用，大幅提升了相机成像的质量和效率，加快了产品的更新迭代，给用户带来了更好的视觉体验。<br /><br /> {::nomarkdown} {:/nomarkdown}'


---
<div>
<head>
    <style>  
        .slideshow img {
            position: absolute;
            width: 100%;
            height: 100%;
            opacity: 0;
            transition: opacity 1s ease-in-out;
        }
    </style>
</head>
<body>
    <div style="position: relative;width: 100%;height: 300px;overflow: hidden;">
        <img src="01.png" alt="Image 1">
        <img src="02.png" alt="Image 2">
        <img src="03.png" alt="Image 3">
    </div>

    <script>
        var images = document.querySelectorAll('.slideshow img');
        var currentImageIndex = 0;

        function showNextImage() {
            images[currentImageIndex].style.opacity = '0';
            currentImageIndex = (currentImageIndex + 1) % images.length;
            images[currentImageIndex].style.opacity = '1';
        }

        setInterval(showNextImage, 2000); 
    </script>
</body>
</div>


{% include feature_row id="intro" type="center" %}

{% include feature_row %}
