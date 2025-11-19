## 2022 Study Group

Winter 2022 focus is on [Richard McElreath 2022 course](https://github.com/rmcelreath/stat_rethinking_2022)  on Bayesian statistics.
Pdf of first two chapters of his [Statistical_Rethinkng](http://xcelab.net/rmpubs/sr2/statisticalrethinking2_chapters1and2.pdf) gives foundational philosophy. Course ends on the subject of [state-space representation of time-series data](https://github.com/study-groups/tsd-study-group). Calendar is from McElreath's site.

### Calendar & Topical Outline

There are 10 weeks of instruction. Links to lecture recordings will appear in this table. Weekly problem sets are assigned on Fridays and due the next Friday, when we discuss the solutions in the weekly online meeting.

Lecture playlist on Youtube: <[Statistical Rethinking 2022](https://www.youtube.com/playlist?list=PLDcUM9US4XdMROZ57-OIRtIK0aOynbgZN)>

[//]: # (11 Feb SPP conflict , 25 Feb Winter Break conflict )

| Week ## | Meeting date | Reading | Lectures |
| ------- | -------------- | ------------- | ---------------------- |
| Week 01 | 07 January  | Chapters 1, 2 and 3 | [The Golem of Prague](https://youtu.be/cclUd_HoRlo), [Bayesian Inference](https://www.youtube.com/watch?v=guTdrfycW2Q&list=PLDcUM9US4XdMROZ57-OIRtIK0aOynbgZN&index=2) |
| Week 02 | 14 January | Chapter 4 | [Basic Regression](https://www.youtube.com/watch?v=zYYBtxHWE0A), [Categories & Curves](https://youtu.be/QiHKdvAbYII) |
| Week 03 | 21 January | Chapters 5 and 6 | [Confounding](#), [Even Worse Confounding](#) |
| Week 04 | 28 January | Chapters 7 and 8 | [Overfitting](#), [Interactions](#) |
| Week 05 | 04 February | Chapters 9, 10 and 11 | [Markov chain Monte Carlo](#), [Binomial GLMs](#) |
| Week 06 | 11 February | Chapters 11 and 12 | [Poisson GLMs](#), [Ordered Categories](#) |
| Week 07 | 18 February | Chapter 13 | [Multilevel Models](#), [Multi-Multilevel Models](#) |
| Week 08 | 25 February | Chapter 14 | [Varying Slopes](#), [Gaussian Processes](#) |
| Week 09 | 04 March | Chapter 15 | [Measurement Error](#), [Missing Data](#) |
| Week 10 | 11 March | Chapters 16 and 17 | [Beyond GLMs: State-space Models, ODEs](#), [Horoscopes](#) |

## History of Bayesian statistics

Devised around  in [1763](https://en.wikipedia.org/wiki/An_Essay_towards_solving_a_Problem_in_the_Doctrine_of_Chances) 
by Thomas Bayes, **[Bayesian Statistics](https://en.wikipedia.org/wiki/Bayesian_statistics)** addresses conditional
probability in terms of the ratio between an event **A** happening simultaneously with another event, **B**
written: **P(A given B) = P( A and B ) / P( only A )**.


Bayes described conditional probability- not how to update priors or measure probability beyond counting. 


In 1814, Laplace presents the 
[classical interpretation of probability](https://en.wikipedia.org/wiki/Classical_definition_of_probability)
which treats probability as a measure of a ratio between a **favorable interpretation of an event** and 
**all those events not deeemed favorable**. In this way, more experimental data leads to tighter 
[confidence intervals](https://en.wikipedia.org/wiki/Confidence_interval#Meaning_and_interpretation) 
&mdash; e.g. 90% of the experiments (confidence level)
 fall between  &theta;<sub>low</sub> and &theta;<sub>high</sub> (confidence interval). This is the
language of  classic
 [statistical hypothesis testing](https://en.wikipedia.org/wiki/Statistical_hypothesis_testing).

In 1857 logicians Venn and Boole introduce the
 [frequentist interpretation of probability](https://en.wikipedia.org/wiki/Frequentist_probability) 
which treats probability as the measure of likelihood after attempting a large number of trials. 


## Primary Resources

- [A Student's Guide to Bayesian Statistics](https://www.youtube.com/playlist?list=PLwJRxp3blEvZ8AKMXOy0fc0cqT61GsKCG): by  [Ben Lambert](https://ben-lambert.com/bayesian/). This course aims to provide a core understanding of Bayesian statistics  that is grounded in mathematical theory, yet friendly to the less mathematically-minded of persons. It aims to focus on the intuitive results of Bayesian theory rather than dwell on the mathematical minutiae.

- [Statistical Rethinking](https://xcelab.net/rm/statistical-rethinking/): by Richard McElreath. The second edition emphasizes the directed acyclic graph (DAG) approach to causal inference. It ends with an entirely new chapter that goes beyond generalized linear modeling, showing how domain-specific scientific models can be built into statistical analyses.

- [Learning Bayesian Statistics Podcast](https://www.stitcher.com/show/learning-bayesian-statistics): A very well produced podcast interviewing big thinkers in Bayesian statistics by Alexandre Andorra.

- [Statistical Thinking](https://www.fharrell.com/):  Frank Harrell is a Professor of Biostatistics in the School of Medicine at Vanderbilt University. This blog is devoted to statistical thinking and its impact on science and everyday life.

- [Modeling Emotions Associated With Novelty at Variable Uncertainty Levels: A Bayesian Approach](https://www.frontiersin.org/articles/10.3389/fncom.2019.00002/full) by Hideyoshi Yanagisawa.  Good, simple example of using Bayesian statistics to model human behaviour based on prior beliefs about states of excitement before (prior distribution), during (ikelihood) and after the event (posterior distribution).

- [Bayesian modeling of time series From Introduction to biological time series data](./lecture10.pdf) by Kyrre Lekve from Department of Biology, University of Oslo. Masterpiece of a lecture. See also: [State-space representation of time-series data](https://hackmd.io/@mricos/HJdJrDdnu#/).
