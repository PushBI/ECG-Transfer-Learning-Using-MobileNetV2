# Detection of Myocardial Infarction With the help of MobileNetV2

> This is the repository that houses our Deep Learning project where, we tried to check if MobileNetV2 can detect and Classify Myocardial Infarction.

## Abstract

> In 2005, 17 million deaths all over the world were caused by cardiovascular diseases. Out of those 17 million, almost half (7.6 million) succumbed to coronary heart disease. [Myocardial infarction](https://en.wikipedia.org/wiki/Myocardial_infarction) (MI) is one of the five main types of coronary heart disease. The number of cases of cardiovascular disease is rising both in high-income countries and low- and middle income countries (LMICs) because of ageing populations. LMICs are in a greater risk as they are more populous with inadequate healthcare and widespread exposure to increasing levels of risk factors such as unhealthy diet, physical inactivity, obesity, tobacco use, diabetes, raised blood pressure and abnormal blood lipids.

> _Myocardial Infarction (MI)_ - more commonly known as heart attack is the irreversible death of heart muscles due to the prolonged lack of oxygen. The patient who is having an Infarction requires immediate medical attention. MI screening is mostly performed by Electrocardiography (ECG) and ECG graphs are manually interpreted by the doctors. If there is a process to analyze the ECG signals and detect whether there is any MI or not - it would decrease the pressure on the doctors. It shall also solve the healthcare problems caused by the lack of doctors in remote parts of the world especially the LMICs. 


## Proposed Model

> In past several techniques involving machine learning and deep learning had been employed to solve the problem, However, feature extraction remained as one of the greatest challenges in MI classification. To counter this problem, we propose a new deep learning solution for MI detection and classification where there is no need for feature extraction or training the model from scratch. Here we have used Transfer Learning on a convolutional neural network named MobileNetV2 initialising the model with imagenet weights. The experiment was performed on  PTB dataset which is a benchmark dataset for ECG analysis and the model was trained on Google Colab TPU. We have used 3358 images to classify 5 categories. We have successfully carried out the experiments with a classification accuracy of 99% and an average accuracy of 97.93% with a standard deviation of 1.61% with sensitivity and specificity of 100% and 95% respectively.

### Diagram for flow of proposed method for detection of Myocardial Infarction
![Flow](https://user-images.githubusercontent.com/39896375/113428695-e0567d80-93f4-11eb-8068-c94f98492c31.png)

## Results
### Training Accuracy and Loss
![accuracy](https://user-images.githubusercontent.com/39896375/113256006-312b8080-92e6-11eb-8b53-8145fd062204.png)
![loss](https://user-images.githubusercontent.com/39896375/113255998-2f61bd00-92e6-11eb-98ae-29c48d6ed6a4.png)
### ROC Curve
![ROC Curve](https://user-images.githubusercontent.com/39896375/113255848-f4f82000-92e5-11eb-9c4e-17290130e27b.png)
### KFold Cross Validation
![kfold](https://user-images.githubusercontent.com/39896375/113256009-312b8080-92e6-11eb-995c-4dc9ad92b945.png)
### Confusion Matrix
![Confusion Matrix](https://user-images.githubusercontent.com/39896375/113429592-67582580-93f6-11eb-848c-413ad7a287b4.png)

## Built With
Google Colab Cloud TPU

## Contributors
* Pushan Bhattacherjee - [Google Scholar](https://scholar.google.co.in/citations?user=aJpPsMsAAAAJ&hl=en)
* Sayantan Samajpati - [LinkedIn](https://www.linkedin.com/in/sayantan-samajpati-1866b7184/) - [Github](https://github.com/creepysta)
* Dipan Banerjee - [Research Gate](https://www.researchgate.net/profile/Dipan-Banerjee)
* Debayan Ganguly - [Google Scholar](https://scholar.google.co.in/citations?user=eZL1OXcAAAAJ&hl=en)
* Kingshuk Chatterjee - [Google Scholar](https://scholar.google.co.in/citations?user=o-WIpn0AAAAJ&hl=en) - [Portfolio](https://sites.google.com/view/kingshukchatterjee/home)


