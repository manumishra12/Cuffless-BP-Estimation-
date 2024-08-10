# Cuffless-BP-Estimation-
Developed a cuffless blood pressure estimation system using ECG and PPG signals, achieving high accuracy in predicting systolic and diastolic blood pressure. Leveraged advanced signal processing and machine learning to enable continuous, non-invasive monitoring

### Abstract
Cuffless blood pressure (BP) estimation presents a promising non-invasive method for continuous BP
monitoring, which can significantly enhance the management of cardiovascular health. This report
explores the use of electrocardiogram (ECG) and photoplethysmogram (PPG) signals to estimate systolic
blood pressure (SBP) and diastolic blood pressure (DBP) without the need for traditional cuff-based
methods. We transform the ECG and PPG signals into bispectrum and bicoherence images, which
capture the nonlinear interactions within the signals. A SWIN Vision Transformer model is then applied
to these images to predict BP values. Our approach demonstrates high accuracy and reliability, offering a
practical solution for continuous BP monitoring in clinical and home settings.


### Methodology

ECG and PPG signals are collected using non-invasive sensors and preprocessed to remove noise. These signals are then converted into bispectrum and bicoherence images for accurate blood pressure (BP) estimation. A SWIN Vision Transformer model processes these images, trained to predict systolic (SBP) and diastolic (DBP) BP values. The dataset is split for training and validation, with performance evaluated using metrics like mean absolute error (MAE) and root mean square error (RMSE). The model's robustness is ensured through cross-validation and compared with existing cuffless BP methods. It is implemented in a prototype for continuous BP monitoring, assessing usability in clinical settings. This approach highlights the potential of advanced signal processing and machine learning in hypertension management.

<img src="methadology.png" alt="Small Image" width="700" height="350">

