```md
# Data Directory

This project uses photometric light curve data from the NASA TESS mission.

Due to data size considerations, raw light curve files are not stored in this repository.
All data are downloaded programmatically using the Lightkurve package.

---

## Data Source

- Mission: TESS (Transiting Exoplanet Survey Satellite)
- Archive: NASA MAST
- Access method: Lightkurve API

---

## Reproducibility

All datasets used in this project can be reproduced by running the notebooks in order.
No manual data download is required.

Data acquisition is handled in:

- `02_data_loading.ipynb`
