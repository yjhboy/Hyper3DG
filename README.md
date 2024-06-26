<div align="center">

# Hyper-3DG:<br> Text-to-3D Gaussian Generation via Hypergraph

<p align="center">
<a href="https://arxiv.org/abs/2403.09236"><img src="https://img.shields.io/badge/Arxiv-2403.09236-B31B1B.svg"></a>
</p>


**Hyper-3DG pioneers a novel framework for text-to-3D generation that seamlessly integrates hypergraph learning with 3D Gaussian splatting, achieving high-fidelity and structurally coherent 3D models from textual descriptions without compromising computational efficiency.**

code coming soon...

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
![](./contents/a_flamethrower.gif)

#### A DSLR photo of a corgi
![](./contents/a_corgi.gif)

#### A classic packard car
![flamethrower, with fire, scifi, cyberpunk, photorealistic, 8K, HD](./contents/a_packard_car.gif)

#### A ceramic lion
https://github.com/yjhboy/Hyper3DG/assets/101305907/0731db49-c0f8-4085-9bf0-ce5d6c6d3bb9

#### a tulip
https://github.com/yjhboy/Hyper3DG/assets/101305907/b57d9e54-030b-43c4-9bf4-398ffbac0fd9

#### an astronaut in sand beach
https://github.com/yjhboy/Hyper3DG/assets/101305907/423b248f-c150-4e9b-a007-510e6feb90fc

#### an ice cream
https://github.com/yjhboy/Hyper3DG/assets/101305907/3048f859-04eb-4b87-91c6-66ab9766b6f1

#### A beagle in a detectives outfit
https://github.com/yjhboy/Hyper3DG/assets/101305907/d25f8f28-f1ea-4b2f-986b-2b4a68c95bc9





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
