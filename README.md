# Physical-Adversarial-Camouflage-Generation-in-Optical-Remote-Sensing-Images
Official Implementation of Physical Adversarial Camouflage Generation in Optical Remote Sensing Images

<div align="center">


![](https://komarev.com/ghpvc/?username=PhysicsAttack&label=visitors)
![GitHub stars](https://badgen.net/github/stars/Arknightpzb/Physical-Adversarial-Camouflage-Generation-in-Optical-Remote-Sensing-Images)
[![](https://img.shields.io/badge/license-MIT-green)](#License)

</div>


## Contributing

This repository mainly provides the camouflage texture generator we used for better reproduction.

We are well aware that the proposed method has some limitations and needs further improvement. We welcome any comments and improvements. Please feel free to send a Pull Request~

## Directory
+ [Abstract](#Abstract)
+ [Updates](#Updates)
+ [Downloads](#Downloads)
## Abstract
Physical adversarial examples in optical remote sensing have garnered significant attention in recent years due to their practicality and high adversarial threat potential. However, existing methods focus on position-fixed adversarial patches, neglecting tailored considerations for the domain-specific texture patterns and mobility required by aerial platforms. To address the issues above, we proposed a novel method of physical adversarial camouflage generation for the first time in optical remote sensing, which paints adversarial camouflage with specialized textures onto the targets to escape detection from DNN-based models. In pursuit of achieving a synthesis of visual harmony and adversarial attack potency, we propose a "latent variable-based" adversarial camouflage generation approach, in which we introduce a texture generator controlled by a group of latent variables to generate camouflage patterns with adversarial properties. By employing this idea, we can constrain the searching domain for adversarial examples to the domain characterized by camouflage exhibiting textures with high visual harmony, and easily focus on finding the most threatening ones during the optimization. We chose airplanes as the object of interest and object detection as the typical reconnaissance method in experiments. Our method achieves high attack success rates (ASRs) against a majority of existing detection models. Comparison with existing pixel-level optimization methods confirms that the integration of a dedicated generator helps solve the trade-off dilemma between visual harmony and adversarial potency. Real-world experiments involving targets painted by our developed adversarial camouflage confirm the adversarial attack potency and practicality, with a more than 50\% increase on average in the ASRs compared to the conventional camouflage.
![](https://github.com/Arknightpzb/Physical-Adversarial-Camouflage-Generation-in-Optical-Remote-Sensing-Images/blob/main/images/painting.jpg)
## Downloads
Generator-StyleGAN3: [Google Drive](https://drive.google.com/file/d/1Zf1G5GizWpE1AcWyLT6A9l9YLegL1TzF/view?usp=sharing).  [Baidu](https://pan.baidu.com/s/10RKW2iiHRAr9KQaKhGTjtg), password: mz48
## Updates
<ul>
<li> **2025-03-19**: Repository was first built. Examples we used were also provided.</li>
<li> **2025-04-04**: The ckpts and usage example (stylegan3test.py) were uploaded. Please refer to these codes for details.</li>
<li> **2025-06-18**: The manuscript has been ACCEPTED for publication as a REGULAR paper in the IEEE Transactions on Information Forensics & Security!!! Welcome to your reading: [10.1109/TIFS.2025.3581771](https://ieeexplore.ieee.org/document/11045780)
</ul>

## Acknowledgment
Thanks [StyleGAN3](https://github.com/NVlabs/stylegan3) for the support.
