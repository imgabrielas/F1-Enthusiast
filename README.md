# F1 Enthusiast

A collection of Formula 1 data projects built around the [FastF1](https://github.com/theOehrly/Fast-F1) API.

## Projects

| Notebook                                                                 | Race                                 | Description                                                                                                                                                                                                                                      |
| ------------------------------------------------------------------------ | ------------------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| [`Round_10_BelgianGP.ipynb`](./Round_10_BelgianGP.ipynb)                 | Belgian GP (Round 10)                | Trains models on 2021-2026 qualifying and 2021-2025 race data to predict the Belgian GP result from qualifying performance.                                                                                                                      |
| [`Round_13_ItalianGP.ipynb`](./Round_13_ItalianGP.ipynb)                 | Italian GP — Monza (Round 13)        | Gradient Boosting model trained on 2026 race lap/sector times plus qualifying and weather data, predicting each driver's average race pace, then compared against the actual 2026 result.                                                        |
| [`Round_17_SingaporeGP.ipynb`](./Round_17_SingaporeGP.ipynb)             | Singapore GP — Marina Bay (Round 17) | Work in progress: winner prediction for the Sprint and Grand Prix sessions of the Singapore weekend.                                                                                                                                             |
| [`F1 Race and Drivers Analysis`](./F1%20Race%20and%20Drivers%20Analysis) | 2026 season                          | Exploratory data analysis and visualisations of the season (driver/constructor performance, points, podiums, DNFs), with a dedicated notebook for the Monaco GP weekend. See its own [README](./F1%20Race%20and%20Drivers%20Analysis/README.md). |

## Repository Structure

```
F1-Enthusiast/
├── Round_10_BelgianGP.ipynb
├── Round_13_ItalianGP.ipynb
├── Round_17_SingaporeGP.ipynb
└── F1 Race and Drivers Analysis/
    ├── README.md
    ├── requirements.txt
    ├── F1_General_Analysis.ipynb
    ├── MonacoGP_Analysis.ipynb
    └── visualisations/
```
