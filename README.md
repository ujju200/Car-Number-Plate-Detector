

# Car-Number-Plate-Detector
The car number plate detector is a project developed using Python, convolutional neural networks (CNNs), and OpenCV. Its primary purpose is to accurately detect and recognize the characters written on car number plates.

# Tech Stack
1. **CNNs(Convolutional Neural Network)** - The project utilizes the power of CNNs, a deep learning algorithm widely used for image classification and object detection tasks. CNNs are particularly effective at automatically learning and extracting relevant features from images, making them suitable for tasks like character recognition.
2. **OpenCV(Open Source Computer Vision Library)** is an open-source computer vision and image processing library that handles image and video processing tasks. It provides a wide range of functions and tools for image manipulation, object detection, and feature extraction, which are crucial for implementing the number plate detection system.

# Working

The car number plate detection process typically involves several steps:-
1. First, the input image is preprocessed using OpenCV techniques such as resizing, noise removal, and image enhancement to improve the quality and reduce unnecessary details.
2. Then, the characters are segregated into different images of individual characters with the help of contours.
3. Then, these images of characters are fed into a trained CNN model. The CNN model has been trained on a large dataset of annotated alphabets and digits images, allowing it to learn and recognize the different character patterns commonly found on number plates. The model processes the input image and produces predictions for the characters present on the number plate.
4. Finally, the detected characters are extracted and post-processed to enhance their legibility and organize them in the correct sequence. The Sequence of characters is then printed in the form of an array of characters.

# Here is the Demo video of the below sample plate
![Chevrolet-Beat-525743c](https://user-images.githubusercontent.com/64632969/115338120-d50a9c80-a1bf-11eb-81d1-352d9869987d.png)


https://user-images.githubusercontent.com/64632969/115339367-3cc1e700-a1c2-11eb-8f5a-088838b56e38.mp4











