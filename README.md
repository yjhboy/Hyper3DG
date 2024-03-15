<div align="center">

# Hyper-3DG:<br> Text-to-3D Gaussian Generation via Hypergraph
<!-- ##### Authors: Donglin Di, Jiahui Yang, Chaofan Luo, Zhou Xue, Wei Chen, Xun Yang, Yue Gao
##### Affiliations: Li Auto Space AI, School of Software (Tsinghua University), School of Information Science and Technology (University of Science and Technology of China), Harbin Institute of Technology -->
#### [Full Paper](https://arxiv.org/abs/2403.09236)

**Hyper-3DG pioneers a novel framework for text-to-3D generation that seamlessly integrates hypergraph learning with 3D Gaussian splatting, achieving high-fidelity and structurally coherent 3D models from textual descriptions without compromising computational efficiency.**

**Hyper-3DG将超图学习与3D高斯飞溅无缝集成，提供了文本到3D生成的优化接口，在占用小显存的情况下，缓解了文生3D中的过度平滑、空间结构不连贯、Janus Problem等问题。**
</div>



**Abstract:** *Text-to-3D generation represents an exciting field that has seen rapid advancements, facilitating the transformation of textual descriptions into detailed 3D models. However, current progress often neglects the intricate high-order correlation of geometry and texture within 3D objects, leading to challenges such as over-smoothness, over-saturation and the Janus problem. In this work, we propose a method named “3D Gaussian Generation via Hypergraph (Hyper-3DG)”, designed to capture the sophisticated high-order correlations present within 3D objects. Our framework is anchored by a well-established mainflow and an essential module, named “Geometry and Texture Hypergraph Refiner (HGRefiner)”. This module not only refines the representation of 3D Gaussians but also accelerates the update process of these 3D Gaussians by conducting the Patch-3DGS Hypergraph Learning on both explicit attributes and latent visual features. Our framework allows for the production of finely generated 3D objects within a cohesive optimization, effectively circumventing degradation. Extensive experimentation has shown that our proposed method significantly enhances the quality of 3D generation while incurring no additional computational overhead for the underlying framework.*
## Framework
![Hyper-3DG framework](contents/fig_framework.png)

## Video results
#### A DSLR Photo of a bald eagle
![A DSLR Photo of a bald eagle](./contents/a_bald_eagle.gif)
#### A DSLR Photo of a bloody lion with sharp tooth
![A DSLR Photo of a bloody lion with sharp tooth](./contents/a_bloody_lion_with_sharp_tooth.gif)
#### A pair of green headphones
![A pair of green headphones](./contents/a_pair_of_green_headphones.gif)
#### A cat wearing armor
![A cat wearing armor](./contents/a_cat_wearing_armor.gif)
#### A DSLR photo of a handbag
![A DSLR photo of a handbag](./contents/a_handbag.gif)
#### A DSLR photo of a pink luxury family SUV
![A DSLR photo of a pink luxury family SUV](./contents/a_pink_suv.gif)
#### A sleek cyberpunk fighter jet adorned with neon lights and chrome plating, ultra realistic, 8k, HD
![A sleek cyberpunk fighter jet adorned with neon lights and chrome plating, ultra realistic, 8k, HD](./contents/a_sleek_fighter.gif)
#### a steam engine train, high resolution
![a steam engine train, high resolution](./contents/a_steam_train.gif)
#### An apple
![An apple](./contents/an_apple.gif)
#### flamethrower, with fire, scifi, cyberpunk, photorealistic, 8K, HD
![flamethrower, with fire, scifi, cyberpunk, photorealistic, 8K, HD](./contents/a_flamethrower.gif)



<!-- 
<video controls> <source src="contents/a_bald_eagle.mp4" type="video/mp4"> NO! </video> -->

# Citation
```shell
@misc{di2024hyper3dg,
      title={Hyper-3DG: Text-to-3D Gaussian Generation via Hypergraph}, 
      author={Donglin Di and Jiahui Yang and Chaofan Luo and Zhou Xue and Wei Chen and Xun Yang and Yue Gao},
      year={2024},
      eprint={2403.09236},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```