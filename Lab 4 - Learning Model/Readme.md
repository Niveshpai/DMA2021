## Traveler Dataset: Preparation of Learning Model

### Points to follow:

[1] Use the traveler_dataset folder from Lab3 repository + sessions.csv file from google drive link.

[2] Install the XGBooster package

- Linux installation of xgboost package via terminal (run):

    conda install -c conda-forge py-xgboost
    
- For Windows/Mac run on Anaconda terminal:

      conda install -c conda-forge py-xgboost

- After installing run following code in IPYNB cell to verify
    
    import xgboost as xgb
    
    print (xgb.VERSION_FILE)

- The output cell need to display version path
    
    /../../anaconda3/lib/python3.6/site-packages/xgboost/VERSION

