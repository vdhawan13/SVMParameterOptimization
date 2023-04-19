# SVM Parameter Optimization

We conducted an investigation to assess the effectiveness of Support Vector Machines (SVM) for classification problems, with a focus on optimizing SVM parameters. The Scikit-learn library in Python was used to implement our SVM model, which was evaluated on the room occupancy Data Set. The dataset was randomly split into 10 samples for training and testing the SVM model, and different combinations of SVM parameters were tested to identify the optimal settings for each sample. The results of our project are summarized in a table, showcasing the accuracy achieved for each sample along with the corresponding SVM parameters that yielded the highest accuracy. This table can serve as a valuable reference for future classification tasks that require SVM parameter optimization.

# DataSet Description
The UCI Machine Learning Repository hosts the "Room Occupancy Estimation Data Set," which contains 20,560 instances and 7 features, including temperature, relative humidity, light intensity, CO2 level, humidity ratio, and a binary occupancy label. This dataset is commonly utilized for binary classification tasks aimed at predicting room occupancy based on sensor measurements, making it valuable for research in areas such as energy management in buildings and smart homes. It serves as a valuable resource for evaluating and comparing the performance of different machine learning algorithms, including Support Vector Machines (SVM), in the context of room occupancy estimation.
https://archive.ics.uci.edu/ml/datasets/Room+Occupancy+Estimation

Number of Instances: 10129 

Number of Attributes: 16

# Comparitive performance of optimized-SVM with 10 samples
![image](https://user-images.githubusercontent.com/88321272/233163795-a27fa51d-c141-4de7-a0b6-7c823847d8eb.png)

# convergence graph of best SVM
![image](https://user-images.githubusercontent.com/88321272/233164465-b5ce16f7-d1c6-4af8-acda-3625ee5cc553.png)

