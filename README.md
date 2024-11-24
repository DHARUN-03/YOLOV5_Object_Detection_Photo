## YOLOv5 Object Detection with PyTorch
This project demonstrates how to use the YOLOv5 model to perform object detection on an image using Python and OpenCV. 
The model is loaded via PyTorch, and the image is processed to detect and label objects within the frame.

## Requirements
   Python 3.x
   PyTorch
   OpenCV
   YOLOv5 model
## Install the required libraries
To set up the environment, you'll need to install the necessary libraries. You can install them using pip:


pip install torch torchvision opencv-python pandas


    
Download the YOLOv5 model (yolov5s) from Ultralytics via PyTorch Hub.

## How to Run the Code
Ensure that you have Python 3.x installed and the necessary libraries (PyTorch, OpenCV, Pandas) are installed using the commands mentioned in the Requirements section.
Place the image (people.jpg) in the same directory as the script or provide the full path to the image.
Run the Python script.

    
python detect_objects.py
The script will display the image with object detections drawn as bounding boxes and labels.
## Screenshot

![pht_image](https://github.com/user-attachments/assets/4196f93d-929d-4d0f-884d-21335cc6c4ba)

## Conclusion
This simple project shows how to apply YOLOv5 for real-time object detection. By following this approach, you can easily integrate object detection into your applications. YOLOv5 can detect a wide range of objects, including people, vehicles, animals, and more. You can experiment with different versions of YOLOv5 (like yolov5m or yolov5l for better accuracy) depending on your use case.
