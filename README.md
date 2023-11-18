# Electronic Component Detection Project

This electronic component detection project utilizes a convolutional neural network (CNN) with Edge Impulse. After configuring the impulse, adjusting image parameters, and adding processing and learning blocks, the model was successfully trained. With a precision score of 90% and a loss of 0.24, the model achieves robust performance. Incorporating spectral analysis, neural network techniques, and K-means anomaly detection, this project provides an effective solution for electronic component detection.

Step 1: Data Collection.

In data collection, I chose Auto split between training and test datas and the software chose to split 80/20. 
![image](https://github.com/saidg78/projet_4/assets/148437845/93bc8376-629c-49ab-a1e9-1b42e249e659)
Step 2: Creating an impulse. 
First of all, I started by converting the photos to 28x28 to resize them.Then I chose the qualification for the classes.
![image](https://github.com/saidg78/projet_4/assets/148437845/5c6afeaa-d798-4c2c-b4e5-ee428489ca78)
Step 3: Extract features and generate features.


![image](https://github.com/saidg78/projet_4/assets/148437845/c473d90a-c25f-4717-a81b-acd25f1599f0)

Step 4: Train
For training the model, I chose 200 number of cycles so I can have the best possible model.

![image](https://github.com/saidg78/projet_4/assets/148437845/ceb20c1f-6652-4975-85fc-13d3c128a698)

Step 5: Import an Arduino Library


![image](https://github.com/saidg78/projet_4/assets/148437845/3bffe175-a781-4ec3-9080-cd56201e323a)

Step 6: Watch the results


Pour un condensateur:

![image](https://github.com/saidg78/projet_4/assets/148437845/57ab6e07-390c-4279-9d0d-32d6793867d9)



