---
layout: splash
permalink: /teams

---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>轮播图片和文字示例</title>
<style>
    .container {
        display: flex;
        align-items: center;
        justify-content: space-between;
        padding: 1px;
    }
    .slideshow {
        width: 45%; /* 调整轮播图片组件的宽度 */
        height: 500px;
        overflow: hidden;
        position: relative;
    }
    .slideshow img {
        position: absolute;
        top: 50%;
        left: 50%;
        transform: translate(-50%, -50%);
        width: auto;
        height: auto;
        max-width: 100%;
        max-height: 100%;
        opacity: 0;
        transition: opacity 1s ease-in-out;
        object-fit: cover;
    }
    .text-container {
        width: 45%; /* 调整文字内容的宽度 */
    }
</style>
</head>
<body>

<div class="container">
    <div class="slideshow">
        <img src="images\01.jpg" alt="Image 1">
        <img src="images\02.jpg" alt="Image 2">
        <img src="images\03.jpg" alt="Image 3">
        <img src="images\04.jpg" alt="Image 4">
    </div>
    <div class="text-container">
        <h1>智能成像研究小组 (I²Group)</h1>
        <p>隶属于中国科学院自动化研究所多模态人工智能系统全国重点实验室视频内容安全团队，团队负责人为胡卫明研究员，研究小组负责人为李兵研究员和王隽副研究员。研究小组围绕ISP智能参数优化、图像质量评估、low-level视觉大模型、白平衡等底层视觉方向开展了一系列具有高学术价值的基础理论和创新方法研究，相关成果发表在TPAMI、IJCV、CVPR、ECCV等国际权威期刊和会议上，并获得了AIM 2022 Learned Smart ISP客观指标赛道的第一名，核心技术已在合作企业的产品上实现落地应用，大幅提升了相机成像的质量和效率，加快了产品的更新迭代，给用户带来了更好的视觉体验。</p>
    </div>
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
</html>

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
