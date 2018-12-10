# Bio
I'm a postdoctoral fellow in the [Center for Research on Computation and Society](https://crcs.seas.harvard.edu/) in the Harvard [John A. Paulson School for Engineering and Applied Sciences (SEAS)](https://www.seas.harvard.edu/).  I work in the intersection machine learning and healthcare with [Finale Doshi-Velez](https://finale.seas.harvard.edu/).

I completed my Ph.D. in [Statistical Science](https://stat.duke.edu) at [Duke](https://duke.edu) in May of 2018 and was funded by an [NDSEG Fellowship](https://ndseg.asee.org/).  I worked under the supervision of [Katherine Heller](http://www2.stat.duke.edu/~kheller/). 

In general, my research interests are in the intersection of machine learning and healthcare, and most of my work is strongly tied to a specific application area. On the methodological side, some areas I'm interested currently in include: reinforcement learning and sequential decision making, partial observability in RL and POMDPs, off-policy policy evaluation techniques, causality, Gaussian processes and other methods for irregularly sampled time series, survival analysis, joint modeling and methods trainable end-to-end. I'm also interested in pragmatic questions surrounding the deployment of machine learning models into the real world, for instance, issues around generalizability, transfer learning between different datasets (e.g. between different hospitals), and how often / how to retrain production models using more recent data.

I'm especially excited to have worked in deploying machine learning models into actual clinical practice to help doctors provide better care and improve patient outcomes.  To that end, I collaborate a lot with the [Duke Institute for Health Innovation](http://www.dihi.org/), and we've [currently deployed a model I developed for early detection of sepsis into the Duke Health System](https://spectrum.ieee.org/biomedical/diagnostics/hospitals-roll-out-ai-systems-to-keep-patients-from-dying-of-sepsis)! I'm also currently working on several other projects with them: predicting hyperglycemic events among patients on high doses of steroids, and learning insulin dosing regimens to improve treatment for these patients; predicting mortality and other outcomes among patients in cardiogenic shock; general methods to predict inpatient mortality.  In the past I've built models for predicting disease progression and adverse events in chronic kidney disease patients, and models for surgical complications, among other things.

Before Duke, I obtained my AB in [Mathematics](https://math.dartmouth.edu/) (2013) from [Dartmouth College](http://home.dartmouth.edu/), where I wrote an honors thesis under the supervision of [Daniel Rockmore](http://www.cs.dartmouth.edu/~rockmore/).

My email address is ``jfutoma14 AT gmail DOT com``. You can find my CV [here](https://github.com/jfutoma/jfutoma.github.io/blob/master/CV.pdf).

# Publications

## Conference Papers 

1. **J. Futoma**, S. Hariharan, M. Sendak, N. Brajer, M. Clement, A. Bedoya, C. O’Brien, and K. Heller. [“An Improved Multi-Output Gaussian Process RNN with Real-Time Validation for Early Sepsis Detection,”](https://arxiv.org/abs/1708.05894) in *Proceedings of the 2nd Machine Learning for Healthcare Conference (MLHC)*, Boston, MA, Aug 2017.
2. **J. Futoma**, S. Hariharan, and K. Heller. [“Learning to Detect Sepsis with a Multitask Gaussian Process RNN Classifier,”](https://arxiv.org/abs/1706.04152) in *Proceedings of the 34th International Conference on Machine Learning (ICML)*, Sydney, Australia, Aug 2017.
3. **J. Futoma**, M. Sendak, C. B. Cameron, and K. Heller. [“Predicting Disease Progression with a Model for Multivariate Longitudinal Clinical Data,”](http://proceedings.mlr.press/v56/Futoma16.pdf) in *Proceedings of the 1st Machine Learning for Healthcare Conference (MLHC)*, Los Angeles, CA, Aug 2016.
4. **J. Futoma**, M. Sendak, C. B. Cameron, and K. Heller. [“Scalable Joint Modeling of Longitudinal and Point Process Data for Disease Trajectory Prediction and Improving Management of Chronic Kidney Disease,”](http://auai.org/uai2016/proceedings/papers/160.pdf) in *Proceedings of the 32nd Conference on Uncertainty in Artificial Intelligence (UAI)*, New York City, NY, Jun 2016.
5. N. Foti, **J. Futoma**, D. Rockmore, and S. Williamson. [“A Unifying Representation for a Class of Dependent Random Measures,”](https://arxiv.org/pdf/1211.4753.pdf) in *Proceedings of the 16th Conference on Artificial Intelligence and Statistics (AISTATS)*, Scottsdale, AZ, May 2013.

## Journal Papers 
1. **J. Futoma**, J. Morris, and J. Lucas. [“A Comparison of Models for Predicting Early Hospital Readmissions,”](http://www.sciencedirect.com/science/article/pii/S1532046415000969) Journal of Biomedical Informatics, vol. 56, pp. 229–238, 2015.

## Workshop Papers 
1. **J. Futoma**, M. Hughes, F. Doshi-Velez. [“Predicton Constrained POMDPs,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/papers/PC-POMDP_NIPS2018_POwkshp.pdf) in *NeurIPS 2018 Workshop on Reinforcement Learning under Partial Observability*, Montreal, Canada, Dec 2018.
2. **J. Futoma**, A. Lin, M. Sendak, A. Bedoya, M. Clement, C. O'Brien, K. Heller . [“Learning to Treat Sepsis with Multi-Output Gaussian Process Deep Recurrent Q-Networks,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/papers/NIPS2017_Workshop.pdf) in *NIPS 2017 Workshop on Machine Learning for Health*, Long Beach, CA, Dec 2017.
3. **J. Futoma** and J. Lucas. [“Predicting Early Hospital Readmissions using Electronic Health Records,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/papers/NIPS2014_Workshop_Readmissions.pdf) in *NIPS 2014 Workshop on Machine Learning for Clinical Data, Healthcare and Genomics*, Montreal, Canada, Dec 2014.


## Other Papers 
1. **J. Futoma**. [“Gaussian Process-Based Models for Clinical Time Series in Healthcare,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/papers/dissertation_final.pdf) *Duke University Ph.D. Dissertation*, May 2018.
2. Z. Sun, **J. Futoma**, M. Sendak, E. Lorenzi, S. Brown, O. Huang, K. Heller, J. Thacker, C. Mantyh,
and E. Huang. “Precision Medicine in Point-Of-Care Management of Surgical Complications” (Contributed 1 page paper), in *NIH-IEEE 2015 Strategic Conference on Healthcare Innovations and Point-of-Care Technologies for Precision Medicine*, Bethesda, MD, Nov 2015.
3. **J. Futoma**. [“Scalable Inference Algorithms for Clustering Large Networks,”](https://math.dartmouth.edu/theses/undergrad/2013/SeniorThesisFutoma.pdf) *Dartmouth College Senior Thesis*, Jun 2013.

## Papers in Preparation 
1. A. Bedoya , **J. Futoma** , M. Clement, N. Brajer, A. Lin, M. Sendak, K. Heller, C. O’Brien. “Deeply Personalized Sepsis Care: Using Deep Learning to Improve Early Detection of Sepsis”.
2. A. Lin, M. Sendak, A. Bedoya, M. Clement, N. Brajer, **J. Futoma**, H. Bosworth, K. Heller, C. O’Brien. “Improving Sepsis Care: Aligning Phenotype Selection with Program Design”.
3. Z. Sun, O. Huang, E. Lorenzi, B. Chang, M. Turner, **J. Futoma**, T. Li, K. Heller, C. Mantyh, and E. Huang. “Validation and Implementation of Wide and Deep Learning for Surgical Risk Prediction At the Point-Of-Care”.


# Talks 

* [“Learning to Detect Sepsis with a Multi-Output Gaussian Process RNN Classifier (in the Real World!),”](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/BNP_NIPS_2018.pdf), Invited Talk, NeurIPS 2018 Workshop on All of Bayesian Nonparametrics (Especially the Useful Bits) ([video of SepsisWatch app](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/SW_blurred.mp4))
* "Deeply Personalized Medicine: Bringing Deep Learning to Sepsis Care," Society of Hospital Medicine Annual Meeting 2018, Plenary Presentation (**top 3/1540 abstracts**; presented by Anthony Lin)
* [“An Improved Multi-Output Gaussian Process RNN with Real-Time Validation for Early Sepsis Detection,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/MLHC_2017.pdf), MLHC 2017 Spotlight
* [“Learning to Detect Sepsis with a Multitask Gaussian Process RNN Classifier,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/ICML_2017.pdf): ICML 2017 Oral Presentation
* [“Learning to Detect Sepsis with a Multitask Gaussian Process RNN Classifier,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/INFORMS_2017.pdf): INFORMS Healthcare 2017 Oral Presentation
* [“Predicting Disease Progression with a Model for Multivariate Longitudinal Clinical Data,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/MLHC_2016.pdf): MLHC 2016 Spotlight
* [“Scalable Joint Modeling of Longitudinal and Point Process Data for Disease Trajectory Prediction and Improving Management of Chronic Kidney Disease,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/talks/UAI_Baysm_2016.pdf), UAI 2016 Workshop on Bayesian Applications *Invited Talk*; Bayesian Young Statisticians Meeting 2016, Oral Presentation

# Posters

* "Leveraging Deep Learning and Rapid Response Team Nurses to Improve Sepsis Management", MLHC 2018
* “What Is Sepsis: Investigating the Heterogeneity of Patient Populations Captured by Different Sepsis Definitions”, American Thoracic Society International Conference 2018
* [“An Improved Multi-Output Gaussian Process RNN with Real-Time Validation for Early Sepsis Detection,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/posters/MLHC_2017.pdf), MLHC 2017
* [“Learning to Detect Sepsis with a Multitask Gaussian Process RNN Classifier,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/posters/ICML_2017.pdf), ICML 2017 
* [“Predicting Disease Progression with a Model for Multivariate Longitudinal Clinical Data,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/posters/MLHC_2016.pdf), MLHC 2016
* [“Scalable Joint Modeling of Longitudinal and Point Process Data for Disease Trajectory Prediction and Improving Management of Chronic Kidney Disease,”](https://github.com/jfutoma/jfutoma.github.io/blob/master/posters/UAI_2016.pdf), ISBA 2016 World Meeting; UAI 2016
* “Developing a Data-Driven Workflow for Population Health Rounding”, Society of General Internal Medicine 2016

# Software
* [MGP-RNN](https://github.com/jfutoma/MGP-RNN)
