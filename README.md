## Kideny Tumor Detection in Medical Image Processing
The primary goal of this project is to develop a robust and efficient deep learning model to assist in the automated classification of kidney abnormalities.

## About
<!--Detailed Description about the project-->
This project focuses on classifying kidney CT scan images into four distinct categories: Normal, Cyst, Tumor, and Stone using a deep learning model based on the VGG16 architecture. By leveraging transfer learning from the pre-trained VGG16 model, we aim to enhance feature extraction from the images and improve the model's classification accuracy.The dataset used in this project comprises CT images categorized into the four aforementioned classes. The model is trained using TensorFlow and Keras, with careful data preprocessing and augmentation to ensure high accuracy and generalization on unseen data.


## Features
<!--List the features of the project as shown below-->
- Accurate Kidney Classification
- Efficient Image Preprocessing
- High scalability.
- Comprehensive Performance Metrics
- Real-time Prediction

## Requirements
<!--List the requirements of the project as shown below-->
* Operating System: Requires a 64-bit OS (Windows 10/11 or Ubuntu) to ensure compatibility with deep learning frameworks.
* Development Environment: Python 3.7 or later is necessary for implementing and training the kidney classification model.
* Deep Learning Frameworks: TensorFlow for building and training the VGG16-based neural network model.
* Image Processing Libraries: OpenCV for efficient image preprocessing and visualization of kidney CT scans.
* Version Control: Git for collaborative development and version tracking of the project’s codebase.
* IDE: Use of Visual Studio Code (VSCode) as the Integrated Development Environment for code writing, debugging, and version control.
* Additional Dependencies: Includes TensorFlow, Keras, scikit-learn, OpenCV, and Matplotlib for data processing, model training, and performance visualization tasks.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![image](https://github.com/user-attachments/assets/b3d4f3d8-85c2-46c7-953f-f89af6ffbeeb)


## Output

<!--Embed the Output picture at respective places as shown below as shown below-->
#### Output1 - Predicted label : stone

![image](https://github.com/user-attachments/assets/5ad666b3-1ee1-49e0-97bc-a4f1816ae969)

#### Output2 - Predicted label : Tumor
![image](https://github.com/user-attachments/assets/93e6ea53-1778-4adc-ba51-ea888824f62b)


#### Output2 - Predicted label : cyst
![image](https://github.com/user-attachments/assets/f4ae62af-3a65-43d0-9d5b-f309ce7fee41)


#### Output2 - Predicted label : normal

![image](https://github.com/user-attachments/assets/da7265eb-8ec3-48af-a7d0-392004d69093)

##### Classification Accuracy: 99.83%

## Results and Impact
<!--Give the results and impact as shown below-->
The project successfully classified kidney abnormalities (Normal, Cyst, Tumor, and Stone) using the VGG16 model, achieving high accuracy across all classes. The model demonstrated strong generalization with validation accuracy exceeding 99%, showing minimal overfitting. The confusion matrix and classification reports confirmed the model's ability to accurately detect abnormalities. This approach has the potential to significantly enhance diagnostic efficiency in medical imaging.

## Articles published / References

1. Maqsood, F., Zhenfei, W., Ali, M.M. et al. Artificial Intelligence-Based Classification of CT Images Using a Hybrid SpinalZFNet. Interdiscip Sci Comput Life Sci (2024). https://doi.org/10.1007/s12539-024-00649-4

2. Bingol H, Yildirim M, Yildirim K, Alatas B. 2023. Automatic classification of kidney CT images with relief based novel hybrid deep model. PeerJ Computer Science 9:e1717 https://doi.org/10.7717/peerj-cs.1717

3. Asif, S., Qurrat-ul-Ain, Awais, M. et al. IR-CNN: Inception residual network for detecting kidney abnormalities from CT images. Netw Model Anal Health Inform Bioinforma 12, 35 (2023). https://doi.org/10.1007/s13721-023-00431-4

4. Bhattacharjee A, Rabea S, Bhattacharjee A,Elkaeed EB, Murugan R, Selim HMRM,Sahu RK, Shazly GA and Salem Bekhit MM(2023) “A multi-class deep learning modelfor early lung cancer and chronic kidney disease detection using computed tomography images”. Front. Oncol. 13:1193746.doi: 10.3389/fonc.2023.1193746

5. Bhandari, M.; Yogarajah, P.;Kavitha, M.S.; Condell, J. Exploring the Capabilities of a LightweightmCNN Model in Accurately Identifying Renal Abnormalities: Cysts, Stones, and Tumors, Using LIME and SHAP. Appl. Sci. 2023, 13, 3125. https://doi.org/10.3390/app13053125

6. Alzu’bi, D., Abdullah, M., Hmeidi, I., AlAzab, R., Gharaibeh, M., El-Heis, M., Almotairi, K. H., Forestiero, A., Hussein, A. M., & Abualigah, L. (2022).” Kidney tumor detection and classification based on deep learning approaches: A new dataset in CT scans”. Article ID 3861161, 22 pages https://doi.org/10.1155/2022/3861161

7. Islam, M.N., Hasan, M., Hossain, M.K. et al. Vision transformer and explainable transfer learning models for auto detection of kidney cyst, stone and tumor from CT-radiography. Sci Rep 12, 11440 (2022). https://doi.org/10.1038/s41598-022-15634-4





