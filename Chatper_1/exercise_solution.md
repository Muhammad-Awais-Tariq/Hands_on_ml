# Exercise

These are all the end chapter exercise questions answers

1. What is maching learning?
- Machine learning is basically define as instead of hardcoding everything we teach the machine based on the past examples to automatically generalize to new examples.

2. what are 4 types of applications for ml?
- Machine Learning is great for complex problems for which we have no algorithmic solution, to replace long lists of hand-tuned rules, to build systems that adapt to fluctuating environments, and finally to help humans learn (e.g., data mining).

3. What is labeled training set?
- A labeled training set is a training set that contains the desired solution (a.k.a. a label) for each instance.

4. Two common tasks of supervised learning?
- The two most common supervised tasks are regression and classification.

5. four common tasks of unsupervised learning?
- Common unsupervised tasks include clustering, visualization, dimensionality reduction, and association rule learning.

6. What is the type of algorithm to allow robot to walk?
- Reinforcement Learning is likely to perform best if we want a robot to learn to walk in various unknown terrains, since this is typically the type of problem that Reinforcement Learning tackles. It might be possible to express the problem as a supervised or semi-supervised learning problem, but it would be less natural.

7. What is the type of algorithm to segmend customer into groups?
- If you don't know how to define the groups, then you can use a clustering algorithm (unsupervised learning) to segment your customers into clusters of similar customers. However, if you know what groups you would like to have, then you can feed many examples of each group to a classification algorithm (supervised learning), and it will classify all your customers into these groups.

8. In which category spam detection fall?
- Spam detection is a typical supervised learning problem: the algorithm is fed many emails along with their labels (spam or not spam).

9. What is online learning system?
- An online learning system can learn incrementally, as opposed to a batch learning system. This makes it capable of adapting rapidly to both changing data and autonomous systems, and of training on very large quantities of data.

10. what is out of core learning?
- Out-of-core algorithms can handle vast quantities of data that cannot fit in a computer's main memory. An out-of-core learning algorithm chops the data into mini-batches and uses online learning techniques to learn from these mini-batches.

11. What type of algorithm rely on similarity to make prediction?
- An instance-based learning system learns the training data by heart; then, when given a new instance, it uses a similarity measure to find the most similar learned instances and uses them to make predictions.

12. What is the difference between model parameter and model hyperparameter?
- A model has one or more model parameters that determine what it will predict given a new instance (e.g., the slope of a linear model). A learning algorithm tries to find optimal values for these parameters such that the model generalizes well to new instances. A hyperparameter is a parameter of the learning algorithm itself, not of the model (e.g., the amount of regularization to apply).

13. What do model based algorithm search for?
- Model-based learning algorithms search for an optimal value for the model parameters such that the model will generalize well to new instances. We usually train such systems by minimizing a cost function that measures how bad the system is at making predictions on the training data, plus a penalty for model complexity if the model is regularized. To make predictions, we feed the new instance's features into the model's prediction function, using the parameter values found by the learning algorithm.

14. What are main challanges in machine learning?
- Some of the main challenges in Machine Learning are the lack of data, poor data quality, nonrepresentative data, uninformative features, excessively simple models that underfit the training data, and excessively complex models that overfit the data.

15. If model perform well on training data but generalizes poorly whats the cause?
- If a model performs great on the training data but generalizes poorly to new instances, the model is likely overfitting the training data (or we got extremely lucky on the training data). Possible solutions to overfitting are getting more data, simplifying the model (selecting a simpler algorithm, reducing the number of parameters or features used, or regularizing the model), or reducing the noise in the training data.

16. What is test set ?
- A test set is used to estimate the generalization error that a model will make on new instances, before the model is launched in production.

17. What is validation set?
- A validation set is used to compare models. It makes it possible to select the best model and tune the hyperparameters.

18. What is train dev set ?
- e train-dev set is used when there is a risk of mismatch between the training data and the data used in the validation and test datasets (which should always be as close as possible to the data used once the model is in production). The train-dev set is a part of the training set that's held out (the model is not trained on it). The model is trained on the rest of the training set, and evaluated on both the train-dev set and the validation set. If the model performs well on the training set but not on the train-dev set, then the model is likely overfitting the training set. If it performs well on both the training set and the train-dev set, but not on the validation set, then there is probably a significant data mismatch between the training data and the validation + test data, and you should try to improve the training data to make it look more like the validation + test data.