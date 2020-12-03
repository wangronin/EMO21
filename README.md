# EMO '21

The data, source code, and plots for EMO '21 paper titled "On Statistical Analysis of MOEAs with Multiple Performance Indicators" by [Hao Wang](https://www.universiteitleiden.nl/en/staffmembers/hao-wang#tab-1), Carlos Igncio Hernández, and [Tome Eftimov](http://cs.ijs.si/eftimov/). In the nutshell, we propose a novel multivariate statistical analysis procedure, where we firstly compare the multivariate performance data (bivariate in this case, namely the hypervolume and deltaP measure) using the multivariate epsilon test, then partition algorithms into groups with statistical significance according to the test, and finally project the grouped data onto a 1D linear space determined by the linear discrimiative analysis (LDA).

* `DSC-result`: the results from DSC ranking schemes and multivariate epsilon test.
* `analysis.Rmd`: an R-notebook containing the statisical analysis approach that utilizes the multivariate epsilon test results and the linear discrimiative analysis (LDA) to rank the MOO algorithms using bivariate performance data.
* `lda`: the folder containing the plots of our proposed approach.
