# Geometry Optimization with Machine Learning and Adsorption Site Clustering in Molecular Simulation
This repository contains code to run ML-based geometry optimizations in molecular simulation, as well as using clustering methods to characterize adsorption site space. Both components of the project are available as [Google Colab](https://colab.research.google.com/) notebooks to make installation of software dependencies and code usage easier. Our code makes use of a [Behler-Parrinello](https://doi.org/10.1063/1.3553717) fingerprint module written in C++ from the [SIMPLE-NN package](https://github.com/MDIL-SNU/SIMPLE-NN), with most ```utils``` scripts being from or modified from [Simple-NN-BP-FP](https://github.com/yilinyang1/Simple-NN-BP-FP). 

## Active Learning-based Geometry Optimization (Google Colab Notebook)
<div align="center">
<img src="https://github.com/ojimenezn/optim-clustering/blob/master/images/al-relax.png" alt="logo"></img>
</div>

The above workflow from our [recently published work](https://doi.org/10.1063/5.0049665) is essentially identical to the one available in the Colab notebook, with the only exception that the latter uses an [Effective Medium Theory (EMT)](https://doi.org/10.1119/1.12734) potential in place of computationally expensive quantum chemical (DFT) calculations (most DFT engines are also not open source). 

## Adsorption Site Clustering with U-Map (Google Colab Notebook)
<div align="center">
<img src="https://github.com/ojimenezn/optim-clustering/blob/master/images/clustering.png" alt="logo"></img>
</div>

## Citing
If you find this code or work useful in any way, please go to [repo](https://github.com/yilinyang1/NN-ensemble-relaxer) for more detailed information and consider citing our paper:
```
@Article{citekey,
  author  = "Yilin Yang and Omar A. Jiménez-Negrón and John R. Kitchin",
  title   = "Machine-learning accelerated geometry optimization in molecular simulation",
  journal = "Journal of Chemical Physics",
  year    = "2021",
}
```
