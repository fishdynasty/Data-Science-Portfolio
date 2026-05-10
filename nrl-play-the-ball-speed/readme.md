# NRL Play-the-Ball Speed Prediction

## Overview

This project analyses play-the-ball speed in rugby league using NRL match data. The goal was to understand which factors influence play-the-ball duration and to build a model that could predict it.

The project was completed as part of a university data science course.

## Problem

Play-the-ball speed can affect attacking momentum and defensive pressure in rugby league. The main question for this project was:

> What factors are most useful for predicting play-the-ball speed?

## Methods

The analysis included:
- Data cleaning
- Feature engineering
- Exploratory data analysis
- Feature selection
- Regression modelling
- Model comparison

The models tested included:
- Multiple linear regression
- Ridge regression
- LASSO
- Elastic Net
- Random Forest
- XGBoost

## Main Findings

XGBoost gave the best overall performance compared with the other models tested.

The most important factors found were:
- Tackle result
- Set type
- Tackle number

These variables had the clearest relationship with play-the-ball duration and were useful for explaining differences in speed.

## Files

- `nrl_analysis.ipynb` — notebook containing the analysis and modelling
- `nrl_report.pdf` — final written report

## Skills Shown

- Regression modelling
- Feature engineering
- Model comparison
- Sports analytics
- Communicating results from data
