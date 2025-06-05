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

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Enigmata: Scaling Logical Reasoning in Large Language Models with Synthetic Verifiable Puzzles</font></strong>\\
Jiangjie Chen\*, Qianyu He\*, Siyu Yuan\*, Aili Chen\*, Zhicheng Cai, Weinan Dai, Hongli Yu, Qiying Yu, **Xuefeng Li**, Jiaze Chen, Hao Zhou, Mingxuan Wang \\
**2025, Blog**. <br>
<a href="https://arxiv.org/pdf/2505.19914" style="pdf"><span>Blog</span></a> / 
<a href="https://seed-enigmata.github.io/" style="code"><span>Code</span></a> / 
<a href="https://huggingface.co/BytedTsinghua-SIA/Enigmata-Qwen2.5-32B" style="pdf"><span>Resources</span></a> /
<a href="https://github.com/BytedTsinghua-SIA/Enigmata"> \\
<br>
</div>


<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">OctoThinker: Revisiting Mid-Training In the Era of RL Scaling</font></strong>\\
Zengzhi Wang\*, Fan Zhou\*, **Xuefeng Li\***, Pengfei Liu \\
**2025, Blog**. <br>
<a href="https://natural-rugby-f7c.notion.site/OctoThinker-Revisiting-Mid-Training-1d20b810e2d680c494a9f9dad0a90d53" style="pdf"><span>Blog</span></a> / 
<a href="https://github.com/GAIR-NLP/OctoThinker" style="code"><span>Code</span></a> / 
<a href="https://huggingface.co/OctoThinker" style="pdf"><span>Resources</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Generative AI Act II: Test Time Scaling Drives Cognition Engineering</font></strong>\\
Shijie Xia, Yiwei Qin, **Xuefeng Li**, Yan Ma, Run-Ze Fan, Steffi Chern, Haoyang Zou, Fan Zhou, Xiangkun Hu, Jiahe Jin, Yanheng He, Yixin Ye, Yixiu Liu, Pengfei Liu \\
**2025, Preprint**. <br>
<a href="https://arxiv.org/abs/2504.13828" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/cognition-engineering" style="code"><span>Code</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Torl: Scaling tool-integrated rl</font></strong>\\
**Xuefeng Li\***, Haoyang Zou\*, Pengfei Liu \\
**2025, Preprint**. <br>
<a href="https://arxiv.org/pdf/2503.23383" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/ToRL" style="code"><span>Code</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Limr: Less is more for rl scaling</font></strong>\\
**Xuefeng Li\***, Haoyang Zou\*, Pengfei Liu \\
**2025, Preprint**. <br>
<a href="https://arxiv.org/pdf/2502.11886" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/LIMR" style="code"><span>Code</span></a> \\
<br>
</div>


<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">O1 Replication Journey -- Part 2: Surpassing O1-preview through Simple Distillation, Big Progress or Bitter Lesson?</font></strong>\\
Zhen Huang\*, Haoyang Zou\*, **Xuefeng Li\***, Yixiu Liu\*, Yuxiang Zheng\*, Ethan Chern\*, Shijie Xia\*, Yiwei Qin, Weizhe Yuan, Pengfei Liu  \\
**2025, Preprint**. <br>
<a href="https://arxiv.org/pdf/2502.11886" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/LIMR" style="code"><span>Code</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">O1 Replication Journey: A Strategic Progress Report--Part 1</font></strong>\\
Yiwei Qin\*, **Xuefeng Li\***, Haoyang Zou\*, Yixiu Liu\*, Shijie Xia\*, Zhen Huang, Yixin Ye, Weizhe Yuan, Hector Liu, Yuanzhi Li, Pengfei Liu \\
**2025, Preprint**. <br>
<a href="https://arxiv.org/abs/2410.18982" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/O1-Journey" style="code"><span>Code</span></a> \\
<br>
</div>




