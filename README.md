# vlabs-challenge
Repo to a machine learning project for VLabs Data Challenge. Based on data from 14 months of purchases, the task is to predict how much each client is going to spent on the next 90 days.

The dataset was transformed to treat the problem as a supervised learning regression task, the data split by chanel (Physical Store, IFood, WhatsApp, ECM or Telesales) and one model trained for each chanel with a ElasticNet algorithm. The final prediction is generated by the the sum of the predictions of each chanel for each client and scored second place in the competition out of 17 teams.

The Notebook **[Final_model.ipynb](https://github.com/marcos-mansur/vlabs-challenge/blob/main/Notebook/Final_model_VKaggle.ipynb)** generated our best solution to the challenge and scored second place on of the competition (private leaderboard). 

[Kaggle Competition Link](https://www.kaggle.com/c/VLabs-DC)

# Developers
- Marcos Mansur
- [Thiago Ouverney](https://github.com/thiago-ouverney/)
