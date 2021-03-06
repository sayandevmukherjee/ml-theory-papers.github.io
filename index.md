---
title: Theoretical aspects of ML
header-includes:
    <meta name="viewport" content="initial-scale=1.0, minimum-scale=1.0, maximum-scale=1.0, user-scalable=no" />
---


- - - -
## Deep Neural Networks

### Supervised Deep Learning
#### Representation
* Deeper networks can represent functions with exponentially more "kinks" 
  - [On the Number of Linear Regions of Deep Neural Networks](https://arxiv.org/abs/1402.1869)
  - [Benefits of depth in neural networks (PDF)](http://proceedings.mlr.press/v49/telgarsky16.pdf)
* There exist functions that can be represented efficiently with 3 layers, but not with 2 layers 
  - [The Power of Depth for Feedforward Neural Networks](https://arxiv.org/abs/1512.03965)
* Deep networks break curse of dimensionality 
  - [Theory I: Why and When Can Deep Networks Avoid the Curse of Dimensionality? (PDF)](https://cbmm.mit.edu/sites/default/files/publications/CBMM-Memo-058-v6.pdf)

#### Optimisation 
* NP Hardness of learning even small networks.
  - [Training a 3-node Neural Network is NP-Complete (PDF)](https://papers.nips.cc/paper/125-training-a-3-node-neural-network-is-np-complete.pdf)
* Hardness of learning parity like functions and deep networks
  - [Embedding Hard Learning Problems Into Gaussian Space (PDF)](https://core.ac.uk/download/pdf/62919210.pdf)
* Failures of Gradient based methods
  - [Failures of Gradient-Based Deep Learning](https://arxiv.org/abs/1703.07950.abs)
* Loss surface arguments
  - [Geometry of Neural Network Loss Surfaces via Random Matrix Theory (PDF)](http://proceedings.mlr.press/v70/pennington17a/pennington17a.pdf)
  - [The Loss Surfaces of Multilayer Networks (PDF)](http://proceedings.mlr.press/v38/choromanska15.pdf)
  - [On the Quality of the Initial Basin in Overspecified Neural Networks](https://arxiv.org/abs/1511.04210)
  - [Theory II: Landscape of the Empirical Risk in Deep Learning](https://arxiv.org/abs/1703.09833abs)
  - [Deep Learning without Poor Local Minima (PDF)](http://papers.nips.cc/paper/6112-deep-learning-without-poor-local-minima.pdf)
* Reparameterisation/Normalisation approaches:
  - Batch Norm: [How Does Batch Normalization Help Optimization?](https://arxiv.org/abs/1805.11604)
  - Weight norm: 
  - Layer Norm: 
  - Path Norm : [Path-SGD: Path-Normalized Optimization in Deep Neural Networks](https://arxiv.org/abs/1506.02617)
  - Natural Gradient: [Fisher-Rao Metric, Geometry, and Complexity of Neural Networks](https://arxiv.org/abs/1711.01530)
* Weight sharing (ala CNNs) help in optimisation
  - [Learning One Convolutional Layer with Overlapping Patches](https://arxiv.org/abs/1802.02547)
  - [When is Convolutional Filter Easy to Learn?](https://arxiv.org/abs/1709.06129)
* Deep Linear Networks for understanding optimisation:
  - [Exact solutions to the nonlinear dynamics of learning in deep linear neural networks](https://arxiv.org/abs/1312.6120)
  - [Deep Linear Networks with Arbitrary Loss: All Local Minima Are Global (PDF)](http://proceedings.mlr.press/v80/laurent18a/laurent18a.pdf)
* Deep nets learn for linearly-separable and other types of “structured data” or in “PAC setting”
  - [SGD Learns Over-parameterized Networks that Provably Generalize on Linearly Separable Data](https://arxiv.org/abs/1710.10174)
  - [Learning Overparameterized Neural Networks via Stochastic Gradient Descent on Structured Data](https://arxiv.org/abs/1808.01204)
  - [Gradient Descent Learns One-hidden-layer CNN: Don’t be Afraid of Spurious Local Minima](https://arxiv.org/abs/1712.00779)
* Overparameterised deep nets “converge”
  - [A Convergence Theory for Deep Learning via Over-Parameterization](https://arxiv.org/abs/1811.03962)
* Using ResNets instead of standard deep nets help in optimisation
  - TO-FILL
  
#### Generalisation
* Size of weights, not number of parameters defines complexity
  - [The Sample Complexity of Pattern Classification with Neural Networks: The size of the weights is more important than the size of the network (PDF)](http://www.yaroslavvb.com/papers/bartlett-sample.pdf)
* VC dimension of Neural Nets.
  - [VC Dimension of Neural Networks (PDF)](http://mathsci.kaist.ac.kr/~nipl/mas557/VCD_ANN_3.pdf)
* Spectral Normalised Margin for deep networks.
  - [Spectrally-normalized margin bounds for neural networks](https://arxiv.org/abs/1706.08498)
* Compression properties of deep networks.
  - [Stronger generalization bounds for deep nets via a compression approach](https://arxiv.org/abs/1802.05296)
    
#### Other Paradigms for Understanding Deep Networks
* Information Bottleneck
  - [Opening the Black Box of Deep Neural Networks via Information](https://arxiv.org/abs/1703.00810)
* Random weights
  - [Deep Neural Networks with Random Gaussian Weights: A Universal Classification Strategy?](https://arxiv.org/abs/1504.08291)
* Sum-Product networks
  - [Analysis and Design of Convolutional Networks via Hierarchical Tensor Decompositions](https://arxiv.org/abs/1705.02302)
  - [Shallow vs. Deep Sum-Product Networks (PDF)](https://papers.nips.cc/paper/4350-shallow-vs-deep-sum-product-networks.pdf)
* Convolutional nets learning filters/scattering networks/sparse coding for images
  - [A Mathematical Theory of Deep Convolutional Neural Networks for Feature Extraction](https://arxiv.org/abs/1512.06293)
  - [Convolutional Kernel Networks (PDF)](https://papers.nips.cc/paper/5348-convolutional-kernel-networks.pdf)
  - [Understanding Deep Convolutional Networks](https://arxiv.org/abs/1601.04920)
  - [Invariant Scattering Convolution Networks](https://arxiv.org/abs/1203.1513)
* Improper learning using Kernels
  - [$\ell_1$-regularized Neural Networks are Improperly Learnable in Polynomial Time](https://arxiv.org/abs/1510.03528)
* SGD/Architecture/Initialisation together to define a “hypothesis class”
  - [SGD Learns the Conjugate Kernel Class of the Network](https://arxiv.org/abs/1702.08503)
  - [Toward Deeper Understanding of Neural Networks: The Power of Initialization and a Dual View on Expressivity](https://arxiv.org/abs/1602.05897)
* “Convexified” neural networks
  - [Breaking the Curse of Dimensionality with Convex Neural Networks](http://jmlr.org/papers/volume18/14-546/14-546.pdf)
  - [Convexified Convolutional Neural Networks](https://arxiv.org/abs/1609.01000)


- - - -
