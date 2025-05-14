# **Automated license plate detection** 

This project performs Automated License Plate Recognition (ALPR) using OpenCV, NumPy, and Tesseract OCR. It detects the license plate region from a car image and attempts to extract the plate text.

📌 Features

Detects license plates from car imagesUses edge detection and contour approximationApplies Optical Character Recognition (OCR) with pytesseractColab-compatible with cv2_imshow

🛠️ Requirements

Install the required Python packages:

pip install opencv-python-headless numpy pytesseract Note: We use opencv-python-headless instead of opencv-python to avoid display issues in headless environments like Google Colab.

📂 File Structure
plaintext 
Copy
Edit
├──Automated_license_plate_recognition├── car4.jpg # Sample input image └── README.md # Project documentation

🚀 How to Run 
Open the notebook in Google Colab. Upload your image (or use car4.jpg). Run each cell in the notebook. View the detected license plate and OCR result. 

📷 Sample Output 
plaintext
Copy 
Edit 
Detected Plate Text: MH12AB1234 Output accuracy depends on image quality and clarity of the number plate.

🔍 Libraries Used
OpenCV 
NumPy
pytesseract 
Google Colab tools (for display) 


