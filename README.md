# WHEN NOISE MEETS CHAOS: STOCHASTIC RESONANCE IN NEUROCHAOS LEARNING

Inspired by the chaotic firing of neurons and the constructive use of noise in neuronal models, we for the first time connect chaos, noise and learning (classification). In this paper, we show the Stochastic Resonance (SR) phenomenon shown by an instance of Neurochaos Learning (NL) algorithm namely \verb+ChaosNet+. We show empirical evidence of SR exhibited at the level of individual neurons, at the level of layer of neurons in the \verb+ChaosNet+ architecture. In the presence of optimum amount of noise \verb+ChaosNet+ provides the peak performance for classification and signal detection. We use macro F1-score  and cross correlation coefficient ($\rho$) computed for various noise intensities as measure to quantify SR exhibited in \verb+ChaosNet+.

[Video explanation on YouTube](https://www.youtube.com/watch?v=8JQstLi4COk) on the usage of chaotic maps as feature extraction and highlighting chief ideas and inspiration.

**Reference Paper:**

1. Balakrishnan, Harikrishnan Nellippallil, et al. "ChaosNet: A chaos based artificial neural network architecture for classification." Chaos: An Interdisciplinary Journal of Nonlinear Science 29.11 (2019): 113125.

2. Harikrishnan, N. B., and Nithin Nagaraj. "Neurochaos Inspired Hybrid Machine Learning Architecture for Classification." 2020 International Conference on Signal Processing and Communications (SPCOM). IEEE, 2020.

# Dependencies

 - `Python 3`
 - `Numpy`
 - `Numba`

# Installation

 - Presently unpackaged
 - Up-to-date conda environment with dependencies installed
 - `git clone` into a working directory

# Usage

 - Please check out `demo.py` to see ChaosFEX in action

# TODO

 - Add Jupyter notebook for detailed demo of trajectory & transformations
 - Examples for showcasing performance as a kernel trick with SVC
 - Integrate with `scikit-learn`
 - Add tests and logging
 - Packaging for PyPI


# License

Copyright 2020 Harikrishnan N. B., and Nithin Nagaraj

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
