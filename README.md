In this project we aim to learn about statistical and regression methods used to study climate events. For the reading material I have followed this course https://www.youtube.com/playlist?list=PLpl-gQkQivXhdgUCdaUQcdb31CRe8Mm2y. 
Now I present my summary of the paper that I analysed for which we try to use the statistical tools learned before.

In this paper we read about oods and other hydro logical factors which occurred
in the U.S causing bridge collapse or damage. Several hydraulic eects were
discussed which could have been the cause of the bridge collapse. In response to
increase in collapse risk due to oods our aim is at determining the magnitude
and frequency of design oods. Method used for estimating the return period of
a ood event include block maxima approaches, in which a series of annual peak
ows is used to dene an extreme value distribution. The generalized extreme
value distribution is a widely used model for extreme events. The major benet
of the GEV model is its ability to t highly skewed data since it combines
three distributions: Gumbel, Frechet, and Weibull. The GEV distribution has
three parameters, namely, the location and scale parameters which are mostly
related to the magnitude of ow, and the shape parameter that determines the
behavior (or shape) of the tail of the distribution. Now this oods will depend
on dierent attributes according to dierent places so we use random forest
mechanism to derive physiography-based important levels. The random forests
algorithm is used for regression, and the estimation of the importance levels
of dierent predictor variables, that is, the contribution of each input variable
in predicting the response within a regional context. A negative importance
level means that inclusion of the predictor variable results in a decrease in the
performance of the algorithm. Positive values indicate a positive contribution
to the prediction of the algorithm. Now we also have predict the frequency
of the return of the ood so for that we use Jiang’s classifcation scheme and
categorize annual peak ows into heavy tail and light tail ows. Heavy tail ow
implies that ows in the heavy tail increase more than the exponential order as
compared to the ows in the light tail, and such high ows are expected to be
with higher return periods. Using GEV and Random forest algorithm we get
which predictor variables are important in which places and also nd a estimate
of return periods in dierent regions and plot graphs showing the same.

