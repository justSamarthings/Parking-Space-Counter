### Parking Space Counter

This project aims to develop a Parking Space Counter using basic Image Processing techniques. The objective is to determine the total number of cars present in a parking lot and the number of vacant spaces available for parking. The implementation utilizes OpenCV, a popular library for computer vision tasks.

### Functionality

The project comprises two main Python scripts:

1. **main.py**: This script processes a video feed of a parking lot, detecting cars and vacant spaces using image processing techniques such as thresholding, blurring, and dilation. The number of vacant spaces is displayed on the video feed in real-time.

2. **parking_space_counter.py**: This script contains functions for detecting parking spaces and counting the number of cars in a given image. It utilizes pickle for storing and retrieving positional data of parking spaces.

### Libraries Used

- **OpenCV (cv2)**: OpenCV is a powerful library for computer vision and image processing tasks. It provides functions for reading, processing, and analyzing images and videos.

- **Pickle**: The pickle module is used for serializing and deserializing Python objects. In this project, it is employed to store and retrieve the positional data of parking spaces.

### Note

This project serves as a basic demonstration of parking space detection using image processing techniques. Further optimizations and enhancements can be made to improve accuracy and efficiency, depending on specific use cases and requirements.
