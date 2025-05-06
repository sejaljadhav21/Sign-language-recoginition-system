## Sign Language Recognition System (Prototype)

This project is an early-stage, machine learning-based system designed to recognize and interpret hand gestures from *American Sign Language (ASL)*, specifically the letters **A**, **B**, and **C**. It uses computer vision techniques—such as hand landmark tracking with **MediaPipe**—and a trained deep learning model to classify gestures in real-time from live video input. The primary goal is to bridge the communication gap between hearing-impaired individuals and others by creating a tool that can translate sign language gestures into readable text or spoken words.

---

## Features

- **Real-time Gesture Recognition:** Detects hand gestures for the letters A, B, and C.
- **MediaPipe Integration:** Utilizes hand landmark tracking for precise gesture recognition.
- **Deep Learning Model:** A custom-trained model to classify hand gestures from video input.
- **User-friendly Interface:** Simplified for easy interaction by non-technical users.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sejaljadhav21/sign-language-recognition.git
````

2. Navigate to the project directory:

   ```bash
   cd sign-language-recognition
   ```

3. Install the required dependencies:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the script:

   ```bash
   python recognize_gesture.py
   ```

2. Allow the script to access your camera to capture live video.

3. Make the ASL gestures for letters A, B, or C in front of the camera. The system will display the recognized gesture in real-time.

## Images

### Training Progress

![Training Progress](https://github.com/user-attachments/assets/b7cc4ff1-8509-4784-a473-46a45df2a80e)


### Sample Output (A, B, C)

<img width="894" alt="Letter A" src="https://github.com/user-attachments/assets/c54c73d6-9b1f-4cf6-8d7d-df542df20e80" />
<img width="895" alt="Letter B" src="https://github.com/user-attachments/assets/4b0d8638-2a69-4a91-a11e-192c0f0a3943" />
<img width="896" alt="Letter C" src="https://github.com/user-attachments/assets/2aa1937c-6bb4-4a01-ae1a-d74d2876891f" />


### MediaPipe Hand Tracking

![Hand Tracking](https://github.com/user-attachments/assets/754ae3c6-dcf9-4002-b395-426275a3d838)

---

## Requirements

* Python 3.x
* OpenCV
* MediaPipe
* TensorFlow (for deep learning model)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgments

* [MediaPipe](https://google.github.io/mediapipe/) for hand tracking solutions.
* [TensorFlow](https://www.tensorflow.org/) for model building.
* [OpenCV](https://opencv.org/) for computer vision tasks.

```

### Notes:
1. **Images:** Replace `images/gesture-recognition.png`, `images/output-sample.png`, and `images/hand-tracking.png` with the actual image paths you plan to use in your repository.
2. **Customization:** Update the clone URL with your actual GitHub repository URL.
3. **Deep Learning Model:** If you're using a specific deep learning framework (e.g., TensorFlow, PyTorch), make sure it's mentioned in the requirements and usage instructions.


```
