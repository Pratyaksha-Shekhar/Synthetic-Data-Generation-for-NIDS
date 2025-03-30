Synthetic Data Generation for Network Intrusion Detection Systems (NIDS)
Introduction:
Developed a machine learning pipeline leveraging CT-Generative Adversarial Networks (CT-GAN) to generate 100% synthetic data for training Network Intrusion Detection Systems (NIDS). This approach mitigates data imbalance issues, reduces data collection costs, and enhances the ethical viability of model training.

Improvements:

Generated fully synthetic data for the CIC-IDS2017 dataset, reducing dependency on real-world data by 100%.

Improved NIDS classification accuracy, achieving 95% for Gradient Boosting, 94% for Random Forest, 91% for KNN, and 92% for SVM.

Applied PCA-based feature selection and StandardScaler normalization, enhancing model interpretability and training efficiency.

Conducted statistical validation using distribution similarity tests to ensure realistic synthetic data generation.

Tech Stack:
Python, Pandas, NumPy, CTGAN, Matplotlib, Seaborn, SciPy, Scikit-learn, PCA, StandardScaler.
