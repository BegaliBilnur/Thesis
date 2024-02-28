# Skin Helper

## Overview

Skin Helper is a Python script designed to assist in analyzing skincare product ingredients. It uses Optical Character Recognition (OCR) to extract text from images containing ingredient lists and matches the extracted ingredients with a database to provide ratings and descriptions for each ingredient.

## Installation

1. Ensure you have Python installed on your system.
2. Install the required dependencies using pip:
3. Download the `SkinHelper.py` script and ensure you have the `dataset_ingr.csv` file available in your working directory.

## Usage

1. Run the script using the command: streamlit run SkinHelper.py
2. Upload an image containing the list of skincare product ingredients.
3. The script will process the image, extract ingredients using OCR, and match them with the database.
4. Matching ingredients will be displayed along with their ratings and descriptions.

## Dependencies

- **Streamlit**: For creating the web application interface.
- **Pandas**: For data manipulation and CSV file reading.
- **PaddleOCR**: For Optical Character Recognition.
- **NLTK**: For text preprocessing.

## Files

- `SkinHelper.py`: The main Python script.
- `dataset_ingr.csv`: The dataset containing ingredient information.

## Notes

- Ensure that the uploaded image is clear and contains text that can be recognized by the OCR model.
- The accuracy of ingredient matching depends on the quality of the OCR and the completeness of the ingredient database.



