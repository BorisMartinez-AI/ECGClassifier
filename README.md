# ECG Classifier
Supervised Learning Algorithm for ECG (Electrocardiogram Classification).
The purpose of this supervised learning algoritm is to classify with decent accuracy a ECG signal into different categories:
    0 - Normal,
    1 - Superventricular Premature Beat,
    2 - Premature Ventricular Contraction,
    3 - Fusion of ventricular and normal beat,
    4 - Unclassifiable beat

The model is built using an RNN network with Conv1D, LSTM and Dense layers. Dataset pulled from: https://www.physionet.org/content/mitdb/1.0.0/

![image](https://user-images.githubusercontent.com/110473221/202070090-6689f534-2faa-48bb-ac70-58d96b4c5a55.png)
