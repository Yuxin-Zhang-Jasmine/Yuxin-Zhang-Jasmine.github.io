---
permalink: /articles/
title: "Publications"
author_profile: true
---

   
1. **Ultrasound Image Enhancement with the Variance of Diffusion Models**  
   *Author(s):* Y Zhang, C Huneau, J Idier, D Mateus  
   *Conference:* 2024 International Ultrasonics Symposium (IUS)  
   [Paper](https://arxiv.org/pdf/2409.11380), [Code](https://github.com/Yuxin-Zhang-Jasmine/IUS2024_Diffusion), [Slides](https://yuxin-zhang-jasmine.github.io/files/IUS/8561_YuxinZ_Diffusion.pdf), [Video](https://www.bilibili.com/video/BV14ADsY1Es5/?vd_source=e06c10e6def4a4103e4728dc5c00fbbb)  
   **Abstract:**  
   <details>
     <summary>Click to show abstract</summary>
     Ultrasound imaging, despite its widespread use in medicine, often suffers from various sources of noise and artifacts that impact the signal-to-noise ratio and overall image quality. Enhancing ultrasound images requires a delicate balance between contrast, resolution, and speckle preservation. This paper introduces a novel approach that integrates adaptive beamforming with denoising diffusion-based variance imaging to address this challenge. By applying Eigenspace-Based Minimum Variance (EBMV) beamforming and employing a denoising diffusion model fine-tuned on ultrasound data, our method computes the variance across multiple diffusion-denoised samples to produce high-quality despeckled images. This approach leverages both the inherent multiplicative noise of ultrasound and the stochastic nature of diffusion models. Experimental results on a publicly available dataset demonstrate the effectiveness of our method in achieving superior image reconstructions from single plane-wave acquisitions. The code is available at: [https://github.com/Yuxin-Zhang-Jasmine/IUS2024_Diffusion](https://github.com/Yuxin-Zhang-Jasmine/IUS2024_Diffusion).
   </details>

2. **Compact Implicit Neural Representations for Plane Wave Images**  
   *Author(s):* M Monvoisin, Y Zhang, D Mateus  
   *Conference:* 2024 International Ultrasonics Symposium (IUS)  
   [Paper](https://arxiv.org/pdf/2409.11370)  
   **Abstract:**  
   <details>
     <summary>Click to show abstract</summary>
     Ultrafast Plane-Wave (PW) imaging often produces artifacts and shadows that vary with insonification angles. We propose a novel approach using Implicit Neural Representations (INRs) to compactly encode multi-planar sequences while preserving crucial orientation-dependent information. To our knowledge, this is the first application of INRs for PW angular interpolation. Our method employs a Multi-Layer Perceptron (MLP)-based model with a concise physics-enhanced rendering technique. Quantitative evaluations using SSIM, PSNR, and standard ultrasound metrics, along with qualitative visual assessments, confirm the effectiveness of our approach. Additionally, our method demonstrates significant storage efficiency, with model weights requiring 530 KB compared to 8 MB for directly storing the 75 PW images, achieving a notable compression ratio of approximately 15:1.
   </details>
   
3. **Ultrasound Imaging based on the Variance of a Diffusion Restoration Model**  
   *Author(s):* Y Zhang, C Huneau, J Idier, D Mateus  
   *Conference:* 2024 32nd European Signal Processing Conference (EUSIPCO)  
   [Paper](https://eurasip.org/Proceedings/Eusipco/Eusipco2024/pdfs/0000760.pdf), [Code](https://github.com/Yuxin-Zhang-Jasmine/DRUSvar), [Slides](https://yuxin-zhang-jasmine.github.io/files/EUSIPCO/yuxinZ_EUSIPCO.pdf)  
   **Abstract:**  
   <details>
     <summary>Click to show abstract</summary>
     Despite today's prevalence of ultrasound imaging in medicine, ultrasound signal-to-noise ratio is still affected by several sources of noise and artifacts. Moreover, enhancing ultrasound image quality involves balancing concurrent factors like contrast, resolution, and speckle preservation. Recently, there has been progress in both model-based and learning-based approaches addressing the problem of ultrasound image reconstruction. Bringing the best from both worlds, we propose a hybrid reconstruction method combining an ultrasound linear direct model with a learning-based prior coming from a generative Denoising Diffusion model. More specifically, we rely on the unsupervised fine-tuning of a pre-trained Denoising Diffusion Restoration Model (DDRM). Given the nature of multiplicative noise inherent to ultrasound, this paper proposes an empirical model to characterize the stochasticity of diffusion reconstruction of ultrasound images, and shows the interest of its variance as an echogenicity map estimator. We conduct experiments on synthetic, in-vitro, and in-vivo data, demonstrating the efficacy of our variance imaging approach in achieving high-quality image reconstructions from single plane-wave acquisitions and in comparison to state-of-the-art methods. The code is available at: [https://github.com/Yuxin-Zhang-Jasmine/DRUSvar](https://github.com/Yuxin-Zhang-Jasmine/DRUSvar).
   </details>
   

4. **Ultrasound Image Reconstruction with Denoising Diffusion Restoration Models**  
   *Author(s):* Y Zhang, C Huneau, J Idier, D Mateus  
   *Conference:* 2023 International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)   
   [Paper](https://arxiv.org/pdf/2307.15990), [Code](https://github.com/YuxinZhang-Jasmine/DRUS-v1), [Slides](https://yuxin-zhang-jasmine.github.io/files/DGM4MICCAI/DGM4MICCAI2023_32_slides.pdf)  
   **Abstract:**  
   <details>
     <summary>Click to show abstract</summary>
     Ultrasound image reconstruction can be approximately cast as a linear inverse problem that has traditionally been solved with penalized optimization using the l1 or l2 norm, or wavelet-based terms. However, such regularization functions often struggle to balance the sparsity and the smoothness. A promising alternative is using learned priors to make the prior knowledge closer to reality. In this paper, we rely on learned priors under the framework of Denoising Diffusion Restoration Models (DDRM), initially conceived for restoration tasks with natural images. We propose and test two adaptations of DDRM to ultrasound inverse problem models, DRUS and WDRUS. Our experiments on synthetic and PICMUS data show that from a single plane wave our method can achieve image quality comparable to or better than DAS and state-of-the-art methods. The code is available at: [https://github.com/YuxinZhang-Jasmine/DRUS-v1](https://github.com/YuxinZhang-Jasmine/DRUS-v1).
   </details>

