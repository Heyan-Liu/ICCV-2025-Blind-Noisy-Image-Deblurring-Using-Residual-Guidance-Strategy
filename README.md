
# Blind Noisy Image Deblurring Using Residual Guidance Strategy (ICCV 2025)

Official implementation of the paper **"Blind Noisy Image Deblurring Using Residual Guidance Strategy"**, accepted by **ICCV 2025**.

## 🚀 Introduction
Blind deblurring is a challenging ill-posed inverse problem. While existing methods often struggle under **high levels of noise**, which compromises kernel estimation and restoration quality. 

To address this, we propose the **Residual Guidance Strategy (RGS)** to suppress the influence of noise. By leveraging adjacent coarser-scale information within an image pyramid, our method provides robust guidance for blur kernel estimation in the current scale. This ensures accurate kernel estimation and high-quality restoration even for images corrupted by severe noise.

### Key Contributions:
* **Noise-Robust Blind Deblurring**: We present a method that employs a novel residual-guided strategy within an image pyramid to refine kernel estimation, leading to significantly improved deblurring results.
* **Broad Applicability**: The proposed residual guidance strategy (RGS) can be broadly applied to various existing deblurring methods to enhance their robustness against strong noise.
* **SOTA Performance without Training**: Comprehensive experiments demonstrate that our simple approach outperforms other state-of-the-art methods quantitatively and qualitatively across synthetic and real datasets.
---


## 🖼️ Method Overview

### 1. Model Architecture (Flowchart)
Our proposed **Residual Guidance Strategy (RGS)** leverages adjacent coarser-scale information to robustly guide blur kernel estimation.

<p align="center">
  <img src="results/Logic chart-ICCV.pdf" alt="Model Architecture" width="800">
</p>

> *Figure 1: The overall pipeline of our Residual Guidance Strategy for blind noisy image deblurring.*

---

### 2. Experimental Comparison
We evaluate our method against state-of-the-art (SOTA) methods under severe noise conditions.

<p align="center">
  <img src="results/high noise.PNG" alt="Experimental Comparison" width="1000">
</p>

> *Figure 2: Qualitative comparison. Our method consistently outperforms numerous SOTA methods by effectively suppressing strong noise while recovering sharp details.*

---
---

## 🛠️ News & Status
* **[2025-6]** Paper accepted by **ICCV 2025**! 🎉
* **[Coming Soon]** We are currently cleaning up the code. They will be released shortly.

## 📖 Citation
If you find our work or code useful, please consider citing:

```latex
@inproceedings{liu2025blind,
  title={Blind Noisy Image Deblurring Using Residual Guidance Strategy},
  author={Liu, Heyan and Liu, Jun and others},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  year={2025}
}
