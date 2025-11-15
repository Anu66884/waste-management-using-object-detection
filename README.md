# Waste Classification Using Object Detection

This repository contains the files and instructions used for the project **“Waste Classification Using Object Detection.”**

## Technologies Used

* **Programming Language:** Python
* **Front-end:** HTML, CSS, JavaScript
* **Back-end:** Flask, YOLOv8, OpenCV
* **Data Preparation:** Roboflow (for image labeling)

## Project Steps

### **STEP 1 – Data Collection**

Nine waste datasets were collected and stored in the **`cdataset`** folder for labeling.

### **STEP 2 – Data Labelling**

Datasets were labeled using **Roboflow**, which generated **train**, **valid**, and **test** splits.
These labeled datasets are stored in the **`CDATA`** folder.

### **STEP 3 – Model Selection and Training**

YOLOv8 was selected as the object detection model and trained using the labeled datasets through the command prompt.

### **STEP 4 – Live Detection**

Real-time waste detection was implemented using **YOLOv8 and OpenCV**.
The live detection code (including the path to the trained model) is located in the **`myproject`** folder.

### **STEP 5 – Front-End Development**

A user-friendly web interface was created to capture waste in real time.
This front-end is connected to the **Flask backend** for communication between the webpage and the server.
A **batch file** is used to run the live detection script when the user clicks **“Open Camera”** on the webpage.

