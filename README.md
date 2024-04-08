# Teachable Machine with TensorFlow.js

![Teachable Machine with TensorFlow.js](https://onedrive.live.com/embed?resid=4B1C8510CEF67D18%219608&authkey=%21AIWV0RmoBG0igv8&width=1069&height=1748)

## Project Overview

This project enables users to train a machine learning model in their browser using Transfer Learning with TensorFlow.js and MobileNet v3. Users can teach the model to recognize objects from the webcam feed by collecting samples in real-time. This approach ensures privacy and immediacy, as no data is sent to a server.

### Key Features

- Real-time data collection and model training in the browser.
- Utilizes TensorFlow.js and MobileNet v3 for efficient, client-side machine learning.
- Supports multiple classes of objects for recognition.
- No server-side processing required, ensuring user privacy.

## Installation Instructions

### Prerequisites

- A modern web browser with support for JavaScript and TensorFlow.js.
- Internet connection for loading TensorFlow.js library.

### Setup

1. Clone this repository or download the provided files (`index.html`, `script.js`, `style.css`).
2. Ensure the files are in the same directory to maintain correct path references.

## Usage Guide

### Starting the Application

- Open `index.html` in a web browser.
- Allow webcam access when prompted.

### Training the Model

1. Enable the webcam by clicking the "Enable Webcam" button.
2. Collect data for Class 1 by pointing the webcam at an object and clicking the "Gather Class 1 Data" button. Aim for at least 30 samples.
3. Repeat the process for Class 2 with a different object.
4. Train the model by clicking the "Train & Predict!" button.
5. Once trained, the model will make live predictions as the webcam feeds new images.

## Configuration

No additional configuration is required for basic usage. Advanced users can modify `script.js` to tweak model parameters or add more classes.

## Contributing

Contributions to improve the project are welcome. You can contribute by:

- Submitting issues for bugs or suggestions.
- Proposing enhancements through pull requests.

Please follow standard coding practices and provide clear descriptions of your contributions.

## License Information

This project is released under the Apache License 2.0. You are free to use, modify, and distribute the software under the terms of this license. Please see the [LICENSE](LICENSE.md) file for detailed information.

## Contact Information

For further information or support, please open an issue on the project's GitHub page.
