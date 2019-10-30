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

At some stage in an empirical neuroimaging research project that aims to find evidence for or against an effect, sample size and statistical power calculations should be considered. This process aims to shed light on questions like:
* how big is the effect size of interest?
* how many study participants, data acquisition runs and trials are needed?
* how likely will the effect be found in the data, given practical constrains?
* how should confidence in the findings be balanced with the likelihood of false positives?

Conducting power analysis to provide tentative answers to these questions could appear relatively straightforward for simple designs with intuitive behavioural variables, especially with the help of programs such as G*Power and standard effect size measures such as Cohen's d.

However, the complex nature of neuroimaging data and designs (processing three-dimensional data over time with mass univariate and multivariate approaches) requires additional steps, e.g. cluster correction, to improve reliability of inferences. And our understanding of "effects" based on these data and methods is not necessarily as intuitive: how strong should the level of activation be, or how large should the cluster extent be?

Experts in these domains have created several primers, tools and software to help researchers approach power analysis appropriately. In a hackathon at the `SIPS2019`_ conference, we set out to start collating a variety of such resources to make neuroimaging power analysis more accessible to researchers. We collected:

1. Informative journal articles and blog posts on the underlying principles of power analysis
2. Software toolboxes for conducting power analysis in neuroimaging
3. A list of useful questions to ask or heuristics to consider when planning an experiment
4. Tools for simulating fMRI data with which to pilot power analyses

This content is still growing. Our short-term goal is make the improve the quality of the current content and to expand the resources with tutorials and worked examples of conducting power analyses on real and simulated fMRI data.

We invite and welcome any and all contributions from the community!

.. _SIPS2019: https://www.improvingpsych.org/SIPS2019/


Getting involved
----------------

New contributors are very welcome and encouraged to join!

To get started, join the discussion on our `Mattermost channel`_!

Do you have a specific question or comment about existing or missing content?
Open or comment on an `issue`_!

If you want to help develop and are familiar with the standard developer workflow, fork the `project`_ on Github and send us a pull-request.

We ask that all contributors adhere to our `code of conduct`_.


.. _Mattermost channel: https://mattermost.brainhack.org/brainhack/channels/neuroimaging_prereg
.. _issue: https://github.com/jsheunis/brainpower/issues
.. _project: https://github.com/jsheunis/brainpower
.. _code of conduct: https://github.com/jsheunis/brainpower/blob/master/CODE_OF_CONDUCT.md


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
