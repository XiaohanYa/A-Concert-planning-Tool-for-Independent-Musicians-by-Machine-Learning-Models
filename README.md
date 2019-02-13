# A Concert-planning Tool for Independent Musicians by Machine Learning Models
This is an in-class project for Machine Learning in New York University Shanghai.

In this project, my partner and I aim at helping independent musicians to plan their concerts based on the economies of agglomeration in music industry. Initially, we planned to design an advisory tool for both concert pricing and location selection. Nonetheless, after implementing SGD linear regression and support vector regression models, we realized that concert price does not vary significantly according to different music types, concert time, concert location and ticket venues.

Therefore, to offer more useful suggestions, we focus on the location choice problem by turning it to a classification task. The overall performance of our classification model is pretty good. After tuning hyper parameters, we discovered random forest gives the best performance, improving the classification result by 316%. This result reveals that we could help independent musicians better locate their concerts to where similar musicians would go, namely a place with higher network effects.
