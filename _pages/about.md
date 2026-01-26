---
permalink: /
title: ""
excerpt: "Robot learning researcher focused on contact-rich manipulation"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a Master Student in the [Helping Hands Lab](https://www2.ccs.neu.edu/research/helpinghands/) at Northeastern University, working with Professor [Robert Platt](https://www2.ccs.neu.edu/research/helpinghands/people/). My research explores data-efficient robot learning and closed-loop control for contact-rich manipulation, with an emphasis on equivariant representations for policy learning.

<p class="contact-links">
  <a href="mailto:zhu.yizhe@northeastern.edu"><i class="far fa-envelope icon-pad-right" aria-hidden="true"></i>Email</a> /
  <a href="https://scholar.google.com/citations?user=MhSyhtwAAAAJ&amp;hl"><i class="fas fa-graduation-cap icon-pad-right" aria-hidden="true"></i>Google Scholar</a> /
  <a href="https://github.com/yizhezhu0925"><i class="fab fa-github icon-pad-right" aria-hidden="true"></i>GitHub</a>
</p>

## Research Interests
- Robot manipulation combining imitation learning and reinforcement learning
- Human-in-the-loop continual learning for robotics
- Mobile Manipulation
- Tactile sensing and closed-loop control for contact-rich tasks

## News
<style>
#news-list {
  margin-bottom: 0;
}
#news-list li:nth-child(n+6) {
  display: none;
}
#news-more {
  cursor: pointer;
  color: #52adc8;
  margin-left: 1.5em;
  margin-top: 0;
  display: inline-block;
}
.contact-links a {
  text-decoration: none;
  margin-right: 0.35em;
}
.contact-links .icon-pad-right {
  margin-right: 0.3em;
}
.project-img-container {
  width: 220px;
  display: flex;
  align-items: center;
  justify-content: center;
  float: right;
  margin-left: 1em;
  margin-bottom: 0.5em;
  background: transparent;
}
.project-img-container img {
  max-width: 100%;
  height: auto;
  display: block;
}
.button-cta {
  appearance: none;
  background-color: #fafbfc;
  border: 1px solid rgba(27, 31, 35, 0.15);
  border-radius: 6px;
  box-shadow: rgba(27, 31, 35, 0.04) 0 1px 0, rgba(255, 255, 255, 0.25) 0 1px 0 inset;
  box-sizing: border-box;
  color: #24292e;
  cursor: pointer;
  display: inline-block;
  font-family: -apple-system, system-ui, "Segoe UI", Helvetica, Arial, sans-serif, "Apple Color Emoji", "Segoe UI Emoji";
  font-size: 16px;
  font-weight: 500;
  line-height: 20px;
  padding: 4px 8px;
  transition: background-color 0.2s cubic-bezier(0.3, 0, 0.5, 1);
  margin-right: 0.3em;
  margin-bottom: 0.4em;
}
.button-cta:hover {
  background-color: #f3f4f6;
  text-decoration: none;
  transition-duration: 0.1s;
}
.button-cta:active {
  background-color: #edeff2;
  box-shadow: rgba(225, 228, 232, 0.2) 0 1px 0 inset;
  transition: none 0s;
}
.button-cta:focus {
  outline: 1px transparent;
}
@media (max-width: 600px) {
  .project-img-container {
    float: none;
    margin-left: auto;
    margin-right: auto;
    margin-bottom: 1em;
    width: 100%;
  }
  .project-img-container img {
    width: 90vw;
    max-width: 320px;
    height: auto;
  }
}
</style>
<script>
document.addEventListener("DOMContentLoaded", function() {
  var showMore = document.getElementById("news-more");
  if (!showMore) return;
  showMore.addEventListener("click", function() {
    var hiddenItems = document.querySelectorAll('#news-list li:nth-child(n+6)');
    hiddenItems.forEach(function(item) {
      item.style.display = 'list-item';
    });
    showMore.style.display = 'none';
  });
});
</script>

<!-- <ul id="news-list">
  <li>07/2025: Released the <em>EquAct</em> preprint on SE(3)-equivariant multi-task transformers for manipulation.</li>
  <li>05/2025: <em>Hierarchical Equivariant Policy via Frame Transfer</em> was accepted to ICML 2025.</li>
  <li>03/2025: Add a recent highlight from your lab or collaboration.</li>
  <li>12/2024: Share a milestone, award, or invited talk here.</li>
  <li>08/2024: Note an internship, visit, or outreach activity.</li>
  <li>05/2024: Include another update to display when “more” is clicked.</li>
</ul>
<a id="news-more" href="javascript:void(0)">more ▾</a>  -->

## Selected Publications
<div class="project-img-container" style="width: 180px;">
  <img src="{{ 'images/equitac.png' | relative_url }}" alt="Residual Rotation Correction using Tactile Equivariance">
