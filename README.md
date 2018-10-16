# 2018_Heldt_et_al

Custom code for the article: <br>
"A comprehensive model for the proliferation-quiescence decision in response to endogenous DNA damage in human cells" <br>
Frank S. Heldt, Alexis R. Barr, Sam Cooper, Chris Bakal, Bela Novak <br>
PNAS, February 2018, doi: 10.1073/pnas.1715345115

This repository contains different versions of the mathematical model used in the article.

- **HeldtBarr2018_QuiescenceInResponseToDnaDamage_SBtoolbox**: Deterministic version of the model for the Systems Biology Toolbox 2 (now known as IQR Tools, https://iqrtools.intiquan.com/) for MatLab. This file was used to obtain most of the deterministic simulations in the manuscript and served as a basis for the stochastic implementation.
- **HeldtBarr2018_QuiescenceInResponseToDnaDamage_XPP**: Deterministic version of the model for XPP-Aut (http://www.math.pitt.edu/~bard/xpp/xpp.html). Modified versions of this file were used to create bifurcation diagrams.
- **HeldtBarr2018_QuiescenceInResponseToDnaDamage_SBML**: Deterministic version of the model in the Systems Biology Markup Language (http://sbml.org), level 3 version 1. This file was created from the Copasi version of the model to provide compatibility with other software tools.
- **HeldtBarr2018_QuiescenceInResponseToDnaDamage_Copasi_Deterministic**: Deterministic version of the model for Copasi (http://copasi.org/). Simulating this file will recreate Fig. 1B.
- **HeldtBarr2018_QuiescenceInResponseToDnaDamage_Copasi_Stochastic**: Stochastic version of the model for Copasi (http://copasi.org/). Simulating this file provides a single stochastic realisation of the model similar to Fig. 1F and G. Stochastic simulations in the article were, however, created with a custom-made MatLab implementation of the Stochastic Simulation Algorithm not provided here.
