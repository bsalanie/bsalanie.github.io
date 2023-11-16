---
layout: archive
title: "News"
permalink: /news/
author_profile: true
---

{% include base_path %}

I am pleased to report that I am now the Sami Mnaymneh Professor at Columbia.

# A Python package

Version 1.1 of `cupid_matching` is out; more details [here](code.md) and [on Pypi](https://pypi.org/project/cupid-matching/). It is `pip`-installable:

```sh
pip install cupid_matching
```

My Streamlit app that demoes solving and estimating the Choo and Siow model now allows users to download a summary of their simulation. Check it out [here](http://3.84.215.135:8501).

Feedback is very welcome.

# Recent work

_New paper_: [Treatment Effects with Targeting Instruments](https://arxiv.org/abs/2007.10432#).
with Simon Lee:

This is a shortened and improved version of *Filtered and Unfiltered Treatment Effects with Targeting Instruments*.

Multivalued treatments are commonplace in applications. We explore the use of discrete-valued instruments to control for selection bias in this setting. Our discussion revolves around the concept of targeting instruments: which instruments target which treatments. It allows us to establish conditions under which counterfactual averages and treatment effects are point- or partially-identified for composite complier groups. We illustrate the usefulness of our framework by applying it to data from the Head Start Impact Study. Under a plausible positive selection assumption, we derive informative bounds that suggest less beneficial effects of Head Start expansions than the parametric estimates of Kline and Walters (2016).

_Now forthcoming in the Journal of Applied Econometrics_: [Estimating Separable Matching Models](../files/estimating_separable_models.pdf),
with Alfred Galichon

Most recent empirical applications of matching with transferable utility have imposed a natural restriction: that the joint surplus be separable in the sources of unobserved heterogeneity. We propose here two simple methods to estimate models in this class. The first method is a minimum distance estimator that relies on the generalized entropy of matching introduced in Galichon and Salanié (2022). The second applies to the more special but popular Choo and Siow (2006) model, which it reformulates as a generalized linear model with two-way fixed effects. Both methods are easy to apply and perform very well.

_Published_: Mating Markets,
with Pierre-André Chiappori:.
This is the second draft of a chapter for the _Handbook of Family Economics_, Shelly Lundberg and Alessandra Voena eds, Elsevier North Holland.

_Published_: [Cupid's Invisible Hand: Social Surplus and Identification in Matching Models](https://academic.oup.com/restud/article-abstract/89/5/2600/6478301),
  _Review of Economic Studies_ (2022), 89, 2600-2629.

We investigate a model of one-to-one matching with transferable utility and general unobserved heterogeneity. Under a separability assumption that generalizes Choo and Siow (2006), we first show that the equilibrium matching maximizes a social gain function that trades off exploiting complementarities in observable characteristics and matching on unobserved characteristics. We use this result to derive simple closed-form formulæ that identify the joint matching surplus and the equilibrium utilities of all participants, given any known distribution of unobserved heterogeneity. We provide efficient algorithms to compute the stable matching and to estimate parametric versions of the model. Finally, we revisit Choo and Siow’s empirical application to illustrate the potential of our more general approach.

The code for the IPFP procedure used in the paper can be found [here](https://pypi.org/project/cupid-matching/), as well as other code for the estimation of separable matching models.

_Published_: [Structural Estimation of Matching Markets with Transferable Utility](https://www.cambridge.org/core/books/online-and-matchingbased-market-design/604CA9FF1396C489D6497CF336368524#), with Alfred Galichon, chapter 26 in _Online and Matching-Based Market Design_,
  Federico Echenique, Nicole Immorlica, and Vijay V. Vazirani eds,
  Cambridge University Press.

We survey recent advances in the estimation of matching models with transferable utility, with special emphasis on methods that exploit the convexity of the problem when the joint surplus is separable.

    For online access to the book, follow [this link](https://www.cambridge.org/files/9216/8487/6990/matching_book_pw.pdf)

and use the password `OMBMD_CUP`.



[Matching with Random Components: Simulations](../files/CNSdraftDec10final.pdf), with Pierre-André Chiappori and Dam Linh Nguyen:

Several recent papers have analyzed matching markets under the dual assumption of perfectly transferable utility and a separable joint surplus. Separability rules out any contribution to the joint surplus of a match of interactions between characteristics of partners that are unobserved by the analyst. Since it may be unrealistic in some settings, we explore the consequences of mistakenly imposing it. We find that the biases that result from this misspecification grow slowly with the magnitude of the contribution of the interaction terms. In particular, the estimated complementarities in the Choo and Siow (2006) model are remarkably robust to the inclusion of interaction terms.

[Labeling Dependence in Separable Matching Markets](../files/MatchingIIL_9dec2019), with Alfred Galichon:

Independence of irrelevant alternatives (IIA) has been much studied in single-agent decision problems. We explore its extension to models of two-sided choice and perfectly transferable utility. We start with models with a separable logit structure, à la Choo and Siow (2006). We first show that this model satisfies a weak version of IIA. On the other hand, we conjecture that no separable model satisfies a stronger version of IIA. We then exhibit a two-sided version of the “blue bus/red bus” paradox, which shows that the separable logit model is not robust to irrelevant relabeling.

[Fast, “Robust”, and Approximately Correct: Estimating Mixed Demand Systems](../files/BLPwith2SLS_8_March_2019.pdf), with Frank Wolak:

Many econometric models used in applied work integrate over unobserved heterogeneity. We show that a class of these models that includes many random coefficients demand systems can be approximated by a "small-$\sigma$" expansion that yields a linear two-stage least squares estimator. We study in detail the models of product market shares and prices popular in empirical IO. Our estimator is only approximately correct, but it performs very well in practice. It is extremely fast and easy to implement, and it is "robust" to changes in the higher moments of the distribution of the random coefficients. At the very least, it provides excellent starting values for more commonly used estimators of these models.
