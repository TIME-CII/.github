# TIME Repository
This repo contains code that is a part of the [TIME collaboration](https://ui.adsabs.harvard.edu/abs/2014SPIE.9153E..1WC/abstract).

## Repository Organization
Design zen: These repositories are organized by the data product they use/produce. E.g. `TIME-analysis` uses `netCDF` files.

1. ``TIME-rx``: Receiver and lab analysis codes.
2. ``TIME-DAQ``: Data acquisition GUI.
3. ``TIME-kms``:  K-mirror codes.
4. ``TIME-sims``: Simulations for TIME (astrophysical sources simulation and telescope simulation).
5. ``TIME-analysis``: Analysis pipeline, mapmaking.

## Instructions
1. Choose the repository that your code fits in most. If nothing fits, let the collaboration knows!
2. When writing new code, create a new branch (100% safe!), commit to the new branch.
3. When writing new code, make sure to write documentation following the `sphinx` format.
4. When your branch is ready for sunlight, create a pull request, it will be reviewed and merge with the main branch afterward.
5. Please update the collaboration with your new pull request.

**Dos and don'ts:**

1. Don't ``git push`` large files (~Megabytes).
2. Do create branches when writing new code.
3. Documentation is (very) good.
