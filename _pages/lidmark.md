---
permalink: /projects/lidmark/
title: ""
author_profile: false
---

<div align="center">
  <h1>All in One: Unifying Deepfake Detection, Tampering Localization, and Source Tracing with a Robust Landmark-Identity Watermark</h1>
  
  <p>
    <strong>Junjiang Wu</strong><sup>1</sup>&nbsp;&nbsp;&nbsp;&nbsp;
    <strong>Liejun Wang</strong><sup>1,2</sup>&nbsp;&nbsp;&nbsp;&nbsp;
    <strong>Zhiqing Guo</strong><sup>1,2</sup>
  </p>
  
  <p><sup>1</sup>School of Computer Science and Technology, Xinjiang University, Urumqi, China</p>
  <p><sup>2</sup>Xinjiang Multimodal Intelligent Processing and Information Security Engineering Technology Research Center, Urumqi, China</p>
  
  <p><strong>CVPR 2026</strong></p>

  <div style="display: flex; justify-content: center; gap: 15px; margin-top: 20px; margin-bottom: 40px;">
    <a href="https://github.com/vpsg-research/LIDMark" target="_blank" style="padding: 10px 20px; background-color: #333; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">
      <i class="fab fa-github"></i> Code
    </a>
    <a href="#" target="_blank" style="padding: 10px 20px; background-color: #e74c3c; color: white; border-radius: 5px; text-decoration: none; font-weight: bold;">
      <i class="far fa-file-pdf"></i> Paper (Coming Soon)
    </a>
  </div>
</div>

<div align="center">
  <img src="/images/teaser.png" alt="LIDMark Teaser" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
  <p style="text-align: left; max-width: 800px; margin: 10px auto; font-size: 0.9em; color: #555;">
    <em>Figure 1: Teaser image showing the capabilities of our LIDMark framework in deepfake detection, localization, and tracing.</em>
  </p>
</div>

<hr>

<h2 align="center">Abstract</h2>
<p style="text-align: justify; max-width: 800px; margin: 0 auto;">
With the rapid advancement of deepfake technology, malicious face manipulations pose a significant threat to personal privacy and social security. However, existing proactive forensics methods typically treat deepfake detection, tampering localization, and source tracing as independent tasks, lacking a unified framework to address them jointly. To bridge this gap, we propose a unified proactive forensics framework that jointly addresses these three core tasks. Our core framework adopts an innovative 152-dimensional landmark-identity watermark termed LIDMark, which structurally interweaves facial landmarks with a unique source identifier. To robustly extract the LIDMark, we design a novel Factorized-Head Decoder (FHD). Its architecture factorizes the shared backbone features into two specialized heads (i.e., regression and classification), robustly reconstructing the embedded landmarks and identifier, respectively, even when subjected to severe distortion or tampering. This design realizes an "all-in-one" trifunctional forensic solution: the regression head underlies an "intrinsic-extrinsic" consistency check for detection and localization, while the classification head robustly decodes the source identifier for tracing. Extensive experiments show that the proposed LIDMark framework provides a unified, robust, and imperceptible solution for the detection, localization, and tracing of deepfake content.
</p>

<hr>

<h2 align="center">Overall Framework of LIDMark</h2>
<div align="center">
  <img src="/images/framework.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<p style="text-align: justify; max-width: 800px; margin: 20px auto 0;">
Overview of the LIDMark framework. The trifunctional forensic framework features an encoder $E$, a stochastic manipulation operator $\mathcal{M}$, a factorized-head decoder FHD, and a discriminator $D$. (a) The encoder embeds the LIDMark $W$ into $I_{co}$ via a two-stream fusion network, yielding the watermarked image $I_{wm}$. (b) $\mathcal{M}$ simulates diverse common distortions and deepfake manipulations on $I_{wm}$, producing the manipulated image $I'_{wm}$. (c) The FHD recovers $\hat{W}_L$ and $\hat{W}_{ID}$ from $I'_{wm}$ via the shared backbone and factorized heads. (d) The multi-task loss functions guide the training process. (e) The ``intrinsic-extrinsic'' consistency check employs recovered landmarks $\hat{W}_L$ and re-detected landmarks $W_{new}$ for fine-grained tamper detection and localization, while identifiers $\hat{W}_{ID}$ are extracted for source tracing.
</p>

<hr>

<h2 align="center">Citation</h2>
<div style="max-width: 800px; margin: 0 auto; background-color: #f4f4f4; padding: 15px; border-radius: 5px; overflow-x: auto;">
<pre><code>@inproceedings{wu2026all,
  title={All in One: Unifying Deepfake Detection, Tampering Localization, and Source Tracing with a Robust Landmark-Identity Watermark},
  author={Wu, Junjiang and Wang, Liejun and Guo, Zhiqing},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)},
  year={2026}
}</code></pre>
</div>
