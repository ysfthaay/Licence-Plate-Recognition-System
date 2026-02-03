# Smart License Plate Recognition System
This project implements an automated License Plate Recognition (LPR) system using Python and Computer Vision. It is designed to detect vehicle plates from images and extract the alphanumeric text using Optical Character Recognition (OCR).


**🎯 Key Features**

Automated Detection: Localizes license plates within images using computer vision techniques.


OCR Extraction: Utilizes EasyOCR to read and extract plate numbers with high accuracy.


Visual Feedback: Automatically draws bounding boxes around detected plates for easy verification.


Batch Processing: Capable of processing multiple images in a single run.


**🛠️ Technologies Used**

Programming Language: Python 3.x 

OCR Engine: EasyOCR 

Computer Vision: OpenCV (Image processing and rendering) 

Visualization: Matplotlib 

Environment: Google Colab 

**🧠 System Architecture**

Input: User uploads one or more vehicle images.

Processing: The system uses EasyOCR to scan the image for text elements.

Filtering: OpenCV identifies high-confidence text regions corresponding to license plates.

Output: The recognized plate number is displayed, and the annotated image is rendered with a bounding box.

**🚀 How to Use**

Open the .ipynb file in Google Colab.

Install the required libraries (!pip install easyocr opencv-python).

Upload your vehicle images to the environment.

Run the cells to see the detected plates and extracted text.

**Developer:** Yusuf Taha ÖNCÜ
