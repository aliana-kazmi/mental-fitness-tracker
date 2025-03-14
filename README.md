# AI Mental Fitness Tracker

A machine learning project designed to analyze and track mental fitness using data-driven techniques. This notebook walks through data cleaning, exploratory analysis, model building, and evaluation to understand and predict mental fitness levels.

---

## Project Structure

```
├── ai-mental-fitness-tracker.ipynb     # Main Jupyter Notebook
├── data-sources/
│   └── mental-and-substance-use-as-share-of-disease.csv # Dataset used in the project
│   └── prevalence-by-mental-and-substance-use-disorder.csv # Dataset used in the project
└── README.md                           # Project documentation
```

---

## Features

- Preprocessing of raw mental fitness data
- Data visualization and correlation analysis
- Training multiple classification models
- Evaluating model performance
- Drawing insights from predictions

---

## Technologies

- Python 3
- Pandas, NumPy — Data manipulation
- Seaborn, Matplotlib, Plotly — Data visualization
- Scikit-learn — Machine learning models
- Jupyter Notebook — Development environment

---

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ai-mental-fitness-tracker.git
   cd ai-mental-fitness-tracker
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Run the Jupyter notebook:

   ```bash
   jupyter notebook ai-mental-fitness-tracker.ipynb
   ```

---

## Results

### Training Set

- MSE: 0.00123
- RMSE: 0.0351
- R² Score: 0.9985

### Testing Set

- MSE: 0.00621
- RMSE: 0.0788
- R² Score: 0.9928

These results indicate that the model performs with high accuracy both during training and on unseen test data, showing strong generalization capabilities.

---

## Contributing

Have ideas or suggestions? Feel free to fork the repo, open an issue, or submit a pull request.
