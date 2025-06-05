<!-- CSS 样式：默认未选中显示灰色，选中时为黑色 -->
<style>
  .publication-header span {
    cursor: pointer;
    color: gray;
  }
  .publication-header span.active {
    color: black;
  }
</style>

<div id="publications">

<!-- 标题区域，使用 h1 实现 Markdown 的 # 标题效果 -->

<h1 class="publication-header">
  <span id="selectedHeader" class="active" onclick="filterPubs('selected')">📖 Selected Publications</span> |
  <span id="fullHeader" onclick="filterPubs('full')">Full</span>
</h1>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Enigmata: Scaling Logical Reasoning in Large Language Models with Synthetic Verifiable Puzzles</font></strong>\\
Jiangjie Chen\*, Qianyu He\*, Siyu Yuan\*, Aili Chen\*, Zhicheng Cai, Weinan Dai, Hongli Yu, Qiying Yu, **Xuefeng Li**, Jiaze Chen, Hao Zhou, Mingxuan Wang \\
**2025, Blog**. <br>
<a href="https://arxiv.org/pdf/2505.19914" style="pdf"><span>Blog</span></a> / 
<a href="https://seed-enigmata.github.io/" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=23em style="vertical-align: middle;"> 
<a href="https://huggingface.co/BytedTsinghua-SIA/Enigmata-Qwen2.5-32B" style="pdf"><span>Resources</span></a> /
<a href="https://github.com/BytedTsinghua-SIA/Enigmata"> \\
</a>
<br>
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">OctoThinker: Revisiting Mid-Training In the Era of RL Scaling</font></strong>\\
Zengzhi Wang\*, Fan Zhou\*, **Xuefeng Li\***, Pengfei Liu \\
**2025, Blog**. <br>
<a href="https://natural-rugby-f7c.notion.site/OctoThinker-Revisiting-Mid-Training-1d20b810e2d680c494a9f9dad0a90d53" style="pdf"><span>Blog</span></a> / 
<a href="https://github.com/GAIR-NLP/OctoThinker" style="code"><span>Code</span></a> / 
<img src="images/huggingface_logo.svg" width=23em style="vertical-align: middle;"> 
<a href="https://huggingface.co/OctoThinker" style="pdf"><span>Resources</span></a> /
<a href="https://github.com/GAIR-NLP/OctoThinker">
<img src="https://img.shields.io/github/stars/GAIR-NLP/OctoThinker?style=social" style="vertical-align: middle;"> \\
</a>
<br>
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Generative AI Act II: Test Time Scaling Drives Cognition Engineering</font></strong>\\
Shijie Xia, Yiwei Qin, **Xuefeng Li**, Yan Ma, Run-Ze Fan, Steffi Chern, Haoyang Zou, Fan Zhou, Xiangkun Hu, Jiahe Jin, Yanheng He, Yixin Ye, Yixiu Liu, Pengfei Liu \\
**2025, Preprint**. <br>
<a href="https://arxiv.org/abs/2504.13828" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/cognition-engineering" style="code"><span>Code</span></a> / 
<a href="https://github.com/GAIR-NLP/cognition-engineering">
<img src="https://img.shields.io/github/stars/GAIR-NLP/cognition-engineering?style=social" style="vertical-align: middle;"> \\
</a>
<br>
<br>
</div>


<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">OlympicArena: Benchmarking Multi-discipline Cognitive Reasoning for Superintelligent AI</font></strong>\\
Zhen Huang, Zengzhi Wang, Shijie Xia, **Xuefeng Li**, Haoyang Zou, Ruijie Xu, Run-Ze Fan, Lyumanshan Ye, Ethan Chern, Yixin Ye, Yikai Zhang, Yuqing Yang, Ting Wu, Binjie Wang, Shichao Sun, Yang Xiao, Yiyuan Li, Fan Zhou, Steffi Chern, Yiwei Qin, Yan Ma, Jiadi Su, Yixiu Liu, Yuxiang Zheng, Shaoting Zhang, Dahua Lin, Yu Qiao, Pengfei Liu \\
**Neurips 2024 (DB track)** <br>
<a href="https://arxiv.org/abs/2406.12753" style="pdf"><span>PDF</span></a> /
<a href="https://github.com/GAIR-NLP/OlympicArena" style="code"><span>Code</span></a> /
<img src="images/huggingface_logo.svg" width=23em style="vertical-align: middle;"> 
<a href="https://huggingface.co/datasets/GAIR/OlympicArena" style="pdf"><span>Datasets</span></a> /
<a href="https://gair-nlp.github.io/OlympicArena/" style="pdf"><span>Project Page</span></a> /
<a href="https://github.com/GAIR-NLP/OlympicArena">
<img src="https://img.shields.io/github/stars/GAIR-NLP/OlympicArena?style=social" style="vertical-align: middle;"> \\
</a>
<span>A challenging multi-modal olympic competition benchmark for LLMs and LVMs.</span> 
<br>
<br>
</div>


</div>

<script>
function filterPubs(filterType) {
  var pubs = document.getElementById('publications').children;
  for (var i = 0; i < pubs.length; i++) {
    var selectedAttr = pubs[i].getAttribute('data-selected');
    if (selectedAttr !== null) { // 只对存在 data-selected 属性的元素进行处理
      if (filterType === 'selected') {
        pubs[i].style.display = (selectedAttr === 'true') ? '' : 'none';
      } else {
        pubs[i].style.display = '';
      }
    }
  }
  // 更新标题 active 样式
  if (filterType === 'selected') {
    document.getElementById('selectedHeader').classList.add('active');
    document.getElementById('fullHeader').classList.remove('active');
  } else {
    document.getElementById('fullHeader').classList.add('active');
    document.getElementById('selectedHeader').classList.remove('active');
  }
}
document.addEventListener('DOMContentLoaded', function() {
  filterPubs('selected');
});
</script>