<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Synthesizing Verified Mathematical Problems</font></strong>\\
**Xuefeng Li\***, Yanheng He\*, Pengfei Liu \\
**NeurIPS2024 MATHAI Workshop**. <br>
<a href="https://openreview.net/pdf?id=L5US093OwO" style="pdf"><span>PDF</span></a>  \\
<br>
</div>


<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">OpenResearcher: Unleashing AI for Accelerated Scientific Research</font></strong>\\
Yuxiang Zheng, Shichao Sun, Lin Qiu, Dongyu Ru, Cheng Jiayang, **Xuefeng Li**, Jifan Lin, Binjie Wang, Yun Luo, Renjie Pan, Yang Xu, Qingkai Min, Zizhao Zhang, Yiwen Wang, Wenjie Li, Pengfei Liu \\
**EMNLP2024**. <br>
<a href="https://arxiv.org/pdf/2502.11886" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/LIMR" style="code"><span>Code</span></a> \\
<br>
</div>


<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Progress or regress? self-improvement reversal in post-training</font></strong>\\
Ting Wu, **Xuefeng Li**, Pengfei Liu \\
**ICLR 2025**. <br>
<a href="https://arxiv.org/pdf/2407.05013" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/self-improvement-reversal" style="code"><span>Code</span></a> \\
<br>
</div>


<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">OlympicArena: Benchmarking Multi-discipline Cognitive Reasoning for Superintelligent AI</font></strong>\\
Zhen Huang, Zengzhi Wang, Shijie Xia, **Xuefeng Li**, Haoyang Zou, Ruijie Xu, Run-Ze Fan, Lyumanshan Ye, Ethan Chern, Yixin Ye, Yikai Zhang, Yuqing Yang, Ting Wu, Binjie Wang, Shichao Sun, Yang Xiao, Yiyuan Li, Fan Zhou, Steffi Chern, Yiwei Qin, Yan Ma, Jiadi Su, Yixiu Liu, Yuxiang Zheng, Shaoting Zhang, Dahua Lin, Yu Qiao, Pengfei Liu \\
**Neurips2024** <br>
<a href="https://arxiv.org/abs/2406.12753" style="pdf"><span>PDF</span></a> /
<a href="https://github.com/GAIR-NLP/OlympicArena" style="code"><span>Code</span></a> /
<a href="https://huggingface.co/datasets/GAIR/OlympicArena" style="pdf"><span>Datasets</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Reformatted alignment</font></strong>\\
Run-Ze Fan, **Xuefeng Li**, Haoyang Zou, Junlong Li, Shwai He, Ethan Chern, Jiewen Hu, Pengfei Liu \\
**EMNLP2024 Findings**. <br>
<a href="https://arxiv.org/pdf/2402.12219" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/ReAlign" style="code"><span>Code</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Evaluating mathematical reasoning beyond accuracy</font></strong>\\
Shijie Xia, **Xuefeng Li**, Yixin Liu, Tongshuang Wu, Pengfei Liu \\
**AAAI2025**. <br>
<a href="https://arxiv.org/pdf/2404.05692" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/ReasonEval" style="code"><span>Code</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="false" markdown="1">
<strong><font color="#374798">Mathpile: A billion-token-scale pretraining corpus for math</font></strong>\\
Zengzhi Wang, **Xuefeng Li**, Rui Xia, Pengfei Liu \\
**NeurIPS2024**. <br>
<a href="https://arxiv.org/pdf/2312.17120" style="pdf"><span>PDF</span></a> / 
<a href="https://github.com/GAIR-NLP/MathPile" style="code"><span>Code</span></a> \\
<br>
</div>

<div class="paper-box-text" data-selected="true" markdown="1">
<strong><font color="#374798">Generative ai for math: Abel</font></strong>\\
Ethan Chern, Haoyang Zou, **Xuefeng Li**, Jiewen Hu, Kehua Feng, Junlong Li, Pengfei \\
**2024, Github**. <br>
<a href="https://github.com/GAIR-NLP/Abel" style="code"><span>Code</span></a> \\
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