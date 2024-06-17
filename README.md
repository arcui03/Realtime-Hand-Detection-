# Realtime Hand Detection Project

This project uses OpenCV and MediaPipe to detect and classify left hand, right hand, and both hands in real-time. The implementation is based on Google Colab, leveraging its GPU capabilities for efficient processing.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

This project demonstrates real-time hand detection and classification using OpenCV and MediaPipe. It identifies and labels the hands in a video stream as left hand, right hand, or both hands simultaneously. The model is implemented and tested using Google Colab, making it easy to run and modify in a cloud-based Google Collab notebook environment.

## Features

- **Real-time Hand Detection:** Utilizes MediaPipe to detect and track hands in video frames.
- **Hand Classification:** Classifies detected hands as left, right, or both based on their positions.
- **Google Colab Integration:** Takes advantage of Google Colab's GPU for faster processing and experimentation.

## Installation

To run this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/arcui03/Realtime-Hand-Detection-.git
   
2. Open the project in Google Colab by uploading the notebook file :
   (`Hand_Detection_Project.ipynb`)
4. Ensure all necessary dependencies are installed. Most dependencies are pre-installed in Google Colab, but you might need to install additional packages using:
   ```bash
   !pip install mediapipe as mp
## Usage

1. Open the `realtime_hand_detection.ipynb` notebook in Google Colab.

2. Follow the instructions in the notebook to execute each cell sequentially.

3. The notebook will demonstrate real-time hand detection and classification. You can adjust parameters or modify the code as needed.

## Contributing

Contributions are welcome! Here's how you can contribute to this project:

- Fork the repository.
- Create a new branch (`git checkout -b feature/new-feature`).
- Make your changes.
- Commit your changes (`git commit -am 'Add new feature'`).
- Push to the branch (`git push origin feature/new-feature`).
- Create a new Pull Request.

Please ensure that your pull request adheres to the repository's code of conduct.

Thank You
Archit Tiwari


