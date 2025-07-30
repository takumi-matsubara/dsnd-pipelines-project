# Important Note
Submission repository is main branch. The develop branch is for work, so please refer to the main branch.

# Data Science Pipeline Project

Binary-classification pipeline that predicts whether a customer recommends a
product (`Recommended IND`) using numerical, categorical, and text features
from 18 k retail reviews.

## Getting Started

Fork and clone the repository, create a virtual environment, install dependencies, and
launch the notebook.
1. Press fork button at the upper right of your screen.
2. Run the following git command at your local CLI.
```bash
git clone git clone https://github.com/<your-fork>/dsnd-pipelines-project.git
```
3. Open the cloned folder, then follow Installation section.

### Dependencies

- Python 3.9+
- scikit-learn
- spaCy
- Pandas
- Numpy
- Matplotlib
- Seaborn

### Installation

1. Create & activate a virtual environment
```bash
python -m venv venv
# macOS / Linux
source venv/bin/activate
# Windows
venv\Scripts\activate
```

2. Install Python packages
```bash
pip install -r /requirements.txt
```

3. Launch jupyter notebook
```bash
jupyter notebook
```

## Testing

Run every cell in starter.ipynb.
The notebook performs cross-validation, hyper-parameter tuning, and evaluates
the final model on a hold-out test set.

### Break Down Tests

- RandomizedSearchCV (cv = 4, n_iter = 12) – trains 12 random hyper-parameter(In this case, all combinations of parameters) combinations with 4-fold cross-validation.

## Project Instructions

Deliverables for grading:

- starter.ipynb – fully executed with visible outputs.

- README.md – this file.

## Built With

- scikit-learn – machine-learning framework
- spaCy – NLP preprocessing
- Matplotlib – result visualisation

Include all items used to build project.

## License

[License](LICENSE.txt)
