The proposed deep learning method outperforms traditional machine learning approaches in seizure prediction. The study demonstrates that CNNs combined with SVMs can successfully predict seizures with high sensitivity and specificity, offering a potential solution for real-time clinical applications.
"Epileptic Seizures Prediction Using Deep Learning Techniques"
Authors & Affiliation

    Authors: Syed Muhammad Usman, Shehzad Khalid, and Muhammad Haseeb Aslam

    Affiliation: Bahria University, Islamabad, Pakistan

Objective

The paper focuses on predicting epileptic seizures using deep learning techniques applied to scalp EEG signals. The goal is to detect the preictal state (which occurs before a seizure) to enable early intervention.
Key Contributions

    EEG-Based Seizure Prediction:

        Utilizes EEG recordings to identify the preictal and interictal states.

        Highlights that detecting the preictal state can help in seizure prevention.

    Deep Learning-Based Approach:

        Uses Convolutional Neural Networks (CNNs) for automated feature extraction.

        Employs Support Vector Machines (SVMs) for classification.

    Dataset Used:

        CHB-MIT scalp EEG dataset (24 subjects).

        EEG signals were preprocessed to remove noise before feature extraction.
        Methodology

    Preprocessing:

        Noise removal using Butterworth filters, notch filters, and other techniques.

        Feature extraction via wavelet transform and Fourier transform.

    Feature Selection:

        Temporal features (entropy, Lyapunov exponents).

        Spectral features (power spectral density, spectral moments).

    Classification:

        CNN for feature extraction.

        SVM for classification of preictal and interictal states.
