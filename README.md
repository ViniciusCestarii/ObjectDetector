# ObjectDetector

This project demonstrates how to perform real-time object detection using a camera feed in the browser. It utilizes TensorFlow.js and the pre-trained COCO-SSD model for object detection directly from the camera.

## Features

- Real-time object detection from the camera feed.

- Displays bounding boxes and labels for detected objects.

- Uses TensorFlow.js and COCO-SSD pre-trained model.

- [Simple game](https://viniciuscestarii.github.io/ObjectDetector/game) to find a random object.

## Requirements

- A modern browser that supports JavaScript and WebRTC (for camera access).

- An internet connection to load TensorFlow.js and COCO-SSD from CDN.

## Installation

Since this project runs in the browser, there's no installation required. Just clone or download the project files and open the index.html file in a browser.

### Steps:

1. Clone or download the repository.

2. Open index.html in your browser.

## How it Works

1. The browser accesses the camera using `navigator.mediaDevices.getUserMedia()`.

2. The live video stream is displayed on the screen in the <video> element.

3. The COCO-SSD model is loaded using TensorFlow.js, and object detection is performed on each video frame.

4. Detected objects are outlined with red bounding boxes, and labels with confidence percentages are shown on top.

### Key Technologies Used

- TensorFlow.js: JavaScript library for machine learning.

- COCO-SSD: Pre-trained object detection model from TensorFlow.

- HTML5 Video and Canvas: For displaying the video feed and drawing detections.

## Troubleshooting

- Camera Permissions: Ensure your browser has permission to access the camera.

- Browser Compatibility: This project is compatible with modern browsers like Chrome, Firefox, and Safari.

## License

This project is open-source and available under the MIT License.
