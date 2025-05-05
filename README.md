# Forensic Printer Detection Using Intrinsic Signatures

This project extracts pages from PDF files, identifies occurrences of the letter **'e'**, computes GLCM texture features, and classifies the document's printing source based on pre-learned printer characteristics.


# Problem Statement

To identify the specific printer that produced a given printed document. Existing methods either require document modification or expensive hardware-based solutions. This research focuses on using intrinsic signatures—natural texture and banding artifacts from printer mechanisms. Such signatures are hard to forge and persist across different fonts, consumables, and usage. The challenge is to reliably classify documents from both known and unknown printers using texture-based features and distance metrics.



## 📦 Features

- Convert PDF pages into images
- Detect and crop character **'e'**
- Extract texture features using GLCM
- Scale, select, and reduce features
- Train a custom distance-based classifier
- Classify unknown PDF pages based on learned printer patterns

---

## 🛠️ Installation

1. Install the libraries that have been mentioned in the **Requirements.txt** file.


## Execution of code

1. We will directly run **main.ipynb** file in Google colab or in VSCode with uploading dataset i.e **scanner dataset-20250502T134328Z-1-001.zip** and change its name to **folder.zip** and also we have uploaded **Xerox_Versalink.PDF**.


## Individual Contributions

1.) **Abhishek Kumar**: Implemented **Tessaract OCR**.

2.) **Abhayveer singh Oberio**: Implemented **GLCM Feature Extraction**.

3.) **G Sai Prabhath**: Handled the dataset and done my part from **feature reduction** to **Classification(end of the project)**(Also created Github link, written technical report and recorded video of executing of code too).
