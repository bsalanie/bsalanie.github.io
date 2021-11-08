## [Bernard Salanie](http://bsalanie.com)'s code for matching models with transferable utility



My  [CupidPython](http://www.github.com/bsalanie/CupidPython.git) repository  contains Python code related to separable matching with transferable utilities, as analyzed in [my paper with Alfred Galichon](http://bsalanie.com/wp-content/uploads/2021/06/2021-06-1_Cupids.pdf). It serves as the basis for my [cupidpython](https://pypi.org/project/cupidpython), which is installable via `pip`.

The `cupidpython` package has code
* to solve for the stable matching using  our Iterative Projection Fitting Procedure (IPFP)  in variants of the  model of bipartite, one-to-one matching with perfectly transferable utility. It has IPFP solvers for variants of the  [Choo and Siow 2006](https://www.jstor.org/stable/10.1086/498585?seq=1) model with or without singles, homoskedastic and heteroskedastic; and also for a class of nested logit models. 
* to estimate the parameters of separable models with  semilinear surplus using a minimum distance estimator.
* to estimate the paranmeters of semilinear Choo and Siow models.
* for a [Streamlit](https://www.streamlit.io/) interactive app that demonstrates solving and estimating the Choo and Siow model. You can try it [here](https://share.streamlit.io/bsalanie/cupidpython/main/cupid_streamlit.py).

The full documentation is [on Read the Docs](https://cupidpython.readthedocs.io/en/latest/).


My [ipfp_R](http://www.github.com/bsalanie/ipfp_R.git) repository only contains R code to solve for equilibrium in the basic version of the Choo and Siow model.




