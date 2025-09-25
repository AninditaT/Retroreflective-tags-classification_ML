🐝 **Distinguishing Coloured Retroreflective tags on insects using ML**

This repository contains the implementation of my M.Sc. Data Analytics dissertation project at the University of Sheffield. The project focuses on using machine learning and computer vision to classify up to 40 retroreflective bee tags under complex tracking conditions — supporting scalable and accurate tracking for ecological research.

📌 **Project Overview**

Traditional methods of tracking bees are limited in scale, cost, and precision. This project enhances retroreflective tag–based tracking by applying machine learning to distinguish multiple colored tags, enabling simultaneous tracking at distances up to 20–25m.

🚀 **Key Contributions**

Developed a preprocessing pipeline: image cropping, Bayer channel splitting, RGB intensity extraction, normalization.

Trained and optimized K-Nearest Neighbors (KNN) and Random Forest models with cross-validation & hyperparameter tuning.

Achieved up to 92.5% accuracy (consistent 85% across scenarios) for multi-tag classification.

Evaluated performance using precision, recall, F1-score, and confusion matrices.

Proposed improvements for scaling to real-world field studies.

🛠️ **Tech Stack**

Languages/Frameworks: Python, scikit-learn, NumPy, Pandas, Matplotlib

Data Processing: JSON metadata parsing, Bayer channel manipulation, RGB feature engineering

ML Methods: KNN, Random Forest, cross-validation, hyperparameter tuning

Evaluation: Accuracy, Precision, Recall, F1, Confusion Matrices

📊 **Results**

Successfully classified 34 out of 40 tags at 20m distance with >85% accuracy.

KNN consistently outperformed Random Forest across longer distances.

Provided scalable methodology for multi-bee tracking at low cost.

📖 **Dissertation Reference**

This work was completed as part of my MSc in Data Analytics under the supervision of Dr. Michael Smith (University of Sheffield).
