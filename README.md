# Exploring benefits of e-value over p-value
*Research Project of M1 Data Science*

### Objectives of the project
* explore the litterature about the replication crisis and the p-value issues (misunderstanding, p-hacking, optional stopping)
* read the preprint of ([Grünwald et al. 2019](https://arxiv.org/abs/1906.07801))
* understand the notion of e-value and its advantages over p-value
* compare the use of p-value and e-value on simulated and real datasets
* test the resistance of e-value to differents situations of data dredging proposed by ([Simmons et al. 2011](https://journals.sagepub.com/doi/full/10.1177/0956797611417632))

### Table of contents of the report

1. **Introduction**
2. **Actual situation in experimental sciences**
    1. The normal process of publication
        * Statistical hypothesis testing, publication process and the replication criterion
        * Importance of p < 0.05
    2. The statistical crisis
        * Low replicability, lack of power, p-hacking (multiple comparisons), HARKing
        * Optional stopping problem
        * Associated risks in decision making (scientific, clinical and political)
3. **Proposed solutions**
    1. Other proposals
        * Lowering the significance level, pre-registration, tools to detect p-hacking
        * Critical thinking in statistic courses, abandoning the use of "statistically significant"
    2. Bayesian Testing
        * Presentation of the framework (by Bayes factor or HDI)
        * Theoretical and practical benefits, possibility to do optional stopping
    3. E-value
        * Presentation of the notion
        * Theoretical and practical benefits, possibility to do optional stopping
    3. p-value versus e-value versus Bayes factor
        * Simulated dataset
        * Real dataset
        * Is e-value resistant to data dredging from ([Simmons et al. 2011](https://journals.sagepub.com/doi/full/10.1177/0956797611417632)) ?
4. **Conclusion**

### Various useful links to understand the problem
* ["Moving to a World Beyond p < 0.05"](https://www.tandfonline.com/doi/full/10.1080/00031305.2019.1583913)
* ["Repenser la robustesse et la fiabilité en recherche : les chercheurs face à la crise de la reproductibilité"](https://www.ouvrirlascience.fr/wp-content/uploads/2019/07/20190625_CR_JE-Urfist-reproductibilite.pdf)
* ["Doing bayesian data analysis : a tutorial with R and BUGS by John K. Kruschke"](https://ssrc.indiana.edu/doc/wimdocs/2011-01-14_kruschke_bayesian_slides.pdf)
* [Science4All, vulgarisation autour du bayésianisme et des problèmes de la p-value](https://www.youtube.com/playlist?list=PLtzmb84AoqRQkc4f38dueiPf8YUegsg8n)
* [Safe Testing (Grunwald video)](https://www.youtube.com/watch?v=xzM_Ggz1Jpo)
* [Power failure: why small sample size undermines the reliability of neuroscience](https://www.nature.com/articles/nrn3475)
