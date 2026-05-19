# lab-mlops-dev-prod
# MLOps Deployment Workflow Lab

## Project description

This project is a simple machine learning workflow created to practise a real DEV → PROD process.

The goal is to simulate how a developer creates code in a separate branch, opens a Pull Request, and a gatekeeper reviews and tests the project before merging it into production.

## Project contents

- `main.ipynb`: machine learning notebook.
- `requirements.txt`: Python dependencies needed to reproduce the project.
- `.gitignore`: files and folders excluded from Git.
- `README.md`: project documentation.

## Machine Learning task

The notebook trains a Random Forest classifier using the Iris dataset.

The workflow includes:

1. Loading the dataset.
2. Creating a pandas DataFrame.
3. Splitting the data into train and test sets.
4. Training a Random Forest model.
5. Evaluating the model with accuracy.
6. Displaying a confusion matrix.
7. Showing feature importance.

## How to recreate the environment

Create a virtual environment:

```bash
python3 -m venv .venv
source .venv/bin/activate
