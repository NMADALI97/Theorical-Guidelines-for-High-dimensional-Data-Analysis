# Huber Adaptive Regression

An implementation of Huber Adaptive Regression.Codes are borrowed from [tfHuber](https://github.com/belepi93/pytorch-rainbow), [baselines](https://github.com/XiaoouPan/tfHuber).

## Author(s)

MADALI Nabil , Virgile Rennard .

## Requirements
```
tfHuber
```
## Installation

Install `tfHuber` from GitHub:

```r
install.packages("devtools")
library(devtools)
devtools::install_github("XiaoouPan/tfHuber")
library(tfHuber)
```

## Functions

There are four functions in this package: 

* `huberMean`: Huber mean estimation.
* `huberCov`: Huber covariance matrix estimation.
* `huberReg`: Adaptive Huber regression.
* `cvHuberLasso`: *K*-fold cross-validated Huber-Lasso regression.

## References

Eddelbuettel, D. and Francois, R. (2011). Rcpp: Seamless R and C++ integration. J. Stat. Softw. 40(8) 1-18. [Paper](http://dirk.eddelbuettel.com/code/rcpp/Rcpp-introduction.pdf)

Eddelbuettel, D. and Sanderson, C. (2014). RcppArmadillo: Accelerating R with high-performance C++ linear algebra. Comput. Statist. Data Anal. 71 1054-1063. [Paper](http://dirk.eddelbuettel.com/papers/RcppArmadillo.pdf)

Fan, J., Liu, H., Sun, Q. and Zhang, T. (2018). I-LAMM for sparse learning: Simultaneous control of algorithmic complexity and statistical error. Ann. Statist. 46 814–841. [Paper](https://projecteuclid.org/euclid.aos/1522742437)

Ke, Y., Minsker, S., Ren, Z., Sun, Q. and Zhou, W.-X. (2019). User-friendly covariance estimation for heavy-tailed distributions: A survey and recent results. Statis. Sci. To appear. [Paper](https://arxiv.org/abs/1811.01520)

Pan, X., Sun, Q. and Zhou, W.-X. (2019). Nonconvex regularized robust regression with oracle properties in polynomial time. Preprint. [Paper](https://arxiv.org/abs/1907.04027).

Sanderson, C. and Curtin, R. (2016). Armadillo: A template-based C++ library for linear algebra. J. Open Source Softw. 1(2) 26. [Paper](http://conradsanderson.id.au/pdfs/sanderson_armadillo_joss_2016.pdf)

Sun, Q., Zhou, W.-X. and Fan, J. (2019). Adaptive Huber regression. J. Amer. Stat. Assoc. 0 1-12. [Paper](https://www.tandfonline.com/doi/abs/10.1080/01621459.2018.1543124)

Tibshirani, R. (1996). Regression shrinkage and selection via the lasso. J. R. Stat. Soc. Ser. B. Stat. Methodol. 58 267–288. [Paper](https://www.jstor.org/stable/2346178?seq=1#metadata_info_tab_contents)

Wang, L., Zheng, C., Zhou, W. and Zhou, W.-X. (2018). A new principle for tuning-free Huber regression. Preprint. [Paper](https://www.math.ucsd.edu/~wez243/Tuning_Free.pdf)



