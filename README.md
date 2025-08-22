# hmt_dashbaord

This project includes:
- An **R pipeline** for cleaning/exporting survey data
- A **Tableau workbook** with dashboards and charts
- (Optional) a **Jupyter notebook** for supplemental geospatial reports

---

## Architecture

![Pipeline diagram](docs/pipeline.png)

---

## Quick Start

1. Place raw survey files in `data/raw/`
2. Run the R pipeline:
   ```bash
   Rscript pipeline/run.R
