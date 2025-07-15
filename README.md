# Generative AI
## What is Generative AI?
Generative AI refers to a class of artificial intelligence algorithms that possess the remarkable ability to generate new, realistic data that wasn't part of the original dataset. This stands in contrast to discriminative models, which  are primarily focused on categorizing and classifying existing data.

In Mathematics, these algorithms can learn the underlying probability distribution of a dataset and create new data smaples the resemble the orginal data.

<img width="747" height="384" alt="image" src="https://github.com/user-attachments/assets/9c4d44a0-3f6d-4108-bfb8-a34fdcdbea4c" />

## Types of Generative AI Algorithms
## 1. Generative Adversarial Networks (GANs) :
GANs are arguably the most well-known and widely used type of generative model. They consist of a generator network that are trained simultaneously through adversarial training.
   Adversial means, it means to oppose each other, so Adversarial training is a method used to improve the robustness and generalization of neural networks by incorporating adversarial or opposing examples that can contradict each other so that model can learn better.
<img width="712" height="406" alt="image" src="https://github.com/user-attachments/assets/f7c15f4b-44ca-428b-926e-a5b099ce70ef" />

The geneator aims to create realistic data, while the discriminator's role is to distinguish between real and generated data. This dynamic creates a competitive process that ultimately results in the generation of highly convincing synthetic content.
<img width="1087" height="442" alt="image" src="https://github.com/user-attachments/assets/b94bb33a-5851-41ee-8578-cbccd2d0aacb" />


## GANs Architecture 
GANs consist of two neural networks - a generator and a discriminator- that are trained simultaneously through adversarial training. The generator creates synthetic data, and the discriminator tries to distinguish between real and generated data. This adversarial process leads to the improvement of both networks over time.

## GANs Training Methodology
GANs use adversarial training, where the generator and discriminator networks are in a constant competition. The generator aims to generate data that is indistinguishable from real data, while the discriminator aims to become better at distinguishing between real and generated data.

## Latent Space Representation
GANs are do not explicitly define a structure latent space. The latent space in GANs is typically considered as a byproduct of the adversarial training process, and it may not have a clear interpretability.

## Application of GANs 
GANs are widely used in tasks such as image-to-image translation, style transfer, and the generation of realistic images, videos, or even text. They are also employed in the creation of deepfake content.





## 2. Variational Autoencoders (VAEs) :
VAEs take a probabilistic approach to generative modelling. They learn the underlying distribution of the data and use it to generate new samples. VAEs are characterized by an encoder-decoder architecture, where the decoder samples from this distribution to generate new data.
   <img width="673" height="551" alt="image" src="https://github.com/user-attachments/assets/791c4ff6-e451-438a-a735-9851ac2092aa" />

   VAEs have been applied in image generation, where they excel in capturing the latent space of images and creating diverse, high-quality samples.
   Other Applications include anomaly detection (e.g., detecting unusual patterns in financial transactions), text to image synthesis (e.g., generating images from text descriptions), and drug discovery (e.g., generating new molecules with desired properties).
   <img width="748" height="230" alt="image" src="https://github.com/user-attachments/assets/7967e3ce-c245-496e-bddb-e7aa05c43a44" />


## VAEs Architecture
VAEs have an encoder-decoder architecture. The encoder maps input data to a probabilistic distribution in a latent space, and the decoder samples from this distribution to generate new data. VAEs focus on learning the underlying probabilistic structure of the data.

## VAEs Training Methodology
VAEs use a probabilistic approach. During training, VAEs maximize the likelihood of generating the input data while ensuring that the learned latent space follows a specific probabilistic distribution (Usually Gaussian).

## Latent Space Representation
VAEs explicitly model a latent space with a well-defined structure. The encoder maps input data to a distribution in this latent space, allowing for interpolation and manipolation of the latent representations.

## Application of VAEs
VAEs find applications in tasks where a structured latent space is beneficial, such as image geneartion, variational image synthesis, and data augmentation in healthcare applications.
