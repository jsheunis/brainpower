Things to consider
==================


Why conduct a power analysis?
*****************************
* Determine your sample size
* Determine whether it is even possible to find an effect with the given means (technical settings, available budget for subjects)
* Optimizing your pre-processing software given your scanner settings (collect your own resting state data as a template)

How to define an effect size?
*****************************
* Test statistic
* Cluster extent
* Relate one contrast of interest A to the strength of another contrast B → see Matan Mazor and David Mehler 
* Length of recording → number of trials

Tools for univariate power analysis
***********************************
* GPower_, Pangea_
* Suited if clearly defined ROIs/ localizers are available
* How to clearly define ROIs? How to define ROIs on a subject-specific level?
* G*Power is suitable for very particular questions/ analyses, but require many decisions a-priori → defining ROIs, defining summary statistics on ROIs
* Can even increase power (e.g. for very small volumes) because you avoid correction for multiple comparisons

.. _GPower: http://www.psychologie.hhu.de/arbeitsgruppen/allgemeine-psychologie-und-arbeitspsychologie/gpower.html
.. _Pangea: https://jakewestfall.shinyapps.io/pangea/

Tools for 3-dimentional power analysis
**************************************
* Simulation: take available data set (resting-state) with a realistic noise profile, add an effect of a certain extent and strength, see if your (preprocessing + analysis) finds it
* What are the parameters to vary?
	* Sample size
	* Effect strength/ extend
	* Noise profile
	* Using nuisance regressors or not
	* Can this be easily extended to M/EEG, because it’s also high-dimensional?

