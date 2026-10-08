# Indian Diet Fitness Tracker 🥗

A personalized fitness tracker designed for Indian dietary patterns, with a focus on accurate calorie/macronutrient estimation, healthcare-aware recommendations, and sustainable long-term tracking.

## Project overview

This repository contains the data assets and analysis used to build FitDhaba, a nutrition and fitness assistant tailored to Indian foods, meals, and health conditions.

The project currently centers on:
- Indian food nutrition data
- packaged food dataset for India
- exploratory analysis and model-building notebook(s)
- architecture and research notes

## Repository structure

```text
fitness-tracker/
├── .gitignore
├── README.md
├── docs/
│   ├── architecture.md
│   └── research.md
├── data/
│   ├── README.md
│   ├── raw/
│   │   ├── README.md
│   │   ├── Indian_Food_Nutrition_Processed.csv
│   │   └── packaged_foods_india.csv
│   └── processed/
│       └── README.md
├── notebooks/
│   ├── README.md
│   └── Indian_Foods_Combined_Analysis.ipynb
├── assets/
│   └── README.md
└── legacy/
    └── README.md
```

## What is inside

### Data
The repository stores food and nutrition records under `data/`.
- `data/raw/` holds source datasets and unprocessed files.
- `data/processed/` is reserved for cleaned, merged, or derived datasets.

### Analysis
The notebook used for analysis and prototyping lives under `notebooks/`.

### Documentation
- `docs/architecture.md` describes the overall product and system design.
- `docs/research.md` stores background research notes and documentation.

### Assets
Visuals such as architecture diagrams can live under `assets/`.

## Recommended workflow

1. Keep raw source files in `data/raw/`.
2. Clean or transform data into `data/processed/`.
3. Use notebooks in `notebooks/` for experiments and validation.
4. Keep product design, architecture, and research notes under `docs/`.
5. Avoid committing local artifacts, notebook checkpoints, or generated outputs.

## Typical use cases

- Track Indian foods by nutrient content
- Estimate calories and macros for home-cooked meals
- Use nutrition research to support health-condition-aware recommendations
- Build personalized dietary plans using food and lifestyle data

## Planning notes

This repository is currently structured as a data-science / research project and can evolve into a full application stack later.
Suggested future expansion:
- `src/` for Python modules or backend logic
- `app/` for dashboard or web app
- `tests/` for validation and QA
- `ml/` for model training modules
- `config/` for dataset or app configuration

## Quick start

1. Review the raw data in `data/raw/`.
2. Open the analysis notebook in `notebooks/`.
3. Use the architecture docs in `docs/architecture.md` to understand the system.
4. Add cleaned datasets to `data/processed/` once transformations are finalized.

## Notes

This repository is intentionally being reorganized to make the project easier to navigate, maintain, and scale as it grows.

---

For a detailed design summary, see `docs/architecture.md`.
