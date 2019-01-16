# Correlated Ellipses Dataset

This repository contains the Correlated Ellipses dataset which can be used for testing disentanglement performance in the case when the factors of variation are not independent of each other.

This dataset was used in our paper [Hyperprior Induced Unsupervised Disentanglement of Latent Representations](https://arxiv.org/abs/1809.04497).

### Usage 

Please check the `Example.ipynb` notebook which contains example code for sampling and conditional sampling from the dataset. Please note that the provided `synthetic.py` file is required for conditional sampling because it generates new samples on the fly. `synthetic.py` has the following requirements: 

* OpenCV
* Numpy
* Matplotlib

If you use this dataset, please consider citing.

```
@inproceedings{ansari2019hyperprior,
  title={Hyperprior Induced Unsupervised Disentanglement of Latent Representations},
  author={Ansari, Abdul Fatir and Soh, Harold},
  booktitle={AAAI Conference on Artificial Intelligence},
  year={2019}
}
```


