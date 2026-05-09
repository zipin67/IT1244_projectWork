## Application of supervised training models to a utility fraud dataset

We implemented a KNN and RF model to classify utility fraud cases. The model was trained
based on a 80/20 split. The code preprocesses the data sheets before performing training and
cross-validation for the KNN model, followed by training and cross-validation for the RF
model. Confusion matrices and ROC curves are also printed as part of data visualisation.

## How to Run
1. Clone repository 
```
git clone <your-repo-url>
```

2. Create virtual environment
```
pip -m venv .venv
```

3. Activate virtual environment
```
source .venv/bin/activate
```

4. Install requirements
```
pip install -r requirements.txt 
```

5. Run notebook in Code/IT1244_Project_Work.ipynb
