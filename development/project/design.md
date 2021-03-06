---
title: Explain how to create cfg.design for ft_statistics
---

{% include /shared/development/warning.md %}

# Explain how to create cfg.design for ft_statistics

cfg.design as input into ft_statistics (freq, timelock, or source) should be designed as follow
size MxN, where N is the number of trials/conditions

M is variable length.  Along with cfg.design, the other options cfg.ivar, cfg.uvar, cfg.wvar, and cfg.cvar may also need to be specified.   They are an index (indices) into which row(s) of the cfg.design correspond to 'independent variables', 'units of observation', 'within-block variables' and 'control variables', respectively.

Not all are needed: see statistics_*.m for what vectors it may include.

See http://fieldtrip.fcdonders.nl/walkthrough#non-paired_comparison and http://fieldtrip.fcdonders.nl/walkthrough#paired_comparison for examples on ivar and uvar.
and http://fieldtrip.fcdonders.nl/development/statistics  for uvar.

Is there any explanation on the wiki for more on uvar and wvar?   (Seems it is all on the email discussion list specific to people's questions).

#####  links to already existing pages with some mention of design matrix

*  http://fieldtrip.fcdonders.nl/walkthrough
*  http://fieldtrip.fcdonders.nl/getting_started/biosemi
*  http://fieldtrip.fcdonders.nl/tutorial/eventrelatedstatistics
*  http://fieldtrip.fcdonders.nl/tutorial/shared/cluster_permutation_background
*  http://fieldtrip.fcdonders.nl/tutorial/multivariateanalysis
*  http://fieldtrip.fcdonders.nl/tutorial/cluster_permutation_freq
*  http://fieldtrip.fcdonders.nl/tutorial/cluster_permutation_timelock
*  http://fieldtrip.fcdonders.nl/example/source_statistics
*  http://fieldtrip.fcdonders.nl/example/apply_clusterrandanalysis_on_tfrs_of_power_that_were_computed_with_besa
*  http://fieldtrip.fcdonders.nl/development/statistics
*  http://fieldtrip.fcdonders.nl/development/multivariate

##### Hierarchy of functions

(figure/diagram helpful http://fieldtrip.fcdonders.nl/development/statistics)

User calls ft_*statistics (freq, timelock, or source)

            cfg.method: different methods for calculating probability of null hypothesis
                         will call function: statistics_(cfg.method)

however, in ft_sourcestatistics, instead sourcestatistics_(cfg.method) is called, or statistics_wrapper if no method specified.

statistics_montecarlo.m (only) calls resampledesign.m

statistics_stat.m (deprecated: see http://fieldtrip.fcdonders.nl/example/statistics_toolbox )
