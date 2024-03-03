# GANs and Diffusion Models

#### Examples of Generative Models
* Generative Adversarial Networks (GANs)
* Denoising Diffusion Probabilistic Models (DDPMs)

#### Generative Adversarial Networks
* Generative model for generating realistic images
* Comprises of two neural networks which are competing with one another to win a zero-sum game i.e., adversaries
* A generator to generate images, discriminator to determine whether images are fake or real
* Proposed by Ian Goodfellow et al, 2014, [paper](https://arxiv.org/pdf/1406.2661.pdf)

#### Denoising Diffusuon Probabilistic Models 
* Generative model for high-quality image synthesis
* Forward diffusion process incrementally adds noise to an image
* Neural Network approximates reverse diffusion process which removes noise to generate image
* Original [paper](https://arxiv.org/pdf/2006.11239.pdf) by Jonathan Ho et al.

NOTE: *GANs* and *DDFMs* both are **Unsupervised learning** techniques.