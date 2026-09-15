# Italian GP Winner Prediction

**Status: ongoing project**

This project uses historical Formula 1 race data from Monza (Italian Grand Prix) to predict race outcomes with a Neural Network.

## Goals

- **Binary classification**: predict winner / not winner for each driver in a race.
- **Multi-class classification**: predict a driver's finishing position among the top 10 grid places.

## Approach

The plan is to build both models using historical Monza race records, with a Neural Network as the modeling approach for each task.

Since this work starts about two weeks after the race took place, final race results are already available, making it straightforward to construct a `race_stats` column to use as the target label for training.