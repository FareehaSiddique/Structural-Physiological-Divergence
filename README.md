# Structural–Physiological Divergence

This repository contains the Python notebooks used to analyze and visualize the results presented in *Atmospheric dryness amplifies structural but buffers physiological variability in forests* (Siddique et al., 2026).

## Information-Flow Calculation

Multivariate, time-varying Liang–Kleeman information flow (LKIF) was calculated using the MATLAB functions and scripts available at https://doi.org/10.5281/zenodo.23409186. The resulting information-flow estimates are presented in Figure 2 and further analyzed in Figures 3 and 4.

## Repository Structure

- **`Regime_Classification.ipynb`**: Classifies monthly hydroclimatic conditions based on region-specific soil moisture (SM) and vapor pressure deficit (VPD) terciles and calculates the occupancy of concurrent land–atmosphere dryness (ConLAD) and wet regimes over rolling 60-month windows (Figure 1a–b).

- **`ConLAD_Persistence_&_EntryProbability.ipynb`**: Quantifies ConLAD persistence and changes in entry probability (ΔP) between the pre-2000 and post-2000 periods (Figure 1c).

- **`Dominant_CouplingPathways_during&around_ConLAD_onset.ipynb`**: Identifies the dominant climate–vegetation coupling pathway during ConLAD and examines the temporal evolution of all four pathways within ±12 months of ConLAD onset (Figure 3a–b).

- **`WUE_&_Information_Flow.ipynb`**: Examines how climate–vegetation coupling pathways vary along the inherent water-use efficiency (iWUE) gradient under sustained low-SM/high-VPD conditions (Figure 4a).

- **`Isohydricity_&_Information_Flow.ipynb`**: Examines how climate–vegetation coupling pathways vary across region-specific isohydricity (β) classes (Figure 4b).

## Note on Terminology

Some scripts may still use the term "drought regime", which was used in an earlier version of the analysis. This term has since been revised to "Concurrent Land–Atmosphere Dryness (ConLAD) regime" to more accurately describe the simultaneous occurrence of low SM and high VPD. Both terms refer to the same regime, and the revision does not affect its definition or classification criteria.

