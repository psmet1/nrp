# **Data sets for the Nurse Rostering Problem** #

Nurse rostering is a combinatorial optimisation problem that involves the assignment of shifts to nurses with respect to coverage constraints, skill categories, labour legislations, contractual agreements, personal preferences, etc. Typically, around the clock service needs to be provided with a highly variable workload which differs from day to day. In practice, the problem is complicated by various aspects such as hierarchical skilled nurses and overlapping shifts.

The instances collected here represent nurse rostering problems (or, in a broader sense, personnel rostering problems) incorporating specific aspects of real-world scenario's as they occur in practice. These instances are available for researchers wishing to work with real world data.

These instances present six wards in two different Belgian hospitals. For each ward, three different scenario's are considered: normal, overload and absence. The normal scenario represents regular working conditions with average working conditions as well as the standard availability of nurses. The overload scenario presents situations in which there is an unforeseen high amount of work, e.g. due to e.g an epidemic. In the instances, this is modelled as higher than normal coverage requirements. Finally, the unexpected absence of a nurse is simulated in the absence scenario.

Name |	Nr. of employees |	Nr. of shift types |	Nr. of skill types
-----|-------------------|---------------------|--------------------
Emergency |	27 |	27 |	4
Psychiatry |	19 |	14 |	3
Reception |	19 |	19 |	4
Meal Preparation |	32 |	9 |	2
Geriatrics |	21 |	9 |	2
Palliative Care |	27 |	23 |	4

There are two datasets based on the aforementioned real world situations. Both contain the same information with regard to nurses, coverage requirements, skills, shifts and constraints. The first dataset (data set 1) has the basic problem elements, whereas the second dataset (data set 2) adds additional elements to the problem such as level of experience. This last dataset also uses a more generic format, which is useful for anyone wishing to model complex personnel rostering problems.

Additional information concerning these data sets can be found in the following publications:

- Burak Bilgin, Patrick De Causmaecker, Benoit Rossie, Greet Vanden Berghe. Local search neighbourhoods for dealing with a novel nurse rostering model, Annals of Operations Research, volume 194, issue 1, pages 33-57, 2012
- Pieter Smet, Burak Bilgin, Patrick De Causmaecker, Greet Vanden Berghe. Modelling and evaluation issues in nurse rostering, Annals of Operations Research, volume 218, issue 1, pages 303-326, 2014
