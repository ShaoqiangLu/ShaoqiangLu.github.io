---
permalink: /
title: ""
excerpt: ""
author_profile: true
last_modified_at: 2025-12-04
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 用来把锚点往上提一点，让实际标题离顶部有空隙 */
  .anchor-offset {
    display: block;
    position: relative;
    top: -50px;   /* 想要空隙大一点就改成 -100、-120 */
    visibility: hidden;
  }
</style>




{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}


<!--<h2 id="homepage" class="section-title">🏠 Homepage</h2>-->

<div class="page-meta" style="font-size:0.9rem;color:#777;margin-bottom:0.5rem;text-align:right;">
  Last updated:
  {{ page.last_modified_at | default: page.date | date: "%Y-%m-%d" }}
  · Page views:
  <span id="busuanzi_value_page_pv">loading...</span>
</div>


<hr style="border: 2px solid #cccccc; margin: 12px 0;">
<h2 id="about-me" class="section-title"
    style="margin: 4px 0; font-weight: bold;">
  😄 About Me
</h2>
<hr style="border: 2px solid #cccccc; margin: 7px 0;">

I have been a Ph.D. candidate at the School of Integrated Circuits, Shanghai Jiao Tong University (SJTU), since September 2022, under the supervision of [Prof. Lei He (IEEE Fellow)](https://scholar.google.com/citations?user=n_N-PJkAAAAJ&hl=en). I am also a research intern at the Eastern Institute of Technology (EIT), Ningbo. Prior to that, I obtained my M.S. degree from Xidian University, supervised by <u>Prof. Kang Li</u>.

<!--
https://faculty.xidian.edu.cn/LK4/zh_CN/index/348597/list/index.htm
-->


<script async src="//busuanzi.ibruce.info/busuanzi/2.3/busuanzi.pure.mini.js"></script>

<div style="margin-top: 10px;">
  <a href="https://github.com/ShaoqiangLu"
     target="_blank"
     style="background-color: #333333; color: white; padding: 5px 10px; border-radius: 4px; font-size: 14px; text-decoration: none; display: inline-block;">
    📄 Download CV
  </a>
</div>





<div style="display: flex; justify-content: space-between; margin-top: 20px;">
  <div style="flex: 1; margin-right: 1px;">
    <h2>🎯 Research Interests</h2>
    <ul>
      <li>Digital IC Design for AI Chips</li>
      <li>Hardware/Software Co-Optimization</li>
      <li>AI Compiler Development</li>
      <li>FPGA-Based Accelerator</li>
      <li>AI Models:Llama,dLLM,Mamba,VLA</li>
    </ul>
  </div>

  <div style="flex: 1; margin-left: 1px;">
    <h2>🎓 Education</h2>
    <ul>
      <li>
        <strong>Shanghai Jiao Tong University</strong> (2022.09 – 2026.06)<br>
        <em>Ph.D. in Integrated Circuits Engineering</em>
      </li>
      <li>
        <strong>Xidian University</strong> (2019.09 – 2022.06)<br>
        <em>Master’s in Integrated Circuit Design</em>
      </li>
      <li>
        <strong>Xidian University</strong> (2015.09 – 2019.06)<br>
        <em>Bachelor’s in Integrated Circuit Design and Systems</em>
      </li>
    </ul>
  </div>
</div>



<span id="awards" class="anchor-offset"></span>
<hr style="border: 2px solid #cccccc; margin: 4px 0;">
<h2>
  🏆 Awards
</h2>
<hr style="border: 2px solid #cccccc; margin: 6px 0;">
- *2025.11*: &nbsp;🏅 1st Prize, the Build Your Dreams (BYD) Scholarship, Shanghai Jiao Tong University — Rank 3/160, <!--¥20000 RMB https://icisee.sjtu.edu.cn/xsgz-gzzd-xssw/2896.html--> 
- *2021.12*: &nbsp;🥉 3rd Prize, the [4th "Huawei Cup" China Graduate Chip Innovation Competition](https://mp.weixin.qq.com/s/QNniK5mCp-8QDefy76pcvw?click_id=3), Special Second Prize GalaxyCore Technology Co., Ltd — Rank 50/499, <!--¥5000 RMB-->
- *2021.7*: &nbsp;🏅 3rd Prize, the [5th National College Student Integrated Circuit Innovation and Entrepreneurship Competition](https://mp.weixin.qq.com/s/YmRTIPAixgHDdzAKwW1xrA)— Northwest Region, Rank 57/180
- *2020.10*: &nbsp;🥈 2nd Prize, the [3rd "Huawei Cup" China Graduate Chip Innovation Competition](https://mp.weixin.qq.com/s/AwZsIw1SNVQMaqknOuSJHg?click_id=2), Special First Prize S2C Technology Co., Ltd — Rank 24/453, <!--¥18000 RMB-->
- *2020.9*: &nbsp;🏅 1st Prize (twice), 2nd Prize (once), Study Excellence Scholarship for Master’s Degree Candidates, Xidian University — Rank 4/188, <!--¥8000 RMB https://sme.xidian.edu.cn/html/tzgg/jx/2021/1125/1673.html-->
<!-- - *2019.7*: &nbsp;🎖️ Excellent Graduate Student Cadre Honor (thrice) and Outstanding Student Class Monitor (twice), Xidian University-->
<!--https://mp.weixin.qq.com/s/WkrwyTyQpA5vGbMlmOAL_Q-->


<span id="publications" class="anchor-offset"></span>
<hr style="border: 2px solid #cccccc; margin: 4px 0;">
<h2>
  📚 Publications
</h2>
<hr style="border: 2px solid #cccccc; margin: 6px 0;">
- [1] <span style="background-color: magenta; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-A </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ASPLOS 2026</span> DFVG: A Heterogeneous Architecture for Speculative Decoding with Draft-on-FPGA and Verify-on-GPU. **<u>Shaoqiang Lu<sup style="color: black;">*</sup></u>**, Yangbo Wei<sup style="color: black;">*</sup>, Junhong Qian, Dongge Qin, Shiji Gao, Yizhi Ding, Qifan Wang, Chen Wu, Xiao Shi, Lei He.

<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  
  <a href="javascript:void(0);" style="pointer-events: none; text-decoration: none;">
    <button style="border: 1px solid #ccc; color: #999; background-color: #f5f5f5; padding: 2px 6px; border-radius: 4px; cursor: not-allowed; font-size: 12px;">
      PDF
    </button>
  </a>
  <!--
  
  <a href="_pages/paper/DATE2025.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
    <a href="https://youtu.be/6DrQbjT2kXI" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>-->
</div>



- [2]  <span style="background-color: magenta; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-A </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">DAC 2025</span> MambaOPU: An FPGA Overlay Processor for State-space-duality-based Mamba Models. **<u>Shaoqiang Lu<sup style="color: black;">*</sup></u>**, Xuliang Yu<sup style="color: black;">*</sup>, Tiandong Zhao, Siyuan Miao, Xinsong Sheng, Chen Wu, Liang Zhao, Ting-Jung Lin, Lei He.

<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  
  <a href="https://ieeexplore.ieee.org/document/11132895" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/ICCAD2024.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  -->
</div>




- [3]  <span style="background-color: darkorange; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-B </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ICCAD 2025</span> MoE-OPU: An FPGA Overlay Processor Leveraging Expert Parallelism for MoE-based Large Language Models. **<u>Shaoqiang Lu<sup style="color: black;">*</sup></u>**, Yangbo Wei<sup style="color: black;">*</sup>, Junhong Qian, Chen Wu, Xiao Shi, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/11240807" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  
  <a href="_pages/paper/ASP-DAC2024.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  -->
</div>

- [4]  <span style="background-color: darkorange; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-B </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">TRETS Journal 2025,ISEDA 2024</span> MCoreOPU: An FPGA-based Multi-Core Overlay Processor for Transformer-based Models. **<u>Shaoqiang Lu<sup style="color: black;">*</sup></u>**, Tiandong Zhao<sup style="color: black;">*</sup>, Ting-Jung Lin, Rumin Zhang, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://dl.acm.org/doi/10.1145/3742437" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/ICCAD2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/EQ50eG3W36Y" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>

- [5]  <span style="background-color: darkorange; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-B </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ICCAD 2024</span> ChatOPU: An FPGA-based Overlay Processor for Large Language Models with Unstructured Sparsity. Tiandong Zhao, **<u>Shaoqiang Lu</u>**, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://dl.acm.org/doi/10.1145/3676536.3676761" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [6]  <span style="background-color: green; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-C </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ASAP 2025</span> <span style="color:red;">(Best Paper Nomination)</span>METAL: A Memory-Efficient Transformer Architecture for Long-Context Inference on FPGA. Zicheng He, **<u>Shaoqiang Lu</u>**, Tiandong Zhao, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/11113558" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2024.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/ZJqte7cuPhk" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [7]  <span style="background-color: green; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-C </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">ASP-DAC 2026</span> dLLM-OPU: An FPGA Overlay Processor for Accelerated Diffusion Large Language Models. Yangbo Wei<sup style="color: black;">*</sup>, **<u>Shaoqiang Lu<sup style="color: black;">*</sup></u>**, Junhong Qian, Chen Wu, Xiao Shi, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="javascript:void(0);" style="pointer-events: none; text-decoration: none;">
    <button style="border: 1px solid #ccc; color: #999; background-color: #f5f5f5; padding: 2px 6px; border-radius: 4px; cursor: not-allowed; font-size: 12px;">
      PDF
    </button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>



- [8]  <span style="background-color: green; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-C </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">FPT 2026</span> FlightOPU: An FPGA Overlay Processor for LLM with HBM-Aware Multi-Die Architecture. Chen Wu, **<u>Shaoqiang Lu</u>**, Yangbo Wei, Junhong Qian, Jinlong Yan, Zhanfei Chen, Rumin Zhang, Xiao Shi, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="javascript:void(0);" style="pointer-events: none; text-decoration: none;">
    <button style="border: 1px solid #ccc; color: #999; background-color: #f5f5f5; padding: 2px 6px; border-radius: 4px; cursor: not-allowed; font-size: 12px;">
      PDF
    </button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [9]  <span style="background-color: magenta; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-A </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">AAAI 2026</span> Mixture-of-Trees: Learning to Select and Weigh Reasoning Paths for Efficient LLM Inference. Yangbo Wei, Zhen huang, **<u>Shaoqiang Lu</u>**, Junhong Qian, Dongge Qin, Ting Jung Lin, Wei Xing, Chen Wu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="javascript:void(0);" style="pointer-events: none; text-decoration: none;">
    <button style="border: 1px solid #ccc; color: #999; background-color: #f5f5f5; padding: 2px 6px; border-radius: 4px; cursor: not-allowed; font-size: 12px;">
      PDF
    </button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [10]  <span style="background-color: green; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-C </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">FPL 2023</span> Token Packing for Transformers with Variable-Length Inputs. Tiandong Zhao, Siyuan Miao, **<u>Shaoqiang Lu</u>**, Jialin Cao, Jun Qiu, Xiao Shi, Kun Wang, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/10296372" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>


- [11]  <span style="background-color: green; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-C </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">FCCM 2025</span> C2OPU: Hybrid Compute-in-Memory and Coarse-Grained Reconfigurable Architecture for Overlay Processing of Transformers. Siyuan Miao, Lingkang Zhu, Chen Wu, **<u>Shaoqiang Lu</u>**, Jinming Lyu, Lei He.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://ieeexplore.ieee.org/document/11008948" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>



- [12]  <span style="background-color: magenta; color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold; margin-right: 4px;"> CCF-A </span> <span style="background-color:rgb(0, 96, 193); color: #ffffff; padding: 1px 6px; border-radius: 3px; font-weight: bold;">Science China: Information Sciences 2025</span> FPGA Overlay processor for AI computing. He Lei, Wang Kun, Wu Chen, Tao Zhuofu, Shi Xiao, Miao Siyuan, **<u>Shaoqiang Lu</u>**.
<div style="margin-top: -15px; margin-bottom: 10px; margin-left: 30px;">
  <a href="https://www.sciengine.com/SSI/doi/10.1360/SSI-2024-0351" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">PDF</button>
  </a>
  <!--
  <a href="_pages/paper/DAC2023.bib" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Cite</button>
  </a>
  <a href="https://youtu.be/58vpAHg66Lc" style="text-decoration: none;">
    <button style="border: 1px solid #007BFF; color: #007BFF; background-color: white; padding: 2px 6px; border-radius: 4px; cursor: pointer; font-size: 12px;"
      onmouseover="this.style.backgroundColor='#007BFF'; this.style.color='white';"
      onmouseout="this.style.backgroundColor='white'; this.style.color='#007BFF';">Video</button>
  </a>
  -->
</div>

<span id="projects" class="anchor-offset"></span>
<hr style="border: 2px solid #cccccc; margin: 4px 0;">
<h2>
  🧰 Projects
</h2>
<hr style="border: 2px solid #cccccc; margin: 6px 0;">

## Project 1: An FPGA-based Overlay Processor Unit for Accelerating AI Models  
<hr style="border: 1px solid #cccccc; margin: 4px 0;">

**Description**  
- Designed an FPGA-based Overlay Processor Unit (OPU) to accelerate inference of diverse AI deep learning models. Optimized data flow and operator execution through hardware–software co-design. Successfully deployed in real-time edge scenarios.

**Responsibilities**  
- Designed the OPU including the instruction set, compiler, and hardware microarchitecture.  
- Built a scalable computing engine for parallel execution of key operations (e.g., convolution, matrix multiplication).  
- Developed specialized functional units for nonlinear operations.  
- Implemented a real-time hardware–software runtime, covering CPU-side model compilation to FPGA inference.  
- Enabled PCIe-based transfer of weights and control instructions.  
- Designed for scalability across various sizes and types of neural networks.  


**Experimental Setup**

- Xilinx Alveo U200 @ 300 MHz (PE 600 MHz)  
- Implementation 4-Core OPU + 64 GB DDR4
- Quantization Models run INT8 bitsandbytes.

**Evaluation**

- Resources Usage (left)   vs.   Model Results (right) <sub>\* We report the first token latency.</sub>

| Resource | **LUT** | **FF** | **BRAM** | **DSP** | | Model | **BERT** | **ViT** | **GPT2** | **LLaMA7B** | 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---| 
| **Used** | 947684 | 1806396 | 1004 | 4364 | | **Latency\*** (ms) | 3.41 | 6.96 | 59.49 | 149.57 | 
| **Util(%)** | 80.1% | 76.3% | 46.5% | 63.8% | | **Throughput** (TOP/s) | 6.08 | 4.66 | 7.42 | 7.99 |





**Tools**  
- Vivado , FPGA (U200) , Verilog , ModelSim , PCIe , DDR , XDMA , C++ , Python , PyTorch

![Mcore](https://raw.githubusercontent.com/ShaoqiangLu/ShaoqiangLu/de8b4fd16601343d67a56b56c8d787636949b653/fig/McoreOPU.png)

<style>
  video {
    width: 100%;
    height: auto;
    display: block;
  }
</style>
<h2>Demo</h2>
<video controls>
  <source src="https://github.com/user-attachments/assets/c6a6ce16-cf15-428c-b061-8f4f8d9d881d" type="video/mp4">
  Your browser does not support the video tag.
</video>



<hr style="border: 1px solid #cccccc; margin: 4px 0;">
## Project 2：A Edge SoC with co-Accelerator in ARM Cortex-M3 for Face Detection  
<hr style="border: 1px solid #cccccc; margin: 4px 0;">

**Description**  
- Developed an Edge System-on-Chip (SoC) integrating an ARM Cortex-M3 processor with a dedicated hardware co-accelerator to enable real-time face detection. Deploy a decision-tree–based PICO (Pixel-Intensity Comparison-based Object Detection) model. 

**Responsibilities**  
- Built a complete image acquisition, storage, and display pipeline with Bus peripheral access in software.  
- Implemented the face detection algorithm on Cortex-M3 for standalone execution.  
- Designed and integrated a dedicated hardware accelerator to boost detection performance.  
- Ran on a 100 MHz AX7103 FPGA with OV5640 (3-million-pixel) for image capture.
- Data is stored in DDR3, HDMI for real-time display, and UART for status communication.  


**Experimental Setup & Results**

- Camera: OV5640, RGB565, 5 MP ; Display: HBMI, RGB888, 640×480 @ 60 Hz ; Memory: DDR3 ×2 (8 Gb each).  

| Resource | Used | Utilization | | SMIC55 | Report | | Platform | Implement | Latency | 
|:---|:---|:---|:---|:---|:---|:---|:---|:---|:---| 
| LUT | 36583| 57.70% | | ASIC Area | 61801 μm² | | CPU | OpenCV | 33 ms | 
| FF | 36130| 28.50% | | PT Power | 361.5 μW | | FPGA | RTL | 42 ms | 
| BRAM| 101 | 75.00% | | NAND2 area | 1.12 μm²/gate | | Cortex-M3 | C | 2,700 ms | 
| DSP | 27 | 11.00% | | Gates/MOScount | 55180/ ≈220k | | Speedup |Cortex/FPGA| ≈ 60x |






**Evaluation**  
- Achieved **41 ms/face** processing time with hardware acceleration, compared to **2700 ms/face** on pure Cortex-M3.  
- Delivered a **65.81×** performance speedup over the baseline software-only implementation.  

**Tools & Technologies**  
- C (embedded Cortex-M3) , AHB/APB/AXI , Keil MDK , AX7103 , OV5640 , HDMI
 
![ARMSoC](https://raw.githubusercontent.com/ShaoqiangLu/ShaoqiangLu/main/fig/ARMSoC.png)  

<style>
  video {
    width: 100%;
    height: auto;
    display: block;
  }
</style>
<h2>Demo</h2>
<video controls>
  <source src="https://github.com/user-attachments/assets/b270133d-72e5-4ff1-bed0-6e5772e15872" type="video/mp4">
  Your browser does not support the video tag.
</video>

<hr style="border: 1px solid #cccccc; margin: 4px 0;">
## Project 3：Digital IC Frontend Design and Implementation of a PE Array  
<hr style="border: 1px solid #cccccc; margin: 4px 0;">

**Description**  
- Designed a Processing Element (PE) array to accelerate irregular sparse AI workloads. Implemented the digital IC frontend design flow and compared resource utilization between ASIC and FPGA implementations.

**Responsibilities**  
- Designed sparse computing architecture for the PE array, including triangular-fed data flow, PE unit logic, and weight bitmask decoding.  
- Verified functionality via simulation before setting timing constraints.  
- Completed both FPGA and ASIC flows, eliminating timing violations through iterative analysis.  
- Integrated the PE array into a complete accelerator system.  
- Analyzed synthesis and power reports to guide RTL refinement for improved performance.  

**Evaluation**  
- Logic synthesis using Synopsys Design Compiler (DC) at TSMC 28nm process node.  
- Power analysis via PrimeTime (PT), achieving:  
  - **1 GHz** operating frequency  
  - **1.06 mm²** core area  
  - **1.32 W** power consumption  
- Balanced performance, area, and power through RTL optimizations.  

**Tools & Technologies**  
- Verilog , Synopsys Design Compiler (DC) , PrimeTime (PT) , VCS , TSMC 28nm , SDC , Shell , Tcl

![PEarray](https://raw.githubusercontent.com/ShaoqiangLu/ShaoqiangLu/de8b4fd16601343d67a56b56c8d787636949b653/fig/PEarray.png)  

<hr style="border: 1px solid #cccccc; margin: 4px 0;">
## Project 4：Expert-Aware Quantization and Sparsity for MoE- based Models  
<hr style="border: 1px solid #cccccc; margin: 4px 0;">

**Description**  
- Designed and implemented expert-aware quantization and sparsity optimization techniques for Mixture-of-Experts (MoE) models to reduce memory footprint.

**Responsibilities**  
- Introduced N:M sparsity patterns (1:4 / 2:4 / 4:8 / 6:8 / 8:8) in MLP layers.  
- Applied mixed-precision quantization (BF16 / FP8 / INT4) guided by expert activation frequency, covering both expert and shared layers.  
- Integrated sparsity and quantization pipelines into the training workflow of the DeepSeek-V2-Lite model on the GSM8K dataset.  

**Evaluation**  
- Reduced parameter size by up to **2.76×** while maintaining accuracy.  
- Only **1.53%** average accuracy drop after fine-tuning.  
- Achieved **2–3×** speedup and **40–60%** memory savings.  

**Tools & Technologies**  
- PyTorch , DeepSeek-V2-Lite , GSM8K dataset , CUDA , NVIDIA A100 , NVIDIA RTX 4090 , Python
 
![MoE](https://raw.githubusercontent.com/ShaoqiangLu/ShaoqiangLu/de8b4fd16601343d67a56b56c8d787636949b653/fig/MoE.png)  

---



