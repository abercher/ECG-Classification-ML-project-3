# ECG-Classification-ML-project-3
This repository contains one of the final notebook I used for the third project of the ML course given by Buhman at ETH in Fall 2017.
The goal was to classify ECG signals.

The main difficulties where
1) We didn't know what the categories corresponded to.
2) There were relatively few samples.

One of the main lessons I took out of this project is that one should first look online for premade tools doing the task one wants to perform. I tried to do all the feature engineering by myself but I learned at the end of the project that there was a library called biosppy which was extracting some features form the signals and some students got a score above 0.8 by using it and XGBoost.

On the implementation side, I got more comfortable with python and Scikit learn.
