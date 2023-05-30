# -Extracting-Data-From-Images-whose-tokens-are-extracted-from-TSV
# Image Data Extraction

This project focuses on extracting information from images using Optical Character Recognition (OCR) and processing the extracted data for further analysis. The extracted data is then stored in a DataFrame for easy manipulation and exploration.

## Project Overview

The project consists of the following steps:

1. Data Preparation:
   - The dataset contains images and TSV (Tab-Separated Values) files.
   - The TSV files provide token-level extractions of their respective images, including coordinates and text transcripts.

2. Image Processing:
   - The images are loaded using the Python Imaging Library (PIL).
   - The TSV data is parsed to extract the relevant coordinates for cropping the images.
   - The cropped regions of the images are then processed using OCR (Pytesseract) to extract the text.

3. Data Extraction:
   - The extracted text is associated with the respective field or label from the TSV data.
   - The extracted data is stored in a DataFrame for further analysis.

4. Output and Analysis:
   - The extracted data can be further analyzed, visualized, or used for machine learning algorithms.

## Usage

To run the code and extract data from the images, follow these steps:

1. Prepare the dataset:
   - Place the input images in the `images/` folder.
   - Store the TSV files in the `tsv_files/` folder, ensuring that each TSV file corresponds to its respective image.

2. Update the code:
   - Modify the paths and file names in the code to match your dataset.
   - Adjust any parameters or settings as needed.
