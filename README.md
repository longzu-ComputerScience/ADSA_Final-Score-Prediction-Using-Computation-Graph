# Final Exam Score Prediction Using Computational Graph

Predict final exam scores from midterm scores using **Linear Regression** with **PyTorch autograd** and **manual Gradient Descent**.

## Project Structure

```
├── Data/TRAIN2.xlsx                                    # Dataset (midterm & final scores)
├── Slide/                                              # Lecture slide (reference)
├── Homework/FinalScorePrediction_ComputationalGraph.ipynb  # Main notebook
├── requirements.txt
└── README.md
```

## Setup

```bash
pip install -r requirements.txt
```

## Run

```bash
jupyter notebook
```

Then open `Homework/FinalScorePrediction_ComputationalGraph.ipynb`.

## Output

The notebook trains a linear model `y = w * x + b` and prints:

- Trained weight **w**
- Trained bias **b**
- Final training **MSE**
- A prediction demo comparing actual vs. predicted scores
