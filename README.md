# Denoising Diffusion-based Generative Modeling: Foundations and Applications
> CVPR 2022 Tutorial

## Overview

Denoising diffusion models, also known as score-based generative models, have recently emerged as a powerful class of generative models. They demonstrate astonishing results in high-fidelity image generation, often even outperforming generative adversarial networks. Importantly, they additionally offer strong sample diversity and faithful mode coverage of the learnt data distribution. This implies that denoising diffusion models are well suited for learning models of complex and diverse data. Denoising diffusion models define a forward diffusion process that maps data to noise by gradually perturbing the input data. Data generation is achieved using a learnt, parametrized reverse process that performs iterative denoising, starting from pure random noise (see figure above). Although diffusion models are relatively new, they have already found many successful applications. For instance, they have been used in computer vision for image editing, controllable, semantic, and text-driven image synthesis, image-to-image translation, superresolution, image segmentation, as well as 3D shape generation and completion.

In this tutorial, we recapitulate the foundations of denoising diffusion models, including both their discrete-step formulation as well as their differential equation-based description. We also discuss practical implementation details relevant for practitioners and highlight connections to other, existing generative models, thereby putting denoising diffusion models into a broader context. Moreover, we review recent technical extensions and advanced methods for accelerated sampling, conditional generation, and beyond. Slow sampling has been the main weakness of denoising diffusion models. However, many promising techniques to overcome this challenge have emerged. Recently denoising diffusion models have also made amazing progress in high-resolution conditional generation tasks, e.g., text-to-image generation, and we discuss several key advanced techiques to achieve that. To demonstrate how denoising diffusion models can be tailored to vision use cases, we also review successful applications in computer vision.

Considering diffusion models' unique strengths, this is, simultaneously offering high generation quality and also mode coverage and diversity, as well as recent works on fast sampling and conditional generation, we foresee that they will be adopted widely in computer vision and graphics. Unfortunately, diffusion models rely on fairly technical concepts, and as a result in many application domains the true potential of these models has not been unleashed yet, as the community working on them is still relatively small. The primary goal of this tutorial is to make diffusion models accessible to a wide computer vision audience by providing an introductory short course. This tutorial will build on simple concepts in generative learning and will provide fundamental knowledge to interested researchers and practitioners to start working in this exciting area.


## Speakers
* Karsten Kreis, NVIDIA
* Ruiqi Gao, Google Brain
* Arash Vahdat, NVIDIA


## References
https://cvpr2022-tutorial-diffusion-models.github.io/ 
https://twitter.com/hashtag/CVPR2022?src=hashtag_click&f=live
https://us06web.zoom.us/j/87547892103?pwd=WkpOVkFqcEJUbXgxMjJLeFBPQklodz09#success  



