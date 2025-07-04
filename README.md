# Audio Feature Engineering & Classification Pipeline

**Features:**

->Extracted 50+ audio features (MFCCs, ZCR, spectral, RMS, tempo) using Librosa & SciPy for downstream analysis

->Engineered robust preprocessing for 1.5K+ audio samples with leak-free train/test split, z-score normalization, and CSV export.

->Reduced dimensions using PCA; clustered with K-Means & DBSCAN; evaluated by silhouette & ARI.

->Grid searched Random Forest, Logistic Regression & XGBoost; implemented ensemble voting for classification accuracy.
