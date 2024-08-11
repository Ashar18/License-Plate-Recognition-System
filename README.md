# License Plate Recognition System

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Challenges Addressed](#challenges-addressed)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This project is an advanced License Plate Recognition (LPR) system designed to detect and recognize license plates in real-time video streams. It integrates deep learning models and image processing techniques to deliver accurate and efficient results under various conditions. The system is built with a focus on robustness and user accessibility, offering a web-based interface for seamless interaction.

![web img](https://github.com/user-attachments/assets/3a5fa5f5-7102-4833-b8a3-4cebf9593633)


## Features

- **Real-Time Video Processing**: Processes live video feeds to detect and recognize license plates instantaneously.
- **Object Detection with YOLOv8**: Utilizes YOLOv8 for detecting vehicles and license plates with high accuracy.
- **Image Processing with OpenCV**: Implements image enhancement techniques using OpenCV to improve detection accuracy.
- **Optical Character Recognition with EasyOCR**: Extracts text from license plates using EasyOCR, handling various formats and languages.
- **Flask Web Application**: Provides a user-friendly web interface for interacting with the system, allowing users to upload videos or stream real-time footage.

  ![output](https://github.com/user-attachments/assets/89cd1878-a323-4f16-a836-e9b2919a0115)


## Installation

To install and run the License Plate Recognition system on your local machine, follow these steps:

### Prerequisites

- Python 3.7+ 
- Git

### Step 1: Clone the Repository

```bash
git clone https://github.com/Ashar18/license-plate-recognition.git
cd license-plate-recognition

### Step 2: Install Dependencies
Install the necessary Python packages:

```bash
pip install -r requirements.txt

### Step 3: Run the Flask Application

```bash
python app.py

Open your web browser and go to http://localhost:5000 to start using the License Plate Recognition system.

## Usage

1. **Upload Video or Stream Live**: You can either upload a video file or provide a live stream for the system to process.
2. **License Plate Detection**: The system automatically detects vehicles and license plates in the video frames.
3. **Text Recognition**: Extracted license plate numbers are processed and displayed in the web interface.
4. **Review Results**: View the recognized license plate numbers directly on the web interface.


## Challenges Addressed

- **Lighting Variations**: Effectively handles different lighting conditions, including low-light environments and glare.
- **Diverse Plate Formats**: Supports recognition across multiple plate formats and regions.
- **Occlusions**: Capable of recognizing partially obscured or occluded license plates.

## Contributing

Contributions are welcome! If you wish to contribute, please fork the repository, create a new branch, and submit a pull request. You can also open an issue for any bugs or feature requests.

## License

This project is licensed under the MIT License.

