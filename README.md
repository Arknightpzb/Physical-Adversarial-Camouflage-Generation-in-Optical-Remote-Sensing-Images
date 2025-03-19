# Physical-Adversarial-Camouflage-Generation-in-Optical-Remote-Sensing-Images
Official Implementation of Physical Adversarial Camouflage Generation in Optical Remote Sensing Images

<div align="center">


![](https://komarev.com/ghpvc/?username=PhysicsAttack&label=visitors)
![GitHub stars](https://badgen.net/github/stars/Arknightpzb/Physical-Adversarial-Camouflage-Generation-in-Optical-Remote-Sensing-Images)
[![](https://img.shields.io/badge/license-MIT-green)](#License)

</div>

## Contributing

This repository mainly provides the camouflage texture generator we used for better reproduction.

We are well aware that the proposed method needs further improvement. We welcome your comments and improvements. Please feel free to send a Pull Request~

## Directory
+ [Abstract](#Abstract)
+ [Updates](#Updates)
  
## Abstract
Physical adversarial examples in optical remote sensing have garnered significant attention in recent years due to their practicality and high adversarial threat potential. However, existing methods focus on adversarial patches, lacking the consideration of practical constraints as targets may be of uneven surface or irregularly shaped. To address the issues above, we proposed a novel method of physical adversarial camouflage generation for the first time in optical remote sensing, which paints adversarial camouflage onto the targets to escape detections from DNN-based models. In pursuit of achieving a synthesis of visual harmony and adversarial attack potency, we propose a “latent variable-based” adversarial camouflage generation approach, in which we introduce a texture generator controlled by a group of latent variables to generate camouflage patterns with adversarial properties. By employing this idea, we can constrict the searching domain for adversarial examples to the domain characterized by camouflage exhibiting textures with high visual harmony and easily find the most threatening ones during the optimization. We choose airplanes as the object of interest and choose object detection as the typical reconnaissance method in experiments. Our method achieves high attack success rates (ASRs) against a majority of existing detection models. Real-world experiments involving targets adorned with our developed adversarial camouflage confirm their adversarial attack potency and practicality, with a more than 50\% increase on average in the ASRs compared to the conventional camouflage.

## Updates
<ul>
<li>**2025-03-19**: Repository was first built. Examples we used were also provided.</li>
<li>...(We are about to provide the weights of the generator and related usage code after the paper is accepted.)</li>
</ul>
