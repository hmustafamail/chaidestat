Chaidestat
===========

Mustafa Hussain -- h.mustafa.mail@gmail.com

Decision trees are awesome. They are far more intuitive, and about as accurate, as logistic regression models. The catch is that STATA does not currently support them as well as logistic regressions. 

Joseph Luchman created the `chaid` function for STATA in 2014, which creates decision trees. However, logistic models are still better supported -- they can be validated on out-of-sample datasets using the `estat classification` function.

That's where `chaidestat classification` comes in. When completed, it will provide the ability to test decision trees on any dataset, after creating the tree.