# Introduction

This repository contains code to reproduce experiments reported in the paper "Leveraging Citizen Science and Low Cost Recorders for Acoustic Monitoring of Bird Species: A Case Study in Kenya" by Ciira wa Maina. The aim of the work is to investigate the use of acoustic models trained using data obtained from citizen scientists in automatic bird species recognition. We use data from the citizen science website [Xeno Canto](http://www.xeno-canto.org/) to train models for bird species recognition and test these models on data collected at the [Dedan Kimathi University of Technology](https://www.dkut.ac.ke/) [wildlife conservancy](https://conservancy.dkut.ac.ke/).

These audio data were collected using a low cost Raspberry Pi based recorder and are available on [Data Dryad]( http://dx.doi.org/10.5061/dryad.69g60). The recordings are described in the paper ["A Bioacoustic Record of a Conservancy in the Mount Kenya Ecosystem."](https://bdj.pensoft.net/articles.php?id=9906)


## Citation
```
@article{wamaina_2018,
  title={{Leveraging Citizen Science and Low Cost Recorders for Acoustic Monitoring of Bird Species: A Case Study in Kenya}},
  author={wa Maina, Ciira },
}
```

# Requirements and Dependencies
* Python 3
* numpy, matplotlib, scipy
* [librosa](https://github.com/librosa/librosa)
* [scikit-learn](http://scikit-learn.org/stable/)
* [pandas](https://pandas.pydata.org/)
* [jupyter notebook](http://jupyter.org/)
