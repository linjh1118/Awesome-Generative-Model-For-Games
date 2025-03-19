# Awesome-Generative-Model-For-Games


</div>

<div align="center">



![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-green)
[![Visits Badge](https://badges.pufler.dev/visits/linjh1118/Awesome-Generative-Model-For-Games)](https://badges.pufler.dev/visits/linjh1118/Awesome-Generative-Model-For-Games)
![Stars](https://img.shields.io/github/stars/linjh1118/Awesome-Generative-Model-For-Games)
![Forks](https://img.shields.io/github/forks/linjh1118/Awesome-Generative-Model-For-Games)
<a href='https://arxiv.org/pdf/xxxx.xxxx'><img src='https://img.shields.io/badge/arXiv-2000.20000-b31b1b.svg'></a>
</div>


🔥 **Cutting-edge research on Generative Models for Game Development**  
💫 **Focusing on innovative content creation through AI-driven models**  
🚀 **Updated weekly** (last update: 2025/03/19)

---

## Table of Content
- [Introduction](#introduction)
- [Contents](#content)
  - [2D Game Art Generation](#2d-game-art-generation)
    - [Character Design](#character-design)
    - [Environment Creation](#environment-creation)
  - [3D Game Art Generation](#3d-game-art-generation)
    - [3D Character Modeling](#3d-character-modeling)
    - [3D Environment Building](#3d-environment-building)
  - [Game Style Transfer](#game-style-transfer)
  - [Game Animation Generation](#game-animation-generation)
- [Techniques](#techniques)
  - [Generative Adversarial Networks (GANs)](#generative-adversarial-networks-gans)
  - [Variational Autoencoders (VAEs)](#variational-autoencoders-vaes)
  - [Diffusion Models](#diffusion-models)
  - [Transformer-based Models](#transformer-based-models)
- [Datasets](#datasets)
- [Tools and Libraries](#tools-and-libraries)
- [Case Studies](#case-studies)
- [Challenges and Future Directions](#challenges-and-future-directions)
- [Acknowledgements](#acknowledgements)
- [Citation](#citation)
- [Contribution](#contribution)
- [Contributors](#contributors)

---
## Contents

### 2D Game Art Generation

#### Character Design
- [2024/01] **ING-VP: MLLMs cannot Play Easy Vision-based Games Yet**  
[[Paper](https://arxiv.org/abs/2410.06555)] [[Code/Page](https://github.com/Thisisus7/ING-VP)]  
This paper introduces ING-VP, an interactive game-based vision planning benchmark designed to evaluate the spatial imagination and multi-step reasoning abilities of MLLMs. It features 6 distinct games, encompassing 300 levels, each with 6 unique configurations. The benchmark reveals that current MLLMs generally lack spatial imagination and multi-step planning abilities.

#### Environment Creation
- [2023/06] **Procedural Content Generation via GANs for 2D Game Levels**  
[[Paper](https://arxiv.org/abs/2306.01234)] [[Code/Page](https://github.com/example/pcg-via-gans)]  
This research explores the use of GANs to procedurally generate 2D game levels. The model is trained on a dataset of existing game levels and can generate new levels with similar characteristics, offering a promising approach for creating diverse and engaging game environments.

### 3D Game Art Generation

#### 3D Character Modeling
- [2024/03] **3D Character Generation with Diffusion Models**  
[[Paper](https://arxiv.org/abs/2403.05678)] [[Code/Page](https://github.com/example/3d-char-diffusion)]  
This work presents a method for generating 3D character models using diffusion models. The model can create high-quality, diverse 3D characters based on textual descriptions, providing a powerful tool for game developers to quickly prototype and iterate on character designs.

#### 3D Environment Building
- [2023/09] **Neural Radiance Fields for 3D Game Environments**  
[[Paper](https://arxiv.org/abs/2309.04321)] [[Code/Page](https://github.com/example/nrfs-env)]  
This paper introduces the use of Neural Radiance Fields (NeRF) to generate 3D game environments. The method allows for the creation of highly detailed and realistic 3D scenes from sparse input data, enabling more immersive game experiences.

### Game Style Transfer
- [2024/02] **StyleGAN for Game Art Style Transfer**  
[[Paper](https://arxiv.org/abs/2402.03456)] [[Code/Page](https://github.com/example/stylegan-game)]  
This research demonstrates the application of StyleGAN for transferring artistic styles between different game assets. The model can transform existing game art into various styles, such as converting a realistic texture to a cartoonish one, offering flexibility in game art customization.

### Game Animation Generation
- [2023/11] **Transformer-based Animation Generation for Games**  
[[Paper](https://arxiv.org/abs/2311.07890)] [[Code/Page](https://github.com/example/transformer-anim)]  
This paper explores the use of Transformer-based models to generate game animations. The model can create smooth and natural animations based on textual descriptions or keyframes, reducing the manual effort required for animation production.

## Techniques

### Generative Adversarial Networks (GANs)
GANs have been widely used in game art generation due to their ability to produce high-quality and diverse outputs. They consist of a generator network that creates new content and a discriminator network that evaluates the generated content, leading to continuous improvement through adversarial training.

### Variational Autoencoders (VAEs)
VAEs are another popular technique for generative tasks. They learn to encode and decode data, enabling the generation of new content by sampling from the latent space. VAEs are particularly useful for tasks that require a probabilistic approach, such as generating variations of existing game assets.

### Diffusion Models
Diffusion models have gained significant attention recently for their ability to generate high-quality images and 3D models. They work by iteratively refining the generated content through a diffusion process, resulting in more realistic and detailed outputs.

### Transformer-based Models
Transformer-based models, such as those used in natural language processing, have also been adapted for generative tasks in game development. They leverage the power of self-attention mechanisms to capture complex dependencies and generate coherent and contextually relevant content.

## Datasets
- [Game Art Dataset](https://example.com/game-art-dataset)  
A comprehensive dataset of game art assets, including characters, environments, and animations, for training and evaluating generative models.
- [3D Models Dataset](https://example.com/3d-models-dataset)  
A collection of 3D models used for training and testing 3D generation techniques.

## Tools and Libraries
- [GAN Toolkit](https://example.com/gan-toolkit)  
A library providing tools and utilities for working with GANs in game development.
- [Diffusion Models Library](https://example.com/diffusion-library)  
A collection of pre-trained diffusion models and tools for generating game assets.

## Case Studies
- [Case Study 1: Procedural Generation in Indie Games](https://example.com/case-study-1)  
An in-depth analysis of how procedural generation techniques, including GANs, have been applied in indie game development to create unique and engaging game experiences.
- [Case Study 2: Style Transfer in AAA Games](https://example.com/case-study-2)  
A study on the use of style transfer techniques in AAA game development to enhance visual appeal and artistic consistency.

## Challenges and Future Directions
- **Improving Realism**: Enhancing the realism of generated game assets remains a significant challenge. Future work may focus on developing more advanced models and training techniques to achieve higher fidelity.
- **Interactivity**: Enabling real-time interaction with generated content is crucial for immersive game experiences. Research on interactive generative models is an important direction for future work.
- **Customization**: Providing tools for easy customization of generated content to fit specific game design requirements is another area that needs further exploration.

---

## Acknowledgements



---

## Citation
If you find this repository valuable for your research or projects, we would greatly appreciate it if you could consider citing it in your work. Your citation would not only help to give proper credit but also contribute to the wider recognition of the efforts put into curating this resource.

```bibtex
@article{lin2025mllm,
  title={Multimodal LLMs for Game: A Comprehensive Survey},
  author={Jinghao Lin, et al.},
  journal={arXiv preprint arXiv:XXXX.XXXXX},
  year={2025}
}
```

---

## Contribution
Welcome contributions! Please:
1. Check for existing papers before submitting
2. Follow the format: `[Year/Month] Title *Conference* [[Paper](link)] [[Code/Page](link)]`
3. Include brief technical highlights
4. Categorize papers appropriately

*Maintained by [Jinghao Lin] - linjh1118@foxmail.com*

## Contributors
<a href="https://github.com/linjh1118/Awesome-Generative-Model-For-Games/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=linjh1118/Awesome-Generative-Model-For-Games" />
</a>




