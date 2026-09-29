# F1 Enthusiast

A collection of Formula 1 data projects built around the [FastF1](https://github.com/theOehrly/Fast-F1) API.

## Projects

| Project | Description                                                                                                                                                                                                       |
| --- |-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [Belgian GP Winner Prediction](./Belgian%20GP%20Winner%20Prediction) | Machine learning models that predict the Belgian GP race winner from qualifying data. The project itself can be improved by creating more relevant features, adding more models, and defining the task more precisely. |
| [Italian GP Winner Prediction](./Italian%20GP%20Winner%20Prediction) | Classifies each driver's Monza (Italian GP) finishing placement — Podium / Points / No Points — from qualifying data, trained on 2016-2025 and evaluated against the 2026 race.                                    |
| [data-analysis](./data-analysis) | Exploratory data analysis and interactive visualisations of the F1 season, with a race-weekend deep dive into Monaco 2026.                                                                                        |

## Repository Structure

```
F1-Enthusiast/
├── Belgian GP Winner Prediction/
│   ├── README.md
│   ├── requirements.txt
│   └── BelgianGP.ipynb
├── Italian GP Winner Prediction/
│   ├── README.md
│   └── ItalianGP.ipynb
└── data-analysis/
    ├── README.md
    ├── requirements.txt
    ├── F1_EDA.ipynb
    ├── visualisations/
    └── monaco2026/
        ├── monaco26.ipynb
        └── weekend_analysis.ipynb
```
