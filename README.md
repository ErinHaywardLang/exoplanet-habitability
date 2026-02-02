# exoplanet-habitability

## 🎯 Project Aims

The goal of this project is to design and implement an **interpretable, data-driven habitability scoring system for confirmed exoplanets**, using publicly available astronomical data from the **NASA Exoplanet Archive**.

Because there is no ground-truth label for extraterrestrial life, this project **does not attempt binary classification** (habitable vs. non-habitable). Instead, it frames habitability as a **continuous ranking problem**, producing a relative score that measures how similar each known exoplanet is to Earth in terms of physical and orbital characteristics.

Specifically, this project aims to:

* Aggregate and clean high-quality **exoplanet and stellar data** using the *Planetary Systems Composite* dataset, including measurement uncertainties where available.
* Engineer **Earth-normalised features** that reflect known physical constraints relevant to habitability (e.g. planetary size, mass, orbital dynamics, stellar energy).
* Construct a **continuous habitability index** that scores and ranks exoplanets on a scale from least to most Earth-like.
* Apply **interpretable machine learning models** to learn the relative importance of planetary and stellar features, prioritising transparency over raw predictive performance.
* Quantify and communicate **uncertainty in habitability scores** by incorporating observational errors and data completeness.
* Produce an **exploratory and visual ranking of exoplanets**, enabling comparison against Earth and identification of promising candidates for further scientific investigation.

