# March Madness Matchup Prediction - Deep Learning Model

## 🏀 Introduction

For my final project in FI 424, Deep Learning and Neural Networks in Finance, I decided to train a model to predict the outcomes of March Madness matchups based on college basketball teams' season stats. 

## Challenges faced

- Since I could not find a standalone model that included both team stats and March Madness outcomes, I had to combine two datasets (one with team stats for each season and one with matchup data), and manipulate the data using Pandas to get it into a suitable format to be fed to a machine learning model and predict the winner of a matchup. This was a challenge, especially due to the different names for colleges in the two datasets, but I was able to combine the data.

## Datasets

- I pulled team stats data from Sports Reference and March Madness matchup data from data.world. I used data from the 1992-93 to the 2018-19 basketball seasons. 
- [Team Stats Data](https://www.sports-reference.com/cbb/seasons/men/2019-school-stats.html)
- [Matchup Data](https://data.world/michaelaroy/ncaa-tournament-results/workspace/project-summary?agentid=michaelaroy&datasetid=ncaa-tournament-results)

## Tech Stack

- Python
- TensorFlow
- Keras
- Pandas

