---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}


A Python package
================

`cupid_matching` is out; more details [here](code.md) and [on Pypi](https://pypi.org/project/cupid-matching/). It is `pip`-installable:
```sh
pip install cupid_matching
```

Feedback is very welcome.

Recent working papers
=====================

Revised: [Mating Markets](https://econ.columbia.edu/working-paper/mating-markets-2/),
with Pierre-André Chiappori:

This is the second draft of a chapter for the *Handbook of Family Economics*, Shelly Lundberg and Alessandra Voena eds, Elsevier North Holland.



[Filtered and Unfiltered Treatment Effects with Targeting Instruments](https://econ.columbia.edu/working-paper/21447/), 
with Simon  Lee:

Multivalued treatments are commonplace in applications. We explore the use of discrete-valued instruments to control for selection bias in this setting. We establish conditions under which counterfactual averages and treatment effects are identified for heterogeneous complier groups. These conditions require a combination of assumptions that restrict both the unobserved heterogeneity in treatment assignment and how the instruments target the treatments. We introduce the concept of filtered treatment, which takes into account limitations in the analyst’s information. Finally, we illustrate the usefulness of our framework by applying it to data from the Student Achievement and Retention Project and the Head Start Impact Study.



[Matching with Random Components: Simulations](../files/CNSdraftDec10final.pdf), with Pierre-André Chiappori and Dam Linh Nguyen:

Several recent papers have analyzed matching markets under the dual assumption of perfectly transferable utility and a separable joint surplus. Separability rules out any contribution to the joint surplus of a match of interactions between characteristics of partners that are unobserved by the analyst. Since it may be unrealistic in some settings, we explore the consequences of mistakenly imposing it. We find that the biases that result from this misspecification grow slowly with the magnitude of the contribution of the interaction terms. In particular, the estimated complementarities in the Choo and Siow (2006) model are remarkably robust to the inclusion of interaction terms.



[Labeling Dependence in Separable Matching Markets](../files/MatchingIIL_9dec2019), with Alfred Galichon:

Independence of irrelevant alternatives (IIA) has been much studied in single-agent decision problems. We explore its extension to models of two-sided choice and perfectly transferable utility. We start with models with a separable logit structure,  à la Choo and Siow (2006). We first show that this model satisfies a weak version of IIA. On the other hand, we conjecture that no separable model satisfies a stronger version of IIA. We then exhibit a two-sided version of the “blue bus/red bus” paradox, which shows that the separable logit model is not robust to irrelevant relabeling.



[Fast, “Robust”, and Approximately Correct: Estimating Mixed Demand Systems](../files/BLPwith2SLS_8_March_2019.pdf), with Frank Wolak:

Many econometric models used in applied work integrate over unobserved heterogeneity. We show that a class of these models that includes many random coefficients demand systems can be approximated by a "small-$\sigma$" expansion that yields a linear two-stage least squares estimator. We study in detail the models of product market shares and prices popular in empirical IO. Our estimator is only approximately correct, but it performs very well in practice. It is extremely fast and easy to implement, and it is "robust" to changes in the higher moments of the distribution of the random coefficients. At the very least, it provides excellent starting values for more commonly used estimators of these models.



Forthcoming
===========

* in the *Review of Economic Studies*: [Cupid’s Invisible Hand: Social Surplus and Identification in Matching Models](https://academic.oup.com/restud/advance-article/doi/10.1093/restud/rdab090/6478301?guestAccessKey=43f4a245-9f5c-48c6-b931-6c8753d31074), with Alfred Galichon.

We investigate a model of one-to-one matching with transferable utility and general unobserved heterogeneity. Under a separability assumption that generalizes Choo and Siow (2006), we first show that the equilibrium matching maximizes a social gain function that trades off exploiting complementarities in observable characteristics and matching on unobserved characteristics. We use this result to derive simple closed- form formulæ that identify the joint matching surplus and the equilibrium utilities of all participants, given any known distribution of unobserved heterogeneity. We provide efficient algorithms to compute the stable matching and to estimate parametric versions of the model. Finally, we revisit Choo and Siow’s empirical application to illustrate the potential of our more general approach.

The code for the IPFP procedure used in the paper can be found [here](https://pypi.org/project/cupid-matching/), as well as other code for the estimation of separable matching models.

* in *Online and Matching-Based Market Design*,
    Federico Echenique, Nicole Immorlica, and Vijay V. Vazirani eds,
    Cambridge University Press:  [Structural Estimation of Matching Markets with Transferable Utility](../files/GalichonSalanie_Chapter_15July2021.pdf), with Alfred Galichon:

We survey recent advances in the estimation of matching models with transferable utility, with special emphasis on methods that exploit the convexity of the problem when the joint surplus is separable.


Recently published
==================



[On Human Capital and Team Stability](https://www.journals.uchicago.edu/doi/pdfplus/10.1086/702925), *Journal of Human Capital*, Summer 2019, with Alfred Galichon and Pierre-André Chiappori:

In many economic contexts, agents from the same population team up to better exploit their human capital. In such contexts (often called “roommate matching problems”), stable matchings may fail to exist even when utility is transferable. We show that when each individual has a close substitute, a stable matching can be implemented with minimal policy intervention. Our results shed light on the stability of partnerships in the labor market. Moreover, they imply that the tools crafted in empirical studies of the marriage problem can easily be adapted to many roommate problems.


[From Aggregate Betting Data to Individual Risk Preferences](https://www.econometricsociety.org/system/files/ecta12418.pdf), *Econometrica*, January 2019, with Pierre-André Chiappori, François Salanié, and Amit Gandhi:

We show that even in the absence of data on individual decisions, the distribution of
individual attitudes towards risk can be identified from the aggregate conditions that
characterize equilibrium on markets for risky assets. Taking parimutuel horse races
as a textbook model of contingent markets, we allow for heterogeneous bettors with
very general risk preferences, including non-expected utility. Under a standard single-crossing condition on preferences, we identify the distribution of preferences among
the population of bettors and we derive testable implications. We estimate the model
on data from U.S. races. Specifications based on expected utility fit the data very poorly. Our results stress the crucial importance of nonlinear probability weighting. They also suggest that several dimensions of heterogeneity may be at work.



[Identifying Effects of Multivalued Treatments](https://www.econometricsociety.org/system/files/ecta14269.pdf)), *Econometrica*, November 2018, with Simon (Sokbae) Lee:

Multivalued treatment models have typically been studied under restrictive assumptions: ordered choice, and more recently, unordered monotonicity. We show how treatment effects can be identified in a more general class of models that allows for multidimensional unobserved heterogeneity. Our results rely on two main assumptions: treatment assignment must be a measurable function of threshold-crossing rules, and enough continuous instruments must be available. We illustrate our approach for several classes of models.

