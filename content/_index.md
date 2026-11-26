---
title: ""
date: 2022-10-24
type: landing

design:
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ""
      button:
        text: Download CV
        url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false

  - block: markdown
    id: papers
    content:
      title: Selected Publications
      subtitle: ""
      text: |-
        \* Equal contribution.

        ### DecQ: Detail-Condensing Queries for Enhanced Reconstruction and Generation in Representation Autoencoders

        **Tianhang Wang**\*, Yitong Chen\*, Wei Song, Zuxuan Wu, Min Li, Jiaqi Wang.

        **NeurIPS 2026 (accepted)** · Co-first author, listed first.

        Detail-condensing queries enrich frozen visual representations to improve both reconstruction and diffusion-based generation.

        [Paper](https://arxiv.org/abs/2605.22777) · [Code](https://github.com/Tianhang-Wang/DecQ)

        ### Channel-wise Vector Quantization: Native 1D Visual Tokenization with Learnable Ordering

        Wei Song\*, **Tianhang Wang**\*, Yitong Chen, Tong Zhang, Zuxuan Wu, Min Li, Jiaqi Wang, Kaicheng Yu.

        **NeurIPS 2026 (accepted)** · Co-first author, listed second.

        Channel-wise visual tokens learn a coarse-to-fine ordering for autoregressive image generation through next-channel prediction.

        [Paper](https://arxiv.org/abs/2605.26089) · [Code](https://github.com/songweii/CVQ)
    design:
      columns: "1"
---
