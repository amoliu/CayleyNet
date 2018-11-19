# CayleyNets
We present a TensorFlow implementation of the Graph Convolutional Neural Network illustrated in:

CayleyNets: Graph Convolutional Neural Networks with Complex Rational Spectral Filters<br>
IEEE Transactions on Signal Processing, 2018<br>
Ron Levie*, Federico Monti*, Xavier Bresson, Michael M. Bronstein

https://arxiv.org/abs/1705.07664

The repository contains a sparse implementation of the NN used for solving the MNIST digits classification problem described in the paper. Rational spectral filters are approximated with Jacobi Method to provide an efficient solution.

## When shall I use CayleyNet?

CayleyNet is a Graph CNN with spectral zoom properties able to effectively operate with signals defined over graphs. Thanks to its particular spectral properties, CayleyNet is well suited for dealing with a variety of different domains (e.g. citation networks, community graphs, user/item similarity graphs...). Variations of the architecture here implemented achieved state-of-the-art performance on vertex classification, community detection and matrix completion tasks.

## Useful links

<img src="pic/home100.jpg" width="20" height="20" style="max-width:100%;"> <a href="http://inf.usi.ch/phd/monti">inf.usi.ch/phd/monti</a><br>
<img src="pic/web.png" width="20" height="20" style="max-width:100%;"> <a href="http://geometricdeeplearning.com">geometricdeeplearning.com</a>
