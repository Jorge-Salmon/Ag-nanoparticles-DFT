# Ag-nanoparticles-DFT
Keywords: DFT, Machine Learning, Physics, Nanoparticles, Materials Science.

## Introduction

Density functional theory (DFT) is a computational quantum mechanical modelling method used in physics, chemistry and materials science to investigate the electronic structure (or nuclear structure) of many-body systems, in particular atoms, molecules, and the condensed phases. Using this theory, the properties of a many-electron system can be determined by using functionals, i.e. functions of another function, which in this case is the spatially dependent electron density. Hence the name density functional theory comes from the use of functionals of the electron density. 

## The problem

Despite of being a powerful tool, DFT has a series of drawbacks and limitations. One of many is the computational limitations when it comes to calculating systems made up of hundreds of atoms. Supercomputers are needed to treat up to thousands of atoms in DFT. 

## The solution

One of the potential solutions to this problem is using Machine Learning methods to estimate values of the properties of many-atoms systems, without having run a DFT calculation. Here, I use Random Forest Regression to predict the value of Formation Energy of 277 Ag nanoparticles of different sizes, with up to ~3000 atoms.  For this, a training dataset with DFT parameters of 148 Ag nanoparticles was used. The original dataset, comprised of 425 Ag nanoparticles was calculated by Amanda Barnard et al. (Barnard, Amanda; Sun, Baichuan; Motevalli Soumehsaraei, Benyamin; Opletal, George (2017): Silver Nanoparticle Data Set. v3. CSIRO. Data Collection. https://doi.org/10.25919/5d22d20bc543e).

