# Notes from 37C3 workshop "Trust me I don't know: Neural network uncertainty methods meetup"

https://events.ccc.de/congress/2023/hub/event/trust-me-i-dont-know-neural-network-uncertainty-me/

organized by [elcorto](https://github.com/elcorto)

## List of papers

### General UQ

* [A Survey of Uncertainty in Deep Neural Networks](http://arxiv.org/abs/2107.03342)

Bayesian-based

* [The infamous "Deep Ensemble paper"](https://proceedings.neurips.cc/paper/2017/hash/9ef2ed4b7fd2c810847ffa5fa85bce38-Abstract.html)
* [Dropout paper](https://dl.acm.org/doi/10.5555/3045390.3045502)
* [Laplace Redux](https://arxiv.org/abs/2106.14806)
* Spectral-normalized Neural Gaussian Process (SNGP)
  * [arxiv version](https://arxiv.org/abs/2205.00403)
  * [journal version](https://jmlr.org/papers/v24/22-0479.html)

Conformal Prediction

* [MAPIE](https://github.com/scikit-learn-contrib/MAPIE): Conformal prediction with sklearn
  API, [no multi-variate
  regression supported so far (2023-12)](https://github.com/scikit-learn-contrib/MAPIE/issues/97)

### Related to language models

* [Semantic Uncertainty: Linguistic Invariances for Uncertainty Estimation in
  Natural Language Generation](https://arxiv.org/abs/2302.09664) --
  unsupervised method out of Yarin Gal's group
* [Teaching Models to Express Their Uncertainty in
  Words](https://arxiv.org/abs/2205.14334) -- supervised fine-tuning method by OpenAI
* [Do Androids Know They're Only Dreaming of Electric
  Sheep?](https://arxiv.org/abs/2312.17249)
* [Language Models (Mostly) Know What They
  Know](https://arxiv.org/abs/2207.05221) -- huge author list, all of them from Anthropic
* [LM-Polygraph: Uncertainty Estimation for Language
  Models](https://arxiv.org/abs/2311.07383)

Further material re. LM hallucination mitigation techniques

* <https://mastodon.social/@HPC_Guru/111724299897994609> -> https://www.fastcompany.com/91006321/how-ai-companies-are-trying-to-solve-the-llm-hallucination-problem
  * https://github.com/vectara/hallucination-leaderboard
  * [A Comprehensive Survey of Hallucination Mitigation Techniques in Large
    Language Models](https://arxiv.org/abs/2401.01313)

## Other

* Resource about Gaussian Processes: https://github.com/elcorto/gp_playground
* Calibration for regression, lots of literature refs: https://github.com/uncertainty-toolbox/uncertainty-toolbox
* [Baba Brinkman - Good Bayesian](https://youtu.be/qV6Wc_f1Cgo)
