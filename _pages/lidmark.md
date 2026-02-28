<div align="center">
  <h1>All in One: Unifying Deepfake Detection, Tampering Localization, and Source Tracing with a Robust Landmark-Identity Watermark (CVPR 2026)</h1>
  
  <p>
    <strong>Junjiang Wu</strong><sup>1</sup>&nbsp;&nbsp;&nbsp;&nbsp;
    <strong>Liejun Wang</strong><sup>1,2 *</sup>&nbsp;&nbsp;&nbsp;&nbsp;
    <strong>Zhiqing Guo</strong><sup>1,2 *</sup>
  </p>
  <p><strong>* Corresponding author</sup></p>
  
  <p><sup>1</sup>School of Computer Science and Technology, Xinjiang University, Urumqi, China</p>
  <p><sup>2</sup>Xinjiang Multimodal Intelligent Processing and Information Security Engineering Technology Research Center, Urumqi, China</p>

<div style="display: flex; justify-content: center; gap: 15px; margin-top: 15px; margin-bottom: 40px; flex-wrap: wrap;">
    <a href="#" target="_blank" style="display: inline-flex; align-items: center; justify-content: center; padding: 6px 16px; border: 1px solid #363636; border-radius: 20px; color: #363636; background-color: #fff; text-decoration: none; font-size: 14px; transition: all 0.2s ease; box-shadow: 0 1px 2px rgba(0,0,0,0.05);" onmouseover="this.style.backgroundColor='#f5f5f5'" onmouseout="this.style.backgroundColor='#fff'">
      <span style="display: flex; align-items: center; margin-right: 6px;">
        <svg class="svg-inline--fa fa-file-pdf fa-w-12" aria-hidden="true" focusable="false" data-prefix="far" data-icon="file-pdf" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 384 512" style="width: 1em; height: 1em; fill: currentColor;"><path d="M369.9 97.9L286 14C277 5 264.8-.1 252.1-.1H48C21.5 0 0 21.5 0 48v416c0 26.5 21.5 48 48 48h288c26.5 0 48-21.5 48-48V131.9c0-12.7-5.1-25-14.1-34zM332.1 132H256V55.9l76.1 76.1zM48 464V48h160v104c0 13.3 10.7 24 24 24h104v288H48z" fill="currentColor"></path></svg>
      </span>
      <span>Paper</span>
    </a>

    <a href="https://github.com/vpsg-research/LIDMark" target="_blank" style="display: inline-flex; align-items: center; justify-content: center; padding: 6px 16px; border: 1px solid #363636; border-radius: 20px; color: #363636; background-color: #fff; text-decoration: none; font-size: 14px; transition: all 0.2s ease; box-shadow: 0 1px 2px rgba(0,0,0,0.05);" onmouseover="this.style.backgroundColor='#f5f5f5'" onmouseout="this.style.backgroundColor='#fff'">
      <span style="display: flex; align-items: center; margin-right: 6px;">
        <svg class="svg-inline--fa fa-github fa-w-16" aria-hidden="true" focusable="false" data-prefix="fab" data-icon="github" role="img" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 496 512" style="width: 1em; height: 1em; fill: currentColor;"><path d="M165.9 397.4c0 2-2.3 3.6-5.2 3.6-3.3.3-5.6-1.3-5.6-3.6 0-2 2.3-3.6 5.2-3.6 3-.3 5.6 1.3 5.6 3.6zm-31.1-4.5c-.7 2 1.3 4.3 4.3 4.9 2.6 1 5.6 0 6.2-2s-1.3-4.3-4.3-5.2c-2.6-.7-5.5.3-6.2 2.3zm44.2-1.7c-2.9.7-4.9 2.6-4.6 4.9.3 2 2.9 3.3 5.9 2.6 2.9-.7 4.9-2.6 4.6-4.6-.3-1.9-3-3.2-5.9-2.9zM244.8 8C106.1 8 0 113.3 0 252c0 110.9 69.8 205.8 169.5 239.2 12.8 2.3 17.3-5.6 17.3-12.1 0-6.2-.3-40.4-.3-61.4 0 0-70 15-84.7-29.8 0 0-11.4-29.1-27.8-36.6 0 0-22.9-15.7 1.6-15.4 0 0 24.9 2 38.6 25.8 21.9 38.6 58.6 27.5 72.9 20.9 2.3-16 8.8-27.1 16-33.7-55.9-6.2-112.3-14.3-112.3-110.5 0-27.5 7.6-41.3 23.6-58.9-2.6-6.5-11.1-33.3 2.6-67.9 20.9-6.5 69 27 69 27 20-5.6 41.5-8.5 62.8-8.5s42.8 2.9 62.8 8.5c0 0 48.1-33.6 69-27 13.7 34.7 5.2 61.4 2.6 67.9 16 17.7 25.8 31.5 25.8 58.9 0 96.5-58.9 104.2-114.8 110.5 9.2 7.9 17 22.9 17 46.4 0 33.7-.3 75.4-.3 83.6 0 6.5 4.6 14.4 17.3 12.1C428.2 457.8 496 362.9 496 252 496 113.3 383.5 8 244.8 8zM97.2 352.9c-1.3 1-1 3.3.7 5.2 1.6 1.6 3.9 2.3 5.2 1 1.3-1 1-3.3-.7-5.2-1.6-1.6-3.9-2.3-5.2-1zm-10.8-8.1c-.7 1.3.3 2.9 2.3 3.9 1.6 1 3.6.7 4.3-.7.7-1.3-.3-2.9-2.3-3.9-2-.6-3.6-.3-4.3.7zm32.4 35.6c-1.6 1.3-1 4.3 1.3 6.2 2.3 2.3 5.2 2.6 6.5 1 1.3-1.3.7-4.3-1.3-6.2-2.2-2.3-5.2-2.6-6.5-1zm-11.4-14.7c-1.6 1-1.6 3.6 0 5.9 1.6 2.3 4.3 3.3 5.6 2.3 1.6-1.3 1.6-3.9 0-6.2-1.4-2.3-4-3.3-5.6-2z" fill="currentColor"></path></svg>
      </span>
      <span>Code</span>
    </a>
  </div>

