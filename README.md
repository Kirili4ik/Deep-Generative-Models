# Deep Generative Models
Deep Generative Models that I have implemented, trained and experimented with.

Each directory is an independent project and repository. This repo is just a hub for them, but there are small descriptions and samples:

<details>
  <summary><b>Pix2Pix</b>
  </summary>
  The task is to translate picture to a different modality (e.g. day photo to night one) using conditional GAN. Results:
  <img src="https://github.com/Kirili4ik/pix2pix-pytorch/blob/main/Experiments/facades.png">
</details>

<details>
  <summary><b>StarGAN</b>
  </summary>
  This repository is an implementation of model described in <a href="https://arxiv.org/pdf/1711.09020v3.pdf">StarGAN: Unified Generative Adversarial Networks for Multi-Domain Image-to-Image Translation</a>. Results:
  <img src="https://github.com/Kirili4ik/StarGAN/blob/main/samples_base.png">
</details>

<details>
  <summary><b>Experimenting w/ GLOW model</b>
  </summary>
  The main experiment is described in <a href="https://arxiv.org/abs/2006.08545">Why Normalizing Flows Fail to Detect Out-of-Distribution Data</a>. For OOD SVHN dataset is used. 
  <img src="https://github.com/Kirili4ik/Glow-PyTorch/blob/main/pictures/distributions.png">
  <br>
  The graph shows that flows are biased towards learning graphical properties of the data such as local pixel correlations (e.g. nearby pixels usually have similar colors) rather than semantic properties of the data (e.g. what objects are shown in the image). 
  <br>
  Quality results can be found in the GLOW repository.
</details>

<details>
  <summary><b>VAE</b>
  </summary>
  Original VAE implementation. Results:
  <img src="https://github.com/Kirili4ik/VAE-PyTorch/blob/main/image.png">
</details>
