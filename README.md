# StochasticScreenSpaceReflection

Please note, this was a learning experience and is not in a usuable state. Some of the projection matrixes are wrong, but are fixable if desired / requested.

![SSSR](https://dl.dropboxusercontent.com/u/1812933/Unity/SSSR.png)

# Features

* Contact hardening
* Specular elongation
* Sharp and blurry reflection
* Per-pixel roughness and normal
* Previous frame reprojection giving one free bounce reflection.
* Convolved scene buffer mip chain.

# Requirements

Unity 2017.1 and a shader model 5.0 ( dx11 ) graphic card.

# How to use

Set project to Linear color space and deferred shading.

Then select your main camera and go to "cCharkes/Image Effects/Rendering/Stochastic Screen Space Reflection" or drag and drop the StochasticSSR.cs to your main camera inspector.

# References
- [Jimenez 2014] "Next Generation Post Processing In Call Of Duty Advanced Warfare"  
- [Michal Valient, Siggraph14] "Reflections and Volumetrics of Killzone Shadow Fall"
- [Tomasz Stachowiak and Yasin Uludag, Siggraph15] "Stochastic Screen-Space Reflections"
- [Michele Giacolone, 2016] "Screen Space Reflections in The Surge"
- Lasse Jon Fuglsang Pedersen <lasse@playdead.com>  https://github.com/playdeadgames/temporal
- Bart Wronski <@BartWronsk> https://github.com/bartwronski/BlueNoiseGenerator/

Thanks to Tomasz Stachowiak (@h3r2tic) for his help.
