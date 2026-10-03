# Predicting Serious or Fatal Road Collisions in Great Britain

A supervised machine learning project (binary classification) that predicts whether a road collision was serious or fatal rather than slight, using scene conditions such as road type, speed limit, junction, lighting, weather and time of day.

**Dataset:** Department for Transport, *Road Safety Data: Collisions, 2025*, published as open data under the Open Government Licence. Source: https://www.gov.uk/government/statistical-data-sets/road-safety-open-data

## Files

- `modeling.ipynb`: the full workflow (data loading, preparation, model comparison, tuning, evaluation, summary)
- `Machine_Learning_Analysis_Report.pdf`: written report with citations
- `requirements.txt`: package versions created with `pip freeze`
- `dft-road-casualty-statistics-collision-2025.csv`: the dataset
- `figures/`: charts produced by the notebook

## How to Run

```
git clone https://github.com/dohigg1987/road-collision-severity-ml-project.git
cd road-collision-severity-ml-project
pip install -r requirements.txt
jupyter notebook modeling.ipynb
```

The notebook uses a fixed random seed (42). A full run takes a few minutes.
