# age-gender-image-search-bias

Reproducing key results from a Nature study (Guilbeault et al., 2024) on how online image search amplifies gender and age bias. Using GPT-2 Large embeddings I measure the age and gender associations of thousands of social categories, and analyse an experiment on how image-based search shifts people's age estimates.

## Files

- `age_gender_distortion.ipynb` — the main notebook containing all analyses and visualizations
- `myData/GPT2-large-dimensions.csv` — GPT-2 Large embeddings with age and gender association scores for 3,495 social categories
- `myData/experiment_control.csv` — age estimates from the control group
- `myData/experiment_treatment.csv` — age estimates from the treatment group
- `plots/` — all generated plots in SVG format and one interactive HTML file
- `requirements.txt` — Python version and library dependencies

## Note

The notebook was written to be read as a standalone document, independently of the assignment. Throughout the notebook I explain what the article does, why each analysis is performed, and what the results mean, so that someone with no prior knowledge of the assignment can follow it.
