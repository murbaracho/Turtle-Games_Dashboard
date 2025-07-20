# Turtle Games Loyalty Analytics – DA301 Final Project  
Monica Baracho • July 2025

## 1 Project overview
This repo contains the full analysis for Turtle Games’ customer-loyalty programme:
* **Python notebook** – exploratory analysis, modelling, segmentation (`Baracho_Monica_DA301_Assignment.ipynb`)
* **R script** – replication of Modules 5–6 tasks (`Baracho_Monica_DA301_Assignment.R`)
* **Report & slides** – technical PDF and business-facing PPTX
* **Data** – raw and cleaned review datasets (`/data/raw`, `/data/processed`)
* **Outputs** – model artefacts and graphics ready for the report

## 2 Quick start
```bash
# create and activate the Conda env
conda env create -f environment.yml
conda activate turtle-loyalty

# optional: install R deps
R -e "install.packages(c('tidyverse','ggplot2','textstem'))"

# run the notebook end-to-end
jupyter notebook Baracho_Monica_DA301_Assignment.ipynb

## 3 Reproducing results

The notebook and R script both run cleanly in the provided environment and will:

Load the cleaned dataset (turtle_reviews_clean.csv)
Re-create all figures and tables used in the report
Export graphics to /outputs for direct inclusion in the report/slides
