---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

The latent space of a VAE extracts salient factors of variation in the data, such as timbre properties, and can be inverted to audio. These latent variables can be used as sound synthesis controls, however they are highly-dimensional and usually not disentangled. This precludes intuitive interactions and identification of the dimensions that account for some specific sound properties. We explore the potential of VAEs for controllable timbre synthesis and creative interactions using two types of representation.

One model learns a continuous latent representation (see [this page](/continuous)), it allows interpolations and expressive manipulations based on specifically designed interactive interfaces (Max/MSP, PureData).

Another model learns a discrete latent representation (see [this page](/discrete)), this constraint allows a direct identification of the acoustic properties of each short-term latent feature and explicit descriptor-based synthesis.

In this paper, we propose new methods for exploring latent synthesis of musical timbre using these two representations and report creative applications led in cooperation with two music composers (see [this page](/creative)).

## References

 1. **[Engel et al., 2017]** Neural Audio Synthesis of Musical Notes with WaveNet Autoencoders. International Conference on Machine Learning, 2017.
 2. **[Kingma and Welling, 2014]** Auto-Encoding Variational Bayes. International Conference on Learning Representations, 2014.
 3. **[Higgins et al., 2017]** beta-vae: Learning basic visual concepts with a constrained variational framework. International Conference on Learning Representations, 2017.
 4. **[Esling et al., 2018]** Generative timbre spaces with variational audio synthesis. In Proceedings of the International Conference on Digital Audio Effects, 2018.
 5. **[Bitton et al., 2019]** Assisted Sound Sample Generation with Musical Conditioning in Adversarial Auto-Encoders. In Proceedings of the International Conference on Digital Audio Effects, 2019.
 6. **[Oord et al., 2018]** Neural Discrete Representation Learning. In Advances in Neural Information Processing Systems, pages 6306–6315, 2017.
