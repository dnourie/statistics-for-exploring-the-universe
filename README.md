# Statistics for Exploring the Universe

A beginner-friendly statistics course taught through astronomy examples.

The central idea of the course is simple: **we use statistics because
astronomical observations are incomplete, noisy, variable, and uncertain, and we
want to determine what the universe is actually telling us.**

## Course Map

1. `notebooks/01_describing_starlight.ipynb` - mean, median, spread, outliers
2. `notebooks/02_measurement_noise.ipynb` - repeated measurements and uncertainty
3. `notebooks/03_distributions_in_astronomy.ipynb` - histograms and distribution shape
4. `notebooks/04_probability_and_photon_counts.ipynb` - probability and random events
5. `notebooks/05_normal_and_poisson_distributions.ipynb` - two common astronomy distributions
6. `notebooks/06_correlation_in_the_cosmos.ipynb` - relationships between variables
7. `notebooks/07_linear_regression.ipynb` - fitting lines and interpreting residuals
8. `notebooks/08_sampling_and_uncertainty.ipynb` - samples, populations, and confidence intervals
9. `notebooks/09_signal_or_noise.ipynb` - introductory hypothesis testing
10. `notebooks/10_bayesian_thinking.ipynb` - priors, evidence, and updated belief

## How To Use This Course

Open the notebooks in order. Each lesson starts with an astronomy question,
then introduces the statistical tool needed to answer it. Do not rush the
interpretation cells. The goal is to learn what the statistic means physically,
not only how to compute it.

The cheat sheet in `reference/statistics_cheat_sheet.md` is intentionally
incremental. It should only contain concepts after they have appeared in the
course, so it becomes a record of ideas you actually understand.

The course also starts with simulated star measurements on purpose. Real
astronomy data is fascinating, but it can be messy in ways that hide the
statistical idea. Once a concept feels clear, later notebooks can swap in real
light curves or catalogs and study the additional weirdness nature adds.

## Setup

Create an environment and install the requirements:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
jupyter lab
```

The first version of the course uses simulated data so you can focus on the
ideas. Real astronomical data can be added later after each statistical concept
feels familiar.
