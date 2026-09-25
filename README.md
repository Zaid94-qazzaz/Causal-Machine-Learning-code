# Causal Machine Learning for Flood Occurrence Assessment Using a Proxy Infrastructure Indicator

This repository contains the source code and implementation used in the study **“Causal Machine Learning for Flood Occurrence Assessment Using a Proxy Infrastructure Indicator.”**

The project applies causal machine learning methods to investigate treatment contrasts associated with a **proxy infrastructure indicator** and flood occurrence using georeferenced observational data.

## Repository Contents

If you are interested in understanding, reproducing, or extending this work, this repository provides:

- **Source Code:** Scripts and computational procedures used for data processing, causal inference, Causal Forest analysis, robustness analysis, treatment-effect estimation, and model interpretation.
- **Causal Analysis:** Implementation of the causal machine learning framework used to estimate average and heterogeneous treatment effects.
- **Model Interpretation:** Procedures for feature-importance and SHAP analyses used to examine predictors associated with variation in the estimated treatment effects.
- **Robustness and Validation:** Code for sensitivity, subgroup, and related validation analyses presented in the study.

## Treatment Variable

The analysis uses a binary **Infrastructure** variable available in the analytical dataset as a **proxy treatment indicator**.

This variable should not be interpreted as a verified inventory of physical flood-protection infrastructure. In particular, `T = 1` does not necessarily indicate the verified physical presence of a specific structure such as a levee, drainage system, flood barrier, or retention basin, and `T = 0` does not necessarily indicate verified physical absence.

Accordingly, the estimated treatment effects should be interpreted as treatment contrasts associated with the **proxy infrastructure classification**, rather than as direct causal effects of installing, removing, or operating a specific physical infrastructure intervention.

## Data Availability

The analytical dataset used in the study is not publicly distributed with this repository.

The dataset supporting the findings of the study is available from the corresponding author upon reasonable request.

## Reproducibility

The provided source code is intended to support transparency and reproducibility of the analytical workflow described in the manuscript.

Users interested in reproducing or extending the analysis are encouraged to review the code and the methodological description in the associated publication.

## Citation

If you use this code or build upon this work, please cite the associated publication:

> Zaid Adil Abdulsahib AL-QAZZAZ, Yasin PAŞA, and Elham PASHAEI. *Causal Machine Learning for Flood Occurrence Assessment Using a Proxy Infrastructure Indicator.*

## License

Please refer to the repository license for terms governing the use and redistribution of the source code.

## Contact

For questions regarding the dataset or the study, please contact the corresponding author.
