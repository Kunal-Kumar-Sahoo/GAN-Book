# Generative Learning Trilemma

1. Models should produce **high-quality samples**
   - Samples from the model should be indistinguishable from the real dataset - should be as realistic as possible
2. Models should have **fast sampling**
   - Samples should be generated fast i.e., generational process should have low computational complexity - this enables interactive real-time applications
3. Models should provide **good diversity** or **mode coverage**
   - The generative model should capture the range and diversity of the input training data
   - GANs generally fail in providing mode coverage

### Mode Coverage

- It's important that generated data faithfully represent the original, especially rare samples
- Long tails of the input distribution often tend to be interesting or important
- Modeling rare scenarios improve the utility of generative models

**Generative models often make trade-offs across these three requirements.**

### GANs

- GANs allow for fast generation of samples and produce very high quality samples
- They often produce only a small number of outputs from the training dataset
- GANs may not capture the diversity and range of the input data

### Generative Learning with Diffusion Models

- A powerful class of generative models have been shown to generate samples of a very high quality with better range and diversity as compared to GANs
- 