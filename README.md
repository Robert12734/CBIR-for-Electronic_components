# CBIR for Electronic Components

## Overview
CBIR (Content-Based Image Retrieval) for Electronic Components is a web-based application that identifies and retrieves visually similar electronic components from a dataset using image processing techniques. The system helps users quickly recognize and classify electronic components, reducing manual effort and improving search accuracy.

## Features
- Upload an image of an electronic component
- Extract visual features from the uploaded image
- Compare the image with components stored in the dataset
- Retrieve and display similar electronic components
- User-friendly web interface built with Flask

## Technologies Used
- Python
- Flask
- HTML/CSS
- Image Processing Techniques
- Content-Based Image Retrieval (CBIR)

## Project Structure
CBIR-for-Electronic_components/
│
├── dataset/ # Dataset of electronic component images
├── templates/ # HTML templates
├── uploads/ # Uploaded images
├── app.py # Main Flask application
├── mergesort.c # Supporting C program
└── README.md


## How It Works

1. The user uploads an image of an electronic component.
2. The system extracts visual features from the image.
3. These features are compared with images stored in the dataset.
4. Similar components are retrieved and displayed to the user.
5. The user can identify the component based on the retrieved results.

Navigate to the project directory
cd CBIR-for-Electronic_components

Install required packages
pip install flask

Run the application
python app.py

Open your browser and visit
http://127.0.0.1:5000/

Applications
Electronic Component Identification
Inventory Management
Educational Learning Tools
Electronics Laboratories
Component Search and Classification
Future Enhancements
Deep Learning-based Feature Extraction
Larger Electronic Component Dataset
Real-time Component Detection
Mobile Application Integration
Improved Classification Accuracy
Results

The system successfully retrieves visually similar electronic components from the dataset, helping users identify and classify components efficiently.

Author
Harsha S
ECE Student

License

This project is developed for academic and educational purposes.


