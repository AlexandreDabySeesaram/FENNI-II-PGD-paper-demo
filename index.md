# Welcome to [Daby-Seesaram, Škardová, Genet,  Submitted]'s demos!

<!-- [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.13785982.svg)](https://doi.org/10.5281/zenodo.13785982) -->

* These demos are based on the [NeuROM-py code](https://pypi.org/project/NeuROM-Py/) version 3.1.21 [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14218478.svg)](https://doi.org/10.5281/zenodo.14218478) and allow reproducing most figures of our paper [Daby-Seesaram, Škardová, Genet, Submitted].
* The notebooks can be executed online with binder [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/AlexandreDabySeesaram/nn-pgd-demos/main?urlpath=lab/tree/./demos/) (no download required).

## Hybridising standard reduced-order modelling methods with interpretable sparse neural networks

This work proposes hybridising classical model-order reduction methods with machine learning capabilities to provide real-time solutions to mechanics problem. 

Analogous to techniques like the Proper Generalised Decomposition (PGD) or the Higher Order Singular Value Decomposition (HOSVD), the parametric mechanical field is represented through a tensor decomposition, effectively mitigating the curse of dimensionality associated with numerous parameters. Each mode of the tensor decomposition is given by the output of a sparse neural network within the HiDeNN framework, constraining the weights and biases to emulate classical shape functions used in the Finite Element Method.
