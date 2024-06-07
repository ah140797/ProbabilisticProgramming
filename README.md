## Probabilistic Programming Exam 


This project examines software quality in a dataset of $N=1127$ records of fragments of GitHub projects that are written in different programming languages. The software quality is defined as the number of commits classified as bugs. We examine whether the choice of programming language affects the number of bugs, and in particular whether the language Haskell is more prone to contain bugs compared to other langauges. In addition we investegate if the age of a project/language combination has a real effect on the number of bugs, or whether the relationship between age and bugs is a spurious relationship caused by commits. 

The hypotheses are as follows:

* **H1** - Haskell code is less prone to contain bugs (B). In other words, the distribution on the number of bugs (B) for Haskell gives high probability to the lowest number of bugs among all programming languages (L).
    
* **H2** - Age (A) has a positive impact on number of bugs (B) for all programming languages (L). That is, projects of old age (A) have larger number of bugs (B). 
    
* **H3** - Number of commits (C) does not impact the effect of age (A) on the number of bugs (B) for any programming language (L). That is, the effect of age (A), conditioned on number of commits (C), on number of bugs (B) is the same as the direct effect of age (A) on number of bugs (B).
