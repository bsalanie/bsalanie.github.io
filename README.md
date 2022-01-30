## [Bernard Salanie](http://bsalanie.com)'s code for matching models with transferable utility



My  [cupid_matching](http://www.github.com/bsalanie/cupid_matching.git) repository  contains Python code related to separable matching with transferable utilities, as analyzed in [my paper with Alfred Galichon](https://academic.oup.com/restud/advance-article-abstract/doi/10.1093/restud/rdab090/6478301). It serves as the basis for my [cupid_matching](https://pypi.org/project/cupid_matching), which is installable via `pip`. 

It replaces my earlier `CupidPython` package, which is now obsolete. 

The full documentation is [here](https://bsalanie.github.io/cupid_matching).

The `cupid_matching` package has code
* to solve for the stable matching using  our Iterative Projection Fitting Procedure (IPFP)  in variants of the  model of bipartite, one-to-one matching with perfectly transferable utility. It has IPFP solvers for variants of the  [Choo and Siow 2006](https://www.jstor.org/stable/10.1086/498585?seq=1) model with or without singles, homoskedastic and heteroskedastic; and also for a class of nested logit models. 
* to estimate the parameters of separable models with  semilinear surplus and entropy using a minimum distance estimator.
* to estimate the parameters of semilinear Choo and Siow models using a Poisson GLM estimator.

{% comment %}
* for a [Streamlit](https://www.streamlit.io/) interactive app that demonstrates solving and estimating the Choo and Siow model. You can try it [here](https://share.streamlit.io/bsalanie/cupid_matching/main/cupid_streamlit.py).
{% endcomment %}



My [ipfp_R](http://www.github.com/bsalanie/ipfp_R.git) repository only contains R code to solve for equilibrium in the basic version of the Choo and Siow model.




