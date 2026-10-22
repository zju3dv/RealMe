<p align="center"><img src="assets/realme-logo.png" alt="RealMe" width="300"></p>

# RealMe: Immersive Volumetric Video from Minimal Captures

[**Chenxu Zhou**<sup>1</sup>](https://zicx.top/) · [**Zhiyuan Yu**<sup>1,†</sup>](https://fishfishson.github.io/) · [**Yudong Jin**<sup>1</sup>](https://krahets.com/) · [**Yinji Shentu**<sup>1</sup>](https://stland-admin.github.io/)<br>
[**Yu Zhang**<sup>2</sup>](https://cn.linkedin.com/in/yu-zhang-4388aa336) · [**Jiaming Sun**<sup>2</sup>](https://jiamingsun.me/) · [**Xiaowei Zhou**<sup>1</sup>](https://xzhou.me/)

<sup>†</sup> Corresponding author

<sup>1</sup> State Key Laboratory of CAD&CG, Zhejiang University · <sup>2</sup> 4DV.ai

**SIGGRAPH Asia 2026 Conference Papers**

[[Paper](https://arxiv.org/abs/2610.30023)] · [[Project Page](https://zju3dv.github.io/realme/)]

![RealMe teaser showing volumetric video results](assets/teaser.webp)

## News

- **2026:** RealMe was accepted to SIGGRAPH Asia 2026. The [paper](https://arxiv.org/abs/2610.30023) and [project page](https://zju3dv.github.io/realme/) are available.

## Method

RealMe creates immersive volumetric video from sparse, low-resolution multi-view captures. It builds a coarse 4D representation and derives auxiliary videos from novel-view renders and input crops. A high-resolution video diffusion model uses these videos to generate 2K, 4D-consistent enhanced views, which are combined with the original captures to refine the final 4D representation.

![RealMe pipeline: auxiliary data construction, video diffusion enhancement, and 4D reconstruction](assets/pipeline.webp)

## Citation

If you use RealMe in your research, please cite:

```bibtex
@inproceedings{zhou2026realme,
  title     = {RealMe: Immersive Volumetric Video from Minimal Captures},
  author    = {Zhou, Chenxu and Yu, Zhiyuan and Jin, Yudong and Shentu, Yinji and Zhang, Yu and Sun, Jiaming and Zhou, Xiaowei},
  booktitle = {SIGGRAPH Asia 2026 Conference Papers},
  year      = {2026},
  doi       = {10.1145/3829340.3842349}
}
```

## Contact

For questions, contact [Chenxu Zhou](mailto:cxzhou35@zju.edu.cn) or open a [GitHub issue](https://github.com/zju3dv/RealMe/issues).
