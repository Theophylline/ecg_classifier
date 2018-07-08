# SVM Classification of Arrythmias from Single Lead ECG Recordings

In this project, a Support Vector Machine (SVM) is used to classify normal and abnormal rhythms from ECG Recordings.

ECG recordings are obtained from https://www.physionet.org/challenge/2017/. The training set contains 5154 normal ECGs and 3328 abnormal ECGs, which can further be broken down into 771 atrial fibrillations (AF) and 2557 other abnormal rhythms (O). Noisy recordings are excluded in this project.

A model for ECG segmentation has already been trained (/misc/hmm_model.dll). You can use it to extract your own features.

For more details, please see the Jupyter Notebook.
