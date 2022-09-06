# Acoustic-Extinguisher-Fire-Data

Yavuz Selim TASPINAR, Murat KOKLU and Mustafa ALTIN
Citation Request :
1: KOKLU M., TASPINAR Y.S., (2021). Determining the Extinguishing Status of Fuel Flames With Sound Wave by Machine Learning Methods. IEEE Access, 9, pp.86207-86216, Doi: 10.1109/ACCESS.2021.3088612
Link: https://ieeexplore.ieee.org/document/9452168 (Open Access)
https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9452168
2: TASPINAR Y.S., KOKLU M., ALTIN M., (2021). Classification of Flame Extinction Based on Acoustic Oscillations using Artificial Intelligence Methods. Case Studies in Thermal Engineering, 28, 101561, Doi: 10.1016/j.csite.2021.101561
Link: https://www.sciencedirect.com/science/article/pii/S2214157X21007243 (Open Access) https://www.sciencedirect.com/sdfe/reader/pii/S2214157X21007243/pdf
3: TASPINAR Y.S., KOKLU M., ALTIN M., (2022). Acoustic-Driven Airflow Flame Extinguishing System Design and Analysis of Capabilities of Low Frequency in Different Fuels. Fire Technology, Doi: 10.1007/s10694-021-01208-9
Link: https://link.springer.com/content/pdf/10.1007/s10694-021-01208-9.pdf"

CV:https://www.muratkoklu.com/en/publications/
DATASET: https://www.muratkoklu.com/datasets/

**Summary:**

Model name: KNN

- Initial Accuracy: 95.98%,
- Accuracy Post Hyper-parameter Tuning: 96.06%,
- Cross Validation Score: 89.07%,
- Bagging Accuracy: 96.00%,
- Best Accuracy Achieved: 96.06%


Model name: Logistic Regression

- Initial Accuracy: 87.52%,
- Accuracy Post Hyper-parameter Tuning: 87.52%,
- Cross Validation Score: 86.45%,
- Bagging Accuracy: 87.57%,
- Best Accuracy Achieved: 87.57%


Model name: Naive Bayes

- Initial Accuracy: 86.72%,
- Cross Validation Score: 87.03%,
- Bagging Accuracy: 86.69%,    
- Best Accuracy Achieved: 86.72%


Model name: Decision Tree

- Initial Accuracy: 96.06%,
- Accuracy Post Hyper-parameter Tuning: 96.65%,
    Criterion Gini:
        Max Depth best Accuracy- 96.29%,
        Min Samples Leaf best Accuracy- 96.00%,
    Criterion Entropy:
        Max Depth best Accuracy- 96.81%,
        Min Samples Leaf best Accuracy- 96.69%,
- Cross Validation Score: 85.46%,
- Bagging Accuracy: 96.52%,
- Best Accuracy Achieved: 96.65%


Model name: Random Forest

- Initial Accuracy: 96.25%,
- Cross Validation Score: 88.89%,
- Best Accuracy Achieved: 96.25%


Model name: Support Vector Classifier

- Initial Accuracy: 
    Kernel "rbf"- 93.48%,
    Kernel "linear"- 87.57%,
- Accuracy Post Hyper-parameter Tuning: 96.38%,
- Cross Validation Score: 89.15%,
- Bagging Accuracy: 96.42%,
- Best Accuracy Achieved: 96.42%


Voting Classifier Accuracy: 94.68%

Boosting:

- Ada Boosting: 92.29%,
- Gradient Boosting: 94.28%,
- XG Boosting: 93.96%,


Deep Learning- Artificial Neural Network

- Best Accuracy: 93.00%
