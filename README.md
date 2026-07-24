# Xgboost-based-Multi-steps-Cybersecurity-Attacks-Detection-Model-1

├── data/
│   ├── raw/                 # Original dataset files (e.g., UNSW-NB15, NSL-KDD, CIC-IDS)
│   ├── processed/           # Cleaned and feature-engineered data
│   └── README.md            # Notes about dataset sources and licenses
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_feature_engineering.ipynb
│   └── 03_model_experiments.ipynb
├── src/
│   ├── config.py            # Global configuration (paths, constants, model params)
│   ├── data_preprocessing.py
│   ├── feature_engineering.py
│   ├── models/
│   │   ├── xgboost_trainer.py
│   │   └── postprocessing.py
│   ├── evaluation.py
│   └── api/
│       └── app.py           # Optional: FastAPI/Flask app for inference
├── models/
│   └── xgboost_multistep_model.json
├── scripts/
│   ├── train.py
│   ├── evaluate.py
│   └── predict.py
├── requirements.txt
├── LICENSE
└── README.md
