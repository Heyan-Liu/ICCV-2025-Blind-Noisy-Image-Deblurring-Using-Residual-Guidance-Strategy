
# Blind Noisy Image Deblurring Using Residual Guidance Strategy (ICCV 2025)

Official implementation of the paper **"Blind Noisy Image Deblurring Using Residual Guidance Strategy"**, accepted by **ICCV 2025**.

## 🚀 Introduction
Blind deblurring is a challenging ill-posed inverse problem. While existing methods perform well on clean images, they often struggle under **high levels of noise**, which compromises kernel estimation and restoration quality. 

To address this, we propose the **Residual Guidance Strategy (RGS)** to suppress the influence of noise. By leveraging adjacent coarser-scale information within an image pyramid, our method provides robust guidance for blur kernel estimation in the current scale. This ensures accurate kernel estimation and high-quality restoration even for images corrupted by severe noise.

### Key Contributions:
* **Noise Robustness**: Specifically designed to suppress the influence of strong noise during the deblurring process.
* **Scale-Recurrent Guidance**: Utilizes a novel Residual Guidance Strategy (RGS) to estimate more accurate blur kernels across different noise levels and types.
* **SOTA Performance**: Consistently outperforms numerous state-of-the-art methods on both synthetic and real-world datasets, both quantitatively and qualitatively.

---

## 🖼️ Visual Results
*(Upload your comparison figures to the repository and link them below)*

| Blurry & Noisy Input | Our Restoration |
|:---:|:---:|
| <img src="results/input_sample.png" width="400"> | <img src="results/output_sample.png" width="400"> |

> *Figure: Comparison of our method against SOTA under severe noise conditions.*

---

## 🛠️ News & Status
* **[2025-XX]** Paper accepted by **ICCV 2025**! 🎉
* **[Coming Soon]** We are currently cleaning up the code and pre-trained models. They will be released shortly.

## 📖 Citation
If you find our work or code useful, please consider citing:

```latex
@inproceedings{liu2025blind,
  title={Blind Noisy Image Deblurring Using Residual Guidance Strategy},
  author={Liu, Heyan and Liu, Jun and others},
  booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision (ICCV)},
  year={2025}
}
