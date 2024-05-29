# BizCardX: Extracting Business Card Data with OCR

BizCardX is a Python application designed to extract information from business cards. It automates the process of extracting key details from business card images, such as the name, designation, company, contact information, and other relevant data. This application leverages the power of OCR (Optical Character Recognition) provided by EasyOCR to extract text from the images.

## Technologies Used

- Python
- EasyOCR
- Streamlit
- SQLite
- Pandas

## Features

- Upload business card images in PNG, JPG, or JPEG format.
- Extract text from uploaded images using EasyOCR.
- Automatically categorize extracted text into various fields such as name, designation, company name, contact, email, website, address, and pincode.
- View and modify extracted data.
- Save extracted data to a SQLite database for future reference.
- View the dataset and delete specific entries as needed.

## Usage

1. **Home**: Provides an overview of the technologies used and the purpose of the application.
2. **Upload & Modifying**: Allows users to upload business card images, extract text, view, modify, and save the extracted data.
3. **View Data Set**: Displays the dataset stored in the SQLite database.
4. **Delete**: Enables users to delete specific entries from the dataset based on name and designation.

## Installation

To run BizCardX locally, follow these steps:

1. Clone this repository.
2. Install the required dependencies by running `pip install -r requirements.txt`.
3. Run the Streamlit app using the command `streamlit run app.py`.

## Credits

- This project utilizes the EasyOCR library for text extraction.
- Built with Streamlit for the web application interface.
