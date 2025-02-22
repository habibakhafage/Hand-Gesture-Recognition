# Hand Gesture Recognition Model

## Project Overview
Hand gesture recognition is a computer vision task that involves interpreting and classifying hand gestures. It has applications in human-computer interaction, sign language interpretation, virtual reality, and more.

### Objective:
- Develop a deep learning model to recognize and classify hand gestures from images.
- Utilize Convolutional Neural Networks (CNNs) for effective feature extraction.
- Implement real-time gesture recognition using OpenCV.

### Dataset:
- LeapGestRecog Dataset containing 10 gesture categories.
- Preprocessed for improved model performance.

---

## Methodology

### 1. Data Preprocessing:
- Loaded images from different gesture categories.
- Converted images to grayscale and resized to 50x50 pixels.
- Normalized pixel values for consistent input.
- Split dataset into training and testing sets.

### 2. Model Development:
- Built a CNN model using:
  - Conv2D, Activation, MaxPooling, Flatten, Dense, and Dropout layers.
- Trained the model on preprocessed hand gesture images.
- Utilized Keras and TensorFlow for deep learning.

### 3. Visualization:
- Displayed sample images from each gesture category.
- Tracked training and validation accuracy/loss over epochs.
- Calculated and visualized the confusion matrix.
- Evaluated precision, recall, and F1-score.

### 4. Real-Time Recognition:
- Integrated the trained model with OpenCV.
- Implemented live video feed for real-time gesture detection.
- Displayed recognized gestures on the screen.

---

## Tools & Technologies Used
- **Programming Language**: Python  
- **Libraries**:
  - OpenCV – Real-time video processing
  - TensorFlow/Keras – Model building and training
  - NumPy – Data handling
  - Matplotlib and Seaborn – Data visualization

---

## Results
- Achieved high accuracy in recognizing various hand gestures.  
- Successfully implemented real-time gesture recognition with a responsive user interface.  

