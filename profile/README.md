# TIME Repository
This repo contains code that is a part of the [TIME collaboration](https://ui.adsabs.harvard.edu/abs/2014SPIE.9153E..1WC/abstract).

## Repository Organization
*Design zen*: These repositories are organized by the data product they use/produce. E.g. `TIME-analysis` uses `netCDF` files.

1. `TIME-rx`: Receiver and lab analysis codes.
2. `TIME-DAQ`: Data acquisition GUI.
3. `TIME-kms`:  K-mirror codes.
4. `TIME-sims`: Simulations for TIME (astrophysical sources simulation and telescope simulation).
5. `TIME-analysis`: Analysis pipeline, mapmaking.

## Instructions
1. Choose the repository that your code fits in most. If nothing fits, let the collaboration knows!
2. When writing new code, create a new branch (100% safe!), commit to the new branch.
3. When writing new code, make sure to write documentation following the `sphinx` format.
4. When your branch is ready for sunlight, create a pull request, it will be reviewed and merged with the main branch afterward.
5. Update the collaboration with your new pull request.

**Dos and don'ts:**

- Don't `git push` large files (~Megabytes). Don't `git push` data files (e.g. plots, `netCDF`). Use `.gitignore`.
- Create branches when writing new code.
- Create issues to keep track of what you and others are working on.
- Documentation is (very) good.
- Communication is (very) good.

## Contacts

 - `TIME-rx`: Abby Crites, Sukhman Singh
 - `TIME-DAQ`: Victoria Butler, Ben Vaughan
 - `TIME-kms`: Victoria Butler, Evan Mayer
 - `TIME-sims`: Dang Pham
 - `TIME-analysis`: Ryan Keenan

