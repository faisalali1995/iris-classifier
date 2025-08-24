\# Iris Classifier (Decision Tree)



\## Overview

End-to-end ML example that trains a Decision Tree on the Iris dataset using scikit-learn.



\## Quick start

```bash

python -m venv venv

\# Windows

.\\venv\\Scripts\\Activate.ps1

pip install -r requirements.txt

python src\\train.py --test-size 0.2 --random-state 42

Project structure

cpp

Copy

Edit

iris-classifier/

├── data/

├── notebooks/

│   └── iris\_model.ipynb  (optional walkthrough)

├── src/

│   └── train.py

├── tests/

├── outputs/

├── .gitignore

├── LICENSE

├── README.md

└── requirements.txt

