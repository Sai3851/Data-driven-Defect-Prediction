# Data-driven-Defect-Prediction
This repository contains a series of experiments focused on defect prediction in software projects using bug data. The models explore variations in training and testing datasets, encoder networks, and the impact of domain adaptation across three scenarios.
## Single-Project Model - copy_of_test model
This notebook features an encoder model built on a single dataset from the "Eclipse" project, sourced from public datasets on platforms like Kaggle. The model is trained on 80% of the dataset, with the remaining 20% reserved for testing, providing baseline metrics for defect prediction within a single project.
## Multi-Dataset, Single-Project Model with Domain Adaptation - copy_copy_of_AEEM
This notebook applies an encoder model to four datasets within a single project, AEEM. Two datasets are used for training and two for testing, incorporating domain adaptation techniques to assess model performance within the same project environment.
## Cross-Project Model with Domain Adaptation - copy_of_AEEM-JIRA
This notebook addresses cross-project defect prediction by utilizing datasets from two different projects, AEEM and JIRA. Domain adaptation is applied, demonstrating the model's capability to generalize and adapt to data from disparate sources.
## Comparative Analysis of Model Efficiency and Metrics
The notebooks include a detailed comparison of model efficiency and performance metrics across all scenarios, highlighting the effects of domain adaptation, cross-project data, and multi-dataset training on defect prediction accuracy.
