# VPMR package for SOE and SOG
We release the package for approximating non-singular kernel functions by `sum-of-exponentials` (SOE) or `sum-of-Gaussians` (SOG) by VP sum and model reduction.

This is a joint work with Ph.d candidate [Z. Gao](https://github.com/ZXGao97/) who is my partner in [Prof. Xu's group](http://math.sjtu.edu.cn/faculty/xuzl/). 
The original MATLAB codes are developed by me and Z. Gao. Zixuan Gao produces the graphical user interface (GUI) in MATLAB.

The underviewed paper of SOG can be found at [J.Liang, Z.Gao, Z.Xu, A Kernel-independent Sum-of-Gaussians method by de la Vallée-Poussion
sums,arXiv:2010.05192](https://arxiv.org/abs/2010.05192).

The underviewed paper of SOE can be found at [Z.Gao, J.Liang, Z.Xu, A Kernel-Independent Sum-of-Exponentials Method and Its Application to Convolution Quadrature, arXiv:2012.13477](https://arxiv.org/abs/2012.13477). 

VPMR used the technical support of Multiprecision Computing Toolbox produced by Advanpix company. Users can download Trail and know more about the toolbox from this [website](www.advanpix.com) (software probation period is allowed for one week).

For more details of the usage, please refer to [Readme.pdf](https://github.com/LiangJiuyang/VPMR/blob/main/Readme.pdf).

If you have any questions, please contact me or Z. Gao (both Chinese and English are OK). 
```
My email address : liangjiuyang@sjtu.edu.cn
Z. Gao's email address : 1270157606gzx@sjtu.edu.cn
```
Good luck to all of you!

## Introduction of VPMR for [SOE](https://arxiv.org/abs/2012.13477) and [SOG](https://arxiv.org/abs/2010.05192)
We propose an accurate algorithm for a novel sum-of-exponentials (SOE) approximation of kernel functions, and develop a fast algorithm for convolution quadrature based on the SOE, which allows an order N calculation for N time steps of approximating a continuous temporal convolution integral. The SOE method is constructed by a combination of the de la Vallée-Poussin sums for a semi-analytical exponential expansion of a general kernel, and a model reduction technique for the minimization of the number of exponentials under given error tolerance. We employ the SOE expansion for the finite part of the splitting convolution kernel such that the convolution integral can be solved as a system of ordinary differential equations due to the exponential kernels. The remaining part is explicitly approximated by employing the generalized Taylor expansion. The significant features of our algorithm are that the SOE method is efficient and accurate, and works for general kernels with controllable upperbound of positive exponents. We provide numerical analysis for the SOE-based convolution quadrature. Numerical results on different kernels, the convolution integral and integral equations demonstrate attractive performance of both accuracy and efficiency of the proposed method.

Approximation of interacting kernels by sum of Gaussians (SOG) is frequently required in many applications of scientific and engineering computing in order to construct efficient algorithms for kernel summation or convolution problems. In this paper, we propose a kernel-independent SOG method by introducing the de la Vallée-Poussin sum and Chebyshev polynomials. The SOG works for general interacting kernels and the lower bound of Gaussian bandwidths is tunable and thus the Gaussians can be easily summed by fast Gaussian algorithms. The number of Gaussians can be further reduced via the model reduction based on the balanced truncation based on the square root method. Numerical results on the accuracy and model reduction efficiency show attractive performance of the proposed method.

```
                           Jiuyang Liang
                           Ph.D candidate
                           School of Mathematical Science and Institute of Natural Science
                           Shang Hai Jiao Tong University
                           [Homepage in Github](https://github.com/LiangJiuyang/)
                           [Homepage in Researchgate](https://www.researchgate.net/profile/Liang-Jiuyang)
```