</div>
<p>
  <a href="https://arxiv.org/pdf/2511.07381v2" style="text-decoration: none; color: inherit;">
    <strong>Residual Rotation Correction using Tactile Equivariance</strong>
  </a><br />
  <strong>Yizhe Zhu</strong>, Zhang Ye, Boce Hu, Haibo Zhao, Yu Qi, Dian Wang, Robert Platt<br />
  <em>under review, 2025</em><br />
  <button class="button-cta" onclick="window.open('https://yizhezhu0925.github.io/equitac.github.io/','_blank')">Project</button>
  <button class="button-cta" onclick="window.open('https://arxiv.org/pdf/2511.07381v2','_blank')">PDF</button>
</p>
<div style="clear: both;"></div>


<div class="project-img-container" style="width: 180px;">
  <img src="{{ 'images/GSL.png' | relative_url }}" alt="Generalizable Hierarchical Skill Learning">
</div>
<p>
  <a href="https://arxiv.org/pdf/2502.05728" style="text-decoration: none; color: inherit;">
    <strong>Generalizable Hierarchical Skill Learning via Object-Centric Representation</strong>
  </a><br />
   Haibo Zhao, Yu Qi, Boce Hu, <strong>Yizhe Zhu</strong>, Ziyan Chen, Xupeng Zhu, Owen Howell, Haojie Huang, Robin Walters, Dian Wang*, Robert Platt* <br />
  <em>under review</em><br />
  <button class="button-cta" onclick="window.open('https://codemasterzhao.github.io/GSL/','_blank')">Project</button>
  <button class="button-cta" onclick="window.open('https://arxiv.org/pdf/2510.21121','_blank')">PDF</button>
</p>
<div style="clear: both;"></div>


<div class="project-img-container">
  <img src="{{ 'images/Bear.png' | relative_url }}" alt="Hierarchical Equivariant Policy teaser">
</div>
<p>
  <a href="https://arxiv.org/pdf/2510.08759" style="text-decoration: none; color: inherit;">
    <strong>BEAR: Benchmarking and Enhancing Multimodal Language Models for Atomic Embodied Capabilities</strong>
  </a><br />
  Yu Qi, Haibo Zhao, Ziyu Guo, Siyuan Ma, Ziyan Chen, Yaokun Han, Renrui Zhang, Zitiantao Lin, Shiji Xin, Yijian Huang, Kai Cheng, Peiheng Wang, Jiazheng Liu, Jiayi Zhang, <strong>Yizhe Zhu</strong>, Wenqing Wang, Yiran Qin, Xupeng Zhu, Haojie Huang, Lawson L.S. Wong<br />
  <em>under review, 2026</em><br />
  <button class="button-cta" onclick="window.open('https://bear-official66.github.io/','_blank')">Project</button>
  <button class="button-cta" onclick="window.open('https://arxiv.org/pdf/2510.08759','_blank')">PDF</button>
</p>
<div style="clear: both;"></div>

<div class="project-img-container">
  <img src="{{ 'images/equact.png' | relative_url }}" alt="EquAct teaser">
</div>
<p>
  <a href="https://arxiv.org/pdf/2505.21351v1" style="text-decoration: none; color: inherit;">
    <strong>EquAct: An SE(3)-Equivariant Multi-Task Transformer for Open-Loop Robotic Manipulation</strong>
  </a><br />
  Xupeng Zhu,<strong>Yizhe Zhu*</strong>, Yu Qi*, Robin Walters, Robert Platt<br />
  <em>ICLR, 2026</em><br />
  <button class="button-cta" onclick="window.open('https://arxiv.org/pdf/2505.21351v1','_blank')">PDF</button>
</p>
<div style="clear: both;"></div>

<div class="project-img-container">
  <img src="{{ 'images/icml2024.png' | relative_url }}" alt="Hierarchical Equivariant Policy teaser">
</div>
<p>
  <a href="https://arxiv.org/pdf/2502.05728" style="text-decoration: none; color: inherit;">
    <strong>Hierarchical Equivariant Policy via Frame Transfer</strong>
  </a><br />
  Haibo Zhao*, Dian Wang#*, <strong>Yizhe Zhu</strong>, Xupeng Zhu, Owen Howell, Linfeng Zhao, Yaoyao Qian, Robin Walters, Robert Platt<br />
  <em>ICML 2025</em><br />
  <button class="button-cta" onclick="window.open('https://codemasterzhao.github.io/HierEquiPo.github.io/','_blank')">Project</button>
  <button class="button-cta" onclick="window.open('https://arxiv.org/pdf/2502.05728','_blank')">PDF</button>
</p>
<div style="clear: both;"></div>

## Education
- (2024&nbsp;–&nbsp;present) M.S. in Robotics, Northeastern University, MA
- (2020&nbsp;–&nbsp;2024) B.Eng. in Robotics, Xi'an Jiaotong-Liverpool University, China
