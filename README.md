# Face-Detection-and-Recognition
Face detection and recognition are two key tasks in computer vision and artificial intelligence.

## Face Detection: 
This is the process of identifying and locating human faces in images or video frames. It involves finding the presence and location of faces within an image or a video stream. Various techniques such as Viola-Jones algorithm, Histogram of Oriented Gradients (HOG), Convolutional Neural Networks (CNNs) and OpenCV have been used for face detection.

![image](https://github.com/MdSaifurRahman/Face-Detection-and-Recognition/assets/100013081/c810405a-d508-4a94-b225-3fc1a50f480e)


## Face Recognition: 
Once faces are detected, face recognition involves identifying or verifying a person's identity from an image or video frame. It is a broader task that not only involves identifying the presence of a face but also matching it with a known database of faces to determine the identity. Face recognition systems typically use deep learning models, particularly Convolutional Neural Networks (CNNs), for feature extraction and classification.

## Here's how the process generally works:
### Face Detection: 
Initially, the system scans an image or video frame for potential faces using techniques like those mentioned above. Once a face is detected, its bounding box or region is identified.
Feature Extraction: For face recognition, features are extracted from the detected face region. These features might include the distances between various facial landmarks, texture patterns, or other distinctive features.

### Face Matching: 
The extracted features are then compared to a database of known faces. This database could be a collection of labeled images, with each image corresponding to a specific individual. The system matches the extracted features with those stored in the database to identify the person.

![image](https://github.com/MdSaifurRahman/Face-Detection-and-Recognition/assets/100013081/ec29f8ce-9d21-44b3-9fad-f283725ecf41)


### Classification: 
Once the system finds a match or determines the closest match based on similarity metrics, it classifies the detected face as belonging to a particular individual. For our project we have used OpenCV and haarcascade classifier which is a weak classiefier but easy to implement.

Face detection and recognition systems have various applications, including security systems, surveillance, biometric authentication, and photo organization. However, it's essential to consider privacy and ethical implications when deploying such systems, particularly regarding data collection and usage.

![image](https://github.com/MdSaifurRahman/Face-Detection-and-Recognition/assets/100013081/9d8ba7d2-a6e6-4dde-a2a0-0aee9df0c46e) Haar Cascade classifier working

## Dataset Used :- https://www.kaggle.com/datasets/vishesh1412/celebrity-face-image-dataset
## HaarCascade File :- https://github.com/opencv/opencv/tree/master/data/haarcascades
