📦 End_To_End_ML_Project/
│
├── 📂 src/
│   ├── 📂 components/
│   │   ├── data_ingestion.py        # Load & split data
│   │   ├── data_transformation.py   # Feature engineering
│   │   └── model_trainer.py         # Train & evaluate models
│   │
│   ├── 📂 pipeline/
│   │   ├── train_pipeline.py        # Orchestrates training
│   │   └── predict_pipeline.py      # Inference pipeline
│   │
│   ├── exception.py                 # Custom exception handler
│   ├── logger.py                    # Logging configuration
│   └── utils.py                     # Shared utility functions
│
├── 📂 notebooks/                    # EDA & experimentation
├── 📂 artifacts/                    # Saved models & preprocessors
├── 📂 logs/                         # Auto-generated log files
│
├── setup.py
├── requirements.txt
└── README.md
