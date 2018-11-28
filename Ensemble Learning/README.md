## Ensemble learning
It helps improve machine learning results by combining several models. This approach allows the production of better predictive performance compared to a single model.

**Traditional Method:**</br>
1. Pick random subsets(uniformly, randomly from the data)
2. Select an algorithm (rule: learn over the data)
3. Finally apply to them, the mean on all the outputs(combine/ bagging)

**Optimal Method:**(Boosting)</br>
1. Instead of randomly picking up the data, pick up the data which is hard(hardest example)
ex: We tend to learn things which we don't know but not that which we have already mastered
	a. ERROR: The probability over a distribution of the hypothesis value (predicted) and the true value (given)  not being equal.
  b.WEAK LEARNER: The learning algorithm being weak. A weak learner is defined to be a classifier that is only slightly correlated with the true classification (it can label examples better than random guessing).
2. We instead of just doing the mean we do weighted mean.

![](https://github.com/neha-duggirala/100DaysOfMLCode/blob/master/Ensemble%20Learning/infographic.png)

References:</br>
[1] https://blog.statsbot.co/ensemble-learning-d1dcd548e936</br>
[2] https://www.youtube.com/watch?v=m-S9Hojj1as </br>
[3] https://www.youtube.com/watch?v=X3Wbfb4M33w
