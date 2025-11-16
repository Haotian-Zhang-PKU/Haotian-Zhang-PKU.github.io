---
layout: page
title: "Haotian Zhang · 张浩天"
---


<!DOCTYPE html>
<html lang="zh-CN">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">

<!-- Google 字体：Merriweather（英） + Noto Serif SC（中） -->
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700&family=Noto+Serif+SC:wght@300;400;700&display=swap" rel="stylesheet">

<title>Haotian Zhang ‧ 张浩天 | Personal Page</title>

<style>
:root{
  --font-main:"Merriweather","Noto Serif SC",serif;
  --clr-primary:#123557;
  --clr-accent:#c0392b;
}
*{box-sizing:border-box;margin:0;padding:0;}
body{
  font-family:var(--font-main);
  color:#263238;
  line-height:1.6;
  padding:1rem;
  max-width:1000px;
  margin:auto;
}
h1,h2,h3{color:var(--clr-primary);margin:1.2rem 0 .6rem;}
h1{font-size:2.2rem;font-weight:700;}
h2{font-size:1.6rem;font-weight:700;border-bottom:2px solid rgba(0,0,0,.06);}
h3{font-size:1.25rem;font-weight:600;}
ul{margin-left:1.5rem;margin-bottom:1rem;}
li+li{margin-top:.25rem;}
a{color:#006c9c;text-decoration:none;}
a:hover{text-decoration:underline;}
section+section{margin-top:2.5rem;}

header{
  display:flex;flex-direction:column;align-items:center;text-align:center;margin-bottom:2rem;
}
@media(min-width:720px){
  header{flex-direction:row;text-align:left;align-items:flex-start;}
  header .info{margin-left:1.6rem;}
}
.avatar{
  width:150px;height:150px;border-radius:50%;object-fit:cover;
  box-shadow:0 4px 12px rgba(0,0,0,.12);flex-shrink:0;
}
.name{font-size:2rem;font-weight:700;transition:opacity .4s;}
.subtitle{color:#546e7a;font-size:1rem;margin:.4rem 0 .8rem;}
.icon-links a{font-size:1.05rem;margin-right:.8rem;}

.awards-year{font-weight:700;margin:.9rem 0 .35rem;}

.fade-in{animation:fadeIn .8s ease-in forwards;opacity:0;}
@keyframes fadeIn{to{opacity:1;}}
</style>
</head>


<body class="fade-in">

<!-- ============== HEADER ============== -->
<header>
  <!-- TODO: 将占位符换成个人头像 -->
  <img class="avatar" src="{{ '/New_photo.jpg' | relative_url }}" alt="avatar">

  <div class="info">
    <div id="name" class="name" data-en="Haotian Zhang" data-zh="张浩天">Haotian Zhang</div>
    <p class="subtitle">Ph.D. Candidate, School of Electronics, Peking University</p>
    <div class="icon-links">
      <a href="https://scholar.google.com/citations?hl=zh-CN&user=Vph0sK0AAAAJ&view_op=list_works&sortby=pubdate" target="_blank">Google Scholar</a>
      <a href="mailto:haotianzhang@stu.pku.edu.cn">Email</a>
    </div>
  </div>
</header>


<!-- ============== ABOUT ============== -->
<section>
<h2>About Me</h2>
<p>I’m now a Ph.D. candidate in the School of Electronics, Peking University, under the supervision of <a href="http://pcni.pku.edu.cn/homepage.html" target="_blank">Prof.&nbsp;Xiang Cheng (IEEE Fellow)</a>. I am a member of the <a href="http://pcni.pku.edu.cn/homepage.html" target="_blank">Pervasive Connectivity and Networked Intelligence (PCNI)</a> group.</p>

<p><strong>Research Interests — Multi-modal Sensing Aided Transceiver Design &amp; Wireless Foundation Model</strong>: exploring how to leverage multi-modal sensing for proactive beamforming, channel estimation, precoding design, and how to construct a generalized wireless foundation model empowered by sensing modalities.</p>
</section>


<!-- ============== EDUCATION ============== -->
<section>
<h2>Education</h2>
<ul>
  <li><strong>2022 .09 – Present</strong>, Ph.D. Candidate, School of Electronics, Peking University, Beijing.</li>
  <li><strong>2018 .09 – 2022 .06</strong>, Undergraduate, School of Information &amp; Communication Engineering, UESTC, Chengdu.</li>
</ul>
</section>


<!-- ============== PUBLICATIONS ============== -->
<section>
<h2>Publications <span style="font-size:.95rem;color:var(--clr-accent)">(Selected)</span></h2>

<h3>SoM &amp; ISAC</h3>
<ul>
  <li><a href="https://ieeexplore.ieee.org/document/10330577" target="_blank">Intelligent Multi-Modal Sensing-Communication Integration: Synesthesia of Machines</a>, X. Cheng, <strong>Haotian Zhang</strong>, et al., IEEE Communications Surveys &amp; Tutorials.</li>
  <li><a href="http://manu46.magtech.com.cn/Jweb_prai/CN/abstract/abstract12648.shtml" target="_blank">机器联觉：通信与多模态感知的智能融合</a>, X. Cheng, <strong>Haotian Zhang</strong>, et al., 模式识别与人工智能.</li>
  <li><a href="https://www.joconline.com.cn/zh/article/doi/10.11959/j.issn.1000-436x.2022137/" target="_blank">车联网通信感知一体化研究：现状与发展趋势</a>, X. Cheng, <strong>Haotian Zhang</strong>, et al., 通信学报.</li>
</ul>

<h3>Transceiver Design</h3>
<ul>
  <li><a href="https://ieeexplore.ieee.org/document/10566572" target="_blank">Integrated Sensing and Communications Toward Proactive Beamforming in mmWave V2I via Multi-Modal Feature Fusion</a>, <strong>Haotian Zhang</strong>, S. Gao, X. Cheng, and L. Yang, IEEE TWC.</li>
  <li><a href="https://ieeexplore.ieee.org/document/10938924/" target="_blank">Synesthesia of Machines-Enhanced Wideband Multi-User CSI Learning with LiDAR Sensing</a>, <strong>Haotian Zhang</strong>, S. Gao, X. Cheng, and L. Yang, IEEE TVT.</li>
  <li><a href="https://ieeexplore.ieee.org/document/11160797" target="_blank">SoM-Aided FDD Precoding with Sensing Heterogeneity: A Vertical Federated Learning Approach</a>, <strong>Haotian Zhang</strong>, S. Gao, W. Wen, and X. Cheng, IEEE ICC 2025.</li>
  <li><a href="https://arxiv.org/abs/2506.07535" target="_blank">SoM-Aided Online FDD Precoding via Heterogenous Multi-Modal Sensing: A Vertical Federated Learning Approach</a>, <strong>Haotian Zhang</strong>, S. Gao, W. Wen, X. Cheng, and L. Yang, under review.</li>
  <li><a href="https://arxiv.org/abs/2511.04015" target="_blank">Tiny-WiFo: A Lightweight Wireless Foundation Model for Channel Prediction via Multi-Component Adaptive Knowledge Distillation</a>, <strong>Haotian Zhang</strong>, S. Gao, and X. Cheng, under review.</li>
  <li><a href="http://manu46.magtech.com.cn/Jweb_prai/CN/abstract/abstract12650.shtml" target="_blank">应用于毫米波车车通信的多模态感知辅助波束预测</a>, W. Wen, <strong>Haotian Zhang</strong>, S. Gao, X. Cheng, and L. Yang, 模式识别与人工智能.</li>
</ul>

<h3>Network Science</h3>
<ul>
  <li><a href="https://ieeexplore.ieee.org/abstract/document/9537594/" target="_blank">LFIC: Identifying Influential Nodes in Complex Networks by Local Fuzzy Information Centrality</a>, <strong>Haotian Zhang</strong>, S. Zhong, et al., IEEE Transactions on Fuzzy Systems.</li>
</ul>
</section>


<!-- ============== HONORS & AWARDS ============== -->
<section>
<h2>Honors &amp; Awards</h2>

<div class="awards-year">2024</div>
<ul>
  <li>National Scholarship (Ph.D. candidates).</li>
  <li>Merit Student Pacesetter.</li>
  <li>Peking University Presidential Scholarship for Ph.D. candidates.</li>
</ul>

<div class="awards-year">2022</div>
<ul>
  <li>Honours Bachelor Degrees of UESTC.</li>
</ul>

<div class="awards-year">2021</div>
<ul>
  <li>The Most Outstanding Students Award of UESTC Nomination.</li>
  <li>WAC Lighting Scholarship.</li>
</ul>

<div class="awards-year">2020</div>
<ul>
  <li>National Scholarship (Undergraduate).</li>
</ul>
</section>


<!-- ============== ACADEMIC SERVICE ============== -->
<section>
<h2>Academic Service</h2>
<h3>Technical Reviewer</h3>
<ul>
  <li>IEEE Transactions on Wireless Communications</li>
  <li>IEEE Transactions on Vehicular Technology</li>
  <li>IEEE Antennas and Wireless Propagation Letters</li>
  <li>IEEE Transactions on Communications</li>
  <li>IEEE Transactions on Intelligent Transportation Systems</li>
  <li>IEEE Communications Magazine</li>
  <li>IEEE Communications Surveys &amp; Tutorials</li>
  <li>IET Communications</li>
  <li>IEEE/CIC International Conference on Communications in China (ICCC)</li>
</ul>
</section>


<!-- ============== CONTACT ============== -->
<section>
<h2>Contact</h2>
<p>Email: <a href="mailto:haotianzhang@stu.pku.edu.cn">haotianzhang@stu.pku.edu.cn</a></p>
</section>


<!-- ============== JS：自动中英文切换名字 ============== -->
<script>
(function(){
  const el=document.getElementById('name');
  const en=el.dataset.en, zh=el.dataset.zh;
  let isZh=false;
  setInterval(()=>{
    isZh=!isZh;
    el.style.opacity=0;
    setTimeout(()=>{el.textContent=isZh?zh:en;el.style.opacity=1;},200);
  },3000);
})();
</script>

</body>
</html>

