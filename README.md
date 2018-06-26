
#### Image compressive sensing recovery using adaptively learned sparsifying basis via L0 minimization (SP 2014) [[pdf]](http://jianzhang.tech/papers/SP2013.pdf)

## Introduction
From many fewer acquired measurements than suggested by the Nyquist sampling theory, compressive sensing (CS) theory demonstrates that, a signal can be reconstructed with high probability when it exhibits sparsity in some domain. Most of the conventional CS recovery approaches, however, exploited a set of fixed bases (e.g. DCT, wavelet and gradient domain) for the entirety of a signal, which are irrespective of the non-stationarity of natural signals and cannot achieve high enough degree of sparsity, thus resulting in poor CS recovery performance. In this paper, we propose a new framework for image compressive sensing recovery using adaptively learned sparsifying basis via L0 minimization. The intrinsic sparsity of natural images is enforced substantially by sparsely representing overlapped image patches using the adaptively learned sparsifying basis in the form of L0 norm, greatly reducing blocking artifacts and confining the CS solution space. To make our proposed scheme tractable and robust, a split Bregman iteration based technique is developed to solve the non-convex L0 minimization problem efficiently. Experimental results on a wide range of natural images for CS recovery have shown that our proposed algorithm achieves significant performance improvements over many current state-of-the-art schemes and exhibits good convergence property.

## Citation
If you find our code helpful in your resarch or work, please cite our paper.
```
@article{zhang2014image,
  title={Image compressive sensing recovery using adaptively learned sparsifying basis via L0 minimization},
  author={Zhang, Jian and Zhao, Chen and Zhao, Debin and Gao, Wen},
  journal={Signal Processing},
  volume={103},
  pages={114--126},
  year={2014},
  publisher={Elsevier}
}
```
