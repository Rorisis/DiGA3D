# 🪄DiGA3D: Coarse-to-Fine Diffusional Propagation of Geometry and Appearance for Versatile 3D Inpainting

>### [Project Page](https://rorisis.github.io/DiGA3D/) | [Arxiv](https://arxiv.org/abs/num)
> 
> [Jingyi Pan](http://scholar.google.com/citations?user=H_oIKS8AAAAJ&hl=zh-CN)<sup>1</sup>, [Dan Xu](https://www.danxurgb.net/)<sup>2</sup>, [Qiong Luo](https://www.cse.ust.hk/~luo/)<sup>1,2</sup> <br>
> <sup>1</sup>The Hong Kong University of Science and Technology (Guangzhou)<br>
> <sup>2</sup>The Hong Kong University of Science and Technology<br>
>
> ICCV 2025
> 

<div align=center>
<img src="docs/static/images/framework.png" width="100%"/>
</div>

## TL;DR:
We introduce <b>DiGA3D</b>, a novel and versatile 3D inpainting pipeline that leverages diffusion models to propagate consistent appearance and geometry in a coarse-to-fine manner. First, DiGA3D develops a robust strategy for selecting multiple reference views to reduce errors during propagation. Next, DiGA3D designs an Attention Feature Propagation (AFP) mechanism that propagates attention features from the selected reference views to other views via diffusion models to maintain appearance consistency. Furthermore, DiGA3D introduces a Texture-Geometry Score Distillation Sampling (TG-SDS) loss to further improve the geometric consistency of inpainted 3D scenes.
Extensive experiments on multiple 3D inpainting tasks demonstrate the effectiveness of our method. 

## To-Do

- [ ] Release paper.
- [ ] Release code.
- [ ] Release test samples.

Codes will be released. Please stay tuned :D

## 📍Citation
If you find our paper or code useful in your research, please consider giving a star and citation.
```
@inproceedings{pan2025diga3d,
    title={DiGA3D: Coarse-to-Fine Diffusional Propagation of Geometry and Appearance for Versatile 3D Inpainting},
    author={Pan, Jingyi and Xu, Dan and Luo, Qiong},
    booktitle={Proceedings of the IEEE/CVF International Conference on Computer Vision},
    year={2025}
    }
```