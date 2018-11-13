---
title: "Optimal seismic reflectivity inversion: data-driven $\ell_p$-loss-$\ell_q$ -regularization sparse regression"
collection: publications
permalink: /publication/2019-01-01-paper-title-number-6
excerpt: 'Our method adaptively adopts a $\ell_p$-loss-$\ell_q$-
regularization to estimate a more accurate and detailed reflectivity profile.'
date: 2019-01-01
venue: 'IEEE Geoscience and Remote Sensing Letters'
paperurl: 'http://ruixie7.github.io/files/lpq_inversion.pdf'
citation: 'Fangyu Li, Rui Xie, WenZhan Song, Hui Chen. (2019) Optimal seismic reflectivity inversion: data-driven $\ell_p$-loss-$\ell_q$ -regularization sparse regression. IEEE Geoscience and Remote Sensing Letters.'
---
Seismic reflectivity inversion is widely applied to
improve the seismic resolution to obtain detailed underground
understandings. Based on the convolution model, seismic inversion
removes the wavelet effect by solving an optimization
problem. Taking advantage of the sparsity property, the $\ell_1$ norm
is commonly adopted in the regularization terms to overcome
the noise/interference vulnerability observed in the $\ell_p$-losses
minimization. However, no one has provided a deterministic
conclusion that $\ell_1$ norm regularization is the best choice for
seismic reflectivity inversion. Instead of using an unproved fixed
regularization norm, we propose an optimal seismic reflectivity
inversion approach. Our method adaptively adopts a $\ell_p$-loss-$\ell_q$-
regularization (i.e. $\ell_{p,q}$ regularization) for $p = 2$, $0 < q < 1$
to estimate a more accurate and detailed reflectivity profile. In
addition, we employ a K fold cross-validation based approach
to obtain the optimal damping factor $\lambda$ to further improve the
seismic inversion results. The letter starts with the introduction of
non-convex constraint for seismic inversion, and the necessity of
the $\ell_q$ norm regularization. Then the majorization-minimization
and cross validation algorithms are briefly described. The performance
of the proposed seismic inversion approach is evaluated
through synthetic examples and a field example from the Bohai
Bay Basin, China.

[Download paper here](http://ruixie7.github.io/files/lpq_inversion.pdf)
 [Bibtex](http://ruixie7.github.io/files/Li2019lpq.bib)