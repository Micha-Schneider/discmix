# DiscMix (R Package for Discrete Mixtures)
This R package fits discrete finite mixture models (such as CUB, CUP, BetaBin and cure models). It can perform unpenalized model estimation (discmix()), variable selection via penalization (penmix()) and forward selection (stepmix()), and bootstrap samples for standard errors (se.discmix()). 

So far, the package only works with R versions up to 3.6.3, as there are some internal dependencies. It is recommended to have at least the following packages installed:
compiler, Formula, formula.tools, matrixcalc, matrixStats, methods, mgcv, MRSP, parallel, stats, VGAM 

For using the full functionality please install first the mentioned packages and then DiscMix (https://github.com/Micha-Schneider/discmix). The current MRSP version can be downloaded from https://github.com/WolfgangPoessnecker/MRSP
