# VSBM

This repository accompanies the paper "Volumetric and Surface Characteristics of Gray Matter in Adult Dyslexia and Dyscalculia". Files include:

```
├── cortical_complexity/cortical_thickness/gyrification/sulcal_depth
│   ├── spmF_0001.gii: main effect of dyslexia
│   ├── spmF_0002.gii: main effect of dyscalculia
│   ├── spmF_0003.gii: interaction
│   ├── spmF_0004.gii: one-way ANOVA
│   ├── spmF_0005.gii: main effect of comorbidity
│   ├── XX_main-effect-dyslexia_left.func.gii: BF01 maps for main effect of dyslexia (left hemisphere)
│   ├── XX_main-effect-dyslexia_right.func.gii: BF01 maps for main effect of dyslexia (right hemisphere)
│   ├── XX_main-effect-dyscalculia_left.func.gii: BF01 maps for main effect of dyscalculia (left hemisphere)
│   ├── XX_main-effect-dyscalculia_right.func.gii: BF01 maps for main effect of dyscalculia (right hemisphere)
│   ├── XX_main-effect-comorbidity_left.func.gii: BF01 maps for main effect of comorbidity (left hemisphere)
│   ├── XX_main-effect-comorbidity_right.func.gii: BF01 maps for main effect of comorbidity (right hemisphere)
│   ├── XX_one-way-ANOVA_left.func.gii: BF01 maps for one-way-ANOVA (left hemisphere)
│   ├── XX_one-way-ANOVA_right.func.gii: BF01 maps for one-way-ANOVA (right hemisphere)
```

```
├── scripts
│   ├── 01_XX.mat - 13_XX.mat: preprocessing and modeling scripts
```

```
├── supplemental_analyses
│   ├── cortical_complexity/cortical_thickness/gyrification/sulcal_depth/volume
│   │   ├── IQR_covariate
│   │   │   ├── spmF_0001.gii/nii: main effect of dyslexia
│   │   │   ├── spmF_0002.gii/nii: main effect of dyscalculia
│   │   │   ├── spmF_0003.gii/nii: interaction
│   │   │   ├── spmF_0004.gii/nii: one-way ANOVA
│   │   │   ├── spmF_0005.gii/nii: main effect of comorbidity
│   │   ├── regression
│   │   │   ├── math/reading/reading_and_math
│   │   │   │   ├── spmF_0001.gii/nii: regression with math/reading/reading_and_math scores as predictors
```


`IQR_plot.png: quality rating for all analyses, plotted by group`

`behavioral_measures.png: violin and box plots for all behavioral measures, broken down by group`

`posthoc_comp_XX.png: posthoc comparisons across groups, for all behavioral measures`

`quality_control.csv: weighted average for preprocessing and image quality, for all subjects`

Link to NeuroVault: https://neurovault.org/collections/4145/

Please cite as: Moreau, D., Wiebels, K., Wilson, A. J., & Waldie, K. E. (2018). Volumetric and Surface Characteristics of Gray Matter in Adult Dyslexia and Dyscalculia.

Suggestions or comments? Please send an email to d.moreau@auckland.ac.nz
