# NHL Contract Modeling

## Introduction

**Author**: Amelia Dobronyi  
**Pace**: Flex  
**Instructor**: Abhineet Kulkarni  

## Overview

This project builds a model to predict NHL contract values, via modeling the two components of the contract: the annual value and the length of the contract. The notebook [data_scrape.ipynb](https://github.com/adobronyi/predicting_movie_recommendations/blob/main/student_v1.ipynb) goes through the process of scraping the NHL API and other websites to obtain player and contract data for the purpose of training and testing the models; it also scrapes information on pending free agents. The notebook [model.ipynb](https://github.com/adobronyi/predicting_movie_recommendations/blob/main/presentation.pdf) goes through the EDA and modeling process, and deploys the final models to output the deliverable, which is a list of pending free agents and the model's predicted contract values. Finally, the [presentation] provides and overview of the business and technical aspects of the project.

Included in this repository is an environment file that can be used to replicate the environment in which the notebooks should be run. To do, run the following line in terminal upon downloading the environment file:

'conda env create -f environment.yml'

## Business Understanding

Most modern professional sports teams are governed by league rules whereby they can sign athletes to contracts under certain constraints. Depending on the sport and league rules, players, perhaps with the help of agents, can arrange for a payout over a given number of years. With the vast increase in statistical data for sports, there has been more publicity surrounding these contract signings and the seemingly ever-increasing payouts these athletes receive. For this project, we will examine how player data and statistics, specifically in professional hockey, influence the value of a contract free agents end up signing.

While the proposed 'fair value' of a contract is useful for both teams and players to know, it is arguably more important for teams to be anchored to this fundamental value. Players and their agents can and should always seek to get the highest value for themselves; but teams are tasked with constructing the best roster given their constraints, and knowing what a player should be paid and not overpaying for a player in particular are essential for building the best team. 

## Data Understanding


## Modeling


## Deployment


## Conclusion



## Repository structure

- technical notebooks: model.ipynb, data_scrape.ipynb
- figures folder
- data folder: data_ng.csv, new_contract_players.csv
- README.md
- presentation.pdf
- .gitignore
- environment.yml
