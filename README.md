# Analyzing Variability in Human Movements: A Wearable Sensor Data Approach for Activity Recognition
This project presents a comprehensive study on Human Activity Recognition (HAR) using data from wearable sensors. We classify 19 distinct human activities (ranging from daily routines like sitting and walking to sports activities like running and basketball) with high accuracy by combining advanced signal processing and machine learning techniques. The approach addresses key challenges in HAR, such as inter-subject variability and environmental noise, making it robust for real-world applications.

**The methodology includes**:
- Data Preprocessing: Noise reduction and segmentation of sensor data (accelerometers, gyroscopes, magnetometers) from 5 body locations.
- Dimensionality Reduction: Principal Component Analysis (PCA) to retain 62.89% of variance using the top 50 components.
- Classification: Evaluation of four ML algorithms K-Nearest Neighbors (KNN), Support Vector Machines (SVM), Decision Trees (DT), and Random Forests (RF).

**Key Achievement**: Random Forest achieved 93% accuracy, outperforming others while maintaining computational efficiency.
This work was conducted as part of a group coursework (ML_7072CEM_CW_GROUP_18) at Coventry University, Faculty of Engineering, Environment and Computing.
For the full research paper, see ML_7072CEM_CW_GROUP_18.pdf in the repository.
# Dataset
We used the Daily and Sports Activities Dataset from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/271/daily+sports+activities) (Barshan & Altun, 2013):
- Subjects: 8 (4 female, 4 male; ages 20-30).
- Activities: 19.
- Sensors: 5 Xsens MTx units (torso, right/left arm, right/left leg) with accelerometer, gyroscope, and magnetometer modalities.
- Sampling: 25 Hz, 5-second segments (125 data points per axis per segment).
- Total Features: 5,625 per segment.
