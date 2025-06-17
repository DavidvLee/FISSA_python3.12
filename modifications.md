# Modifications to make FISSA work in python 3.12
scikit-learn.decomposition.NMF has depricated the use of `alpha` as a keyword. The new keywords are `alpha_W` and `alpha_H`, these are set to the same value as the original `alpha` argument was set to. <br>
I.e., `alpha=alpha` became `alpha_W=alpha, alpha_H=alpha`.