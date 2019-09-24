Simulating data
===============

Tools for easily simulating data, i.e. “placing” effects of certain strength and certain temporal and/or spatial extent into a brain.

fmrisim
*******
A python module, part of the `Brainiak package`_, that contains a set of functions necessary to produce realistic simulations of fMRI data for a single subject. Steps include haracterizing the signal and generating the noise model, which are then combined to simulate brain data.

* bioRxiv preprint: `Ellis et al 2019`_ - Facilitating open-science with realistic fMRI simulation: validation and application
* `fmrisim code on GitHub`_
* `fmrisim documentation`_
* `fmrisim example code`_
* `Brainiak website`_

neuRosim
********
An R package to simulate fMRI Data, including activated data, noise data and resting state sata.

* Journal article: `Welvaert et al 2011`_ - neuRosim: An R Package for Generating fMRI Data
* `neuRosim package on CRAN`_
* `neuRosim code on GitHub`_

STANCE
******
The MATLAB-based Spontaneous & Task-related Activation of Neuronally Correlated Events simulator

* Journal article: `Hill et al 2017`_ - A task-related and resting state realistic fMRI simulator for fMRI data validation
* `STANCE code on GitHub`_

SimTB
*****
MATLAB Toolbox for flexible generation of fMRI datasets under a model of spatiotemporal separability

* Journal article: `Erhardt et al 2012`_ - SimTB, a simulation toolbox for fMRI data under a model of spatiotemporal separability.
* `simTB website`_



.. _Brainiak package: https://brainiak.org/docs/brainiak.html
.. _Ellis et al 2019: https://www.biorxiv.org/content/10.1101/532424v2
.. _fmrisim code on GitHub: https://github.com/brainiak/brainiak/blob/master/brainiak/utils/fmrisim.py
.. _fmrisim documentation: https://brainiak.org/docs/brainiak.utils.html?highlight=fmrisim#module-brainiak.utils.fmrisim
.. _fmrisim example code: https://brainiak.org/tutorials/13-real-time/
.. _Brainiak website: https://brainiak.org/
.. _Welvaert et al 2011: http://dx.doi.org/10.18637/jss.v044.i10
.. _neuRosim package on CRAN: https://CRAN.R-project.org/package=neuRosim
.. _neuRosim code on GitHub: https://github.com/NeuroStat/neuRosim
.. _Hill et al 2017: https://doi.org/10.1117/12.2254777
.. _STANCE code on GitHub: https://github.com/jasohill/STANCE
.. _Erhardt et al 2012: https://doi.org/10.1016/j.neuroimage.2011.11.088
.. _simTB website: http://trendscenter.org/software/simtb/







