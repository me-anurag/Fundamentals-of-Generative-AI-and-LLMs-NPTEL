# Glossary of Key Terms

A running glossary of terms and architectures covered across the course. Add to this as you go through each week.

| Term | Short Definition | Introduced In |
|------|-------------------|----------------|
| Generative AI | Models that learn to generate new data resembling a training distribution | Week 1 |
| CNN | Convolutional Neural Network, used for extracting spatial features from images | Week 1 |
| Autoencoder | A network trained to reconstruct its input through a compressed bottleneck | Week 2 |
| Bottleneck Representation | The compressed latent representation at the center of an autoencoder | Week 2 |
| Denoising Autoencoder | An autoencoder trained to reconstruct clean input from a noisy version | Week 2 |
| VAE | Variational Autoencoder, a generative model with a probabilistic latent space | Week 3 |
| Reparameterization Trick | Technique to backpropagate through random sampling in a VAE | Week 3 |
| ELBO | Evidence Lower Bound, the objective function optimized when training a VAE | Week 3 |
| KL Divergence | A measure of how one probability distribution differs from another | Week 3 |
| Conditional VAE | A VAE that generates outputs conditioned on a class label or attribute | Week 4 |
| Disentanglement | Property where each latent dimension controls a distinct, interpretable factor | Week 4 |
| GAN | Generative Adversarial Network, consisting of a generator and a discriminator trained adversarially | Week 5 |
| Mode Collapse | Failure mode where a GAN generator produces limited variety of outputs | Week 5 |
| DCGAN | A convolutional architecture that stabilizes GAN training for images | Week 5 |
| CycleGAN | A GAN variant for image-to-image translation without paired training data | Week 6 |
| StyleGAN | A GAN architecture that separates style and content for controllable image generation | Week 6 |
| FID | Frechet Inception Distance, a metric for evaluating generated image quality | Week 6 |
| Diffusion Model | A generative model that learns to reverse a gradual noising process | Week 7 |
| Forward Diffusion | The process of gradually adding noise to data over a series of timesteps | Week 7 |
| DDPM | Denoising Diffusion Probabilistic Model, the standard diffusion model framework | Week 8 |
| UNet | A convolutional architecture with skip connections, commonly used for denoising in diffusion models | Week 8 |
| Classifier-Free Guidance | A technique to steer diffusion model generation without a separate classifier | Week 8 |
| LSTM | Long Short-Term Memory network, designed to model long-range dependencies in sequences | Week 9 |
| Transformer | An attention-based architecture that replaced RNNs and LSTMs for sequence modeling | Week 9, Week 10 |
| Self-Attention | Mechanism that lets each token in a sequence attend to every other token | Week 10 |
| Tokenization | Process of splitting text into smaller units (tokens) for model input | Week 10 |
| Prompt Engineering | Practice of designing inputs to guide an LLM toward a desired output | Week 10 |
| RAG | Retrieval-Augmented Generation, combining document retrieval with text generation | Week 11 |
| In-Context Learning | Model learns a task from examples given in the prompt without updating weights | Week 11 |
| LoRA | Low-Rank Adaptation, a parameter-efficient fine-tuning method for large models | Week 11 |
| Hallucination | When a model generates confident but factually incorrect or fabricated output | Week 12 |

Keep updating this table as new terms come up week by week.
