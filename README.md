# Live 5G Positioning: Joint ToA + Carrier Phase under Correlated Errors

Interactive demo accompanying the IEEE GLOBECOM 2026 Workshop paper:

**"Accuracy of Joint Time-Based and Carrier-Phase Positioning in 5G Networks under Correlated Measurement Errors"**
Nahidul Islam, Mohammad Razzaghpour, Marwan Hammouda, Carsten Bockelmann, Armin Dekorsy
University of Bremen, Germany

**Live demo:** https://nahidmasoom.github.io/5g-toa-cp-positioning/

## What it shows
- 7-BS hexagonal 5G layout (UMa and InF scenarios, 3GPP path loss)
- Draggable mobile terminal with live ToA, ToA+CP (ρ = 0) and correlation-aware ToA+CP position fixes
- Error clouds, running RMSE, and the gain from exploiting ToA/CP error correlation
- Sliders for ρ, bandwidth, carrier frequency, Tx power, antenna elements, and number of BSs

## Note
The demo uses CRB-style scaling constants, so the absolute RMSE values are illustrative, not the paper's Monte Carlo results. The trends match the paper.

## Run locally
Open `index.html` in a browser. No build step or dependencies.

## Citation
```
@inproceedings{islam2026toacp,
  title     = {Accuracy of Joint Time-Based and Carrier-Phase Positioning in 5G Networks under Correlated Measurement Errors},
  author    = {Islam, Nahidul and Razzaghpour, Mohammad and Hammouda, Marwan and Bockelmann, Carsten and Dekorsy, Armin},
  booktitle = {IEEE GLOBECOM Workshops},
  year      = {2026}
}
```
