# Advanced_Coin_Segmentation
Advanced coin detection and classification system using OpenCV and hardcoded logic to identify UK coins based on visual features such as size, shape, and colour.

#🔍 Overview
This project was developed as part of a university module to demonstrate practical image processing and computer vision skills. The solution uses manual rule-based segmentation (no machine learning) and applies feature extraction techniques to identify and classify coins from images.

💡 Implemented in Python using OpenCV within a Google Colab Notebook for easy testing and sharing.

#🛠 Features:
Image preprocessing (blurring, thresholding, edge detection)

Watershed segmentation for accurate coin isolation

Feature extraction: radius, contour area, colour histograms

Rule-based classification of UK coins (e.g., 1p, 2p, 5p, 10p, 20p, 50p, £1, £2)

Visual annotation of identified coins in output images

#🧪 Example:
![image](https://github.com/user-attachments/assets/6eaec4ef-8e78-4edc-a73d-d4b425c0ea3d)

Above: Detected coins labelled using hardcoded classification logic.

#🖥 Tech Stack:
Python

OpenCV

Google Colab

NumPy

#📁 Project Structure:
bash
Copy
Edit
├──  updated_coins_Project_V_13.ipynb       # Main Colab notebook
├── images/
│   ├── sample_input.jpg
│   └── demo_output.png
├── README.md
#🚀 How to Run:
Open the Google Colab Notebook

Upload an image of UK coins on a flat surface

Run the notebook cells to process the image and see classification results

#🧠 What I Learned:
Watershed segmentation for overlapping objects

Manual feature engineering and rule-based classification

Designing and validating a vision-based system without ML

📸 Future Improvements
Add support for real-time webcam-based detection

Replace hardcoded rules with a lightweight ML model

Expand to include foreign coins
