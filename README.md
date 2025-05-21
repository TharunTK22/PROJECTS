Sign Language Detection
In propose work we are employing deep learning algorithms to detect and recognize hand sign. In propose work we are experimenting with various algorithms such as Yolov8, Yolov11 and Spatial Temporal Graph Neural Network (STGCN). Among all algorithms YoloV11 giving best Mean Precision result and all algorithms recognizing maximum number of test hand signs with an accuracy of more than 99%.
To train and test above algorithms performance we have used American Sign Language dataset which contains alphabets from A to Z and some words like ‘Apple, get, Good and can’
SCREEN SHOTS
For training, testing, dataset analysis we have used JUPYTER notebook and then use window-based application to detect hand signs from webcam.
In below screens showing JUPYTER code and output with blue color comments
 
In above screen loading required python packages and classes
 
In above screen reading and loading images from Dataset folder and after loading all images will get below output
 
In above screen in blue color text can see total 1600 images loaded from dataset
 
In above screen visualizing graph of different class labels found in dataset where x-axis represents class labels and y-axis represents number of images exists in that class label
 
In above screen displaying Yolo11 classification result where each alphabet predicted precision is between 80 to 100
 
In above screen visualizing Yolo11 training loss and precision graph where x-axis represents number of epoch and y-axis represents loss/precision and in each graph can see with each increasing epoch precision got increase and loss got decrease
 
In above screen displaying Yolo8 classification result and this algorithm prediction precision of each label between 80 to 90% 
 
In above screen visualizing yolov8 training graph
 
In above screen defining ‘Detect Sign’ function which will detect and predict hand sign from given image using Yolov11
 
In above screen processing loaded dataset using various processing techniques such as shuffling, normalization and splitting data into train and test where application using 80% dataset for training and 20% for testing and in blue text can see train and test size
 
In above screen defining and training ST-GCN algorithm and after executing above block will get below output
 
In above screen can see ST-GCN algorithm also predicting different hand signs with a precision of 80 to 100%.
So in above screen we have shown training, testing and performance of all algorithms and now double click on ‘runCam.bat’ file to start window application and get below page
 
In above screen click on ‘Hand Sign from Webcam’ button to get below page
 
In above screen sign detected as ‘Y’ 
 
In above screen sign detected as A
 
In above screen sign detected as I 
 
In above screen sign detected as ‘Apple’ and similarly show different signs to get different types of detection.
To know various signs you can see images available inside ‘Data/images/train’ folder like below screen
 
In above ‘Data/images/train’ folder you can see images of different signs and you need to show same type of sign to get accurate detection


 