<hr>

<h2 align="center">Abstract</h2>
<p style="text-align: justify; max-width: 800px; margin: 0 auto;">
With the rapid advancement of deepfake technology, malicious face manipulations pose a significant threat to personal privacy and social security. However, existing proactive forensics methods typically treat deepfake detection, tampering localization, and source tracing as independent tasks, lacking a unified framework to address them jointly. To bridge this gap, we propose a unified proactive forensics framework that jointly addresses these three core tasks. Our core framework adopts an innovative 152-dimensional landmark-identity watermark termed LIDMark, which structurally interweaves facial landmarks with a unique source identifier. To robustly extract the LIDMark, we design a novel Factorized-Head Decoder (FHD). Its architecture factorizes the shared backbone features into two specialized heads (i.e., regression and classification), robustly reconstructing the embedded landmarks and identifier, respectively, even when subjected to severe distortion or tampering. This design realizes an "all-in-one" trifunctional forensic solution: the regression head underlies an "intrinsic-extrinsic" consistency check for detection and localization, while the classification head robustly decodes the source identifier for tracing. Extensive experiments show that the proposed LIDMark framework provides a unified, robust, and imperceptible solution for the detection, localization, and tracing of deepfake content.
</p>

<hr>

<h2 align="center">Differences from Existing Works</h2>
<div align="center">
  <img src="/images/discrepancy.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<p style="text-align: justify; max-width: 800px; margin: 0 auto;">
Comparison of proactive deepfake forensic paradigms. Conventional approaches shown at the top are limited to single tasks or require complex dual-decoder architectures for bifunctional forensics. The proposed ``all-in-one'' framework illustrated at the bottom employs the trifunctional LIDMark and a novel FHD for deepfake detection, source tracing, and tampering localization.
</p>

<hr>

<h2 align="center">>Overall of LIDMark</h2>
<div align="center">
  <img src="/images/structure.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>
<p style="text-align: justify; max-width: 800px; margin: 0 auto;">
The 152-D LIDMark $W$ construction. The composite watermark concatenates two primary streams: (1) $W_L$, a 136-D vector of normalized 2-D facial landmarks, and (2) $W_{ID}$, a 16-D bipolar identifier derived via a SHA-256 hash of the filename.
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

<h2 align="center">Results</h2>
<div align="center">
  <img src="/images/vision.png" alt="LIDMark Framework" style="width: 100%; max-width: 800px; border-radius: 8px; box-shadow: 0 4px 8px rgba(0,0,0,0.1);">
</div>

<hr>

<h2 align="center">Citation</h2>
<div style="max-width: 800px; margin: 0 auto; background-color: #f4f4f4; padding: 15px; border-radius: 5px; overflow-x: auto;">
<pre><code>@inproceedings{wu2026lidmark,
  title={All in One: Unifying Deepfake Detection, Tampering Localization, and Source Tracing with a Robust Landmark-Identity Watermark},
  author={Wu, Junjiang and Wang, Liejun and Guo, Zhiqing},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2026}
}
}</code></pre>
</div>
