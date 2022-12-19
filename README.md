# Reddit-fake-post-detection
Classify whether a Reddit post is fake or not based on its text.

✔️ Problem Formulation:

The objective is to find out whether a Reddit post is fake or not. NLP techniques is used to handle this problem. The challenges is to find the best way of preprocessing techniques of posts and also type of vectorization used to indicate the importance of each word/feature. The impact could be having much less fake posts by banning the fake ones.

The ideal solution is finding model with accuracy with at least 70% success rate.

Strategy used:

Try different classifiers.
Try the best one with word and vector vectorizers also RandomSearch was used to help find better hyperparameter values.
Try different preprocessing techniques with RandomSearch with the best model and best vectorizer.
Try XGBoost with RandomSearch.
