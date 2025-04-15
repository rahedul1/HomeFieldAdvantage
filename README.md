# HomeFieldAdvantage
In this project I investigated one of the important factors affecting the outcomes of English Premier League games. Do home teams have an advantage over their opponents?

This paper investigates the home ground advantage phenomenon in English Premier League (EPL) matches and explores the feasibility of accurately predicting match outcomes (Win, Lose, Draw) through the analysis of specific match statistics. 

The study employs extensive exploratory data analysis, examining diverse machine learning architectures, and employing various data preprocessing techniques to optimize the dataset for model training. Experimental findings highlight the comparable performance of various Neural Networks, with the Recurrent Neural Network (RNN) demonstrating the highest Precision and Recall, and both Long Short-Term Memory (LSTM) and RNN exhibiting identical F-1 Scores of 77%. 

Surprisingly, the SVM Classifier with a Linear kernel outperformed all neural models, achieving the highest F-1 score of 78%, while its more intricate counterpart with a Radial Basis Function (RBF) kernel displayed inferior performance with an F-1 score of 39%. The multiclass classification problem of predicting match outcomes is discussed, emphasizing the significance of continuous model updates, the integration of current knowledge, and player forms for improved repeatability and reliability. 

The complexity of the dataset, evident through challenges in identifying clusters via dimension reduction techniques, raises concerns about model validity and interpretability. 

In conclusion, the study showcases the potential of machine learning models to predict match outcomes in the English Premier League, achieving a 78% accuracy with the best-performing model, while also addressing challenges and suggesting avenues for further refinement and exploration.
