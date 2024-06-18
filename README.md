# eKYC System

The eKYC (Electronic Know Your Customer) system is a project that allows customers to upload an image of their Aadhaar card. Using computer vision and deep learning, the system performs various tasks such as auto-cropping, face detection, detail extraction (name, DOB, address, etc.), and stores the extracted information in a pandas DataFrame.

## Features

- **Auto Cropping:** Automatically crops the uploaded image to focus on the Aadhaar card.
- **Face Detection:** Detects and verifies the face in the Aadhaar card.
- **Details Extraction:** Extracts key details such as Name, Date of Birth, Address, etc., from the Aadhaar card.
- **Data Storage:** Stores the extracted details in a pandas DataFrame for further processing and analysis.

## Technologies Used

- `Python`
- `OpenCV` (Computer Vision)
- Deep Learning (for OCR and Face Detection)
- `pandas` (Data Storage and Manipulation)
- `pyzbar` (for QR code)
- `DeepFace` (for face recognition and verification)
- `json` (for handling JSON data)
- `re` (for regular expressions)
- `easyocr`(for optical character recognition)
