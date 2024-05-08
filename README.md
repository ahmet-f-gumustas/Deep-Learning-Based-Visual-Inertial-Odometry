# DeepVIO: Deep Learning-based Visual Inertial Odometry

## About The Project
DeepVIO aims to enhance Visual Inertial Odometry (VIO) systems, which integrate image and inertial data, by utilizing deep learning techniques. This project focuses on developing more robust and reliable VIO systems capable of navigating complex and dynamic environments.

## Key Features
- **Data Handling**: Processes image and inertial sensor data collected from various environments.
- **Model Training**: Improves VIO performance using deep learning algorithms with models based on CNNs, RNNs, and Transformers.
- **Real-Time Testing**: Tests and evaluates developed models in real-time environments.
- **Performance Enhancement**: Increases the accuracy and reliability of VIO under challenging conditions.

## Getting Started
Follow these steps to run the project on your local machine:

### Prerequisites
You must have the following tools installed to run this project:
- Python 3.8 or higher
- pip
- git
- Opencv 4.8.0 or higher with build the Cpp  

### Installation
1. Clone the project:

- git clone https://github.com/ahmet-f-gumustas/Deep-Learning-based-Visual-Inertial-Odometry.git
- cd Deep-Learning-based-Visual-Inertial-Odometry
- pip3 install -r requirements.txt

## Usage
To run the project:
- python main.py --config config/default.yaml