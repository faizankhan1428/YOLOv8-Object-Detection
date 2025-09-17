# YOLOv8 Object Detection

This repository contains a Jupyter notebook (`Object_Detection.ipynb`) that demonstrates how to perform object detection using the powerful Ultralytics YOLOv8 model. The notebook is a great starting point for anyone new to object detection or the YOLO framework.

## Key Features

* **Setup:** Installs all necessary libraries, including `ultralytics`, `opencv-python-headless`, `matplotlib`, and `pillow`.
* **Model Inference:** Loads a pre-trained `yolov8n.pt` model and runs inference on a user-uploaded image.
* **Visualization:** Displays the detected objects with bounding boxes and labels on the input image.
* **Gradio Integration:** Includes an optional section to create a simple web interface for the model using Gradio, allowing for easy, interactive testing of the object detection model.

## Getting Started

### Prerequisites

* Python 3.8 or later
* Git (for cloning the repository)

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/YOLOv8-Object-Detection.git](https://github.com/your-username/YOLOv8-Object-Detection.git)
    cd YOLOv8-Object-Detection
    ```

2.  **Install dependencies:**
    It is recommended to use a virtual environment.
    ```bash
    pip install -r requirements.txt
    ```

### Usage

1.  **Launch Jupyter Notebook:**
    ```bash
    jupyter notebook Object_Detection.ipynb
    ```

2.  **Run the cells:** Follow the instructions in the notebook to upload an image and run the object detection model.
