---
permalink: /
title: "About Me"
author_profile: true
page_class: about-page
redirect_from: 
  - /about/
  - /about.html
---

I am currently an Assistant Professor (Research) at the Department of Computing at [the Hong Kong Polytechnic University (PolyU)](https://www.polyu.edu.hk/en/), working closely with [Prof. Qing Li](https://www4.comp.polyu.edu.hk/~csqli/). I received my Ph.D. degree in Computer Science and Engineering from [the Hong Kong University of Science and Technology (HKUST)](https://hkust.edu.hk/) in 2023, advised by [Prof. Lei Chen](https://cse.hkust.edu.hk/~leichen/). Prior to that, I received my Bachelor's degree in Computer Science and Technology from the ACM Honor Class at [Huazhong University of Science and Technology (HUST)](https://english.hust.edu.cn/) in 2018, advised by [Prof. Hai Jin](http://english.cs.hust.edu.cn/info/1296/1201.htm). Email and address: [haoyang-comp.li@polyu.edu.hk](mailto:haoyang-comp.li@polyu.edu.hk), PQ810 PolyU.

<div class="research-interests">
  <p>My main research interests include:</p>
  <ul>
    <li>AI Agents and LLMs</li>
    <li>Data Management and Security</li>
    <li>AI for Science</li>
  </ul>
</div>

## News

<div class="news-scroll" markdown="1">

* **Sep 2026:** One paper received the AIRS@ICPP 2026 Best Paper Award.
* **Sep 2026:** Received the BESC 2026 Rising Star Award.
* **Sep 2026:** Six papers accepted at SIGMOD’27, ICDE’27, and NeurIPS’26 (Spotlight).
* **Aug 2026:** Five papers accepted at EMNLP 2026.
* **Aug 2026:** I will serve as an Area Chair for ICLR 2027.
* **Aug 2026:** One paper accepted at CIKM 2026.
* **Jun 2026:** Three papers accepted at VLDB 2026 (Research, Demo, and Tutorial).
* **May 2026:** Two papers accepted at KDD 2026.
* **May 2026:** Co-organizing the AI4Mental Workshop at KDD 2026.

</div>

<script>
(function () {
  function updateNewsFade(news) {
    var hasMoreBelow = news.scrollHeight - news.scrollTop - news.clientHeight > 2;
    news.classList.toggle('news-scroll--more-below', hasMoreBelow);
  }

  function fitNewsToSixItems() {
    var news = document.querySelector('.news-scroll');
    if (!news) return;

    var items = news.querySelectorAll('li');
    if (items.length <= 6) {
      news.style.maxHeight = 'none';
      news.classList.remove('news-scroll--more-below');
      return;
    }

    var newsTop = news.getBoundingClientRect().top;
    var sixthBottom = items[5].getBoundingClientRect().bottom - newsTop + news.scrollTop;
    news.style.maxHeight = Math.ceil(sixthBottom + 2) + 'px';
    updateNewsFade(news);
  }

  var news = document.querySelector('.news-scroll');
  if (news) {
    news.addEventListener('scroll', function () {
      updateNewsFade(news);
    }, { passive: true });
  }

  fitNewsToSixItems();
  window.addEventListener('load', fitNewsToSixItems);
  window.addEventListener('resize', fitNewsToSixItems);
}());
</script>

## Position Opening

If you are interested, please send me your CV and transcripts. Thank you!

* **<span class="opening-label">[MSc Dissertation or Project]</span>** PolyU MSc students seeking a dissertation or project supervisor are welcome. My previous students received 11 A+/A and 4 A-/B+ grades, and some also published papers.
* **<span class="opening-label">[PhD]</span>** Positions starting in September 2026 or later are open, co-supervised by me and our department head, Prof. Qing Li.
* **<span class="opening-label">[MPhil]</span>** Self-funded PhD and MPhil candidates are also welcome.
* **<span class="opening-label">[Intern]</span>** Self-motivated undergraduate and master's students with strong coding skills from PolyU, mainland universities, and elsewhere are welcome. These students will receive priority consideration for future PhD opportunities.

P.S.: I will personally mentor all students, including interns, RAs, and PhD/MPhil candidates. I may also invite experienced PhD graduates to provide additional guidance as needed.

<!-- *
## Selected Preprints  

* **Survey and Experiments on Mental Disorder Detection via Social Media: From Large Language Models and RAG to Agents**    
Zhuohan Ge, Nicole Hu, Yubo Wang, Darian Li, Xinyi Zhu, **Haoyang Li**, Xin Zhang, Mingtao Zhang, Shihao Qi, Yuming Xu, Han Shi, Chen Jason Zhang, Qing Li 

* **LoopServe: An Adaptive Dual-phase LLM inference Acceleration System for Multi-Turn Dialogues**  
 **Haoyang Li**, Zhanchao Xu, Yiming Li, Xuejia Chen, Darian Li, Anxin Tian, Qingfa Xiao, Cheng Deng, Jun Wang, Qing Li, Lei Chen, Mingxuan Yuan

* **Can Graph Foundation Models Replace Graph Neural Networks? An Experimental Study with Theoretical Analysis**   
 **Haoyang Li**, Mingtao Zhang, Xinyi Zhu, Yuming Xu, Yiming Li, Wei Dong, Alexander Zhou, Yubo Wang, Yongqi Zhang, Chen Jason Zhang, Lei Chen, Qing Li


* **PLM: Efficient Peripheral Language Models Hardware-Co-Designed for Ubiquitous Computing**    
Cheng Deng, Luoyang Sun, Jiwen Jiang, Yongcheng Zeng, Xinjian Wu, Wenxin Zhao, Qingfa Xiao, Jiachuan Wang, **Haoyang Li**, Lei Chen, Lionel M. Ni, Haifeng Zhang, Jun Wang

* **Activation-aware Probe-Query: Effective Key-Value Retrieval for Long-Context LLMs Inference**   
 Qingfa Xiao, Jiachuan Wang, **Haoyang Li**, Cheng Deng, Jiaqi Tang, Shuangyin Li, Yongqi Zhang, Jun Wang, Lei Chen.

* **Learning Towards Emergence: Paving the Way to Induce Emergence by Inhibiting Monosemantic Neurons on Pre-trained Models**    
Jiachuan Wang, Shimin Di, Tianhao Tang, **Haoyang Li**, Charles Wang-wai Ng, Xiaofang Zhou, Lei Chen

* **Towards A Generalizable and Expressive Graph Neural Network for Graph-Level Tasks with Theoretical Guarantees**   
**Haoyang Li**, Yuming Xu, Chen Jason Zhang, Alexander Zhou, Lei Chen, Qing Li.

* **Revisiting Graph Neural Networks on Graph-level Tasks: Comprehensive Experiments and Analysis**   
**Haoyang Li**, Yuming Xu, Chen Jason Zhang, Alexander Zhou, Lei Chen, Qing Li.

* **GraphKnow: An Efficient and Effective Graph Foundation Model for Diverse Graph Tasks**

-->
