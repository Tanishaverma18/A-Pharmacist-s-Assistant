# Pharmacist AI Assistant
The Pharmacist AI Assistant is an intelligent web-based tool designed to assist pharmacists and healthcare professionals in managing prescriptions efficiently. The application leverages OCR (Optical Character Recognition) to extract text from uploaded prescriptions, verifies medication names using RxNorm API, and allows users to create and manage orders seamlessly.

## Features
* Prescription OCR Processing: Extracts text from uploaded prescription images using Tesseract OCR.
* Medication Verification: Checks drug validity using RxNorm API.
* Order Management System: Allows pharmacists to create, store, and manage prescription orders in an SQLite database.
* User-Friendly Interface: Built using Flask, HTML, CSS, and JavaScript.
* Secure and Scalable: Ensures privacy and data integrity with secure handling of patient information.

## Technologies Used
* Programming Languages: Python, HTML, CSS, JavaScript
* Frameworks & Libraries:
          * Flask (Backend framework)
          * SQLite (Database)
* OpenCV & NumPy (Image processing)
* Tesseract OCR (Text recognition)
* Requests (API calls)
* APIs Used:
          * RXNorm API (Drug validation)

## Installation & Setup
Clone the Repository
git clone https://github.com/yourusername/pharmacist-ai-assistant.git
cd pharmacist-ai-assistant

Create a Virtual Environment (Optional but Recommended)
ython -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

Install Dependencies
pip install -r requirements.txt

Initialize the Database
python app.py
(This will create the pharmacist.db file automatically.)

Run the Flask App
flask run

Access the Application
Open your browser and go to: http://127.0.0.1:5000

## Usage
* Upload a Prescription Image: The OCR will extract text automatically.
* Verify Drug Validity: Use the drug checker to confirm medicine authenticity.
* Create and Manage Orders: Add medications to the order system and process them.

## Contact
For any queries, reach out at tanishaverma081@example.com or open an issue on GitHub.
