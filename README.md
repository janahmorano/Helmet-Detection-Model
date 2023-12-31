﻿# Helmet-Detection-Model


A Real-Time Helmet Detection project powered by YOLOv8. This project employs state-of-the-art object detection techniques to identify helmets in live video feeds and images, ensuring safety compliance and risk mitigation. Whether in dynamic environments or controlled settings, this solution offers real-time monitoring with precision.

## Usage Instructions

To run the helmet detection model live, follow these steps:

1. **Clone the Repository:**
   Clone this repository to your local machine.

2. **Download the Model:**
Download the pre-trained YOLOv8 model weights file ("best.pt") and place it in the project directory.

3. **Run the Notebook:**
Open the "Helmet_Detection_Live.ipynb" Jupyter Notebook. Make sure the `model` variable is set to the correct path where your "best.pt" model weights file is located.

4. **Run the Notebook Cells:**
Execute the notebook cells to initialize the model and start real-time helmet detection. The notebook will utilize the live video feed and display the detected results.

## Requirements

- Python 3.6 or later
- PyTorch
- OpenCV
- Jupyter Notebook (for running the provided notebook)

## Model Training and Customization

This project is built using YOLOv8, a popular object detection framework. If you're interested in training the model on your own dataset or customizing its behavior, refer to the YOLOv8 documentation and tutorials.

---

Created by Janah Patricia Morano

