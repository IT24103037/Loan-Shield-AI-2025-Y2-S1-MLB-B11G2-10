LoanShield AI — Default Prediction (Progress Review I)

Team
IT Number	Name	Role (Preprocessing focus)
IT24103089	Bandara M.M.S.D.	Missing values
IT24103056	Jpgnanatheepan N.	Categorical encoding
IT24103037	Marasingha M.T.N.	Outliers
IT24102987	Liyana Arachchi L.A.S.I. Scaling / Normalization
IT24103059	Premasekara J.J. Feature selection
IT24103112	Navodya M.K.N.	Imbalance analysis & data split


Dataset

Source: Kaggle — Finance Default Prediction

Target column: Default (0/1)

Notes: We avoid feature leakage (only features known at application time).

Repository Layout
Group_ID/
├─ README.md
├─ data/
│  ├─ raw/            # Original dataset(s)
│  └─ external/       # Any external reference datasets (if used)
├─ notebooks/
│  ├─ IT24103089_MissingValues.ipynb
│  ├─ IT24103056_CategoricalEncoding.ipynb
│  ├─ IT24103037_Outliers.ipynb
│  ├─ IT24102987_Scaling_PCA.ipynb
│  ├─ IT24103059_FeatureSelection.ipynb
│  ├─ IT24103112_Splits_Imbalance.ipynb
│  └─ group_pipeline.ipynb        # Integrated pipeline (combined work)
└─ results/
   ├─ eda_visualizations/         # PNG/JPEG plots
   └─ outputs/                    # Processed CSVs, models, reports
