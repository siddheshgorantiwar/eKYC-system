# 🛡️ eKYC System

The eKYC (Electronic Know Your Customer) system is an advanced project that simplifies and secures the process of customer verification. By leveraging the power of computer vision and deep learning, the system allows customers to upload an image of their Aadhaar card and automatically processes it to extract key details. This README provides a comprehensive overview of the features, technologies used, and how to get started with the project.

<!-- <img src="e-kyc-system.jpeg" alt="eKYC Banner" width="300" height="200"> -->
## ✨ Features

### 🌐 Auto Cropping
Automatically crops the uploaded image to focus precisely on the Aadhaar card, removing any unnecessary background.

### 🤖 Face Detection
Utilizes cutting-edge face detection algorithms to identify and verify the face on the Aadhaar card, ensuring authenticity.

### 📝 Details Extraction
Extracts crucial information such as:
- **Name**
- **Date of Birth**
- **Address**
- **Gender**

### 💾 Data Storage
Efficiently stores the extracted details in a pandas DataFrame for seamless processing and analysis.

## 🛠️ Technologies Used

- **Python**: Core programming language for the project.
- **OpenCV**: Library used for computer vision tasks such as image processing and auto-cropping.
- **Deep Learning**: Utilized for OCR (Optical Character Recognition) and face detection.
- **pandas**: Essential for data storage and manipulation.
- **pyzbar**: Employed for QR code scanning.
- **DeepFace**: Used for face recognition and verification.
- **json**: Handles JSON data.
- **re**: Used for regular expressions.
- **easyocr**: Facilitates optical character recognition.

<!--![Tech Stack](https://via.placeholder.com/800x400.png?text=Technologies+Used) <!-- Replace with actual image -->

## 📋 How It Works

1. **Upload Aadhaar Image**: User uploads an image of their Aadhaar card.
2. **Image Processing**: The system automatically crops the image to focus on the Aadhaar card.
3. **Face Detection**: Detects and verifies the face on the Aadhaar card.
4. **Detail Extraction**: Extracts key details such as name, DOB, address, and more.
5. **Data Storage**: Stores the extracted information in a pandas DataFrame for further use.

<!--![Process Flow](https://via.placeholder.com/1000x400.png?text=Process+Flow)  Replace with actual image -->


## 📂 Project Structure

```plaintext
eKYC-System/
│
├── Aadhaar_cropped.ipynb         # Autocropping image of aadhaar card
├── Aadhaar_OCR.ipynb             # extract text and other details from aadhaar card           
├── find_photo.ipynb              # Find photo in Aadhaar card
└── face_recognition.ipynb        # recognize face
