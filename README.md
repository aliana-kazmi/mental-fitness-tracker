# AI Mental Fitness Tracker

A machine learning project designed to analyze and track mental fitness using data-driven techniques. This notebook walks through data cleaning, exploratory analysis, model building, and evaluation to understand and predict mental fitness levels.

---

## Project Structure

```
├── ai-mental-fitness-tracker.ipynb     # Main Jupyter Notebook
├── data_sources/
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

The model performance for training set
--------------------------------------
MSE is 0.005276217088551818

RMSE is 0.07263757353155334

R2 score is 0.999018080885132


The model performance for testing set
--------------------------------------
MSE is 0.030082319628787615

RMSE is 0.1734425542615987

R2 score is 0.993746436032746

These results indicate that the model performs with high accuracy both during training and on unseen test data, showing strong generalization capabilities.

---

## Contributing

Have ideas or suggestions? Feel free to fork the repo, open an issue, or submit a pull request.
