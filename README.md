# Advanced Coin Segmentation
An advanced coin detection and classification system using OpenCV and hardcoded logic to identify UK coins based on visual features such as size, shape, and color.

## 🔍 Overview
This project was developed as part of a university module to demonstrate practical image processing and computer vision skills. The solution uses manual rule-based segmentation (no machine learning) and focuses on detecting and classifying UK coins.

💡 **Implemented in Python** using OpenCV within a Google Colab Notebook for easy testing and sharing.

## 🛠 Features
- **Image Preprocessing**: Blurring, thresholding, and edge detection.
- **Watershed Segmentation**: For accurate coin isolation.
- **Feature Extraction**: Radius, contour area, and color histograms.
- **Rule-Based Classification**: Identification of UK coins (e.g., 1p, 2p, 5p, 10p, 20p, 50p, £1, £2).
- **Visual Annotation**: Labeling identified coins in the output images.

## 🧪 Example
![Detected Coins](https://github.com/user-attachments/assets/6eaec4ef-8e78-4edc-a73d-d4b425c0ea3d)
![demo_output](https://github.com/user-attachments/assets/237915c2-d0e7-410b-8b35-d23d2cccf93e)

*Above: Detected coins labeled using hardcoded classification logic.*

## 🖥 Tech Stack
- Python
- OpenCV
- Google Colab
- NumPy

## 🚀 How to Run
1. Open the Google Colab Notebook (`updated_coins_Project_V_13.ipynb`).
2. Upload an image of UK coins on a flat surface.
3. Run the notebook cells to process the image and see classification results.

## 🧠 What I Learned
- **Watershed Segmentation**: For overlapping objects.
- **Manual Feature Engineering**: And rule-based classification.
- **System Design**: Building and validating a vision-based system without machine learning.

## 📸 Future Improvements
- Add support for real-time webcam-based detection.
- Replace hardcoded rules with a lightweight ML model.
- Expand to include foreign coins.
