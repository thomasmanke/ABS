[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thomasmanke/ABS.git/HEAD)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/thomasmanke/ABS/)

# **Applied Biostatistics (ABS)**
Author: Thomas Manke
 

Training material and notebooks for the Applied Biostatistics Course.

It covers three larger blocks

* Markov Chains: Notebooks/MarkovChains/*
* Hidden Markov Models: Notebooks/HiddenMarkovChains/*
* Artifical Neural Networks: Notebooks/ANN/_*

The material was originally developed for the CQ Training Programme.

If jupyter-book is installed a book can be build using
> jupyter-book build .

Notice that the timeout was set to 200s (_config.yml).
This long time was required for the more expensive tensorflow parts to finish on a modern laptop.

```{tableofcontents}
```