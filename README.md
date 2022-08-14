# Mixed-effects Regression Models

## This is an example of mixed-effects regression models in R.

Data is from a laboratory experiment measuring the effect of sleep deprivation on cognitive performance (see Belenky et al., 2003).

> Belenky, G., Wesensten, N. J., Thorne, D. R., Thomas, M. L., Sing, H. C., Redmond,D. P., Russo, M. B., & Balkin, T. J. (2003) Patterns of performance degradation and restoration during sleep restriction and subsequent recovery: A sleep dose-response study. Journal of Sleep Research, 12, 1{12.

18 participants chosen from a population of long-distance truck drivers participated in a 10-day trial. The participants were restricted to 3 hours of sleep per night. On each day of the study, each particiapnt's reaction time was measured during a variety of cognitive tasks. The average reaction time for each participant on each day is provided in the datafile (i.e. sleepstudy). This datafile has 4 columns: 

* (1) the row number of the data matrix, 
* (2) Reaction = average reaction time each day for each person, 
* (3) Days = timepoints that data was collected on, notice the equal spacing and what "0" indicates, 
* (4) Subject = participant ID.  

Also, note that these data are balanced in that each subject is measured the same number of times and on the same occasions{however, this need not be the case for MRMs. 
