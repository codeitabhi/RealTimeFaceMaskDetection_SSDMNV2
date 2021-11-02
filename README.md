# RealTimeFaceMaskDetection_SSDMNV2
It is a real time face mask detection model which uses the single shot detection and MobilenetV2 architecture.


•	A real-time face mask detection system using Single shot multibox detection and MobilenetV2 architecture.
•	It took inputs as image snapshots, through the webcam in real-time and that input image was fed into my model which classified the images into 2 categories that are ‘with mask’ and ‘without mask’.
•	I used OpenCV for detection of frontal face in any given image.
•	The dataset that I used was taken from Kaggle which is an open-source database. It consisted of around 6000 images which were then split into training and test sets.
•	Data preprocessing was done which included reduction of repeated images present in the database.
•	One of the main aspects of this project was to study the impact of data augmentation on the accuracy of the output even if large quantity of data is available. So, the input database went through data augmentation where geometric transformations like flipping, cropping, rotation, noise injection etc. were applied to increase the training dataset.
•	The transfer learning framework that I used was MobilenetV2 architecture which is based on Convolutional Neural networks.
•	It consisted of convolutional layer, pooling layer, dropout layer and a fully connected layer towards the end. I experimented with the various parameters of the model like the activation functions, learning rate etc. 
•	With a certain set of model parameter, I was able to achieve a maximum accuracy of 97.2 on the test set.
•	The performance metrics I used were in terms of accuracy and recall.
•	Their values with and without data augmentation showed its significance in the model efficiency.
•	We want false negative to be as low as possible if we use this model for automated model for charging fines from people without masks in public. 
Hence recall is much more important than precision here since ….. 
