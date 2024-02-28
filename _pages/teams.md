---
layout: splash
permalink: /teams

---

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Research Team Members</title>
<style>
    body {
        font-family: Arial, sans-serif;
        margin: 0;
        padding: 0;
    }
    .container {
        max-width: 800px;
        margin: 50px auto;
        text-align: center;
    }
    .member {
        display: inline-block;
        margin: 1px;
        position: relative;
        cursor: pointer;
    }
    .member img {
        border-radius: 50%;
        width:auto ;
        height: auto;
        transition: transform 0.3s ease-in-out;
    }
    .member .name {
        margin-top: 10px;
        font-weight: bold;
    }
    .member:hover img {
        transform: scale(1.1);
    }
</style>
</head>
<body>

<div class="container">
    <h2>研究员</h2>
    <div class="member">
        <img src="images\李兵 研究员.jpg" alt="Main Researcher">
        <div class="name">李兵</div>
    </div>
    <h2>幅研究员</h2>
    <div class="member">
        <img src="images\王隽 副研究员.jpg" alt="Min Researcher">
        <div class="name">王隽</div>
    </div>
    <h2>博士研究生</h2>
    <div class="member">
        <img src="images\陈泽文 博士研究生.jpg" alt="Researcher 1">
        <div class="name">陈泽文</div>
    </div>
    <div class="member">
        <img src="images\覃海纳 博士研究生.jpg" alt="Researcher 2">
        <div class="name">覃海纳</div>
    </div>
    <div class="member">
        <img src="images\孙鑫雨 博士研究生.jpg" alt="Researcher 3">
        <div class="name">孙鑫雨</div>
    </div>
    <div class="member">
        <img src="images\冯紫钰 博士研究生.jpg" alt="Researcher 4">
        <div class="name">冯紫钰</div>
    </div>
</div>

</body>
</html>

{% include feature_row id="intro" type="center" %}

{% include feature_row %}
