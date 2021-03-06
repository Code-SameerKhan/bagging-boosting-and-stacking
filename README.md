# Bagging, Boosting and Stacking in ML


<h2>BAGGING</h2>

Bootstrap aggregating, also called bagging (from bootstrap aggregating), is a machine learning ensemble meta-algorithm designed to improve the stability and accuracy of machine learning algorithms used in statistical classification and regression. It also reduces variance and helps to avoid overfitting. Although it is usually applied to decision tree methods, it can be used with any type of method. Bagging is a special case of the model averaging approach.

![](visuals/440px-Ensemble_Bagging.svg.png)


<h2>BOOSTING</h2>

In machine learning, boosting is an ensemble meta-algorithm for primarily reducing bias, and also variance in supervised learning, and a family of machine learning algorithms that convert weak learners to strong ones. A weak learner is defined to be a classifier that is only slightly correlated with the true classification (it can label examples better than random guessing). In contrast, a strong learner is a classifier that is arbitrarily well-correlated with the true classification.


![](visuals/220px-Ensemble_Boosting.svg.png)

Types of Boosting:


* AdaBoost

Adaptive Boosting is a type of boosting algorithm where the predictors concentrates on cases on which the previous learner has underfitted thus making the learners
progressively stronger and deal with harder and harder cases.

* Gradient Boost

It's the second type of boosting in the predcitor focusses more on the resudual error of the previous predictor. So instead of updating weights after every predictors output
it works on residual errors between predictions of the predecessor and the truth values.

<h3>Bagging and Boosting difference</h3>

![](visuals/Diff_bagging_boosting.png)


<h2>STACKING</h2>

Stacked generalization means the idea of instead of using trivial functions such as hard voting to aggregate the predictions all predictions in an ensemble, 
we train a model to perform these aggregations. Final model known as meta learner or blender takes predictions from predecessor models as input and makes final prediction.

![](visuals/stacking.png)
