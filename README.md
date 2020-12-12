# Introduction to Machine Learning, Fall 2020 Term Project

This project was done for the Introduction to Machine Learning course at the University of Helsinki as a solo project because of personal reasons. The objective of the project was to train a machine learning model on labeled NPF data and then to predict unlabeled data using that model. There were 3 possible scoring methods for the models: binary accuracy, multi-class accuracy, and perplexity. In this project, the first two are used to evaluate classification models. These two accuracies as scoring method lead the project to end up choosing Gaussian Process classifier for explaining and predicting NPF data. 

The organizers of the course hosted a challenge on which any project (a group of 1-3) could participate by returning an additional file. The file needed to contain a prediction on what the classes of the unlabeled test data are and the probability of how likely it is for the event to happen on each observation. In the challenge, there were 4 categories. The first three are the already mentioned criteria, and the fourth was the accuracy of binary accuracy estimate. In the challenge, the Gaussian Process classifier performed quite well. It had second place in binary accuracy, first place in multi-class accuracy, and 30. place in perplexity because of a mistake in code at a time of prediction generation. In the fourth category, my estimation of binary accuracy was so close to the true binary accuracy of the model that I placed fifth in the accuracy estimate category. There was 43 project participating in the challenge.

All the code of the project is written into a jupyter notebooks. This means that to use the code, either of the following has to be satisfied: 
1. [Anaconda](https://www.anaconda.com/products/individual)
2. [Python enviroment](https://docs.python.org/3/tutorial/venv.html) with following:
    1. Jupyter notebook
    2. Pandas
    3. Scikit-learn
    4. Seaborn
