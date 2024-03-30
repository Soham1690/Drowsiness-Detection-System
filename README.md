# Drowsiness-Detection-System

The proposed approach of AD3S has been well demonstrated with the help of an algorithm and is implemented with the
help of an Android application. The application can be installed on an Android device. Once the application gets installed
on the device, it captures facial landmarks at the backend by utilizing Dlib library. A server has been implemented on
Flask. When the application is running, the images of the driver are continuously sent over the server and are processed
for capturing facial landmarks. A data set of 1200 participants is collected and trained using machine learning classifiers. A. Data Procurement The module captures facial landmarks of the real-time user. The application provides different
options for drivers and passengers using the toggle option on the login page. In case if the application user is driver,
he/she performs registration, followed by creating a new ride followed by setting up the origin and destination of the ride.
In case if the application user is passenger, then they can add themselves in the ride created by the driver. Once the passengers have joined the ride, the driver can start the ride. Once driver and passengers are ready for the ride,
AD3S then captures photos of the driver continuously for entire ride duration. Pictures are clicked each time the
application gets a response from the server. The system continuously captures the pictures until the driver stops the ride. The images are simultaneously sent on the server to be processed for feature extraction. For testing the efficiency of the
proposed approach, facial landmark points of 1200 volunteers were gathered and their EAR, NLR and MOR values were
collected by AD3S. Later, the accumulated results were additionally examined to test the viability of the proposed
framework utilizing Machine learning classifiers and Artificial Neural Network(ANN). B. Feature Extraction Dlib library support of Python has been employed to obtain 68 facial landmark points from the
image captured during the entire duration while the ride is being carried out. The dlib library comprises of a pre-trained
face detector and uses Support vector machine (SVM ) for identifying objects. The Euclidean distance between the
coordinate points is calculated.Three parameters namely are EAR, NLR, and MOR have been taken into consideration.
