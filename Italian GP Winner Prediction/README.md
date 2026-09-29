# Italian GP Winner Prediction

Predicts each driver's finishing placement at the Italian Grand Prix (Monza) from qualifying data.

## Goal

Multi-class classification of race outcome into three buckets, derived from points scored (robust to DNFs and non-classified finishes):

- **Podium** — P1-P3 (15+ points)
- **Points** — P4-P10 (1-12 points)
- **No Points** — P11+ or retired (0 points)

## Approach

1. Pull qualifying and race results for every Italian GP from 2016-2026 via FastF1.
2. Merge them into one row per driver per year: qualifying position, Q1/Q2/Q3 lap times, best lap, gap to pole, team, and actual starting grid position as features.
3. Train on 2016-2025 and hold out 2026 as the evaluation set — the 2026 race has already taken place, so predictions can be checked directly against the real result.
4. Compare a Logistic Regression baseline against a Random Forest classifier (5-fold cross-validation on the training years, classification report on the 2026 holdout).

## Next steps

- Add features beyond raw qualifying pace: team/driver season form, historical Monza performance, grid penalties, weather.
- Try a Neural Network approach and compare against the current baselines.
- More training data (other tracks, more seasons) to better support the minority Podium class.
