.. brainpower documentation master file, created by
   sphinx-quickstart on Sun Aug 11 10:38:32 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.


BrainPower: resources for power analysis in neuroimaging
========================================================

.. image:: https://img.shields.io/badge/license-MIT-brightgreen
   :target: https://github.com/jsheunis/brainpower/blob/master/LICENSE
   :alt: License

.. image:: https://readthedocs.org/projects/brainpower/badge/?version=latest
   :target: https://brainpower.readthedocs.io/en/latest/?badge=latest
   :alt: Documentation Status

.. image:: https://img.shields.io/badge/chat-on%20mattermost-blue
   :target: https://mattermost.brainhack.org/brainhack/channels/neuroimaging_prereg
   :alt: Join the chat

About
-----

Every planning phase of an empirical neuroimaging research project should consider sample size and statistical power: How big is the effect that I am interested in? How likely am I to observe it given the resources (number of subjects, number of trials) at my disposal? How should I balance my confidence in the findings with the possibility of false positives? Power analysis to provide clarity on these questions could appear relatively easy for simple designs with intuitive behavioural variables, especially with the help of programs such as G*Power and standard effect size measures such as Cohen's d. However, the complex nature of neuroimaging data and designs (processing three-dimensional data over time with mass univariate and multivariate approaches) requires additional steps, e.g. cluster correction, to improve reliability of inferences. And our understanding of "effects" based on these data and methods is not necessarily as intuitive: how strong should the level of activation be, or how large should the cluster extent be?

Experts in these domains have created several primers, tools and software to help researchers approach power analysis appropriately. At the SIPS2019 conferenceIn this hackathon, we set out to collate a variety of such resources to make neuroimaging power analysis more accessible to researchers. We collected:

1. Informative journal articles and blog posts on the underlying principles of power analysis
2. Software toolboxes for conducting power analysis in neuroimaging
3. A list of useful questions to ask or heuristics to consider when planning an experiment
4. Tools for simulating fMRI data with which to pilot power analyses

This content is still growing. Our short-term goal is to expand the resources with tutorials and worked examples of conducting power analyses on real and simulated fMRI data.

We invite and welcome any and all contributions from the community!




.. toctree::
   :maxdepth: 2
   :caption: Contents:
   
   things_to_consider
   publications
   software_tools
   simulations
   tutorials



Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
