
<h1 align="center"> Understand Before You Generate: Self-Guided Training for Autoregressive Image Generation</h1>


<div align="center">
  <a href="https://yuexy.github.io/" target="_blank">Xiaoyu&nbsp;Yue</a><sup>1,2</sup> 
  &ensp; <b>&middot;</b> &ensp;
  <a href="https://github.com/WZDTHU" target="_blank">ZiDong&nbsp;Wang</a><sup>3</sup> 
  &ensp; <b>&middot;</b> &ensp;
  <a href="https://github.com/yuqingwang1029" target="_blank">Yuqinng&nbsp;Wang</a><sup>4</sup> 
  &ensp; <b>&middot;</b> &ensp;
  <a href="https://wenlongzhang0517.github.io" target="_blank">Wenlong&nbsp;Zhang</a><sup>1</sup> 
  &ensp; <b>&middot;</b> &ensp;
  <a href="https://xh-liu.github.io" target="_blank">Xihui&nbsp;Liu</a><sup>4</sup> 
  &ensp; <b>&middot;</b> &ensp;
  <a href="https://wlouyang.github.io" target="_blank">Wanli&nbsp;Ouyang</a><sup>1,3</sup>
  &ensp; <b>&middot;</b> &ensp;
  <a href="http://leibai.site" target="_blank">Lei&nbsp;Bai</a><sup>1</sup> 
  &ensp; <b>&middot;</b> &ensp;
  <a href="https://sites.google.com/view/lupingzhou" target="_blank">Luping&nbsp;Zhou</a><sup>2</sup> </b>
  
  <sup>1</sup> SH AI Lab &emsp; <sup>2</sup>USYD &emsp; <sup>3</sup>CUHK &emsp; <sup>4</sup>HKU <br> 
  <!-- <sup></sup>Correspondance &emsp; <br> -->
</div>
<h3 align="center">
[<a href="">arXiv</a>]&emsp;
[<a href="">Model (Coming Soon)</a>]&emsp;
[<a href="https://github.com/yuexy/ST-AR">Codes (Coming Soon)</a>]&emsp;

</h3>
<br>

<b>Highlights</b> In this work, we present the first systematic investigation into the mechanisms of applying the next-token prediction paradigm to the visual domain. 

- We identify three key properties that hinder the learning of high-level visual semantics: local and conditional dependence, inter-step semantic inconsistency, and spatial invariance deficiency. 
  ![Figure](./assets/three_issues.png)
- We show that these issues can be effectively addressed by introducing self-supervised objectives during training, leading to a novel training framework, **S**elf-guided **T**raining for **A**uto**R**egressive models (ST-AR). 
  ![Figure](./assets/st_ar.png)
- We conduct comprehensive experiments to validate the design of each component of ST-AR. Specifically, ST-AR brings approximately $42\%$ FID improvement for LlamaGen-L and $49\%$ FID improvement for LlamaGen-XL, while maintaining the same sampling strategy.
  ![Figure](./assets/performance.png)

### 🚨 News

- Our ST-AR is accepted by NeurIPS 2025!🍺 


### Setup & Training & Sampling (Coming Soon)
