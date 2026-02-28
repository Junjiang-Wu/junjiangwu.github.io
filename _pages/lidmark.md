---
permalink: /projects/lidmark/
title: ""
author_profile: false
sidebar: false
toc: false
layout: single
---

<script>
  MathJax = {
    tex: {
      inlineMath: [['$', '$'], ['\\(', '\\)']],
      displayMath: [['$$', '$$'], ['\\[', '\\]']]
    }
  };
</script>
<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-chtml.js"></script>

<style>
  body, p, h1, h2, h3, h4, h5, h6, div, span, a, strong, em, button {
    font-family: "Times New Roman", Times, serif !important;
  }

  .project-title { font-size: 2.2em; font-weight: bold; text-align: center; margin: 30px 0 25px; color: #2c3e50; line-height: 1.4;}
  .conference-tag-inline { font-size: 0.6em; font-weight: bold; display: inline-block; margin-top: 10px; }

  .author-list { text-align: center; font-size: 1.1em; margin-bottom: 10px; }
  .institution-list { text-align: center; font-size: 0.95em; color: #7f8c8d; margin-bottom: 30px; line-height: 1.5;}
  .btn-container { display: flex; justify-content: center; gap: 20px; margin-bottom: 40px; flex-wrap: wrap; }
  
  .action-btn {
    position: relative;
    display: flex; align-items: center; padding: 10px 24px; border-radius: 30px;
    background-color: #2c3e50; color: #ffffff !important; text-decoration: none;
    font-size: 15px; font-weight: bold; box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    overflow: hidden;
    z-index: 1;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .action-btn::before {
    content: '';
    position: absolute;
    top: 0; left: 0; height: 100%; width: 0;
    background: linear-gradient(to right, #3498db, #9b59b6);
    z-index: -1;
    transition: width 0.4s ease-in-out;
  }
  .action-btn:hover {
    transform: translateY(-2px); box-shadow: 0 6px 12px rgba(0,0,0,0.2);
  }
  .action-btn:hover::before {
    width: 100%;
  }
  .action-btn svg, .action-btn span {
    position: relative; z-index: 2;
  }
  .action-btn svg { margin-right: 8px; width: 1.2em; height: 1.2em; fill: currentColor; }

  .hover-gradient-link {
    position: relative;
    text-decoration: none !important;
    color: #3498db !important; 
    display: inline-block;
  }
  .hover-gradient-link strong { color: #3498db !important; }
  .hover-gradient-link::after {
    content: ''; position: absolute; width: 0; height: 2px; bottom: -2px; left: 0;
    background: linear-gradient(to right, #3498db, #9b59b6);
    transition: width 0.3s ease-in-out;
  }
  .hover-gradient-link:hover::after { width: 100%; }

  /* Carousel Styles */
  .carousel-wrapper { position: relative; max-width: 800px; margin: 0 auto 40px auto; }
  .carousel-container { overflow: hidden; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1); position: relative; }
  .carousel-track { display: flex; transition: transform 0.4s ease-in-out; }
  .carousel-slide { min-width: 100%; box-sizing: border-box; }
  .carousel-slide img { width: 100%; display: block; }
  
  .carousel-btn {
    position: absolute; top: 50%; transform: translateY(-50%);
    background-color: rgba(255, 255, 255, 0.8); border: none;
    color: #333; font-size: 24px; cursor: pointer;
    padding: 10px 15px; border-radius: 50%; z-index: 10;
    box-shadow: 0 2px 4px rgba(0,0,0,0.2); transition: background-color 0.3s;
  }
  .carousel-btn:hover { background-color: rgba(255, 255, 255, 1); }
  .prev-btn { left: -25px; } 
  .next-btn { right: -25px; }
  
  @media (max-width: 850px) {
    .prev-btn { left: 10px; }
    .next-btn { right: 10px; }
  }

  .carousel-dots { text-align: center; margin-top: 15px; }
  .dot {
    cursor: pointer; height: 12px; width: 12px; margin: 0 5px;
    background-color: #bbb; border-radius: 50%; display: inline-block;
    transition: background-color 0.3s ease;
  }
  .dot.active, .dot:hover { background-color: #3498db; }
  
  /* Footer Styles */
  .project-footer {
    margin-top: 60px; padding: 40px 20px; text-align: center;
    border-top: 1px solid #e1e4e8; color: #57606a;
    font-size: 0.95em; line-height: 1.6;
  }
</style>

<div class="project-title">
  All in One: Unifying Deepfake Detection, Tampering Localization,<br>
  and Source Tracing with a Robust Landmark-Identity Watermark<br>
  <span class="conference-tag-inline">(<a href="https://cvpr.thecvf.com/Conferences/2026" target="_blank" class="hover-gradient-link" style="color:#2c3e50 !important;">CVPR 2026</a>)</span>
</div>

<div class="author-list">
  <a href="https://junjiang-wu.github.io/" target="_blank" class="hover-gradient-link"><strong>Junjiang Wu</strong></a><sup>1</sup>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://it.xju.edu.cn/info/1155/3270.htm" target="_blank" class="hover-gradient-link"><strong>Liejun Wang</strong></a><sup>1,2 *</sup>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="http://www.guozhiqing.cn/" target="_blank" class="hover-gradient-link"><strong>Zhiqing Guo</strong></a><sup>1,2 *</sup>
</div>

<div class="institution-list">
  <p><sup>1</sup>School of Computer Science and Technology, Xinjiang University, Urumqi, China</p>
  <p><sup>2</sup>Xinjiang Multimodal Intelligent Processing and Information Security Engineering Technology Research Center, Urumqi, China</p>
  <p><em>* Corresponding author</em></p>
</div>

<div class="btn-container">
  <a href="#" target="_blank" class="action-btn">
    <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
      <path d="M14 2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V8l-6-6zM13 3.5L18.5 9H13V3.5zM10.8 15.6c-.6 1.4-1.6 2.4-2.8 2.4-.7 0-1.3-.4-1.3-1 0-.9 1.1-1.6 2.8-2.1.4-1.1.8-2.4 1-3.6-1.1-1.9-1.5-3.4-1.1-4.1.3-.5 1.1-.5 1.6.1.4.5.3 1.7-.1 3 1.1 1.1 2.5 1.9 4 2.3 1.3-.1 2.4.1 2.8.6.3.3.3.8-.2 1.2-.6.5-1.7.4-3.1-.4-1.3.5-2.5 1.1-3.6 1.6zm-1.8.8c.6 0 1.3-.6 1.8-1.5-1.1.3-1.8.8-1.8 1.5zm3.1-6.9c-.1-.7-.2-1.4-.4-1.9.3-1.1.5-1.7.3-1.9 0 0-.1-.1-.2-.1-.2.1-.2.6.3 3.9zm-1.1 2.9c.8 1.2 1.8 2 2.7 2.5.9.4 1.7.5 2.1.1.1-.1.1-.3-.1-.5-.5-.4-1.4-.5-2.5-.4-1.1-.6-2.2-1.2-3.2-1.9.4.1.7.2 1 .2z"></path>
    </svg>
    <span>Paper</span>
  </a>
  <a href="https://github.com/vpsg-research/LIDMark" target="_blank" class="action-btn">
    <svg aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z"></path></svg>
    <span>Code</span>
  </a>
</div>

<h2 align="center">Abstract</h2>
<p style="text-align: justify; max-width: 800px; margin: 0 auto 40px auto;">
With the rapid advancement of deepfake technology, malicious face manipulations pose a significant threat to personal privacy and social security. However, existing proactive forensics methods typically treat deepfake detection, tampering localization, and source tracing as independent tasks, lacking a unified framework to address them jointly. To bridge this gap, we propose a unified proactive forensics framework that jointly addresses these three core tasks. Our core framework adopts an innovative 152-dimensional landmark-identity watermark termed LIDMark, which structurally interweaves facial landmarks with a unique source identifier. To robustly extract the LIDMark, we design a novel Factorized-Head Decoder (FHD). Its architecture factorizes the shared backbone features into two specialized heads (i.e., regression and classification), robustly reconstructing the embedded landmarks and identifier, respectively, even when subjected to severe distortion or tampering. This design realizes an "all-in-one" trifunctional forensic solution: the regression head underlies an "intrinsic-extrinsic" consistency check for detection and localization, while the classification head robustly decodes the source identifier for tracing. Extensive experiments show that the proposed LIDMark framework provides a unified, robust, and imperceptible solution for the detection, localization, and tracing of deepfake content.
</p>

<h2 align="center">Comparison of proactive deepfake forensic paradigms</h2>
<div align="center">
  <img src="/images/discrepancy.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<p style="text-align: justify; max-width: 800px; margin: 20px auto 40px auto;">
Conventional approaches shown at the top are limited to single tasks or require complex dual-decoder architectures for bifunctional forensics. The proposed "all-in-one" framework illustrated at the bottom employs the trifunctional LIDMark and a novel FHD for deepfake detection, source tracing, and tampering localization.
</p>

<h2 align="center">Overall of the LIDMark construction</h2>
<div align="center">
  <img src="/images/structure.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<p style="text-align: justify; max-width: 800px; margin: 20px auto 40px auto;">
The 152-D LIDMark $W$ construction. The composite watermark concatenates two primary streams: (1) $W_L$, a 136-D vector of normalized 2-D facial landmarks, and (2) $W_{ID}$, a 16-D bipolar identifier derived via a SHA-256 hash of the filename.
</p>

<h2 align="center">Overview of the LIDMark framework</h2>
<div align="center">
  <img src="/images/framework.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<p style="text-align: justify; max-width: 800px; margin: 20px auto 40px auto;">
The trifunctional forensic framework features an encoder $E$, a stochastic manipulation operator $\mathcal{M}$, a factorized-head decoder FHD, and a discriminator $D$. (a) The encoder embeds the LIDMark $W$ into $I_{co}$ via a two-stream fusion network, yielding the watermarked image $I_{wm}$. (b) $\mathcal{M}$ simulates diverse common distortions and deepfake manipulations on $I_{wm}$, producing the manipulated image $I'_{wm}$. (c) The FHD recovers $\hat{W}_L$ and $\hat{W}_{ID}$ from $I'_{wm}$ via the shared backbone and factorized heads. (d) The multi-task loss functions guide the training process. (e) The "intrinsic-extrinsic" consistency check employs recovered landmarks $\hat{W}_L$ and re-detected landmarks $W_{new}$ for fine-grained tamper detection and localization, while identifiers $\hat{W}_{ID}$ are extracted for source tracing.
</p>

<h2 align="center">Results</h2>
<div class="carousel-wrapper" id="results-carousel">
  <button class="carousel-btn prev-btn" onclick="moveSlide(-1)">&#10094;</button>
  <button class="carousel-btn next-btn" onclick="moveSlide(1)">&#10095;</button>
  
  <div class="carousel-container">
    <div class="carousel-track" id="results-track">
      <div class="carousel-slide">
        <img src="/images/vision.png" alt="Result Vision 1">
      </div>
      <div class="carousel-slide">
        <img src="/images/vision2.png" alt="Result Vision 2">
      </div>
    </div>
  </div>
  
  <div class="carousel-dots">
    <span class="dot active" onclick="setSlide(0)"></span>
    <span class="dot" onclick="setSlide(1)"></span>
  </div>
</div>

<div style="max-width: 800px; margin: 0 auto 15px auto; display: flex; justify-content: space-between; align-items: center;">
  <h2 style="margin: 0;">BibTeX</h2>
  <button id="copy-bibtex-btn" class="action-btn" onclick="copyBibtex()" style="border: none; cursor: pointer; padding: 8px 20px;">
    <svg aria-hidden="true" focusable="false" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512">
      <path d="M208 0H332.1c12.7 0 24.9 5.1 33.9 14.1l67.9 67.9c9 9 14.1 21.2 14.1 33.9V336c0 26.5-21.5 48-48 48H208c-26.5 0-48-21.5-48-48V48c0-26.5 21.5-48 48-48zM48 128h80v64H64V448h192v-64h64v80c0 26.5-21.5 48-48 48H48c-26.5 0-48-21.5-48-48V176c0-26.5 21.5-48 48-48z"></path>
    </svg>
    <span>Copy</span>
  </button>
</div>

<div style="max-width: 800px; margin: 0 auto 40px auto; background-color: #f6f8fa; border: 1px solid #d0d7de; border-radius: 6px; padding: 16px; overflow-x: auto;">
  <pre style="margin: 0; font-family: ui-monospace, SFMono-Regular, SF Mono, Menlo, Consolas, Liberation Mono, monospace; font-size: 14px; line-height: 1.45; color: #24292f; white-space: pre-wrap; word-wrap: break-word;"><code id="bibtex-text">@inproceedings{wu2026lidmark,
  title={All in One: Unifying Deepfake Detection, Tampering Localization, and Source Tracing with a Robust Landmark-Identity Watermark},
  author={Wu, Junjiang and Wang, Liejun and Guo, Zhiqing},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2026}
}</code></pre>
</div>

<footer class="project-footer">
  <p>
    This page was built using the <a href="https://github.com/eliahu/Project-Page-Template" target="_blank" class="hover-gradient-link" style="font-weight: normal;">Academic Project Page Template</a> which was adopted from the <a href="https://nerfies.github.io/" target="_blank" class="hover-gradient-link" style="font-weight: normal;">Nerfies</a> project page. You are free to borrow the source code of this website, we just ask that you link back to this page in the footer.
  </p>
  <p style="margin-top: 10px;">
    This website is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/" target="_blank" class="hover-gradient-link" style="font-weight: normal;">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
  </p>
</footer>

<script>
  function copyBibtex() {
    const bibtexCode = document.getElementById('bibtex-text').innerText;
    navigator.clipboard.writeText(bibtexCode).then(() => {
      const btnSpan = document.querySelector('#copy-bibtex-btn span');
      btnSpan.innerText = 'Copied!';
      setTimeout(() => { 
        btnSpan.innerText = 'Copy'; 
      }, 2000);
    }).catch(err => {
      console.error('Failed to copy text: ', err);
    });
  }

  let currentSlide = 0;
  const totalSlides = 2;
  let slideInterval;

  function moveSlide(direction) {
    currentSlide = (currentSlide + direction + totalSlides) % totalSlides;
    updateCarousel();
    resetAutoPlay();
  }

  function setSlide(index) {
    currentSlide = index;
    updateCarousel();
    resetAutoPlay();
  }

  function updateCarousel() {
    const track = document.getElementById('results-track');
    const dots = document.querySelectorAll('.dot');
    
    track.style.transform = `translateX(-${currentSlide * 100}%)`;
    
    dots.forEach((dot, index) => {
      dot.classList.toggle('active', index === currentSlide);
    });
  }

  function startAutoPlay() {
    slideInterval = setInterval(() => {
      currentSlide = (currentSlide + 1) % totalSlides;
      updateCarousel();
    }, 5000);
  }

  function stopAutoPlay() {
    clearInterval(slideInterval);
  }

  function resetAutoPlay() {
    stopAutoPlay();
    startAutoPlay();
  }

  startAutoPlay();

  const carouselWrapper = document.getElementById('results-carousel');
  carouselWrapper.addEventListener('mouseenter', stopAutoPlay);
  carouselWrapper.addEventListener('mouseleave', startAutoPlay);

</script>
