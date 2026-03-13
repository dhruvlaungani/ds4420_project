# ds4420_project

# Detecting Song "Breakout" on Spotify
## Predicting Chart Success from Initial Stream Trajectories Using AR/MA and Bayesian Regression
**DS 4420 — Spring 2026 | Lucas Tolman & Dhruv Laungani**

---

## Project Overview
Can you predict whether a song will be a Top 10 hit after just 2–3 weeks on the charts? This project builds a two-stage pipeline:

1. **Stage 1 (AR/MA):** Fit AR(p) and MA(q) models to a song's first 21 days of daily Spotify streams to extract early momentum features.
2. **Stage 2 (Bayesian Regression):** Combine those trajectory features with static audio attributes (danceability, energy, valence, etc.) in a Bayesian regression model to produce a probabilistic Top 10 prediction.

---

## Phase I Contents
- `literature_review.pdf` — lit review covering our approach
- `spotify_merged.csv` - proof that we started. We have cleaned the data and merged it. Hopefully that is enough
---

## Datasets
| Dataset | Source | Description |
|---|---|---|
| Spotify Charts | [Kaggle (Dave, 2022)](https://www.kaggle.com/datasets/dhruvildave/spotify-charts) | 26.2M daily chart entries, 2017–2021, 73 regions |
| Spotify Tracks | [Kaggle (Pandya, 2023)](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-dataset) | Audio features for 114,000 tracks |
