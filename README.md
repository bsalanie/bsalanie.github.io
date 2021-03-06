## [Bernard Salanie](http://bsalanie.com)'s code for matching models with transferable utility



My  [CupidPython](http://www.github.com/bsalanie/CupidPython.git) repository  contains Python code related to separable matching with transferable utilities, as analyzed in [my paper with Alfred Galichon](http://bsalanie.com/wp-content/uploads/2021/06/2021-06-1_Cupids.pdf). It  has code for our Iterative Projection Fitting Procedure (IPFP)  to solve for equilibrium in variants of the  [Choo and Siow 2006](https://www.jstor.org/stable/10.1086/498585?seq=1) model of bipartite, one-to-one matching with perfectly transferable utility. The repository contains IPFP solvers for  the Choo and Siow model with or without singles, homoskedastic and heteroskedastic. It also has  code that uses moment matching to estimate the semilinear Choo and Siow model as per Proposition 5 of the Galichon-Salanie paper. Please see the [html docs](https://github.com/bsalanie/ipfp_python/blob/master/docs/build/html/index.html)  or the [pdf manual](https://github.com/bsalanie/ipfp_python/blob/master/docs/build/latex/ipfp_python.pdf) for more information.

I also coded a [Streamlit](https://www.streamlit.io/) interactive app that demonstrates the basic model (homoskedastic, with singles). You can try it [here](http://3.131.97.82:8501).

My [ipfp_R](http://www.github.com/bsalanie/ipfp_R.git) repository only contains R code to solve for equilibrium in the basic version of the Choo and Siow model.




