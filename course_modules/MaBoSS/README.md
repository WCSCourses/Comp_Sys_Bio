# CoLoMoTo Notebook and MaBoSS Practicals

## MaBoSS Introduction

The slides of the introduction lecture are available [here](https://github.com/WCSCourses/CompSysBio24/blob/main/Modules/MaBoSS/slides.pdf).

## Using MaBoSS with WebMaBoSS

This first practical uses WebMaBoSS, the web interface for MaBoSS, accessible at https://maboss.curie.fr/WebMaBoSS.

A brief description of the graphical interface, as well as the different exercises are available in [These slides](https://github.com/WCSCourses/CompSysBio24/blob/main/Modules/MaBoSS/webmaboss.pdf).

The model to be simulated is composed of a BND file (model) and a CFG file (config), and will need to be loaded via the web interface.
- [metastasis.bnd](https://github.com/WCSCourses/CompSysBio24/blob/main/Modules/MaBoSS/models/metastasis.bnd)
- [metastasis.cfg](https://github.com/WCSCourses/CompSysBio24/blob/main/Modules/MaBoSS/models/metastasis.cfg)


## Using MaBoSS with pyMaBoSS via CoLoMoTo jupyter notebook

This first practical uses pyMaBoSS, the python library of MaBoSS, accessible in the CoLoMoTo jupyter notebook.

A brief description of library, as well as the different exercises are available in [These slides](https://github.com/WCSCourses/CompSysBio24/blob/main/Modules/MaBoSS/pymaboss.pdf).

To load the notebook, run : 
```
   cd ~/CompSysBio24/Modules/MaBoSS
   colomoto-docker -V next --bind . 
```
