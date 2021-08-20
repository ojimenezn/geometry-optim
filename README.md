# Geometry Optimization with Machine Learning and Adsorption Site Clustering in Molecular Simulation
This repository contains code to run ML-based geometry optimizations in molecular simulation, as well as using clustering methods to characterize adsorption site space. Both components of the project are available as [Google Colab](https://colab.research.google.com/) notebooks to make installation of software dependencies and code usage easier. Our code makes use of a [Behler-Parrinello](https://doi.org/10.1063/1.3553717) fingerprint module written in C++ from the [SIMPLE-NN package](https://github.com/MDIL-SNU/SIMPLE-NN), with most ```utils``` scripts being from or modified from [Simple-NN-BP-FP](https://github.com/yilinyang1/Simple-NN-BP-FP). 

## Active Learning-based Geometry Optimization (Google Colab Notebook)
<div align="center">
<img src="https://raw.githubusercontent.com/ojimenezn/optim-clustering/images/al-relaxation.png" alt="logo"></img>
</div>

## Adsorption Site Clustering with U-Map (Google Colab Notebook)
This

## Citing
If you find this code or work useful in any way, please consider citing our paper:
```
@Article{citekey,
  author  = "Yilin Yang and Omar A. Jiménez-Negrón and John R. Kitchin",
  title   = "Machine-learning accelerated geometry optimization in molecular simulation",
  journal = "Journal of Chemical Physics",
  year    = "2021",
}
```
