# Doing Bayesian Data Analysis - Python/PyMC3
This repository contains Python/<A href="https://docs.pymc.io/">PyMC3</A> code for a selection of models and figures from the book <A target="_blank" href='https://sites.google.com/site/doingbayesiandataanalysis/'>'Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan'</A>, Second Edition, by John Kruschke (2015).
The datasets used in this repository have been retrieved from the book's website. Note that, in its current form, this repository is not a standalone tutorial and that you probably should have a copy of the book to follow along. Suggestions for improvement and help with unsolved issues are welcome!<P>
Note that the code is in Jupyter Notebook format and requires modification to use with other datasets.<P>
Some of the general concepts from the book are discussed in papers by Kruschke & Liddell. See references below.
</P>

**2018-08-16:**  
Updating the notebooks with PyMC3 v3.5 and general code clean-up. Inserting plots of the PyMC models in plate notation (v3.5 feature). Fixing some deprecation warnings.
 
</P>
<IMG src='Notebooks/images/DBDA2.png' height=30% width=30%><P>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%209.ipynb'>Chapter 9 - Hierarchical Models</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2010.ipynb'>Chapter 10 - Model Comparison and Hierarchical Modelling</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2012.ipynb'>Chapter 12 - Bayesian Approaches to Testing a Point ("Null") Hypothesis</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2016.ipynb'>Chapter 16 - Metric-Predicted Variable on One or Two Groups</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2017.ipynb'>Chapter 17 - Metric-Predicted Variable with One Metric Predictor</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2018.ipynb'>Chapter 18 - Metric Predicted Variable with Multiple Metric Predictors</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2019.ipynb'>Chapter 19 - Metric Predicted Variable with One Nominal Predictor</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2020.ipynb'>Chapter 20 - Metric Predicted Variable with Multiple Nominal Predictor</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2021.ipynb'>Chapter 21 - Dichotomous Predicted Variable</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2022.ipynb'>Chapter 22 - Nominal Predicted Variable</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2023.ipynb'>Chapter 23 - Ordinal Predicted Variable</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Chapter%2024.ipynb'>Chapter 24 - Count Predicted Variable</A><P>
Extra:<BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/Various-Machine-Learning-bits/blob/master/Bayesian%20Linear%20Regression.ipynb'>Bayesian Linear Regression example (Bishop, 2006)</A><BR>
<A href='http://nbviewer.jupyter.org/github/JWarmenhoven/DBDA-python/blob/master/Notebooks/Ordinal%20Model_Kruschke_Liddell.ipynb'>Example on modelling Ordinal Data (Liddell & Kruschke, 2018)</A>
<P>
Libraries used:

 - pymc3
 - theano
 - pandas
 - numpy
 - scipy
 - matplotlib
 - seaborn  

#### References:
Bishop, C.M. (2006), <I>Pattern Recognition and Machine Learning</I>, Springer Science+Business Media, New York. https://www.microsoft.com/en-us/research/people/cmbishop/<P>
Kruschke, J.K. (2015), <I>Doing Bayesian Data Analysis: A Tutorial with R, JAGS, and Stan</I>, Second Edition, Academic Press / Elsevier, https://sites.google.com/site/doingbayesiandataanalysis/
<P>
Kruschke, J.K. & Liddell, T.M. (2017), <I>The Bayesian New Statistics: Hypothesis testing, estimation, meta-analysis, and power analysis from a Bayesian perspective</I>, Psychonomic Bulletin & Review, http://dx.doi.org/10.3758/s13423-016-1221-4
<P>
Kruschke, J.K. & Liddell, T.M. (2017), <I>Bayesian data analysis for newcomers</I>, Psychonomic Bulletin & Review, http://dx.doi.org/10.3758/s13423-017-1272-1
<P>
Liddell, T., & Kruschke, J. K. (2018, April 5). Analyzing ordinal data with metric models: What could possibly go wrong? Retrieved from http://osf.io/3tkz4 
 <P>
Salvatier J, Wiecki TV, Fonnesbeck C. (2016), <I>Probabilistic programming in Python using PyMC3</I>, PeerJ Computer Science 2:e55, https://doi.org/10.7717/peerj-cs.55 <BR>
PyMC3 - http://pymc-devs.github.io/pymc3/

#### Note:
The repository below contains python code for the first edition of the book. The code in that repository is a much more direct implementation of the R/JAGS code from the book than you will find here.<BR>
https://github.com/aloctavodia/Doing_bayesian_data_analysis
