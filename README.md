# Master-s-Thesis

The project orbited around information representation at single neuron and network levels, and was divided into two parts. The first part aimed to test whether Acetylcholine's neuromodulation could change the coding properties of single neurons while being stimulated in an in vitro experimental setting. The second part aimed to see how coding properties could arise in network models of neurons (namely the Poisson Balanced Spiking Network) using the same analysis techniques from the first part of the project. 

The experimental data used in the analyses can be found in bit.ly/NeuromodulationDatabase, and further information of the recordings in Yan et al. (2022). In the second part of the thesis I implemented the Poisson Balanced Spiking Network (first explained in Buixó and Pillow (2020)). I have made some modifications of their implementations (which were done in MATLAB), but preserved the core ideas.

In this repository I share the code used for the two parts of the project (single neuron analysis and network modelling):

  - Part 1: Electrophysiological experimental data analysis --> Code to visualize the data and to compute Spike-Triggered Averages (STA).
  
  - Part 2: Network modelling --> Code to implement the Poisson Balanced Spiking Network in several ways and code to visualize the simulations.

If you are interested about the thesis or anything related to it do not hesitate to contact me!

References:

Rullán Buxó, C. E., & Pillow, J. W. (2020). Poisson balanced spiking networks. PLoS computational biology, 16(11), e1008261.

Yan, X., Calcini, N., Safavi, P., Ak, A., Kole, K., Zeldenrust, F., & Celikel, T. (2022). A whole-cell recording database of neuromodulatory action in the adult neocortex. bioRxiv.
