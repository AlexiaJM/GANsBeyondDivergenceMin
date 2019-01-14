# GANsBeyondDivergenceMin

I wrote the paper "GANs beyond divergence minimization" (http://arxiv.org/abs/1809.02145) a month before the paper "The relativistic discriminator: a key element missing from standard GAN" (https://arxiv.org/abs/1807.00734), more precisely on May 15th 2018. I did not release it on ArXiv until now because it was under anonymous reviews. Sadly, it was rejected by NIPS2018 because of the lack of extensive experiments (I only looked at CIFAR-10 and a toy example).

In retrospect, I would have calculated the FID using Tensorflow (as done in the Relativistic GAN paper) rather than PyTorch to get values that can be comparable to other papers. I also would have run more experiments with different datasets. However, my computing power is extremely limited, and it is very demanding for me to train models (every night I have to reboot my computer on Linux, train some models for the night, stop training in the morning, keep track of what I did, and reboot on Windows). I also have new projects I am more interested in pursuing. Therefore, I am not planning to redo the analyses with Tensorflow FID and to add more experiments with these alternative loss functions. I leave this code for those who would like to try the different generator loss functions proposed in the paper. This is simply the code from https://github.com/AlexiaJM/RelativisticGAN, but with the additional generator loss functions.

See more details on the paper here: https://ajolicoeur.wordpress.com/gans-beyond-divergence-minimization/

## Citation

If you find this code useful please cite us in your work:
```
@article{jolicoeur2018gans,
  title={GANs beyond divergence minimization},
  author={Jolicoeur-Martineau, Alexia},
  journal={arXiv preprint arXiv:1809.02145},
  year={2018}
}
```
