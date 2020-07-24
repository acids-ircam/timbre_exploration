---
layout: home
---

**Website under construction.**

The latent space of a VAE extracts salient factors of variation in the data, such as timbre properties, and can be inverted to audio. These latent variables can be used as sound synthesis controls, however they are highly-dimensional and usually not disentangled. This precludes intuitive interactions and identification of the dimensions that account for some specific sound properties. We explore the potential of VAEs for controllable timbre synthesis and creative interactions using two types of representation.

One model learns a continuous latent representation (see [this page]({{ "continuous" | relative_url }})), it allows interpolations and expressive manipulations based on specifically designed interactive interfaces (Max/MSP, PureData).

Another model learns a discrete latent representation (see [this page]({{ "discrete" | relative_url}})), this constraint allows a direct identification of the acoustic properties of each short-term latent feature and explicit descriptor-based synthesis.

In this paper, we propose new methods for exploring latent synthesis of musical timbre using these two representations and report creative applications led in cooperation with two music composers (see [this page]({{ "creative" | relative_url}})).
